# Diário do projeto

## Sessão 1 (26/10/2026): preparar o ambiente
- **O que fiz:** pensei no projeto, criei a pasta do projeto, extraí os dados, criei o venv, instalei as bibliotecas, configurei o Git e subi o primeiro commit no GitHub.
- **Dificuldades:** (Escolher o projeto, definir a estrutura)

- **Descobertas:**
  - O Jupyter Notebook roda dentro do próprio VS Code, sem abrir navegador: basta a extensão Jupyter, o `ipykernel` no venv e escolher o kernel do `venv` no canto superior direito.
  - Para conferir o kernel certo: `import sys; print(sys.executable)` deve mostrar o caminho do `venv`.
  - O arquivo `.ipynb` guarda código, texto e resultados (tabelas e gráficos), então vai para o Git e o GitHub mostra tudo formatado.
  - Pasta vazia não sobe no Git; o Git só guarda arquivos.