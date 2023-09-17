# Curso-Docker
Repositório criado para aplicar os conceitos aprendidos no Curso Docker Completo do Zero ao Avançado do instrutor Andre Iacono disponível na Udemy.

### Instalar Projeto e Iniciar o Projeto

### :information_source: Como Usar

### Instalar Projeto e Iniciar o Projeto (APP)

```bash
# Clone o repositório
$ git clone https://github.com/Mvsrodri/Curso-Docker.git

# Entre no repositório
$ cd Curso-Docker/app

# Construir a imagem da aplicação
$ docker build -t Hello-World .

# Visualizar a imagem criada
$ docker images

# Rodar aplicação
$ docker run Hello-World

```

### Instalar Projeto e Iniciar o Projeto (TODO LIST)

```bash
# Clone o repositório
$ git clone https://github.com/Mvsrodri/Curso-Docker.git

# Entre no repositório
$ cd Curso-Docker/todo list

# Construir a imagem da aplicação
$ docker build -t app .

# Visualizar a imagem criada
$ docker images

# Rodar aplicação
$ docker run -dp 3000:3000 app

Rodando na porta 3000
```

### :hammer: Ferramentas

- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker](https://www.docker.com/products/docker-desktop/)
