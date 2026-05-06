# Sistema Acadêmico CRUD de Produtos e Fornecedores

## Descrição do Projeto

Este é um projeto acadêmico desenvolvido para demonstrar a criação de um sistema CRUD (Create, Read, Update, Delete) completo para gerenciamento de **Produtos** e **Fornecedores** utilizando o framework **Laravel**. O sistema segue as boas práticas de arquitetura MVC (Model-View-Controller), utilizando Blade Templates para o front-end e Bootstrap para estilização, sem a necessidade de frameworks JavaScript adicionais ou Livewire.

### Funcionalidades Implementadas

**Produtos:**
- Criar novo produto
- Listar todos os produtos com seus fornecedores vinculados
- Editar informações de produtos existentes
- Excluir produtos

**Fornecedores:**
- Criar novo fornecedor
- Listar todos os fornecedores
- Editar informações de fornecedores existentes
- Excluir fornecedores

### Regras de Negócio
- Um produto pertence a apenas um fornecedor (relacionamento 1:N).
- Validação de dados para CNPJ único para fornecedores.

## Tecnologias Utilizadas

- **Backend:** PHP 8+ com Laravel Framework
- **Banco de Dados:** SQLite (configurado por padrão, mas compatível com MySQL)
- **Front-end:** Blade Templates, Bootstrap 5
- **Gerenciador de Dependências:** Composer
- **Versionamento:** Git

## Como Instalar e Rodar o Projeto

Siga os passos abaixo para configurar e executar o projeto em seu ambiente local:

1.  **Clone o Repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd sistema-produtos
    ```

2.  **Instale as Dependências do Composer:**
    ```bash
    composer install
    ```

3.  **Configure o Arquivo `.env`:**
    O arquivo `.env.example` já foi copiado para `.env` durante a instalação. Verifique as configurações do banco de dados. Por padrão, o projeto está configurado para usar SQLite. Se desejar usar MySQL, ajuste as variáveis `DB_CONNECTION`, `DB_DATABASE`, `DB_USERNAME` e `DB_PASSWORD`.

4.  **Gere a Chave da Aplicação:**
    ```bash
    php artisan key:generate
    ```

5.  **Execute as Migrations e Seeders:**
    Isso criará as tabelas no banco de dados e populará com alguns dados de exemplo.
    ```bash
    php artisan migrate --seed
    ```

6.  **Inicie o Servidor de Desenvolvimento:**
    ```bash
    php artisan serve
    ```

    O sistema estará acessível em `http://127.0.0.1:8000` (ou outra porta indicada pelo Artisan).

## Informações dos Alunos

-   **Leonardo Estevão Alves** — R.A: 00250458-1
-   **Vinicius Correia de Andrade** — R.A: 251953-1

## Nível Esperado

Este projeto foi desenvolvido com um nível intermediário para avançado, demonstrando:
-   Organização de código e estrutura limpa.
-   Boas práticas de desenvolvimento Laravel.
-   Uso correto de Migrations, Models, Controllers e Views.
-   Implementação de relacionamentos de banco de dados e validação de formulários.

## Resultado Esperado

Um sistema CRUD funcional, limpo, organizado e pronto para rodar em qualquer máquina com Laravel configurado, atendendo aos requisitos acadêmicos propostos.
