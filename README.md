# Match Reuniões 📅

> PRD — Product Requirements Document

Repositório contendo o **PRD (Documento de Requisitos de Produto)** do projeto **Match Reuniões**, uma solução que entrega automaticamente o contexto de reuniões diretamente no fluxo de trabalho dos desenvolvedores ausentes.

---

## 📌 Sobre o Projeto

Equipes de desenvolvimento frequentemente realizam reuniões de alinhamento mesmo com membros ausentes por incompatibilidade de agendas (estagiários, trainees, equipes distribuídas). Isso cria "gaps" de informação e desalinhamento técnico, obrigando quem faltou a buscar atualizações de forma individual e ineficiente.

O **Match Reuniões** resolve esse problema adotando um modelo **ativo ("push")**: em vez de depositar atas em repositórios externos, a solução extrai os pontos de ação específicos de cada desenvolvedor e os entrega diretamente nas ferramentas que ele já utiliza no dia a dia — GitHub, GitLab, Jira ou Slack.

---

## 🎯 Público-alvo

- Desenvolvedores de software (foco em estagiários, trainees e juniores)
- Membros de equipes distribuídas ou assíncronas
- Faixa etária: 18–35 anos
- Contexto: trabalho remoto/híbrido com metodologias ágeis (dailies, plannings, reviews)

---

## 🏆 Indicadores de Sucesso

| Indicador | Meta |
|-----------|------|
| **Taxa de Engajamento** | > 70% dos membros ausentes consomem o resumo em até 24h |
| **Time-to-Information** | 2 a 5 minutos para o dev absorver o contexto |
| **Redução de reuniões** | 2 a 4 horas semanais economizadas por colaborador |

---

## 📂 Estrutura do Repositório

```
prd-projeto-match-reunioes/
├── docs/
│   └── index.md      # PRD completo do produto
├── mkdocs.yml        # Configuração do MkDocs
└── README.md         # Este arquivo
```

---

## 📖 Documentação

O PRD completo está disponível em [`docs/index.md`](docs/index.md) e inclui:

- **Problema**: descrição do desafio enfrentado pelas equipes
- **Público-alvo**: perfil detalhado dos usuários
- **Soluções existentes**: análise de ferramentas atuais (Outlook, Google Calendar, Loom, tl;dv, Notion)
- **Concorrentes**: análise de concorrentes diretos e indiretos
- **Indicadores de sucesso**: métricas e benchmarks de mercado
- **Oportunidade**: gap identificado e proposta de valor

### Visualizar a documentação localmente

1. Instale o MkDocs:

   ```bash
   pip install mkdocs
   ```

2. Inicie o servidor local:

   ```bash
   mkdocs serve
   ```

3. Acesse [http://localhost:8000](http://localhost:8000) no navegador.

---

## 🤝 Contribuindo

1. Faça um fork do repositório
2. Crie uma branch para sua contribuição: `git checkout -b minha-contribuicao`
3. Realize as alterações e faça o commit: `git commit -m "descrição da mudança"`
4. Envie para o seu fork: `git push origin minha-contribuicao`
5. Abra um Pull Request

---

## 📄 Licença

Este projeto é um documento interno de produto. Consulte a equipe responsável para informações sobre uso e distribuição.
