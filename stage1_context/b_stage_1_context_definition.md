[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| [Paprika]    | [Plataforma de receitas e planeamento de refeições]        | [[Competitor Analysis Paprika]] |
| [Cookpanion] 		| [Plataforma de receitas e planeamento de refeições]   |[[Competitor Analysis Cookpanion]]  | 						
|                |                                             |                                     |




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)
-[expert1_heuristic_evaluation_workbook 2](<heuristic_evaluations/expert1_heuristic_evaluation_workbook 2.md>)
- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)
-[expert2_heuristic_evaluation_workbook 2](<heuristic_evaluations/expert2_heuristic_evaluation_workbook 2.md>)
- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)
-[expert3_heuristic_evaluation_workbook 2](<heuristic_evaluations/expert3_heuristic_evaluation_workbook 2.md>)

#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **João Cabral** | **Mariana Marques** | **André Nunes** | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Dificil adicionar receitas(Paprika-7) | 3            | 3        | 3        | Disponibilizar catálogo interno com receitas básicas |
| As receitas não contém calorias nem macros(Paprika-4)  | 3            | 3        | 2        | Adicionar automaticamente calorias e macros |
| As receitas não contém calorias nem macros(Paprika-8) | 2            | 2        | 2        | Evitar simplificação excessiva da informação nutricional |
| Navegação na app é dificil(Paprika-6)   | 2            | 2        | 2        |  Melhorar a interface para facilitar a navegação                    |
| É possivel criar receitas vazias(Paprika-5) | 1            | 1        | 1        | Impedir criação de receitas vazias |
| Escolher restrições alimentares sem explicação de cada uma(cookpanion-2)   | 2            | 2        | 2        |  Incluir descrições detalhadas de cada restrição                   |
| Dificil alterar receitas(cookpanion-6) | 2            | 3        | 2        | Tornar mais acessível o bot de edição das receitas |
| Dificil alterar receitas(cookpanion-7)   | 4            | 3        | 4        | Adicionar a opção de adicionar/retirar ingredientes                   |
| Dificil alterar receitas(cookpanion-8) | 2            | 3        | 3        | Permitir alteração direta, sem recurso ao bot   |

---
### - Cognitive Walkthrough

#### Method
[1-Identificar tarefas principais
2-Analizar a tarefa
3-Analizar as subtarefas ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Adicionar receita, quando ainda já existe receitas na app** | Clicar no botão do browser    |
|                             | Procurar receitas |
|                             | Selecionar receita      |
|                             |	Adicionar receita à app                  |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Adicionar refeição** | Clicar no botão refeições|
|                               | adicionar refeição             |
|                               | adicionar receita             |
|                               | escolher data e qual refeição        |


#### Results

Task: [1. Adicionar receita, quando ainda já existe receitas na app]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Clicar no botão do browser]   | [No]                                         |Não se encontra na página principal. É necessário aceder ao menu para conseguir ver       | [Yes]                                                                                  |       | [Yes]                       | [Colocar um botao de adicionar receitas na página principal]              |     |
| 2      | [Procurar receitas]   | [Yes]                                         |       | [Yes]                                                                                  |       | [Yes]                       | []              |     |
| 3      | [Selecionar receita]   | [Yes]                                         |       | [Yes]                                                                                  |       | [Yes]                       | []              |     |
| ...    | [Adicionar receita à app]        | [Yes]                                         |       | [Yes]                                                                                  |       | [Yes]                       | []               |     |

Task: [2. Adicionar refeição]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Clicar no botão refeições]   | [Yes]                                         |Apesar de não estar na pagina principal é intuitivo ir ao menu para o encontrar       | [Yes]                                                                                  |       | [Yes]                       | [Botão igual ao que se encontra nas secção das receitas mas tem funcionalidade diferente (um edita o outro adiciona)]              |     |
| 2      | [Procurar receitas]   | [Yes]                                         |       | [Yes]                                                                                  |       | [Yes]                       | []              |     |
| 3      | [Selecionar receita]   | [Yes]                                         |       | [Yes]                                                                                  |       | [Yes]                       | []              |     |
| ...    | [Adicionar receita à app]        | [Yes]                                         |       | [Yes]                                                                                  |       | [Yes]                       | []               |     |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]

**Para falar com os entrevistados, foi feita uma dinâmica em sala de aula. Os tipos de utilizadores que foram considerados foram alunos universátios presentes na sala de aula. As entrevistas tiveram como objetivo perceber os possiveis problemas existentes e receber pontos de vista que préviamente talvez não tenham sido considerados. As questões consideradas foram inicialmente para alertar o entrevistado do problema, visto que este pode nem se ter aprecebido do mesmo e numa fase mais avançada questões de preferiências, opinião e desejo de resolução.**
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 25-02-2025 | Anonymous / student| Gostava de uma App mais relacionada com Fitness                 | [📄 Notes](interview-1.md)   |     |
| 25-02-2025 | Anonymous / student| Gostava de uma App mais relacionada com Receitas e agendamento de refeições| [📄 Notes](interview-2.md)   |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Ter o seu menu semanal organizado
	- Encontrar substituição de alimentos que não tem em casa
- **Frequently Used Tools:** 
	- Pesquisa no Google
- **Desired Features / Solutions:** 
	- Calendário/Agendamento de refeições
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
