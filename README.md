# replicacao-pesquisa

Repositório para extração e análise de dados a fim de replicar uma pesquisa. Atividade para a disciplina de Fundamentos da Pesquisa Científica em Ciências da Computação 1 e 2

Reanalise feita a partir de novos dados gerados com base no artigo: Understanding the Factors that Impact the Popularity of GitHub Repositories - DOI: 10.1109/ICSME.2016.31

O repositório está organizado em 3 pastas:
- extracao: Contém um notebook em Python com a extração dos dados
- dados: Contém dos dados extraídos e processados em formato csv
- analise: Contém os arquivos oriundos da análise feita em R, bem como as visualizações geradas

A extração dos dados foi feita na linguagem Python utilizando a própria api do github e a biblioteca PyGithub. 
A extração final dos dados foi realizada do dia 7 de julho de 2019.

Sobre os dados extraídos:

- 'id': Id do repositório 
- 'full_name': Nome completo do repositório
- 'description': Descrição curta do repositório
- 'owner_type': Tipo de dono do repositório. Pode ser Usuário ou Organização.
- 'owner_url’: Url do proprietário do repositório via api do github.
- ’owner_html_url': Url do proprietário do repositório na interface web do github.
- 'html_url': Url do repositório na interface web do github.
- 'url': Url do repositório via api do github.
- 'fork’: Se o repositório é oriundo de um fork.
- 'created_at': Quando o repositório foi criado.
- 'updated_at': Quando o repositório sofreu update.
- 'size': Tamanho do repositório.
- 'stargazers_count': Quantidade de stars.
- 'language': Linguagem predominante no repositório.
- 'has_issues': Se tem issues.
- 'has_wiki': Se tem wiki.
- 'forks_count': Quantidade de forks que o repositório sofreu.
- 'forks': Quantidade de forks que o repositório sofreu.
- 'open_issues': Quantidade de issues abertas.
- 'watchers': Quantidade de pessoas que tem interesse em observar o repositório.
- 'commits': Quantidade de commits recebido.
- 'contributors': Quantidade de contribuidores.
- 'timestamp_extract': Timestamp de quando os dados foram extraídos
