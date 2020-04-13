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

![screenshot](images/showcase-paste-embed.png)

+ Run your trinket to test it and you should see your Happy Birthday project embedded in the webpage. 

![screenshot](images/showcase-embed-output.png)

+ You may find that the bottom of your trinket isn't displayed. You can fix that by changing the height value on the `<iframe>`. 

![screenshot](images/showcase-embed-height.png)

Set the height to **400**. If you made changes to the Happy Birthday project you might need to choose a different value.

![screenshot](images/showcase-embed-fixed.png)