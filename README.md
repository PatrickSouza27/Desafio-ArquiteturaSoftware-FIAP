# Desafio ArquiteturaSoftware FIAP

<img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">

## O Problema


* Há muitos anos, a Escola Municipal de Ensino Fundamental Pegasus estava passando por muitos desafios de gerenciamento, pois a quantidade de alunos aumentava a cada ano e a infraestrutura do sistema escolar não conseguia acompanhar o ritmo. O conselho escolar decidiu que era hora de modernizar o sistema de ge- renciamento da escola, tornando-o mais eficiente e fácil de usar.

* Foi então que o conselho escolar decidiu convocar os alunos da faculdade de tecnologia local para ajudar a desenvolver um sistema de gerenciamento de escolas que usasse a arquitetura hexagonal. A escola fornece- ria os requisitos e as necessidades do sistema, e os alunos teriam a oportunidade de desenvolver um sis- tema completo do zero
Depois de algumas entrevistas com os stakeholders, os alunos da faculdade de tecnologia chegaram nos seguintes pontos:
O sistema deve permitir aos usuários, como professores e administradores, gerenciar informações sobre alunos, cursos, notas, horários de aula e matrículas. A arquitetura hexagonal deve ser usada para separar a lógica de negócios da infraestrutura, permitindo que o sistema seja facilmente testado e escalável.


## Requisitos




* Os usuários devem ser capazes de criar e atualizar perfis de aluno, incluindo informações pesso- ais, de contato e histórico acadêmico.
* Os usuários devem ser capazes de criar e gerenciar cursos, incluindo informações sobre os pro- fessores, materiais didáticos e horários de aula.
* O sistema deve ser implementado em uma linguagem de programação à escolha dos alunos, mas é recomendado que usem uma linguagem orientada a objetos.
Esses foram os requisitos básicos levantados pelos alunos para que pudessem desenvolver o MVP do projeto.
* A ideia do desafio será você desenvolver um sistema (API) sem frontend, com a finalidade de atender os re- quisitos mínimos levantados pelos alunos da faculdade técnica.


## Entregáveis

* Desenho da arquitetura proposta, pode ser no draw.io, word, onde você se sentir confortável em demonstrar o desenho básico da arquitetura e da infraestrutura do seu projeto;
* Desenvolvimento de uma solução baseada na arquitetura hexagonal, focando na divisão das res- ponsabilidades do Core e dos atores condutores e conduzidos;
Na parte do Core, modelar as suas entidades focando nas boas práticas de desenvolvimento de software mencionados em aula;
* Nos atores condutores, desenvolver uma uma API na linguagem de programação de sua escolha;
* Nos atores conduzidos, criar um banco de dados com Docker ou no caso de escolher o Post- greSQL, utilizar o Supabase para criação de base de dados gratuita. Ainda nos atores conduzidos, criar uma camada de cache para aplicação (não esquecer de adicionar ela no desenho de infra estrutura do projeto);
* Criar testes unitários para garantir que o sistema esteja funcionando corretamente;
* Criar um teste de carga com o K6 para exercitar o que aprendemos em aula.
