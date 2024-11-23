EcoDrive Project
EcoDrive é uma aplicação web projetada para gerenciar e localizar estações de carregamento de veículos elétricos. Este projeto foi construído utilizando .NET Core 8.0 e inclui os módulos WebAPI, Infrastructure e Core. Ele demonstra os princípios da arquitetura limpa e inclui suporte para migrações de banco de dados usando o Entity Framework.

Pré-requisitos
Para configurar e rodar o projeto em outra máquina, garanta que os seguintes pré-requisitos estejam instalados:

.NET SDK (Versão 8.0 ou superior)
Oracle Database (para rodar a aplicação com a string de conexão fornecida)
Um editor de código ou IDE que suporte projetos .NET, como Visual Studio ou Visual Studio Code
Oracle Data Provider for .NET (ODP.NET) caso ainda não esteja incluído

Estrutura do Projeto
Core: Contém os modelos de domínio e a lógica de negócios.
Infrastructure: Inclui o contexto de banco de dados, migrações e repositórios.
WebAPI: O ponto de entrada da API, com controladores e injeção de dependência configurados.
