[Back to main Logbook Page](../hci_logbook.md)

---

# F. Discussion of Evaluation Results

A avaliação funcional da aplicação NutriChef revelou um desempenho sólido na maioria das tarefas testadas. Os utilizadores conseguiram completar com sucesso ações como registo/login, consulta de calorias diárias, edição de perfil e acesso aos detalhes das receitas. No entanto, foram identificadas algumas limitações e pontos a melhorar:

Problemas técnicos: um erro na funcionalidade do carrinho impedia a adição de múltiplas receitas — entretanto corrigido.

Erros de usabilidade: o indicador do dia atual reduzia-se visualmente ao navegar por vários dias, o que afetava a legibilidade.

Sugestões valiosas: os utilizadores sugeriram melhorias como permitir adicionar receitas ao menu a partir de várias páginas e redirecionar automaticamente após o registo.

A limitação mais significativa foi imposta pela API gratuita da Edamam, que condicionou a profundidade dos dados nutricionais e a integração de funcionalidades mais completas. Apesar disso, a aplicação demonstrou um ciclo de utilização coeso e funcional.

# Refinement List

Com base na avaliação e na análise crítica da equipa, foram identificadas várias oportunidades de melhoria:

    1- Melhorar a usabilidade do calendário, permitindo navegação direta ao clicar nos dias.

    2- Corrigir erros visuais no indicador gráfico do dia atual.

    3- Redirecionar automaticamente após criação de conta para evitar frustração do utilizador.

    4- Permitir adicionar receitas ao plano semanal a partir de várias páginas (ex: Recipe Details).

    5- Melhorar a apresentação do nome do utilizador no perfil.

    6- Implementar a funcionalidade associada ao botão de gerar plano semanal, que ainda não estava completa.

    7- Incluir estatísticas nutricionais mais detalhadas.

# Refined Prototype

O protótipo funcional da aplicação foi desenvolvido em React com uso de armazenamento de dados no localStorage e uso da base de dados "Edamam". Após a fase de avaliação e recolha de feedback, o protótipo foi refinado com base nas melhorias da refinement list acima mencionada.

O protótipo atualizado demonstra um fluxo de utilização mais fluido e uma experiência de utilizador mais intuitiva, evidenciando a evolução da aplicação NutriChef com base no feedback real dos utilizadores.

---

[Back to main Logbook Page](../hci_logbook.md)

---
