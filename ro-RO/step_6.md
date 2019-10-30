## Încorporarea proiectelor

Pe lângă redirecționarea către trinket-uri ca pagini web, putem, de asemenea, să le încorporăm într-o pagină web.

+ Dacă vrei, poți lucra în modul Fullscreen pentru a avea mai mult spațiu:

![captură de ecran](images/showcase-fullscreen.png)

Apasă Esc pentru a ieși din modul Fullscreen.

+ Rulează trinket-ul și apasă pe link-ul „La mulți ani”.

+ Apasă pe meniul trinket și selectează **embed**. Dacă nu ești în modul Fullscreen, e posibil să fie nevoie să folosești scroll-ul. Folosește bara de scroll din dreapta sau săgeata în jos de pe tastatură.

![captură de ecran](images/showcase-embed-code.png)

+ Alege „Only show code or result (let users toggle between them)” și **copiază** codul de încorporare pentru trinket. 

![captură de ecran](images/showcase-embed.png)

+ Trinket a creat niște HTML pentru a îl putea include în pagina ta web. Folosește tag-ul `<iframe>`, care permite conținutului să fie încorporat într-o pagină.

+ Acum lipește acel cod sub link-ul către trinket-ul „La mulți ani”:

![captură de ecran](images/showcase-paste-embed.png)

+ Rulează trinket-ul pentru a îl testa și ar treubi să vezi proiectul tău „La mulți ani” încorporat în pagina web. 

![captură de ecran](images/showcase-embed-output.png)

+ Este posibil ca partea inferioară a trinket-ului să nu fie afișată. Poți rezolva acest lucru prin schimbarea valorii „height” în `<iframe>`. 

![captură de ecran](images/showcase-embed-height.png)

Setează „height” ca **400**. Dacă ai făcut schimbări la proiectul „La mulți ani”, e posibil să fie necesară alegerea altei valori.

![captură de ecran](images/showcase-embed-fixed.png)