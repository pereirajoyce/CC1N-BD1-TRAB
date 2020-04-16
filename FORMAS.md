# Primeira Forma Normal (1FN)

A primeira forma normal mostra que não é possível haver vários valores para um atributo. Quando isso ocorre e há um atributo com essas características, é necessário a criação de uma entidade extra, que será relacionada com a entidade original de forma que um valor está para N ocorrências. O atributo que depende do identificador único mostra que ele realmente faz parte daquela entidade.

# Segunda Forma Normal (2NF)

A segunda forma garante a coerência dentro do banco de dados, fazendo com que todos os atributos dentro de uma entidade pertençam/dependam dela. É possível identificar a necessidade/aplicação dessa regra quando observa-se a entidade e o UID da mesma e vê-se uma relação direta entre as atributo e o identificador, caso essa relação não seja direta, é necessário a mudança dele para uma outra entidade.

# Terceira Forma Normal (3NF)

A terceira forma explica que nenhum atributo que não seja um identificador exclusivo pode depender de outro que também não seja um. Ou seja, não é tolerado uma dependência transitiva, quando um atributo é dependente de outro que não é o exclusivo nessa entidade. Quando isso ocorre, é preciso movê-los para outra entidade.
