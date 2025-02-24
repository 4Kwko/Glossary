# glossary

SGDB (Sistema de Gerenciamento de Banco de Dados)
📌 Definição: Software que gerencia bancos de dados, permitindo armazenamento, recuperação e manipulação de dados (ex.: MySQL, PostgreSQL).

💡 Exemplo prático: Um e-commerce utiliza um SGDB para armazenar informações de produtos, pedidos e clientes, garantindo que os dados sejam acessíveis e organizados.

ODBC (Open Database Connectivity)
📌 Definição: API que permite a comunicação entre aplicações e diferentes SGDBs.

💡 Exemplo prático: Um sistema de contabilidade precisa acessar dados de um banco SQL Server e um Oracle DB. O ODBC permite que ele se conecte a ambos sem precisar de configurações específicas para cada SGDB.

Mineração de Dados
📌 Definição: Processo de análise para extrair padrões e informações úteis de grandes volumes de dados.

💡 Exemplo prático: Um banco analisa padrões de transações para identificar fraudes ao detectar movimentações atípicas na conta de um cliente.

TCPT (Três Camadas para Projeto de Tabelas)
📌 Definição: Modelo que organiza tabelas em conceitual, lógico e físico para estruturar bancos de dados.

💡 Exemplo prático: Em um hospital, o modelo conceitual define as relações entre pacientes, médicos e consultas, o modelo lógico traduz isso para tabelas e chaves, e o modelo físico define como os dados serão armazenados no SGDB.

SaaS (Software as a Service)
📌 Definição: Modelo de software baseado na nuvem, acessado via internet sem necessidade de instalação local.

💡 Exemplo prático: O Google Drive permite que os usuários armazenem arquivos na nuvem e acessem de qualquer lugar, sem precisar instalar um programa específico no computador.

Modelo de Dados
📌 Definição: Estrutura que define como os dados são organizados, armazenados e manipulados (ex.: relacional, hierárquico, orientado a objetos).

💡 Exemplo prático: Um supermercado adota um modelo relacional para armazenar informações de produtos, fornecedores e vendas, garantindo que os dados estejam estruturados e acessíveis para consultas.

Ordem de Serviço (O.S)
📌 Definição: Registro único que documenta um serviço prestado, vinculado a um cliente e produto.

💡 Exemplo prático: Em uma assistência técnica de celulares, cada Ordem de Serviço contém informações do cliente, o modelo do celular e o problema relatado, garantindo rastreamento do atendimento.

Entidade
📌 Definição: Representação de um objeto real no banco de dados (ex.: Cliente, Produto).

💡 Exemplo prático: Em um sistema de biblioteca, as entidades incluem Livros, Usuários e Empréstimos, cada uma com seus próprios atributos.

Classe
📌 Definição: Estrutura na programação orientada a objetos que encapsula dados e comportamentos.

💡 Exemplo prático: Em um sistema de vendas, a classe Produto pode conter atributos como nome, preço e estoque, além de métodos para calcular descontos.

Categoria
📌 Definição: Agrupamento de entidades com características semelhantes (ex.: eletrônicos, móveis).

💡 Exemplo prático: Em um marketplace, os produtos são organizados em categorias como Eletrodomésticos, Roupas e Brinquedos, facilitando a navegação dos usuários.

Atributo Chave Primária
📌 Definição: Identificador único de uma entidade (ex.: CPF para Cliente).

💡 Exemplo prático: No banco de dados de uma universidade, cada aluno possui um ID único como chave primária, garantindo que não existam registros duplicados.

Atributo Chave Secundária
📌 Definição: Usado para buscas, mas não identifica unicamente a entidade (ex.: nome do cliente).

💡 Exemplo prático: Em um sistema de RH, o CPF pode ser a chave primária, enquanto o nome pode ser uma chave secundária, permitindo buscas sem garantir unicidade.

Redundância Não Controlada
📌 Definição: Duplicação de dados sem gerenciamento adequado, causando inconsistências e desperdício de armazenamento.

💡 Exemplo prático: Em um hospital, um paciente pode ser cadastrado duas vezes com nomes ligeiramente diferentes ("João da Silva" e "João Silva"), gerando registros duplicados e inconsistentes.

Diagrama ER (Entidade-Relacionamento)
📌 Definição: Representação gráfica do modelo de dados, mostrando entidades, atributos e relações entre elas.

💡 Exemplo prático:
Em um sistema de locadora de filmes, o Diagrama ER pode representar as entidades Cliente, Filme e Locação, onde:

Cliente tem atributos como ID, Nome e CPF.
Filme tem atributos como ID, Título e Gênero.
Locação conecta Cliente e Filme, registrando Data da Locação e Data de Devolução.

Cardinalidade
📌 Definição: Define o número máximo e mínimo de ocorrências de uma entidade que pode se relacionar com outra em um banco de dados.

💡 Exemplo prático:
Em um sistema acadêmico, a cardinalidade pode ser representada assim:

Um professor pode ministrar várias disciplinas (1:N).
Cada disciplina deve ter pelo menos um professor (1:1 ou 1:N).
Um aluno pode se matricular em várias disciplinas e cada disciplina pode ter vários alunos (N:N).

Relação Transitiva – Uma relação entre entidades em que, se A está relacionado a B e B está relacionado a C, então A está relacionado a C.

💡 Exemplo prático:
Em um sistema de gestão de projetos, se:

João está subordinado a Maria, e
Maria está subordinada a Carlos,
Então, pela relação transitiva, João está subordinado a Carlos.
