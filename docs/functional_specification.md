# Funkcionális specifikáció  
### A rendszer céljai és nem céljai.
### Jelenlegi helyzet leírása 
Mi egy általános iskolákat összefogó tanári szervezet vagyunk, célunk, hogy a város minden általános iskolása ugyanabban a tanítási minőségben részesüljön, mint bármelyik társa.       
Az iskoláink tanulóinak többsége **Microsoft Windows** felhasználó, így
alapértelmezetten **a gyári számológépet használják** különböző számításai igényeik kielégítésére.      
Észrevettünk azonban egy egyre nagyobb mértékeket öltő tendenciát, a nebulók
elhagyják _szeretett_ Microsoft Windows operációs rendszerünket egy újabb, még általunk is alig ismert, általuk __GNU+Linux__-nak nevezett operációs rendszerekre.       
__Olyan rendszereket használnak, mint például:__   
* Arch Linux
* Gentoo
* Manjaro
* Fedora
* Hannah Montana Linux
* Pop! OS    

De természetesen akadnak még Windows felhasználók is.   
Ezeknél a rendszereknél azt tapasztaltuk, hogy a beépített számológépek nagyon eltérőek egymástól, így egyelőre még Windows-os számológépet ajánljuk használatra és használjuk oktatásra.    

---

### Vágyálomrendszer leírása

A csoportunk nagyon fontosnak tartja, hogy tanárokként lépést tartsunk a technológiával, hogy a lehető legkorszerűbb eszközöket használjuk az oktatásban, illetve védeni tudjuk diákjainkat az új technológiák jelentette veszélyektől.    
Dedikáltságunkat semmi sem jelzi jobban, mint például **a 80 éves Stefi** bácsi esete, aki a beszterce-lakótelepi általános iskolások testnevelő tanára, aki nemrégiben feltelepítette számítógépére az **Arch Linux** Linux disztribúciót egy úgynevezett ``dwm`` ablakkezelő rendszerrel, hogy naprakész maradjon a fiatalsággal, így jobban tudva motiválni őket a sportolásra.     
Amit mi szeretnék, az a szoftverek egységesítése a különböző platformokra. Nem szeretnénk eltiltani a tanulókat a választás lehetőségétől, a digitális szabadságuk fenntartása az érdekünk, viszont annak érdekében hogy az intézményekben hatékonyan tudjunk tanítani egy-egy programot szeretnénk használni egy-egy konkrét feladatra egységesen.  


Először is szeretnénk rendelni egy olyan számológépet ami nem függ az operációs rendszertől, a számológép támogasson haladó matematikai számításokhoz szükséges funkcionalitást is, pl trigonometria függvények. Az operációs rendszer függetlenségét úgy tudjuk, hogy a Java nyelv támogatja, ezt a technológiát preferálnánk.    
Továbbá, szeretnénk, ha a számológép támogatna egyfajta __"Történelem"__ módot, tehát az elvégzett számításokat szeretnénk eltárolni amíg a program fut, illetve szeretnénk egy __"Rögzítés"__ módot is ahol a tanulók feltudják venni az általuk lenyomott gombokat, majd visszajátszani.     

--- 
### Jelenlegi üzleti folyamatok modellje.
### Igényelt üzleti folyamatok modellje.
### Követelménylista.
### Használati esetek[Use cases].
### Megfeleltetés, hogyan fedik le a használati esetek a követelményeket.
### Képernyő tervek.
### Forgatókönyvek.
### Funkció –követelmény megfeleltetés.
### Fogalomszótár
Fogalmak:
* **Linux**: Avagy Linux-rendszermag, rendszermag.  
* **Rendszermag**: Az operációs rendszer erőforrásait kezelő program.
* **Linux disztribúció**: A Linux-disztribúciók a Linux-kernelre épülő terjesztések. Linux kernel mellett több-kevesebb szabad szoftvert és kereskedelmi szoftvert tartalmazhatnak.  
* **GNU/Linux, GNU+Linux, ...**: Linux nem egy operációs rendszer magában, inkább egy újabb szabad komponense a teljesen fukcionáló GNU rendszernek, amelyeket a GNU corelibs, shell eszközök és létfontosságú rendszerkomponensek műküödtetnek egy teljes OS-ként, POSIX-meghatározás szerint.
* **GUI (Graphic User Interface)**: A felület amit a felhasználó lát és ahol a program funkcióit használja
* **Előzmény (History) mód**: A korábban elvégzett műveletek listája.
* **Felvétel (Record) mód**: Műveletek egy sorának kimentése későbbi felhasználásra.
* **Cross-Platform**: Másnéven platformfüggetlenség, mely olyan operációs rendszerekre, programozási nyelvekre vagy számítógépes programokra, szoftverekre és implementációikra vonatkozik, amelyek több számítógépes platformon képesek mülködni. 
* **Platform**: Olyan hardver- és/vagy szoftverkörnyezet, mely meghatározza, hogy az adott számítógépen milyen más programok használhatók.