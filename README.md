# Secure Access App

 É uma aplicação desenvolvida para garantir segurança robusta através de controle de acesso e autenticação de usuários. Os usuários informam suas credenciais para obter acesso a diferentes recursos com base em seus perfis. 

Utilizamos OAuth2 com o método Password Grant Type para emitir tokens JWT (JSON Web Tokens) que autenticarão os usuários e controlarão o acesso aos recursos. A aplicação também implementa Spring Security para a segurança e controle CORS para gerenciar políticas de acesso de diferentes origens.

A seguir, uma visão geral das principais funcionalidades:

- 
  Autenticação de Usuário: Os usuários podem autenticar-se informando suas credenciais (username e senha) para obter um token JWT.

- Controle de Acesso baseado em Perfis:

  - Público: Alguns endpoints são acessíveis a todos os usuários, sem necessidade de autenticação.
  - Clientes: Endpoints acessíveis apenas para usuários autenticados com o perfil de cliente.
  - Administradores: Endpoints restritos a administradores, que têm acesso total a todos os recursos da aplicação.

- Emissão de Tokens: Utilização de OAuth2 para emitir tokens JWT que são usados para autenticar e autorizar acessos subsequentes.

- Segurança Robusta com Spring Security: Proteção dos endpoints e validação dos tokens para garantir que apenas usuários autorizados possam acessar determinados recursos.

- Controle CORS: Implementação de políticas CORS para permitir ou restringir acessos de diferentes origens.

  

# Tecnologias Utilizadas

Nesta aplicação foram empregadas diversas tecnologias para o desenvolvimento e funcionamento adequado. Abaixo estão algumas das principais:

## Linguagens de Programação

- Java: Utilizado como linguagem principal de programação.

## Frameworks e Bibliotecas

- Spring Boot: Framework para criar aplicações Java.
- Spring Security: Framework para segurança e autenticação.
- OAuth2: Protocolo de autorização usado para permitir que aplicativos de terceiros obtenham acesso limitado a um serviço HTTP.
  - Password Grant Type: Método de obtenção de token onde o usuário envia suas credenciais diretamente ao servidor de autorização.

- JWT (JSON Web Tokens): Formato compacto e seguro para transmitir informações entre as partes como um objeto JSON.

## Ferramentas e Bibliotecas de Desenvolvimento

- Maven: Ferramenta de gerenciamento de dependências e construção de projetos.
- Git: Sistema de controle de versão utilizado para colaboração e gerenciamento de código-fonte.
- GitHub: Plataforma utilizada para hospedagem de repositórios Git.
- IntelliJ IDEA: Ambiente de desenvolvimento integrado (IDE) utilizado para desenvolvimento Java.

## Banco de Dados

- H2: Banco de dados relacional leve, rápido e que oferece suporte para SQL. Ideal para desenvolvimento, testes e aplicações de pequeno porte.

## Outras Tecnologias

- RESTful: Arquitetura utilizada para construção de APIs web que se baseiam no protocolo HTTP.

  

# Contato

[Linkedin ](https://www.linkedin.com/in/pativilaka/)