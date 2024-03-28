Para iniciar o projeto usando venv, siga estes passos:

1. Abra um terminal e navegue até o diretório raiz do projeto.
2. Crie um novo ambiente virtual executando o seguinte comando:
```
python -m virtualenv .venv
```
Isso criará um novo diretório chamado 'venv' que conterá o interpretador Python e a biblioteca padrão.
3. Ative o ambiente virtual:
- No Windows, execute:
  ```
  venv\Scripts\activate
  ```
- No macOS e Linux, execute:
  ```
  source venv/bin/activate
  ```
O prompt do terminal deve agora mudar para mostrar o ambiente ativado.
4. Instale as dependências do projeto usando o pip:
```
pip install -r requirements.txt
```
Isso instalará todas as pacotes necessárias listados no arquivo 'requirements.txt'.
