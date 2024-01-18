# Exercício #

# Cenário de Teste: #

Cadastro de usuário com telemóvel inválido

Given que o usuário está na página em questão
And clica em criar conta
And adiciona o Nome e Apelido válidos
When adiciona um telemóvel inválido
Then aparece a mensagem de erro “telemóvel inválido”
