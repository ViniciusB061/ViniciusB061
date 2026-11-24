# Vinicius Borges

Sou dev em Brasília e trabalho com sistema de crédito consignado. Faço um pouco de tudo: tela, API, banco de dados e uns robôs que digitam proposta no lugar da gente.

Uso JavaScript e Node.js na maior parte do tempo, PostgreSQL no banco e Python nos robôs.

Quase tudo que faço está em repositório privado, então vou anotando por aqui o que andei fazendo.

## Semana de 17 a 24/11/2026

Refiz do zero a tela de um dashboard de vendas. A tabela antiga só mostrava uma linha e o gráfico não tinha nem legenda. A primeira versão nova ficou pior que a original, aí mudei o layout inteiro e deu certo. Agora funciona no celular também.

Passei boa parte da segunda-feira numa API para outro sistema consultar o nosso. O mais chato foi não deixar a mesma consulta rodar duas vezes quando chegam pedidos iguais juntos.

Nos robôs saíram cinco versões na semana. Tem um novo, e ele agora confere os campos da proposta que preenche.

Também troquei uma integração antiga por outra API, coloquei o histórico das últimas consultas em três telas e arrumei uns erros de lint que tinham quebrado o CI.
