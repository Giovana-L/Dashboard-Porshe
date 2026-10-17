Dashboard de Vendas da Porshe
Feito para o curso Santander - Excel com IA e Claude (DIO)
Ferramenta utilizada para criação do Dashboard: Gemini Pro

Perguntas de negócio:
1 - Quais modelos de Porsche geram a maior receita total e qual é o preço médio de venda por modelo e ano de fabricação?
2 - Como a receita de vendas está distribuída por estado/cidade?
3 - Qual o modelo mais popular por cidade?

Prompt inicial:
Utilizando como base o arquivo de excel em anexo, renderize um dashboard em html, seguindo as seguintes instruções:
#Filtros
Modelo da Porshe (coluna PorscheModelSanitized)
Ano do Modelo (coluna ModelYearSanitized)
Cidade (coluna CitySanitized)
Método de Pagamento (coluna PayMethodSanitized)
#Perguntas de Negócios
Quais modelos de Porsche geram a maior receita total e qual é o preço médio de venda por modelo e ano de fabricação?
Como a receita de vendas está distribuída por estado/cidade?
Qual o modelo mais popular por cidade?
#Design
UI/UX: se baseie no site oficial da Porshe Brasil https://www.porsche.com/brazil/pt/
Aparência elegante e refinada 

Prompts de Refinamento:
É possível refinar os filtros, para que as opções deixem de aparecer se não houver correspondência?
Exemplo:
O modelo "718 Boxster" só tem modelos de 2021
No dashboard, seria possível, quando eu selecionar o "Ano do Modelo" diferente de 2021, o 718 boxster não aparecer na lista de modelos?

Adicione um filtro de "Estado", mantenha os demais filtros
