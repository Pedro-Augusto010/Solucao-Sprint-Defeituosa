# Raio-X da Sprint: Diagnóstico e Recuperação 🚑🎓

## 📖 Visão Geral
Este projeto é um trabalho acadêmico prático que tem como objetivo simular a gestão de uma *Sprint* em estado caótico e aplicar intervenções de correção baseadas em Métodos Ágeis. O cenário de estudo utiliza o projeto **Carona UCB**, com a análise focada no sexto dia de uma Sprint de 10 dias, momento em que a equipe enfrentava um grave colapso no fluxo de trabalho.

## ⚠️ Diagnóstico da Sprint (O Cenário de Crise)
No 6º dia da Sprint, de uma projeção inicial de 40 *Story Points*, apenas 8 haviam sido concluídos. O diagnóstico detalhou os seguintes problemas principais:

* **Fuga de Escopo e Distração (*Scope Creep*):** O *Product Owner* (PO) solicitou a adição de duas funcionalidades não essenciais no meio da Sprint (integração com o Spotify e ajuda de custo para gasolina via Pix), ameaçando a capacidade técnica do time.
* **Ausência de Limites de Trabalho (WIP):** Sem limites, a equipe acumulou e começou a trabalhar em 13 histórias simultaneamente, entregando apenas duas nos primeiros seis dias.
* **Falha Crítica no Planejamento:** Assumir 40 *Story Points* em apenas 10 dias provou ser um volume irreal, superestimando gravemente a capacidade produtiva da equipe.
* **Sobrecarga de Tarefas:** As colunas *Doing* e *Testing/Code Review* estavam superlotadas de tarefas em andamento, gerando um gargalo no fluxo de entrega.

## 🛠️ Intervenções e Plano de Recuperação
Para salvar o *Sprint Goal* e garantir a entrega do Produto Mínimo Viável (MVP), o quadro Trello e a metodologia foram reestruturados com as seguintes soluções:

### 1. Reorganização do Kanban (WIP e DoD)
* **Limites de Work In Progress (WIP):** Estabelecimento do limite rígido de apenas 3 tarefas simultâneas para as colunas *Doing* e *Testing/Code Review*. Diversos cartões (como as US 12, 13, 14, 15, etc.) foram regredidos para o *To Do* para desafogar o gargalo.
* **Definition of Done (DoD):** Criação de uma coluna visível de regras para considerar um cartão como feito, como código testado em Android/iOS, tempo de resposta inferior a 2 segundos e regras de segurança da universidade validadas.

### 2. Nova Postura na Daily Scrum
* A reunião diária abandonou o formato de "relatório de status" para focar em soluções emergenciais.
* Estabeleceu-se que **nenhuma** tarefa nova sairia do *To Do* enquanto houvessem cartões travados ocupando o limite do WIP.
* **Força-Tarefa e *Pair Programming*:** Desenvolvedores pausaram a criação de novos códigos para atuar como testadores (*Swarming*) nas tarefas presas na coluna *Testing*.

### 3. Corte Severo de Escopo e Foco no Essencial
* **Rejeição de Adições:** O *Scrum Master* barrou formalmente o pedido do PO para as funções do Spotify e do Pix.
* **Transparência:** O PO assumiu diante dos *stakeholders* o erro de planejamento e oficializou o abandono das histórias secundárias.
* **Pausa no Refinamento Visual:** Congelamento total de ajustes estéticos, polimentos de interface e animações. O esforço técnico foi 100% redirecionado para a lógica de negócio e segurança da API.

## 📈 Expectativa de Resultado
Através dessas soluções, espera-se que a Sprint finalize o décimo dia de forma estabilizada, com as funcionalidades essenciais concluídas e o quadro perfeitamente organizado de acordo com a capacidade real do time, evidenciando o poder de adaptação dos métodos ágeis.
