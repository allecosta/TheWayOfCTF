
# [CTF] Level 10

*Requisito: Manipulação de cookies*

URL: https://www.hackthissite.org/missions/basic/10/

*Este desafio requer conhecimento básico de cookies e como manipular, para chegar ao resultado final.*

![screenshot](/basic/10/img/challenge.png)

![screenshot](/basic/10/img/challenge10.png)

*O enunciado nos passa uma breve informação do que precisariamos fazer, e foi com essa dica que logo pesquisei no browser via javascript, encontrando já de cara a informação que precisavamos.*

![screenshot](/basic/10/img/console.png)

*Porém ao tentar usar como senha a informação encontrada, fomos notificado que não tinhamos autorização para visualizar a página. 

![screenshot](/basic/10/img/block.png)

Neste caso seria necessário alterar o campo ```level10_authorized``` de ```no``` para ```yes```.*

![screenshot](/basic/10/img/cookies.png)

*Com essa modificação, inserimos a senha e obtivemos a conquista do desafio!*

![screenshot](/basic/10/img/congratz.png)