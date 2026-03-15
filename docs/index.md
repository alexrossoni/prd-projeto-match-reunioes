# Product Requirements Document (PRD)

---

## 1. Problema

Um desafio frequente enfrentado por equipes de desenvolvimento de software é a dificuldade de encontrar horários em comum para realizar reuniões virtuais de alinhamento. Isso ocorre devido à incompatibilidade de agendas de integrantes com jornadas diferentes, como estagiários e trainees que possuem compromissos acadêmicos. Essa falta de sincronia acontece constantemente e gera graves "gaps" de informação e desalinhamento técnico. Como as equipes acabam realizando as reuniões mesmo com a ausência de alguns membros, a dependência posterior de atas e transcrições obriga os ausentes a buscarem atualizações de forma individualizada, reativa e ineficiente.

---

## 2. Público-alvo

| Campo                             | Descrição |
|-----------------------------------|-----------|
| **Perfil** | Desenvolvedores de software, com foco especial em profissionais em início de carreira (estagiários, trainees e juniores) ou membros de equipes distribuídas/assíncronas. |
| **Faixa etária** | Majoritariamente 18 a 35 anos. |
| **Contexto de uso** | Trabalho remoto ou híbrido, lidando com metodologias ágeis (dailies, plannings, reviews) em times de tecnologia. |

**Benefícios esperados do produto**
O público-alvo espera **ganhar tempo e autonomia**. A solução deve eliminar a dor de se sentir "por fora" do que foi decidido na reunião, proporcionar a sensação de controle sobre suas tarefas e evitar o desgaste de ter que decifrar atas longas ou assistir a horas de gravação apenas para conseguir o contexto necessário para continuar programando.

---

## 3. Soluções Existentes

| Solução         | Categoria (SaaS, app, serviço...) | Resolve bem? |
|-----------------|-----------------------------------|--------------|
| **Microsoft Outlook** | SaaS (Calendário e E-mail) | Resolve parcialmente. Ajuda na verificação de disponibilidade, mas não soluciona o conflito inevitável de agendas incompatíveis por natureza. |
| **Google Calendar** | SaaS (Calendário) | Resolve parcialmente. Permite a visualização de agendas para encontrar horários, mas não cobre o "gap" de informação de quem inevitavelmente precisa faltar. |
| **Loom** | SaaS (Comunicação Assíncrona) | Resolve parcialmente. É ótimo para evitar reuniões, mas requer o esforço ativo de gravar um vídeo bem estruturado para cada atualização. |
| **tl;dv / Fireflies** | SaaS (IA para Reuniões) | Resolve parcialmente. Resume bem a reunião que já aconteceu, mas ainda exige que o membro ausente acesse uma plataforma externa. |
| **Notion / Confluence**| SaaS (Gestão de Conhecimento)| Não resolve bem para atualizações diárias. Depende de documentação manual pesada (atas) que raramente é lida no dia a dia. |

---

## 4. Concorrentes

| Tipo                  | Nome | Diferencial |
|-----------------------|------|-------------|
| **Concorrente direto 1** | tl;dv | Gravação automática de reuniões no Meet/Zoom com transcrição e geração de resumos e clipes curtos por IA. |
| **Concorrente direto 2** | Loom | Cultura de "vídeo-mensagem" em vez de reuniões. Interface rápida e extensão de navegador muito fácil de usar. |
| **Concorrentes indiretos** | Microsoft Outlook e Google Calendar | Uso de convites de reunião e verificação de disponibilidade e visualização de agendas para encontrar horários. |

---

## 5. Indicadores de Sucesso do Produto

| Indicador          | O que mede              | Benchmark de mercado |
|--------------------|-------------------------|----------------------|
| **Taxa de Engajamento** | % de membros ausentes que consumiram o resumo/atualização em até 24h. | > 70% (Superior à leitura de atas em texto, que é < 20%). |
| **Time-to-information** | Tempo médio (em minutos) que um dev leva para absorver o contexto e estar pronto para codar. | Leitura/visualização de 2 a 5 minutos no máximo. |
| **Redução de reuniões** | Horas semanais economizadas pela equipe em reuniões síncronas de status. | Economia de 2 a 4 horas semanais por colaborador. |

---

## 6. Oportunidade (gap identificado)

As soluções existentes falham porque adotam um modelo passivo ("pull"), onde a informação é depositada em um repositório (como o Notion ou a plataforma do tl;dv) e o desenvolvedor ausente precisa proativamente ir até lá buscar o que perdeu. O grande *gap* que identificamos é a falta de uma solução que entregue o contexto exato e acionável diretamente no fluxo de trabalho técnico. 

A oportunidade está em criar algo ativo ("push"), que não apenas resuma a reunião, mas extraia os pontos de ação específicos de cada desenvolvedor ausente e os integre diretamente nas ferramentas que ele já tem abertas o dia todo (como enviando o contexto diretamente no GitLab, GitHub, Jira ou Slack), eliminando o atrito da troca de contexto e a necessidade de ler atas generalistas.