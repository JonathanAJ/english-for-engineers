# English for Engineers: Anki Decks & Survival Kit

Coleção de baralhos para Anki com áudios neurais de estúdio, vocabulário técnico contextualizado e guia prático para desenvolvedores de software atuando em empresas globais e equipes remotas multiculturais.

---

## Visão Geral

Este repositório foi criado para solucionar um desafio comum de engenheiros de software brasileiros: o domínio da linguagem técnica escrita e da lógica de programação versus o travamento na comunicação verbal em reuniões rápidas (Daily Standups, 1-on-1s, Code Reviews, refinamentos técnicos e negociações de débito técnico).

### Destaques dos Baralhos
* **Áudios Neurais Embutidos:** 100% dos cartões possuem arquivos `.mp3` sintetizados com vozes de inteligência artificial de alta fidelidade (Microsoft Edge Neural: Guy, Jenny, Eric e Aria).
* **Fórmula Dupla (Formal + Casual):** Treino da fala corporativa para reuniões e da variação coloquial usada em canais de Slack e huddles rápidos.
* **Tema AMOLED True Black:** Layout com `#000000` absoluto para economia de bateria e contraste ideal em telas OLED/AMOLED de smartphones e desktop.
* **Otimizado para FSRS:** Estruturado para o algoritmo moderno de repetição espaçada do Anki.

---

## Catálogo de Baralhos

Todos os pacotes prontos para importação estão disponíveis no diretório [`decks/`](decks/).

| Baralho | Total de Cards | Áudios | Foco Principal | Arquivo |
| :--- | :--- | :--- | :--- | :--- |
| **English - Tech & Engineering** | 86 cards | 172 áudios | Dailies, Code Review, Arquitetura, System Design, Pushback sênior, Gestão de crises | [`English_Tech_and_Engineering.apkg`](decks/English_Tech_and_Engineering.apkg) |
| **English - Phrasal Verbs de TI** | 30 cards | 30 áudios | Verbos compostos essenciais: *spin up*, *tear down*, *roll out*, *chime in*, *flesh out*, *drill down* | [`English_Phrasal_Verbs_TI.apkg`](decks/English_Phrasal_Verbs_TI.apkg) |
| **English - Small Talk Corporativo** | 30 cards | 60 áudios | Quebra-gelo nos 3 minutos antes da reunião, papo de segunda e sexta, 1-on-1s, fusos horários | [`English_Small_Talk_Corporativo.apkg`](decks/English_Small_Talk_Corporativo.apkg) |
| **English - Connected Speech & Reductions** | 30 cards | 30 áudios | Treino auditivo (*Ear Training*): decodificar a fala rápida de nativos (*Whaddya*, *Gonna hafta*, *Coulda*) | [`English_Connected_Speech.apkg`](decks/English_Connected_Speech.apkg) |

---

## Como Instalar e Usar (1 Minuto)

1. Baixe o arquivo `.apkg` desejado da pasta [`decks/`](decks/).
2. Abra o Anki Desktop ou o aplicativo móvel (AnkiDroid no Android ou AnkiMobile no iOS).
3. Dê duplo clique no arquivo `.apkg` (ou use o menu **Arquivo -> Importar**).
4. O baralho será importado com todos os áudios e estilizações aplicados automaticamente.

### Configurações Recomendadas no Anki
* **Algoritmo FSRS:** Nas opções do baralho, ative o FSRS e defina a retenção desejada entre `0.85` e `0.90`.
* **Meta Diária:** Configure entre `5` e `10` novos cards por dia para manter a consistência sem sobrecarga de revisões.

---

## Metodologia de Estudo Diário (15 Minutos)

Para desenvolver fala natural e automática sem tradução mental:

1. **Active Recall + Vocal Shadowing (10 minutos):**
   * Ao visualizar o cenário na frente do cartão, tente formular a resposta em voz alta antes de revelar o verso.
   * Ao virar, repita a frase em voz alta acompanhando o áudio, prestando atenção no ritmo, na ênfase das palavras-chave e nas pausas.
2. **Simulação Pré-Daily (5 minutos):**
   * Antes da sua Daily real, pegue os tickets do Jira do seu dia e monte mentalmente seu reporte em 3 frases usando os blocos aprendidos:
     * *Yesterday I wrapped up...*
     * *Today I'm diving into ticket MOBI-XXXX to work on...*
     * *No blockers on my end / I'm currently blocked waiting on...*

---

## Cheat Sheet de Sobrevivência (Consulta Rápida)

Frases corporativas de alto impacto para consulta imediata durante o expediente:

### Falhas de Áudio e Conexão
* *"Sorry about that, I was on double mute! Can everyone hear me clearly now?"*
* *"Your audio cut out for a second there. Would you mind repeating that last requirement?"*
* *"You're breaking up slightly. Could you please paste that link in the chat?"*

### Reporte de Impedimentos (Blockers)
* *"I'm currently blocked by the payment gateway team. I've reached out on Slack and I'm waiting on their response."*
* *"I ran into a few edge cases while handling concurrent transactions, so this took a bit longer than originally estimated."*

### Alinhamentos Rápidos e Foco
* *"Let's take this offline to keep the standup moving, and we can sync on Slack right after."*
* *"Do you have five minutes for a quick huddle after this? I'd love to bounce an idea off you regarding the API schema."*

### Pushback Técnico e Prazos
* *"While we could rush a quick patch by Friday, it would accumulate massive technical debt. I strongly suggest taking an extra sprint to build it properly."*
* *"I don't have that metric off the top of my head, but I'll pull the production logs and get back to you with the data right after this call."*
* *"That sounds like a great enhancement, but it's outside our current sprint scope. Let's log it in the backlog so we can prioritize it for sprint N+1."*

---

## Estrutura do Repositório

* `decks/`: Arquivos `.apkg` finais compilados com áudios embutidos.
* `src/tsv/`: Arquivos de texto tabulados com as perguntas, respostas e marcações de som.
* `src/scripts/`: Script Python (`build_decks.py`) para gerar os áudios neurais via `edge-tts` e montar os pacotes `.apkg`.

---

## Como Contribuir

Sugestões de novos cenários, expressões regionais ou melhorias nas frases técnicas são bem-vindas. Consulte as orientações em [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## Licença

Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE) para mais informações.
