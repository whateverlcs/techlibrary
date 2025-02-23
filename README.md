# Tech Library

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/whateverlcs/techlibrary?color=black">
  
  <img alt="GitHub Size Repository" src="https://img.shields.io/github/repo-size/whateverlcs/techlibrary?color=black">
    
  <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/whateverlcs/techlibrary?color=black">
  
  <img alt="GitHub Stars Repository" src="https://img.shields.io/github/stars/whateverlcs/techlibrary?style=social">
</p>


Tech Library é uma API de livros de tecnologia. O projeto foi realizado durante o evento NLW Connect.

## Pré-Requisitos

Antes de rodar a aplicação, você deve:

1. Realizar o download do `banco de dados utilizado pela aplicação` presente na pasta deste repositório `db_api`: [Link da Pasta](https://ffmpeg.org/download.html).

## Como usar

1. Clone o repositório: `git clone https://github.com/whateverlcs/techlibrary`.
2. Modifique o caminho do banco em `TechLibrary.API -> Infraestructure -> DataAccess -> TechLibraryDbContext.cs -> optionsBuilder.UseSqlite("Data Source=SEUCAMINHODOBANCOAQUI");`.
3. Realize o Build e rode a solução.