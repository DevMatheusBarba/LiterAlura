# LiterAlura
Este projeto é um desafio proposto no programa ONE - Oracle Next Education. Um programa de ensino realizado em parceria da Alura com a Oracle.

### Descrição do desafio
Desenvolver um Catálogo de Livros que ofereça interação textual (via console) com os usuários, proporcionando no mínimo 5 opções de interação. 
Os livros e autores serão buscados através da API Pública [Gutendex](https://gutendex.com/) específica e registrádos em um banco de dados.

### Funcionalidades
- Buscar livro por título
- Listar livros registrados
- Listar Autores
- Listar Autores vivos em determinado ano
- Listar Livros em determinado Idioma


### Tecnologias utilizadas
- Java 21
- Maven
- Spring Boot
- Banco de dados Postgre
- API [Gutendex](https://gutendex.com/)

### Resultado
![Menu](https://github.com/DevMatheusBarba/LiterAlura/blob/main/assets/menu.PNG)

![Pastas pacotes e arquivos e classes do projeto](https://github.com/DevMatheusBarba/LiterAlura/blob/main/assets/Classes.PNG)

![Livros](https://github.com/DevMatheusBarba/LiterAlura/blob/main/assets/consulta-livros.PNG)

### Instalação
Para executar a aplicação localmente, siga estas etapas:
1. Clone este repositório.
2. Certifique-se de ter a JDK do Java 21 ou superior instalado.
3. Importe o projeto utilizando o Maven em uma IDE se sua preferida. 
4. Configure o PostgreSQL atualizando as configurações no arquivo application.properties.
5. Execute a classe LiterAluraApplication.java.
