# Primeira Forma Normal (1FN)

A primeira forma normal mostra que não é possível haver vários valores para um atributo. Quando isso ocorre e há um atributo com essas características, é necessário a criação de uma entidade extra, que será relacionada com a entidade original de forma que um valor está para N ocorrências.

# Segunda Forma Normal (2NF)

Essa regra garante a coerência dentro do banco de dados, fazendo com que todos os atributos dentro de uma entidade pertençam/dependam dela.

# Terceira Forma Normal (3NF)

A terceira forma explica que nenhum atributo que não seja um identificador exclusivo pode depender de outro que também não seja um. Ou seja, não é toleradora uma dependência transitiva, quando um atributo é dependente de outro que não é o exclusivo nessa entidade. Quando isso ocorre, é preciso movê-los para outra entidade.
