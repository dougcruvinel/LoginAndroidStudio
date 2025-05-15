Descrição em Português: Aplicativo Android de Cadastro e Venda de Produtos
Este projeto Java é um aplicativo Android simples que permite cadastrar produtos, visualizar um menu principal e registrar vendas. Ele foi desenvolvido utilizando o Android Studio e segue o padrão de atividades (Activities) com navegação entre telas.

Componentes principais:
MainActivity.java: Tela de login inicial do aplicativo.Verifica o usuário e senha para liberar o acesso ao menu.

MenuActivity.java: Tela de menu principal com opções para acessar o cadastro de produtos ou registrar uma venda.

ProdutoActivity.java: Tela onde é possível cadastrar produtos, armazenando seus dados em uma lista.

Activity_Venda.java: Tela para registrar uma venda. Permite escolher produtos da lista e armazenar a transação.

Produto.java: Classe de modelo (model) que representa os produtos cadastrados, incluindo atributos como nome, preço e quantidade. Possivelmente usa uma lista estática para manter os produtos em memória.

Funcionalidades do App:
Login inicial com autenticação básica.

Cadastro de produtos com nome, preço e quantidade.

Listagem e seleção de produtos para realizar vendas.

Navegação entre telas usando Intent.

Armazenamento temporário em memória (sem banco de dados).

Tecnologias e conceitos utilizados:
Android SDK com linguagem Java.

Activity, Intent, EditText, Button, ListView.

Manipulação de listas em memória.

Interface gráfica com XML.

Encapsulamento e reaproveitamento de código com classes Java.

-----------------------------------------------------------

Description in English: Android App for Product Registration and Sales
This Java-based Android project is a simple app that allows users to register products, access a main menu, and record sales. It is developed using Android Studio and follows the Activity pattern for screen navigation.

Main Components:
MainActivity.java: The app’s login screen. Likely checks credentials to access the main menu.

MenuActivity.java: Main menu screen with navigation options for product registration and sales.

ProdutoActivity.java: Screen where users can register new products, storing them in a static list.

Activity_Venda.java: Sales screen where users can choose products from the list and record the transaction.

Produto.java: Model class representing a product with attributes such as name, price, and quantity. Uses a static list to store data in memory.

App Features:
Basic login validation.

Product registration interface.

Product listing and selection for making sales.

Screen navigation with Intent.

In-memory data storage (no database).

Technologies and Concepts:
Android SDK using Java.

Use of Activity, Intent, EditText, Button, ListView.

Object-oriented design.

XML for UI layout.

Static data handling in Java.
