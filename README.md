### Passos para execução da aplicação:
- Certifique-se de ter instalado no seu sistema operacional as ferramentas Git, Python 3, Django e Pip.
- Pelo terminal (preferencialmente o integrado com a IDE), acesse o caminho do diretório do projeto:
  - `cd/<diretório do local do projeto>/Django`.
- O ambiente virtual (virtualenv) não é necessário instalar porque este projeto já possui um configurado (venv).
- No terminal, digite:
  - `source venv/Scripts/activate` ou `. venv/Scripts/activate` à depender da versão do seu Windows;
  - `source venv/bin/activate` no Linux.
- Caso haja a necessidade de instalar o Pip, apague o diretório **venv** já existente no projeto e reinstale o ambiente virtual,
  fazendo no terminal:
  - `pip install virtualenv`(caso este comando gere um erro no Linux, faça `sudo apt install pythonx.y-venv`, onde "x.y" é a versão do python ativa no sistema e/ou na IDE);
  - `python -m venv venv` no Windows ou `python3 -m venv venv` no Linux;
  - Finalmente execute o comando com **source** mostrado acima.
- Ainda no terminal, faça:
  - `cd/<diretório do local do projeto>/Django/barbearia_pdv`;
  - `python manage.py runserver` no Windows ou `python3 manage.py runserver` no Linux.
