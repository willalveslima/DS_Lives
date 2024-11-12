# Dicas de uso

Para utilizar um ambiente virtual (venv) com Jupyter Notebook no Visual Studio Code (VS Code), siga os passos abaixo:

1. **Crie um ambiente virtual**:
   - Abra o terminal no VS Code.
   - Navegue até o diretório do seu projeto.
   - Execute o comando `python -m venv nome_do_ambiente` para criar o ambiente virtual.

2. **Ative o ambiente virtual**:
   - No Windows, execute `nome_do_ambiente\Scripts\activate`.
   - No macOS e Linux, execute `source nome_do_ambiente/bin/activate`.

3. **Instale o Jupyter**:
   - Com o ambiente virtual ativado, instale o Jupyter Notebook executando `pip install jupyter`.

4. **Adicione o kernel do Jupyter**:
   - Ainda com o ambiente virtual ativado, adicione o kernel do Jupyter com o comando `python -m ipykernel install --user --name=nome_do_ambiente`.

5. **Abra o Jupyter Notebook no VS Code**:
   - No VS Code, abra a paleta de comandos (Ctrl+Shift+P) e digite `Jupyter: Create New Blank Notebook`.
   - Selecione o kernel que você adicionou anteriormente (nome_do_ambiente).

6. **Verifique se o kernel está ativo**:
   - Certifique-se de que o kernel do Jupyter Notebook está usando o ambiente virtual que você criou.

Seguindo esses passos, você conseguirá utilizar um ambiente virtual com Jupyter Notebook no VS Code. Se precisar de mais alguma coisa, estou à disposição!
