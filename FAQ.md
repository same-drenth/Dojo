# Veelgestelde vragen

## Mag ik games maken?

Jazeker! Sterker nog, het programmeren van games is een van de leukste manieren om programmeren te leren.

## Mag ik gamen?

Nee. De Dojo is een cursus avond, waarbij leren voorop staat. Gamen draagt niet bij aan het leren programmeren.
Ook niet voor de cursus, ook niet in de pauze en ook niet na de pauze.
Heb je *zelf* een spel geprogrammeerd, dan krijg je de ruimte om het spel te laten zien en te laten testen.

## Waar ga ik zitten?

Dit is afhankelijk van wat je wilt doen:

  * nieuwe dingen leren: grote tafel in kantine bij het bord
  * samenwerken: andere tafels in kantine
  * rustig alleen werken: aquarium

In het begin zul je veel aan de grote tafel zitten, totdat je zelfstandig kunt werken.

## Wie stel ik een vraag?

  * Zit er een leerling naast je? Zo ja, dan hij/zij.
  * Zit er een leerling aan je tafel? Zo ja, dan hij/zij
  * Als er niemand is of niemand is die het weet, vraag het dan een volwassene

## Waar staan de lessen?

 * De lessen Processing staan [in de map LessenProcessing](LessenProcessing/README.md).
 * De lessen C++ staan [in de map LessenCpp](LessenCpp/README.md).

## Wat als er een nieuwe leerling binnenkomt?

 * De gastheer/gastvrouw vangt hem/haar op:
    * Jas ophangen
    * Naam op de lijst zetten
    * Koppelen aan een leerling die hem/haar op wilt starten: ze gaan dan aan de grote tafel zitten

## Ik wil Processing doen, kan dat?

