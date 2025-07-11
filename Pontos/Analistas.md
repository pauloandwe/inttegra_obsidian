- Analisar possíveis efeitos colaterais e imprevistos que podem surgir durante ou antes do desenvolvimento (ex. mudança de calculo em algum indicador na dashboard),

- Ao exemplificar um bug, utilizar os dados existentes no portal como base (isso facilita na identificação e reprodução do mesmo),

- Checar a origem dos dados, por exemplo, movimentações, lote finalizado, produtos formulados e etc (isso facilita na identificação e reprodução dos mesmos),

- Especificar com mais detalhes a funcionalidade dos campos (ex. obrigatoriedade, label, inputs dependentes),

- Observar se o comportamento de um input não afetará o comportamento de outros campos (caso tenha, especificar como contorná-lo),

- Observar repetição na inclusão de dados em formulários relacionados (evita retrabalho),

- Especificar todas as colunas que uma listagem deve possuir (basear-se a partir de um formulário pode ficar confuso, muito extenso e/ou com informações desnecessárias),

- Caso exista documentação anexada na tarefa, atualizar sempre que houver mudança (evita ter que explicar tudo que precisou ser alterado para o tester)

- Validar dados no sistema antes de subir um bug, porque a gente não sabe a regra de negócio, então a gente gasta muito tempo para achar o que está acontecendo e as vezes é alguma regra de negócio correta que faz não aparecer os valores esperados (ex: data fora do período, lançamentos não validados, dados esperados com a planilha, etc.)
  
- Validar cada ponto a ser implementado comparando o que já tem no sistema e com o que tem que ser implementado.
  
- Revisão técnica prévia (pré-refinamento; ex: analistas perguntarem para a gente como está estruturado o sistema para saber como implementar novas funções)

- Critérios de aceitação das tarefas mais objetivos.

- Validação das análises por um analista senior ( durante temporada de onboarding de novos integrantes )

- Scrum dos analistas, com todos os rituais, caso viável. (
	1. **Clareza de Requisitos** – Reuniões frequentes com o cliente (como o backlog grooming) garantem entendimento claro das necessidades.
	    
	2. **Adaptação Contínua** – Permite ajustar requisitos rapidamente conforme novas descobertas.
	    
	3. **Foco Prioritário** – O backlog priorizado ajuda o analista a entender o que é mais importante entregar primeiro.
	    
	4. **Menor Retrabalho** – Feedback constante evita análises baseadas em premissas erradas.
	    
	5. **Documentação Essencial** – Incentiva documentação leve e objetiva, sem burocracia.
	    
	6. **Colaboração Direta** – Aproxima o analista dos desenvolvedores e do Product Owner, facilitando a comunicação.
	    
	7. **Validação Rápida** – Sprint reviews permitem validar se o que foi entregue atende aos requisitos analisados.
	    
	8. **Transparência** – Todos têm visibilidade do que está sendo feito e o **porquê**.
	    
	9. **Melhoria Contínua** – As retrospectivas ajudam o analista a melhorar seu processo de análise sprint após sprint. )