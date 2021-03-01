# 01-04-02-if-elagazas-1
## Egyágú elágazás
Bevezető feladatok
Ezeknél a feladatoknál az elágazásban csak igaz ágat használjon!
```
if (…) {
   …
}
```
1. feladat  
Írjon programot, amely a megadott szám esetén kiírja „Az x szám páratlan.” szöveget, ha az páratlan!  
2. feladat  
Legyen adott az int password=12345; kódrészlet.  
Egészítse ki ezt a kódrészletet a következő feladat alapján!  
Kérje be a felhasználótól a jelszót, és írja ki a „Jelszó helytelen!” szöveget, ha a beírt jelszó nem egyezik a megadott „password” változó értékével!  
3. feladat  
Legyen adott a következő kódrészlet. Egészítse ki ezt a kódot úgy, hogy csak akkor legyen a program felhasználóbarát, ha a „userFrendly” változó értéke true!
```
bool userFrendly=true;
System.out.print("Megmondom, hogy ön felnőttkorú-e!");
System.out.print("Adja meg hány éves:");
Scanner in=new Scanner(System.in);
int year=in.nextInt();  
if (year>18) {
	System.out.print("Ön már felnőtt korú!");
}
```