Ja, dat kan altijd! [Download Processing hier](https://processing.org/download/).

De lessen Processing staan [in de map LessenProcessing](LessenProcessing/README.md).

## Ik wil C++ doen, kan dat?

Ja, dat kan! C++ is wat moeilijker dan Processing, daarom kun je er niet zomaar mee beginnen. 

Om ermee te mogen beginnen moet je:
  * (1) zelf een C++ programmeeromgeving installeren 
  * (2) een voorbeeld SFML of Urho3D programma kunnen laten runnen 
  * (3) dit allemaal zelfstanding Googlen. 

Natuurlijk helpen we je bij je vragen, maar het meeste zul je zelf moeten doen.

De lessen C++ staan [in de map LessenCpp](LessenCpp/README.md).

## Ik wil Arduino doen, kan dat?

Jazeker, maar we geven op de donderdag geen les in Arduino.

Je zou de [Arduino cursus van de vrijdagavond](https://github.com/richelbilderbeek/ArduinoCourse)
kunnen volgen :-)

## Ik wil iets met dieren/planten/biologie doen, kan dat?

Jazeker, maar we geven op de donderdag geen les in dieren/planten/biologie.

Je zou de [biologie cursus van de woensdagavond](https://github.com/DIYbioCourse/BioCourse)
kunnen volgen :-)

## Welke vrijwilligers zijn er?

### Anton

Anton is een volwassen vrijwilliger. Hij zit met Dagmar in de kantine, waar ze vooral Scratch en Processing geven.

### [Dagmar](https://github.com/dagmarhofman)

![dagmarhofman](Images/dagmarhofman.jpg)

Dagmar is een volwassen vrijwilliger. Hij zit met Anton in de kantine, waar ze vooral Scratch en Processing geven.

### [Frode](https://github.com/Modanung)

Frode is een volwassen vrijwilliger. Hij zit met Thijs in het houtlokaal, waar ze vooral Processing en Inkscape geven.

Frode is ook erg handig met 3D tekenen in Blender en 3D games maken in C++ met Urho3D.

### [Jan](https://github.com/janderkkotlarski)

![janderkkotlarski](Images/Photo_March_2017_Small.png)

[Jan geeft les in SFML](https://github.com/janderkkotlarski/Cplusplus-with-SFML-course) en is ook handig
met GameMaker.

### [Jorn](https://github.com/jorn600)

![jorn600](Images/jorn600.jpg)

Jorn is een leerling, gastheer en leraar. 

Jorn vangt de nieuwe leerlingen op.

### [Richel](https://github.com/richelbilderbeek)

![Richel](Images/Richel.png)

Richel is een volwassen vrijwilliger. Hij heeft geen vast lokaal, maar helpt waar het nodig is.

Richel programmeert sinds zijn achtste. Hij is de meest ervaren en belezen programmeur, vooral in C++.
Richel is vooral geinteresseerd in onderwijs en heeft de lerarenopleiding aan de universiteit afgerond.
Hij coordineert de Dojo.

Zijn werk is te zien op [zijn website met meer dan 3900 pagina's](http://richelbilderbeek.nl) en [meer dan 300 GitHub repositories](https://github.com/richelbilderbeek?tab=repositories).

### [Ruben](https://github.com/ruben-bouman)

![ruben-bouman](Images/ruben-bouman.png)

Ruben is een vrijwilliger en helpt nieuwe leerlingen opstarten. 

Ruben is ook leerlingvertegenwoordiger: vind je dat iets aan
de cursus beter kan, dan kun je dit Ruben zeggen. Ruben vertelt
dit dan anoniem (zonder je naam erbij te zeggen) aan de volwassenen.

Vindt je het leuk om leerlingen te helpen opstarten? Laat het
Ruben weten, want hij zal je dan vragen. Wil je liever aan je
eigen werk verder, laat dat Ruben weten.

### [Thijs](https://github.com/thijsvb)

![thijsvb](Images/thijsvb.jpg)

Thijs is een volwassen vrijwilliger. Hij zit met Frode in het houtlokaal, waar ze vooral Processing en Inkscape geven.

Thijs is ook handig met Arduino, te zien aan [de GitHub van de Arduino cursus](https://github.com/richelbilderbeek/ArduinoCourse). 

# Wat is de missie van de cursus?

De missie van De Jonge Onderzoekers is: '[Het] exploiteren van een activiteitencentrum met als doel kinderen op een uitdagende en creatieve manier met techniek en wetenschap in aanraking te laten komen'. De missie van de DOJO heeft veel overlap hiermee. We vinden het belangrijk dat de kinderen iets leren, uitgedaagd worden en hun creativiteit gebruiken om iets te maken. Om dit te bereiken laten we de leerlingen games maken en presenteren, maar het spelen van niet-zelfgemaakte games vinden we niet goed.


## Ik wil niet dat Processing in `Update` scherm laat zien

![Update scherm](Images/Update.png)

In de folder van Processing, bijvoorbeeld `processing-3.2.3`, doe:

```
sed -i "s/update.check = true/update.check = false/" lib/defaults.txt
```

## `Unsupported major.minor version 51.0`. Ik heb Debian

Je hebt Java 8 nodig.

```
su
echo "deb http://ppa.launchpad.net/webupd8team/java/ubuntu precise main" | tee -a /etc/apt/sources.list
echo "deb-src http://ppa.launchpad.net/webupd8team/java/ubuntu precise main" | tee -a /etc/apt/sources.list
apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys EEA14886
apt-get update
apt-get install oracle-java8-installer
```


## `Could not find fonts. Please reinstall processing`. Ik heb Debian

Processing kan de fonts niet vinden. Kopieer ze bij de folder van Java.

```
cd ~/Programs/processing-3.0.1/java/lib/fonts
su
cp *.* /usr/lib/jvm/java-8-oracle/jre/lib/fonts
```

## Could not start `java`. Ik heb Debian

Doe

```
uname -a
```

Dan kun je zien dat je de 64 bit versie moet downloaden :-)
