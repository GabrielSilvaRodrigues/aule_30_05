# aule_30_05
Aula de Estrutura de Dados, sobre arvores.
# Repositório Modelo

## Boas Práticas

- O nome do repositório precisa ter o mesmo nome do Projeto. Por Exemplo: Projeto SIGA.
- Todo arquivo README precisa informar:
    - Visão Geral do Projeto;
    - As Tecnologis utilizadas;
    - Como instalar ou utilizar esse projeto;
    - Quem contribuiu (A Equipe);
    - Como pode contribuir? (Comunidade externa que visualiza esse repósitorio PÚBLICO).

## Organização de Pastas

- Toda pasta 
    -/src -> A pasta indicada para colocar o código fonte do projeto;
    -/test -> A pasta é indicada para colocar os testes unitérios;
    -/public -> A pasta é indicada para colocar o Front-End ou qualquer arquivo que precisa ficar a nível Público. A nível de API, ter

## Na raiz do Projeto
- É necessário ter:
    - .gitignore: é utilizado para informar ao git quais extenções ou pastas são ignoradas;
    - LISCENSE: é informado qual é a liscença do projeto (obrigatório quando o projeto é Público);
    -

## Gerenciar Branchs
- Um projeto pode ter algumas dessas branchs abaixo:
    - main (ou master): Versão estável do Projeto (ou aquilo que o público está utilizando no momento);
    - homolog (ou tests): versão posterior a de desenvolvimento, ou seja, é a de testes. Normalmente ela antecipa a main;
    - develop:
        - versão em desenvolvimento;
        - centralizadora das modificações
    - branchs relacionadas ao card do kanban:
    - flow das branchs:
        - branch-de-trabalho -> develop -> homolog -> main