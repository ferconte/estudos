#### O que é Docker?

*Docker é uma ferramenta/plataforma open source (código aberto) que ajuda na criação e administração
de ambientes isolados (containers).*

![01vmvsdocker](https://user-images.githubusercontent.com/108905120/177891630-eae5ca49-831b-4f7d-849f-ef79da27d8b6.png)

#### O que é um container?

*É um ambiente completo e isolado que pode armazenar todos os arquivos e configurações de uma aplicação.*

![01container](https://user-images.githubusercontent.com/108905120/177891670-85208947-2283-40d2-a671-5eac4551856e.png)

#### Namespaces e Cgroups

*O Docker utiliza de recursos do linux como por exemplo namespaces, cgroups dentre vários outros para isolar os containers que serão executados. (Conhecimento intermediário/avançado).*

#### Componentes do Docker

Para explicar os compenentes, iremos executar um container com o comando:

$ `docker container run --rm -it hello-world`

- *O Docker Client se comunicou com o Docker Daemon.*
- *O Docker Daemon fez o download da imagem hello-world no Docker Hub.*
- *O Docker Daemon criou um novo container, através da imagem que rodou o executável que produz o texto que vimos no terminal.*
- *O Docker Daemon enviou o texto diretamente para o Docker Client que enviou para nosso terminal.*

![01componentes](https://user-images.githubusercontent.com/108905120/177891687-ade596d0-55ee-42d8-8a6b-386dc13bdb0f.png)
