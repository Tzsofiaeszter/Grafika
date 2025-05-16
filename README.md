                                                    Hádész, a szabaduló szoba

Leírás:
        - Ez egy OpenGL-alapú 3D szabadulószoba játék, amelyben különböző tematikájú szobák rejtvényeit kell megoldani a továbbjutáshoz.
        - 4db szoba helyzekedik el a központi tér körül - közvetlen kapcsolat van köztük

A játék története:
    Kirándulás közben utolér bennünket egy hatalmas fekete esőfelhő. Nem szeretnénk elázni, ezért menedéket keresünk. Szerencsére meglátunk egy erdei menedékházat, ahova bemenekülünk az eső elől. A vihar elmúltával szeretnénk folytatni utunkat, azonban az ajtó nem nyílik. A rajta lévő papír utasítása szerint össze kell gyűjtenünk 4 darab kulcsot. Majd meg kell találnunk egy nagy ládát, ami egy nyitógombot tartalmaz. Ez fogja nyitni a ház tetején lévő kupolát. 

A szobákban különböző feladatokat kell megoldanunk.

    Ahogy a házba belépünk világosság lesz az előtérben. Szépen berendezett helyiség. Egy hosszú faasztal van középen, körülötte székek. Kellemes meleg van, mert a kandallóban tűz lobog. A falon egy régi ingaóra mutatja az időt. A szemközti falon egy plafonig érő ódon könyvespolc áll, rajta sok-sok régi könyv. 
    Az ajtók zárva vannak. Mindegyik egy 4 jegyű kód segítségével nyílik. 

1.szoba: (nappali)

    Ez a nappali. 
    A szoba közepén szép színes szőnyeg. Ezen egy kis dohányzóasztal áll. Van rajta egy tulipánnal tele váza. Balra, a fal mentén egy sarok ülő garnitúra. Rajta 3 db szép színes párna. Jobbra egy nagy, a teljes falat beborító polcozott szekrény, rajta egy televízió, vázák, fényképek, könyvek és egy olló (ezzel kell felvágni a rózsaszínű párnát, amiben az első kulcs van). Az ablakon átlátszó függöny, így látszik, hogy az ablakon rács van.

        Az ajtón egy találóskérdés van, aminek a megfejtése egy 4 betűs szó, aminek betűi össze vannak keverve. A betűkockák sarkaiban 1-1 szám. Ha a betűket helyesen rakjuk össze, akkor megkapjuk a nyitókódot. Ezt begépelve kinyílik az ajtó. 

        Mikor fekszel, ő akkor kél. Egyszer egész, máskor csak fél. Nincsen tüze, mégis lámpás, A vándornak szinte áldás. => HOLD 

	
2.szoba: (konyha)

    Ez a konyha.
    A helyiség közepén egy fából készült konyhasziget van. A mosogató tele van vízzel. A beépített tűzhelyen van egy piros színű kicsi lábas. Tányérok, poharak és evőeszközök vannak az étkezőrészen, ami körül 4, szintén fából készült szék áll. A főzőrész alatti polcokon színes edények vannak. A szigetet felűről lámpa világítja meg.
    A jobb falon végig húzódó konyhapulton tea és kávéfőző van. A kávékapszulák, a cukor, a teás és kávéscsészék mellettük. A konyhaszekrény fából készült, barna színű teli ajtókkal mind felül, mind pedig alul is. Itt az alsó rész második ajtó előlapján egy 4 színből álló (lila, piros, narancs és zöld) rész található, alatta üres négyzetek. Ide kell beírni a hűtőben található gyümölcsök szín szerinti darabszámát és akkor az ajtó kinyílik. Itt találjuk meg a következő kulcsot.
			
        7-lila	3-piros	2-sárga	5-zöld

        A hatalmas, szürke színű dupla hűtőszekrény az ablak mellett, jobbra a sarokban áll. A hűtőben 3 db piros alma, 7 db lila szilva, 2 db narancs és 5 db lime van. 

        Az ajtón a következő felirat olvasható: „Ki itt belépsz, hagyj fel minden reménnyel!” Kinek a művéből van az idézet? 5 Betű! Ezt a nevet kell begépelni és az ajtó kinyílik. (Dante)

3.szoba: (fürdőszoba)

    Ez a fürdőszoba.
    Ez egy elég kicsi helység. Ballra a WC, szemben velünk a fürdőkád, jobbra pedig a kézmosó és a mosógép van. A kézmosóból csöpög a víz. A kulcs a kézmosó feletti szekrényben található, ami egy környezetről készített kép kirakó.
        Az ajtón egy matematikai feladvány:
        A + A = 18				A = ?			A kód: 9
        A + C = 15				B = ?				5
        B + C = 11				C = ?				6
        D + C = 9				D = ?				3
        Ezt üssük be, és kinyílik az ajtó.


Követelmények:
- OpenGL, GLUT telepítve kell legyen
- Fordításhoz: `make`

Használat:
    1. Fordítás: `make`
    2. Futtatás: `./hadesz`
    3. Kilépés: `ESC` gomb

Funkciók:
- 3D térben mozgatható kamera
- Különböző szobák különféle rejtvényekkel
- Fények és textúrák alkalmazása