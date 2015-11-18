# MongoDB, Aula 1 - Exercício
autor: maisumbruno

## Importando os Restaurantes

$ mongoimport -d be-mean -c restaurantes --drop --file restaurantes.json
2015-11-17T22:40:46.901-0200	connected to: localhost
2015-11-17T22:40:46.903-0200	dropping: be-mean.restaurantes
2015-11-17T22:40:49.168-0200	imported 25359 documents


## Contando os Restaurantes

$ mongo be-mean
be-mean> db.restaurantes.find({}).count()
25359
