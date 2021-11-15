# GPA-wiki
 Página para divulgação de conteúdo entre o grupo.

 ## Pré requisitos:
 
 - Python
 - jupyter (via pip)
 - jupyter-book (via pip)
 
 
 ## Servindo localmente
 Para rodar a página no seu computador local, rodar no prompt:
 ```
 git clone https://github.com/pedrohlopes/GPA-wiki.git
 cd GPA-wiki/
 jupyter-book build .
 python -m http.server
 ```
 Depois, basta acessar o endereço que aparece na saída do comando. Default: http://localhost:8000.
