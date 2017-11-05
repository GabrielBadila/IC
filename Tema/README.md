# Amplificator de buzunar CMOY (Romanian language)



	Ingineria calculatoarelor

	Tema - Amplificator de buzunar CMOY

	Badila Gabriel Alin
	333 CA


	============================================================================

	Arhiva temei contine trei fisiere: tema.sch (schematicul), tema.brd 
	(board-ul) si acest Readme.

	In fisierul tema.sch am realizat schema electrica a amplificatorului CMOY 
	cu ajutorul bibliotecilor: rhine-misc.lbr si project-box.lbr, prevazute in 
	documentatia temei, pe baza schemei si a listei de piese, prevazute de 
	asemenea in documentatia temei. Au fost realizate trei circuite: partea de 
	alimentare, canalul stang, respectiv canalul drept al semnalului, ultimele 
	doua fiind comasate intr-un singur circuit din cauza jack-urilor de 
	input/output care legau cele doua circuite. Mentionez ca circuitele au fost 
	realizate in acelasi fisier, deoarece liniile de supply si ground sunt 
	legate in momentul adaugarii surselor/GND-ului, asa cum este precizat si in 
	cerinta temei. Am verificat apoi ca ERC sa nu genereze nicio eroare/warning.
	
	In fisierul tema.brd am realizat partea de board a temei. Am luat piesele 
	aflate la gramada si le-am asezat in chenarul de proiectare al board-ului 
	astfel incat numarul de suprapuneri al conexiunilor dintre piese sa fie 
	minim. Apoi am selectat auto-route si am ales una dintre rutele generate de 
	tool. Am verificat cu DRC, si dupa cum era de asteptat nu exista nicio 
	eroare. Am activat optiunile prevazute in cerinta temei (distantanta intre 
	oricare doua componente = 10mil, verificarea pentru gaurile de burghiu = 
	10mil si dimensiunea pad-urilor sa fie mai mare cu 50% decat valoarea 
	implicita) si am rulat din nou DRC. In urma modificarilor facute era si 
	normal sa apara erori (erorile aparute faceau referire la distanta dintre 
	componente). Am realizat modificarile necesare rutelor, iar DRC nu a mai 
	generat nicio eroare/warning.

	============================================================================
