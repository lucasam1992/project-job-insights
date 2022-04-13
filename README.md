# Boas vindas ao repositório do projeto Job Insights!

O projeto teve como intuito o desenvolvimento de análises de um conjunto de dados sobre empregos. A partir dos arquivos
`csv` que estão no diretório `tests/mocks` foram desenvolvidas as pesquisas nos arquivos. Os dados foram extraídos do site [Glassdoor](https://www.glassdoor.com.br/) e obtidos através do [Kaggle](https://www.kaggle.com/atharvap329/glassdoor-data-science-job-data), uma plataforma disponiblizando conjuntos de dados para cientistas de dados.

## Tecnologias Usadas
 - Python
 - Flake8


## Rodando o Projeto Localmente

1° `git clone https://github.com/lucasam1992/project-recipes-app.git` - Clone o repositório para sua máquina

2° `cd sd-010-a-project-job-insights` - Entre na pasta do repositório clonado

3° `python3 -m venv .venv && source .venv/bin/activate` - Crie e ative o ambiente virtual para o projeto

4° `python3 -m pip install -r dev-requirements.txt` - Instale as dependências

5° `flask run` - Rode a aplicação flask para visualizar o resultado do projeto

** Após rodar o quinto passo, acesse `http://localhost:5000`. 

## Requisitos

- 1 - Implemente a função `read` - Função responsável por abrir o arquivo CSV e retornar os dados no formato de uma lista de dicionários.

- 2 - Implemente a função `get_unique_job_types` - Função retorna uma lista de valores únicos presentes na coluna `job_type`.

- 3 - Implemente a função `get_unique_industries` - Função retorna uma lista de valores únicos presentes na coluna `industry`

- 4 - Implemente a função `get_max_salary` - Função retorna *um valor inteiro* com o maior salário presente na coluna `max_salary`

- 5 - Implemente a função `get_min_salary` - Função retorna *um valor inteiro* com o menor salário presente na coluna `min_salary`.

- 6 - Implemente a função `filter_by_job_type` - Função retorna uma lista com todos os empregos onde a coluna `job_type` corresponde ao parâmetro `job_type`.

- 7 - Implemente a função `filter_by_industry` - Função retorna uma lista de dicionários com todos os empregos onde a coluna `industry` corresponde ao parâmetro `industry`.

- 8 - Implemente a função `matches_salary_range` - Função retorna `True` se o salário procurado estiver dentro da faixa salarial ou `False` se não estiver.

- 9 - Implemente a função `filter_by_salary_range` - Função retorna uma lista com todos os empregos onde o salário `salary` estiver entre os valores da coluna `min_salary` e `max_salary`.

- 10 - Implemente um teste para a função `sort_by` - Garantir que a ordenação para `min_salary` deve ser crescente, mas para `max_salary` ou `date_posted` devem ser decrescentes. 

- 11 - Requisito Bônus - Implemente a página de um job - Função renderiza o template `job.jinja2`, passando um parâmetro `job` contendo o job retornado pela `get_job`.


# Autor
 - Lucas Machado
