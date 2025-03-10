[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: [Sónia] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Sónia\|100](personas/persona1.jpeg)  |
| **Name**         | [Sónia]                                |
| **Age**          | [45]                                 |
| **Occupation**   | [Enfermeira]                           |
| **Location**     | [Anadia, Portugal]                               |
| **Goals**        | [Sónia deseja equilibrar a sua carreira exigente como Chefe de Secção no hospital com a vida familiar, sem comprometer a qualidade da alimentação da sua família. Ela aspira a manter uma rotina alimentar saudável e organizada, garantindo refeições equilibradas sem o stress de decidir o que cozinhar após um longo dia de trabalho. Atualmente, um dos seus maiores desafios é a falta de planeamento nas compras, que muitas vezes resulta na ausência de ingredientes essenciais, tornando o processo de cozinhar mais complicado e frustrante. Para resolver esse problema, Sónia procura uma solução que lhe permita otimizar o tempo e garantir que tem sempre tudo o que precisa na cozinha, sem preocupações. Além disso, gostaria de diversificar mais as refeições da família, evitando cair na repetição dos mesmos pratos por falta de tempo ou inspiração. Gostaria de ter opções variadas e saudáveis sempre à mão, sem precisar de passar longos períodos a planear menus ou a procurar receitas. Ter um sistema prático que a ajude a organizar e preparar as refeições com antecedência tornaria o seu dia a dia muito mais fácil e prazeroso.]           |
| **Pain Points**  | [Falta de tempo para planear refeições; Esquecimento de ingredientes essenciais; Repetição de pratos; Desperdício de alimentos; Falta de controlo nutricional; Dificuldade em encontrar receitas rápidas e simples.]              |
| **Motivation**   | ["Quero garantir que a minha família tenha sempre refeições saudáveis e equilibradas, sem o stress de última hora. Se conseguir organizar melhor as compras e planear as refeições de forma prática, sei que o meu dia a dia será muito mais fácil e poderei desfrutar mais do tempo com a minha família."]                |
| **Full Profile** | [📄 Read More](personas/persona1_template.md) |

---
## Persona: [Alexandre] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Alexandre](personas/persona2.jpeg)            |
| **Name**         | [Alexandre]                                |
| **Age**          | [19]                                 |
| **Occupation**   | [Estudante Universitário]                           |
| **Location**     | [Braga, Portugal]                               |
| **Goals**        | [O Alexandre quer ganhar massa muscular e seguir uma dieta equilibrada que o ajude a melhorar o desempenho no ginásio. Para isso, sabe que precisa de ter refeições ricas em proteína e nutrientes, mas sem complicações. Como tem pouco tempo entre a faculdade e o treino, procura opções rápidas e fáceis de preparar. Também quer aprender a cozinhar melhor, porque está cansado de depender sempre dos mesmos pratos básicos. Gostava de ter um plano alimentar estruturado que o ajudasse a variar as refeições sem ter de pensar demasiado nisso. Além disso, quer evitar desperdícios e aproveitar melhor os ingredientes que já tem em casa. Se conseguisse manter uma alimentação equilibrada e ganhar mais confiança na cozinha, sabia que isso ia facilitar muito o seu dia a dia.]           |
| **Pain Points**  | [Repetição de refeições; Dieta desequilibrada; Falta de tempo; Falta de organização; Desmotivação.]              |
| **Motivation**   | ["Quero ter refeições equilibradas sem ter de pensar demasiado. Se a app me ajudar a organizar as refeições e facilitar a cozinha, vou conseguir manter o foco no treino e na faculdade."]                |
| **Full Profile** | [📄 Read More](personas/persona2_template.md) |

---





# Scenarios


## Scenario 1: Maria goes on a Museum Tour

Após um longo dia de trabalho no hospital, a Sónia chega a casa cansada, mas aliviada ao saber que o jantar já está completamente organizado com a ajuda do NutriChef. Ao sentar-se no sofá, relaxa um pouco e abre a app, encontrando imediatamente o menu do dia, que inclui frango com molho teriyaki, brócolos assados e arroz soltinho. A aplicação mostra os ingredientes que vai precisar e a Sónia já os tem, uma vez que já tinha planeado o menu semanal e feito todas as compras no domingo.

A Sónia verifica rapidamente a lista e retira os ingredientes necessários, colocando-os no balcão da cozinha para começar a preparação. Com a ajuda do NutriChef, consulta passo a passo como preparar o molho teriyaki, algo que nunca havia feito antes. A aplicação simplifica todo o processo, permitindo que Sónia cozinhe de forma fácil e eficaz.

---
## Scenario 2: Xandinho pós-ginásio

Alexandre saiu do ginásio cansado, mas motivado. Sabia que precisava de uma refeição rica em proteína para ajudar na recuperação muscular, mas a ideia de cozinhar algo elaborado depois de um treino puxado não lhe agradava.  

Assim que chegou a casa, abriu a nossa app. A interface simples sugeriu-lhe automaticamente uma receita de wrap de frango com molho de iogurte, rica em proteína e pronta em menos de 10 minutos — perfeita para o pós-treino. Como tinha alguns ingredientes em falta, a app sugeriu substituições rápidas e práticas, como trocar o espinafre (que ele não gosta) por alface.   

No final, a app mostrou-lhe um resumo dos macronutrientes da refeição — 40g de proteína, 30g de hidratos e 10g de gordura — confirmando que estava alinhado com o seu plano de treino. Sentiu-se satisfeito por ter conseguido preparar uma refeição equilibrada sem complicações.  


# Requirements





## C.1. Functional requirements

- Permitir aos utilizadores criar e gerir menus semanais personalizados;

- Questionar inicialmente o utilizador sobre objetivos nutricionais específicos (perda de peso, dieta vegana, etc) e adaptar automaticamente as calorias e macros recomendadas, conforme os seus objetivos e o seu corpo;

- Fornecer sugestões de receitas com base nos ingredientes disponíveis;

- Monitorizar e exibir valores nutricionais detalhados e calorias consumidas diariamente;

- Gerar automaticamente listas de compras a partir das refeições planeadas;

- Oferecer opções de personalização de receitas com base em restrições alimentares e preferências;


## C.2. Non-functional requirements

- Interface intuitiva e fácil de usar;

- Alta personalização com perfis e preferências individuais;

- Bom desempenho e tempos rápidos de resposta;

- Compatibilidade com diferentes dispositivos móveis;

- Capacidade de sincronização e armazenamento seguro dos dados;


---
[Back to main Logbook Page](hci_logbook.md)
