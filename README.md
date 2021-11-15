# GPA-wiki
 Página para divulgação de conteúdo entre o grupo.

 ## Pré requisitos
 
 - Python
 - jupyter
 - jupyter-book
 - matplotlib
 - numpy
 
 
 ## Servindo localmente
 Para rodar a página no seu computador local, rodar no prompt:
 ```
 git clone https://github.com/pedrohlopes/GPA-wiki.git
 cd GPA-wiki/
 pip install -r requirements.txt
 jupyter-book build .
 cd _build/html/
 python -m http.server
 ```
 Depois, basta acessar o endereço que aparece na saída do comando + 'intro.html'. Default: http://localhost:8000/intro.html.

 Obs.: Para atualizar o conteúdo no navegador, atualizar o build rodando `jupyter-book build .` na pasta raiz.


## Documentação
Acessar a página do tutorial de ínicio com o jupyter books: https://jupyterbook.org/start/your-first-book.html

