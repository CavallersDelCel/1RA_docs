# Pas 7: Descàrrega de mods

S'ha creat una recopilació de mods per fer servir a les partides del grup per tal de potenciar i millorar el realisme, alhora que dona més opcions al grup.

* Millora el realisme.
* Millora el comportament de la IA del simulador.
* Ofereix un parc armamentístic immens.
* Ofereix una quantitat immensa de vehicles.
* Ofereix eines que faciliten la tasca del soldat.
* Cobreix diferentes èpoques històriques.

## Instal·lació ArmA3Sync

Per poder descarregar els mods cal que instal·lis l'aplicació ArmA3Sync. Aquesta permet actualitzar els nostres "mods" de forma automàtica, alhora que serveix de llançadora de l'ArmA 3.

Un dels seus principals atractius, és que compara els fitxers dels teu ordinador amb els fitxers oficials del servidor. Si no coincideixen, només descarrega els fitxers que son diferents.

* Podeu descarregar l'última versió de l'Arma3Sync a través d'[aquest enllaç](http://hosted.anrop.se/arma3sync.exe).
* *Requereix [Java](http://www.java.com/en/download) per funcionar.*

Un cop instal·lat el programa, quan l'executis és possible que et pregunti on tens instal·lat l'ArmA 3. Li has d'indicar la carpeta arrel de l'Arma 3, sovint es troba dintre de la carpeta Steam `...\Steam\SteamApps\common\Arma 3`. Si has de seleccionar l'executable del simulador, assegura't de seleccionar el de 64 bits, es a dir `arma3_x64.exe`.

## Configuració ArmA3Sync

Fet això, escollirem la carpeta on vols descarregar els "addons". Aquesta carpeta pot ser a qualsevol lloc, inclús en un disc dur diferent al que tens instal·lat l'ArmA 3.

Per a fer-ho ves a la pestanya `Addon Options` i dins del requadre `Addon Search Directories` clica el botó `+` que hi ha a la dreta i selecciona el directori que vulguis. Si no saps quin seleccionar, pots seleccionar el mateix de l'ArmA 3.

![image](_imatges/addonoptions.png){: .center}

Un cop fet això, has d'establir les opcions de llançament. Clica la pestanya `Launcher Options`.

![image](_imatges/launcheroptions.png){: .center}

A les opcions de l'esquerra marca `No Splash Screen` i `Default World Empty`. A la casella de la dreta, escriu `-skipintro`.

Aprofita per verificar que l'executable de l'ArmA 3 sigui `arma3_x64.exe`.

## Descàrrega

A partir d'aquí has de configurar i descarregar tots els nostres repositoris de mods. Has de repetir els passos següents per a cadascun dels següents repositoris:

`http://www.cavallersdelcel.cat/magatzem/ArmA/repositori_a3sync/0_basic/.a3s/autoconfig`

`http://www.cavallersdelcel.cat/magatzem/ArmA/repositori_a3sync/1_terrain/.a3s/autoconfig`

`http://www.cavallersdelcel.cat/magatzem/ArmA/repositori_a3sync/2_moderna/.a3s/autoconfig`

`http://www.cavallersdelcel.cat/magatzem/ArmA/repositori_a3sync/3_historica/.a3s/autoconfig`

1- Has d'anar a la pestanya del final, `Repositories`. Fes clic al primer botó, el signe + blau.

![image](_imatges/repositories1.png){: .center}

2- A la primera casella has de posar l'adreça del repositori i clicar el botó `Import`.

![image](_imatges/repositories2.png){: .center}

3- Això farà que s'omplin les caselles restants. Ara només queda clicar `Ok`.

![image](_imatges/repositories3.png){: .center}

4- Per accedir al repositori que acabes de configurar, selecciona’l a la llista i fes clic al botó de la fletxa blava.

Nota: Si ho desitges, pots marcar les caselles `Notify` i `Auto` per a que t'avisi de quan hi ha novetats i intenti actualitzar-lo de forma automàtica. Tingues present que solem avisar amb antelació quan cal actualitzar.

![image](_imatges/repositories4.png){: .center}

5- Ja al repositori, has clicar el botó verd `Check for addons`. Aquest comprova si tens els mods descarregats correctament. Després comprova que tens seleccionada la adreça on es descarregaran els mods. Marca la casella `Select All` i seguidament clica el botó `Play`.

![image](_imatges/repositories5.png){: .center}

El procés descarrega fitxer a fitxer. Si tens algun error, pots esperar uns 10 minuts i tornar-ho a intentar. No et preocupis, ho continuarà descarregant allà on s'havia quedat. Si es repeteix sovint, contacta a un company del grup.

!!! danger "Important"

	És habitual que el proces de descàrrega doni errors amb codi 503, això sol passar quan hi ha algú més a part de tu descarregant els mods. Com hem dit, espera 10 minuts i torna-ho a intentar fins que es descarregui tot.

Més endavant quan hagis d'actualitzar els mods, hauràs de seguir el mateix procés.

## Configuració dels modsets

Un cop tinguis els mods descarregats, és el moment de configurar els modsets. Els modsets son una mena de "carpetes" virtuals que permeten agrupar els mods per grups. És important ja que no sempre carreguem els mateixos mods per a totes les missions.

Per a configurar els modsets simplement has d'anar a la pestanya `Addons` i clicar el botó `Modsets`.

![image](_imatges/modsets1.png){: .center}

S'obrirà una finestra com la següent. Marca totes les caselles i clica `Ok`.

![image](_imatges/modsets2.png){: .center}

Fes clic dret al requadre de la dreta i crea tres nous grups que es diguin `GM`, `PF` i `WS`.

![image](_imatges/modsets3.png){: .center}

Seguidament fes clic a la pestanya `DLC` (requadre de l'esquerra) i arrossega `GM` dins el grup `GM` i `vn` dins el grup `PF`.

![image](_imatges/modsets4.png){: .center}

Fes el mateix amb el `WS`:

![image](_imatges/ws.png){: .center}

Ja gairebé ho tens!

[Següent pas >](http://arma.cavallersdelcel.cat/gn/pas8)
