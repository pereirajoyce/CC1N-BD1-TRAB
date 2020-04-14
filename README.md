# CC1N-BD1-TRAB
> <b>Grupo:</b><br>
Joyce Paiva Pereira.<br>
Davi Gomes Leardine Pontes.<br>
Arthur do Espírito Santo Paganini.

# Cenário: gerenciamento de uma livraria.
A livraria Peixoto foi criada em 1973, quando a era tecnológica ainda estava há décadas de ser impulsionada. Graças a paixão dos seus donos, conseguiu sobreviver por todos esses anos na cidade de Linhares, Espirito Santo. Por ser um negócio antigo, o gerenciamento era provido de forma analógica, com cadernos empoeirados e informações nem sempre fáceis de serem encontradas.

Com o passar dos anos, o negócio familiar fora passado dos pais para o filho mais velho. Sabendo que nos dias atuais é impossível lidar com a grande quantidade de informações de maneira tradicional, a necessidade de armazenar, organizar e recuperar informações com mais eficiência durante o seu cotidiano fez com que o dono buscasse um método novo de gerenciar sua empresa. Para se orgarnizar e manter um bom funcionamento do estabelecimento, é necessário levantar todos os seus requisitos fundamentais. Assim, através de um especialista na criação de banco de dados, o proprietário detalhou todas as funções exercidas no seu comércio.

A partir do momento que o cliente entra na livraria, caso o livro esteja na prateleira, ele poderá ir direto para o balcão, onde é atendido por um balconista. Lá, caso ainda não tenha um, o funcionário criará um cadastro do cliente, onde estará todas as informações pessoais e mercadorias já compradas pela pessoa. Caso não esteja, o balconista pesquisará no estoque, tudo de forma digital. Todos os livros danificados serão separados para reciclagem ao fim do mês. Os livros serão organizados nas prateleiras por gênero, para que o cliente possa encontrá-los com facilidade. Um balconista poderá ou não efetuar vários atendimentos, mas todos os atendimentos precisam ser concluídos através de um balconista e um cliente. Da mesma forma, um cliente pode ou não fazer várias compras.

No cadastro dos funcionários, cada um terá seu <b>username</b>, assim como será obrigatório informações como <b>nome completo</b>, <b>CPF</b> e <b>telefone</b>. O <b>e-mail</b> será uma informação opcional. Além disso, o balconista, responsável pelo atendimento do cliente, terá uma característica extra: a <b>nota</b>, gerada com base nas avaliações dos clientes da livraria. O username do funcionário será seu identificador exclusivo.

Os clientes serão cadastrados através do <b>nome completo</b> e <b>CPF</b> como informações obrigatórias, assim como seu CPF será usado como o identificador exclusivo de cada um. Como informações opcionais, há o <b>e-mail</b> e <b>telefone</b>.

No estoque, os livros serão organizados através do seu <b>título</b>, <b>autor</b>, <b>gênero</b>, a <b>quantidade</b> disponível e sua <b>situação</b> física – danificado ou não –, onde todas essas informações serão obrigatórias no cadastro. A junção de título e autor será seu identificador exclusivo. 
  
Um atendimento é seguido do seu <b>protocolo</b>, que também é o identificador exclusivo, a <b>data</b> de ocorrência, o <b>status</b> em que está – esperando pagamento, cancelado etc – e poderá conter a <b>avaliação</b> do balconista caso o cliente se sinta à vontade. 

O item informado é identificado através da informação de qual <b>livro</b> e a <b>quantidade</b> vendida do mesmo. Em seguida, no processo da venda do produto será gerado uma <b>nota fiscal</b>, que funcionará como o identificador exclusivo dessa etapa. Também será informado a <b>data</b> da venda e o <b>preço</b> total.

# Perguntas que o sistema conseguirá responder:
Dado as informações obtidas pelo banco de dados, o sistema conseguirá responder inúmeras perguntas. Como, por exemplo:

Qual o gênero mais vendido?<br>
Clientes que leem um determinado gênero são mais propensos a lerem quais autores?<br>
Qual o autor/livro mais popular da livraria?<br>
Em média, quantos livros são vendidos mensalmente?<br>
Qual é a média de livros danificados por mês?
Em qual época do ano são vendidos mais livros?<br>
Qual é a média de preço dos livros mais procurados?<br>
Com base na média das notas dadas pelo atendimento, o balconista está fazendo um bom trabalho?<br>
