# Programação Aplicada a Mecânica Técnica

## Descrição
Algoritmos desenvolvidos durante a disciplina de Mecânica Técnica, para aprimorar o entendimento dos conceitos de forças e momentos. 
O projeto contempla tanto atividades avaliativas quanto exercícios propostos em sala de aula.

## Estrutura
-   `notebooks/`: Pasta com os notebooks de exercícios;
-   `arquivos/`: Saídas de relatórios em PDF renderizados com a ferramenta `quarto`;
-   `pyproject.toml`: Arquivo com a as configurações de projeto (versão do python e dependencias).

## Recursos
-   `uv`: Gerenciador de dependencias e versões do python;
-   `quarto`: Renderizador de notebooks em varios formatos (PDF, HTML e etc.).

## Comandos
### Inicializa o projeto
-   `pip install uv` (execute apenas uma vez)

### Inicializar o servidor do Jupyter
-   `uv run jupyter notebook`

### Adicionar algum pacote extra
-   `uv add <pacote>`

### Alterações no arquivo `pyproject.toml`
-   `uv sync`
   
### Comando para renderizar os notebooks como PDFs
-   `quarto render ./notebooks/<notebook_especifico>.ipynb --output-dir ../arquivos/`
