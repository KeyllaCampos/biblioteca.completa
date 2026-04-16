# biblioteca.completa
# Sistema de Biblioteca Web

Este projeto foi desenvolvido para a disciplina de **Programação Web II** do Instituto Federal de Mato Grosso (IFMT) – Campus Campo Verde.
O objetivo foi construir a estrutura inicial de um sistema web de biblioteca, com foco na interface visual utilizando o padrão **MVC**.

---

## Integrantes do grupo

- Michelly Aparecida Suhre  
- Keylla Vitória Campos Silva  

---

## Descrição do projeto

O sistema simula uma biblioteca digital, permitindo ao usuário:

- Visualizar livros em destaque  
- Acessar informações detalhadas de uma obra  
- Consultar dados sobre o autor  

!O projeto é focado na camada de apresentação, não possuindo funcionalidades completas como cadastro ou empréstimo de livros.

---

## Estrutura do site

O sistema possui três páginas principais:

- **Página inicial**  
  Apresenta nome da biblioteca, imagem de destaque, livros recomendados e informações de contato.

- **Página do livro**  
  Exibe capa, sinopse, autor e quantidade de páginas.

- **Página do autor**  
  Mostra imagem e biografia do escritor.

As páginas estão interligadas, permitindo navegação entre elas.

---

## Tecnologias utilizadas

- ASP.NET Core MVC  
- HTML  
- CSS  
- Razor (.cshtml)  
- Visual Studio Code  

---

## Organização do projeto (MVC)

### Controllers
- HomeController → página inicial  
- LivroController → detalhes do livro  
- AutorController → informações do autor  

### Models
- Livro.cs → dados do livro  
- Autor.cs → dados do autor  

### Views
- Views/Home/Index.cshtml → página inicial  
- Views/Livro/Detalhes.cshtml → página do livro  
- Views/Autor/Index.cshtml → página do autor  

### Shared
- Views/Shared/_Layout.cshtml → layout padrão (cabeçalho e navegação)

---

## Como executar o projeto

  ### Pré-requisitos

  - .NET instalado  

  ---

###  Passos

```bash
# Abrir o projeto
# (Visual Studio Code ou Visual Studio)

# No terminal, executar:
dotnet run

