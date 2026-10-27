# Diário do projeto

## Sessão 1 (26/10/2026): preparar o ambiente
- **O que fiz:** pensei no projeto, criei a pasta do projeto, extraí os dados, criei o venv, instalei as bibliotecas, configurei o Git e subi o primeiro commit no GitHub.
- **Dificuldades:** Escolher o projeto, definir a estrutura
- **Descobertas:**
  - O Jupyter Notebook roda dentro do próprio VS Code, sem abrir navegador: basta a extensão Jupyter, o `ipykernel` no venv e escolher o kernel do `venv` no canto superior direito.
  - Para conferir o kernel certo: `import sys; print(sys.executable)` deve mostrar o caminho do `venv`.
  - O arquivo `.ipynb` guarda código, texto e resultados (tabelas e gráficos), então vai para o Git e o GitHub mostra tudo formatado.
  - Pasta vazia não sobe no Git; o Git só guarda arquivos.

  ## Sessão 2 (26/10/2026): extrair dados
  - **O que fiz:** importei o `pandas`, realizei a leitura do arquivo CSV, carreguei-o em um `DataFrame` e exibi as 10 primeiras linhas das colunas do arquivo CSV no terminal com `.head(10)`, além das informações dos dados com `.info()`.
  - **Dificuldades:** escolher nome para o DataFrame, escolher como exibir dados brutos no terminal (`.to_string()`, `.head()`, etc.), entender o `.info()` do DataFrame.
  - **Descobertas:**
    -  '`../`' acessa a raíz do projeto para caminhos de diretórios.
    - '`.head(10)`' decide o número de linhas a serem exibidas(Ex. 10)