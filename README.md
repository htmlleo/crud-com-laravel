# crud-com-laravel
Sistema Acadêmico CRUD de Produtos e Fornecedores
Sistema Acadêmico CRUD de Produtos e Fornecedores

Descrição do Projeto

Este é um projeto acadêmico desenvolvido para demonstrar a criação de um sistema CRUD (Create, Read, Update, Delete) completo para gerenciamento de Produtos e Fornecedores utilizando o framework Laravel. O sistema segue as boas práticas de arquitetura MVC (Model-View-Controller), utilizando Blade Templates para o front-end e Bootstrap para estilização, sem a necessidade de frameworks JavaScript adicionais ou Livewire.

Funcionalidades Implementadas

Produtos:

•
Criar novo produto

•
Listar todos os produtos com seus fornecedores vinculados

•
Editar informações de produtos existentes

•
Excluir produtos

Fornecedores:

•
Criar novo fornecedor

•
Listar todos os fornecedores

•
Editar informações de fornecedores existentes

•
Excluir fornecedores

Regras de Negócio

•
Um produto pertence a apenas um fornecedor (relacionamento 1:N).

•
Validação de dados para CNPJ único para fornecedores.

Tecnologias Utilizadas

•
Backend: PHP 8+ com Laravel Framework

•
Banco de Dados: SQLite (configurado por padrão, mas compatível com MySQL)

•
Front-end: Blade Templates, Bootstrap 5

•
Gerenciador de Dependências: Composer

•
Versionamento: Git

