Curso de Engenharia de Software - UniEVANGÉLICA
Disciplina de Sistemas Gerenciadores de Banco de Dados
Dev: Thiago Silva Soares
DATA: 02/07/2023

Descrição da Implementação e Aplicação do Sistema de Gerenciamento de Banco de Dados no Projeto NADespensa:

O projeto NADespensa é um software ou aplicativo desenvolvido com o objetivo de armazenar alimentos em uma despensa virtual, permitindo o cálculo da data de validade dos alimentos, identificação daqueles que estão em boas condições para consumo e de boa aparência, além de fornecer informações sobre preços para compra. Para possibilitar essas funcionalidades, é essencial a utilização de um sistema de gerenciamento de banco de dados (SGBD) eficiente e adequado às necessidades do projeto.

Estrutura do Banco de Dados:
O banco de dados do NADespensa é projetado para armazenar informações sobre os alimentos, incluindo seus nomes, categorias, data de validade, condição (bom para consumo ou não), aparência, preços e outras características relevantes. Além disso, é importante considerar a inclusão de informações sobre os usuários, como perfis, preferências alimentares e histórico de compras.

O banco de dados pode ser estruturado de forma relacional, onde as informações são organizadas em tabelas com linhas e colunas. Por exemplo, pode-se ter uma tabela de alimentos com campos como ID, Nome, Categoria, Data de Validade, Condição, Aparência, etc. Outra tabela pode ser utilizada para armazenar informações dos usuários, com campos como ID, Nome, Preferências Alimentares, Histórico de Compras, etc. Os relacionamentos entre as tabelas podem ser estabelecidos por meio de chaves estrangeiras, que vinculam registros de uma tabela a registros de outra.

Gerenciamento do Banco de Dados:
Para um gerenciamento eficiente do banco de dados do NADespensa, recomenda-se a utilização de um Sistema de Gerenciamento de Banco de Dados (SGBD) que ofereça recursos adequados para a persistência, recuperação e manipulação dos dados. Dentre as opções disponíveis, podem-se considerar SGBDs relacionais tradicionais, como MySQL, PostgreSQL ou SQL Server.

Esses SGBDs oferecem recursos robustos para garantir a integridade e consistência dos dados, além de suportar consultas eficientes e transações seguras. Eles possuem uma ampla gama de ferramentas e linguagens de programação para interação com o banco de dados, como SQL (Structured Query Language), que é uma linguagem padrão para consulta e manipulação de dados em SGBDs relacionais.

Tecnologias Adicionais:
Além do SGBD, podem ser utilizadas tecnologias adicionais para aprimorar a análise de dados e a experiência do usuário no NADespensa. Por exemplo, para a análise de dados sobre preços de alimentos, podem ser empregadas ferramentas de análise de dados, como Python com bibliotecas como Pandas, NumPy e Matplotlib, para realizar manipulações e visualizações dos dados coletados.

No contexto mobile, a escolha da tecnologia de desenvolvimento do aplicativo pode variar. Se for um aplicativo nativo para Android, pode-se utilizar o Android Studio com a linguagem Java ou Kotlin. Já para o desenvolvimento de um aplicativo iOS, é possível utilizar o Xcode com a linguagem Swift. Alternativamente, é possível adotar abordagens híbridas, como o desenvolvimento de um aplicativo utilizando frameworks como React Native ou Flutter, que permitem criar um único código-base que pode ser executado tanto em dispositivos Android quanto iOS.

No que se refere à usabilidade, é importante considerar a interface do usuário (UI) e a experiência do usuário (UX), projetando uma interface intuitiva, de fácil utilização e que ofereça uma experiência agradável ao usuário durante a navegação pelo sistema. Isso envolve a criação de telas claras, botões e menus de fácil compreensão, além de garantir a responsividade e adaptação a diferentes tamanhos de tela.

Por fim, em relação à conformidade com as normas e modelos de qualidade de processos e produtos de software, é fundamental seguir as melhores práticas de desenvolvimento de software. Isso inclui a adoção de metodologias ágeis, como Scrum ou Kanban, para um gerenciamento eficiente do projeto, a realização de testes de software rigorosos para garantir a estabilidade e qualidade do sistema, a documentação adequada do sistema para facilitar a manutenção futura, além de adotar medidas de segurança para proteger as informações armazenadas no banco de dados, como criptografia, controle de acesso e auditorias regulares.

Em resumo, a implementação do sistema de gerenciamento de banco de dados no projeto NADespensa é crucial para armazenar e manipular as informações sobre alimentos e usuários de forma eficiente. O uso de um SGBD adequado, junto com tecnologias adicionais para análise de dados e desenvolvimento mobile, e o foco na usabilidade e conformidade com as melhores práticas de desenvolvimento, são elementos-chave para o sucesso do projeto.




