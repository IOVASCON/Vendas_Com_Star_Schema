# Projeto Star Schema: Análise dos Professores

Este projeto documenta a criação de um modelo de banco de dados utilizando o Star Schema focado na análise de dados de professores, suas disciplinas, cursos, e departamentos em uma instituição de ensino.

## Visão Geral

O objetivo deste projeto foi desenvolver um schema em estrela para facilitar a análise dos dados relacionados aos professores, cursos e disciplinas, permitindo análises detalhadas e agregadas sem a complexidade de múltiplos joins. As tabelas de dimensão e a tabela fato foram configuradas para permitir uma visualização clara e direta das relações de dados.

## Ferramentas Utilizadas

- **SqlDBM**: Ferramenta online para modelagem de dados SQL, utilizada para criar e visualizar o diagrama do Star Schema.
- **GitHub**: Utilizado para armazenar e compartilhar o diagrama e a documentação do projeto.

## Etapas do Projeto

### 1. Definição do Schema

As tabelas a seguir foram definidas para compor o nosso Star Schema:

- **Professor**: Armazena informações detalhadas dos professores.
- **Departamento**: Contém dados sobre os departamentos acadêmicos.
- **Curso**: Registra informações sobre os cursos oferecidos.
- **Disciplina**: Inclui detalhes sobre as disciplinas ministradas.
- **Data**: Guarda informações de data para análises temporais.
- **Fato_Professores**: Tabela fato que conecta todas as dimensões com métricas relevantes.

### 2. Configuração das Tabelas e Relacionamentos

Cada tabela foi configurada com campos específicos adequados às análises pretendidas. Relacionamentos de chave estrangeira foram estabelecidos entre a tabela fato e cada uma das tabelas de dimensão para facilitar as consultas.

### 3. Exportação e Compartilhamento

O diagrama final foi exportado como uma imagem PNG do SqlDBM e carregado no repositório GitHub deste projeto para fácil acesso e visualização.

## Diagrama

A imagem abaixo mostra o diagrama Star Schema criado para este projeto:

![Diagrama Star Schema](https://github.com/IOVASCON/Vendas_Com_Star_Schema/blob/main/Professor_Star_Schema-V3.PNG)

## Conclusão

Este projeto proporcionou uma estrutura robusta para a análise de dados educacionais, com foco na atividade docente, e demonstrou a utilidade de um modelo de dados bem planejado. O Star Schema facilitou a criação de relatórios e dashboards, permitindo uma compreensão mais profunda dos padrões e tendências dentro da instituição.

OBS: Favor verificar o arquivo "Observações Importantes.docx" para outras considerações e passo a passo.
