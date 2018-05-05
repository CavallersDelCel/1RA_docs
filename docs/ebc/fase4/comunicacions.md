# Comunicacions

Hi han diverses opcions de comunicació disponibles per qualsevol jugador d'Arma. El simulador ve amb un sistema de veu sobre xarxa (VON), que és bastant flexible, mentre que els mods creats per la comunitat, com l'Advanced Combat ràdio Environment (ACRE) o el Task Force ràdio Arrowhead (TFAR) permeten fins i tot unes comunicacions més avançades. Com que actualment fem servir el mod ACRE 2, la terminologia aquí donada es basa en el funcionament de les comunicacions amb aquest sistema de ràdio avançat.

## Canals del simulador

El simulador té el seus propis canals predefinits, que serveixen tant per la comunicació per xat com per ràdio (el sistema VON del propi simulador). Aquests canals serveixen per separar les comunicacions, de manera que només es transmeti la informació per el canal correcte.

Els canals que incorpora el simulador són:

**Canal**     	| **Destinataris** 
--------------- | ----------------------------------------------------------
**Global**    	| Transmet a tothom, inclòs bàndol enemic o neutral.
**Bàndol**  	| Transmet a tot el bàndol al qual pertany el jugador.
**Comandament** | Transmet als líders.
**Grup**   		| Transmet als jugadors del teu mateix grup.
**Vehicle**   	| Transmet als jugadors del vehicle en el qual et trobes.
**Directe**   	| Transmet per veu i no per ràdio a uns 20m aproximadament.

Per canviar entre canals, cal prémer ++comma++++period++. Cal recordar que el canal serveix tant per xat com per VON. Per poder parlar per VON, el sistema de veu integrat del simulador, cal prémer ++tab++. Si prems 2x++tab++ aquest deixarà el canal de ràdio obert, i sempre que detecti la teva veu ho transmetrà.

## Principis bàsics de les comunicacions de combat per veu

Els principis bàsics per a una correcta comunicació al camp de batalla del simulador són els següents:

  - **Brevetat.** És l'art de dir molt amb poques paraules. Sempre t'has d'esforçar en ser concís a l'hora de transmetre un missatge. Hi ha molts soldats que volen transmetre molta informació en una zona de combat, i tot és important. Fent servir comunicacions curtes, poques paraules, t'assegures que tothom pugui transmetre ràpidament la seva informació.
  - **Claredat.** Juntament amb la brevetat, has de ser molt clar en el llenguatge emprat. Això requereix de fer servir un termes definits de llenguatge tàctic, el Brevity Cody, i un to de veu clar i alt. Repetir els punts importants és una bona ajuda.
  - **Confirmació i col·lació.** És molt important confirmar que has rebut i entès la comunicació, si no l'emissor no té cap manera de saber si ho has rebut. Addicionalment, és molt útil repetir la informació rebuda, perquè així l'emissor pot estar segur que has entès tot el missatge correctament, o corregir-te en cas necessari.
  - **Alertar i identificar.** És important fer servir les paraules correctes per assegurar-te que el receptor et presta atenció. I a l'hora cal que identifiquis de qui ve i cap a qui va el missatge, perquè les parts implicades es concentrin en el missatge.
  - **Ús de procediments operatius estàndard i llenguatge tàctic.** Fer servir un llenguatge tàctic, i mètodes i procediments operatius estàndard, ajuda a que tothom entengui correctament els missatges.

## Procediments i regles

Els procediments de comunicació són totalment estandarditzats, i permeten una ràpida i fàcil transmissió de la informació, saltar-se els protocols de comunicació pot donar lloc a errors al combat.

### Establir comunicació

Una transmissió sempre es fa dient cap a qui va el missatge, seguit de la teva identificació, i a continuació el cos del missatge.

<table>
<colgroup>
<col style="width: 26%" />
<col style="width: 10%" />
<col style="width: 26%" />
<col style="width: 10%" />
<col style="width: 26%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong>RECEPTOR</strong></td>
<td><strong>&gt;</strong></td>
<td><strong>EMISSOR</strong></td>
<td><strong>&gt;</strong></td>
<td><strong>MISSATGE</strong></td>
</tr>
</tbody>
</table>

Però abans has d'assegurar-te que el receptor estarà escoltant, amb una comprovació de comunicació.

Pots veure com **Alfa 2-1** fa la comprovació amb aquesta senzilla formula, i **Alfa 1-1** acusa el rebut amb la mateixa formula.

| **Alfa 1-1** aquí **Alfa 2-1** |
|--------------------------------|
| **Alfa 2-1** aquí **Alfa 1-1** |

Immediatament després d'haver fet la comprovació de comunicació, Alfa dóna les instruccions, sempre mantenint al principi la formula **Receptor - Emissor** i després **Missatge**. D'aquesta manera s'eviten confusions sobre l'autoritat del missatge. Fixat també que **Alfa 2-1** no només confirma que ha rebut el missatge, sinó que també el repeteix (**Col·laciona**) perquè **Alfa 1-1** tingui clar que s'ha entès correctament.

| **Alfa 2-1** aquí **Alfa 1-1**, avança pel flanc esquerra 100 metres.        |
|------------------------------------------------------------------------------|
| **Alfa 1-1** aquí **Alfa 2-1**, rebut avancem 100 metres pel flanc esquerra. |

Aquí **Alfa 2-1** informa a **Alfa 1-1** que ja han començat l'avanç. És important notificar sempre l'inici de qualsevol acció o sobretot ordre, ja que és molt normal que hi hagi una demora entre que el líder rep les ordres, aquest les comunica als seus soldats i s'inicia l'acció.

| **Alfa 1-1** aquí **Alfa 2-1**, avançant. |
|-------------------------------------------|
| **Alfa 2-1** aquí **Alfa 1-1**, rebut.    |

!!! note "Nota"

	Si la informació es transmet dintre del propi escamot, es poden fer servir formules més curtes, ja que són esquadres del mateix escamot coordinant-se.

	* **Alfa 2-1**, avançant.
	* Rebut **Alfa 2-1**.


Un cop assolida la posició, s'ha de notificar i acusar rebut.

| **Alfa 1-1** aquí **Alfa 2-1**, en posició. |
|---------------------------------------------|
| **Alfa 2-1** aquí **Alfa 1-1**, rebut.      |

!!! note "Nota"

	Si fossin entre equips de la mateixa esquadra, encara es podrien fer servir designacions més curtes.

  	* **2-1**, en posició.
  	* Rebut **1-1**.

### Alertar sobre contactes

A l'hora d'alertar sobre contactes, cal seguir sempre la mateixa formula, primer s'indica la identitat del contacte, després la orientació cap al mateix, seguit de la distància, i per últim qualsevol informació extra d'utilitat. Seguint aquesta formula es dóna tota la informació vital d'un contacte en poques paraules.

<table style="width:100%;">
<colgroup>
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 85%" />
</colgroup>
<tbody>
<tr class="odd">
<td><strong>IDENTITAT</strong></td>
<td><strong>&gt;</strong></td>
<td><strong>ORIENTACIÓ</strong></td>
<td><strong>&gt;</strong></td>
<td><strong>DISTÀNCIA</strong></td>
<td><strong>&gt;</strong></td>
<td><strong>INFORMACIÓ EXTRA</strong></td>
</tr>
</tbody>
</table>

**Alfa 1-1** informa d'enemics, amb la formula **IDENTITAT + ORIENTACIÓ + DISTÀNCIA + INFORMACIÓ EXTRA** (que no dóna en aquest cas). Llavors **Alfa 2-1** acusa el rebut.

| **Alfa 2-1** aquí **Alfa 1-1**, contactes enemics a l'Est, llarga, damunt del turo! |
|-------------------------------------------------------------------------------------|
| **Alfa 1-1** aquí **Alfa 2-1**, rebut.                                              |

!!! note "Nota"

	**Alfa 2-1** podria també **col·lacionar** el missatge per deixar clar que s'ha entès tot.

  	* **Alfa 2-1** aquí **Alfa 1-1**, contactes enemics a l'Est, llarga, damunt del turo\!
  	* Aquí **Alfa 2-1**, enemics a l'Est, damunt del turo, rebut.

Per indicar distàncies, pots fer servir els metres, més lent ja que normalment cal mesurar-los d'alguna manera, o les tres indicacions bàsiques: curta, mitja o llarga.

Igualment, per indicar orientació, pots indicar la posició relativa (davant, dreta...), pots fer servir els graus (a 350º...), o el sistema cardinal (nord, sud...). Si bé al simulador per simplicitat és molt fàcil fer servir els graus mirant ràpidament la brúixola, a la pràctica, amb experiència, fer servir el sistema cardinal en comptes dels graus acaba sent més ràpid, i reforça el sentit de la orientació.

Quan es faci servir la posició relativa, has d'entendre que l'avantguarda és el sentit de la marxa, o la direcció a la que esta orientada tota la unitat quan resta aturada.

## Veu directe

El sistema que fem servir al grup permet diferenciar entre comunicacions per veu i comunicacions per ràdio, de tal manera que les comunicacions per ràdio només poden ser escoltades per jugadors que estiguin equipats amb ràdio i tinguin establerta la mateixa freqüència i les comunicacions per veu directe se senten atenuades per la distància de l'emissor i els obstacles que pugui haver-hi pel mig.

Aquest sistema permet una gran dosis de realisme, i facilita la transmissió d'informació, a l'hora que crea cohesió.

### Fer circular les ordres entre companys

Per limitar l'ús excessiu de la ràdio, i així permetre als líders tenir les freqüències lliures, has de fer servir la comunicació per veu directe en tot moment, i reservar la ràdio només pels moments que sigui realment necessaria. Aquí entra en joc la transmissió d'ordres entre companys de la unitat. Quan un líder doni una ordre, aquesta ordre s'ha de passar per veu directe des de l'origen fins a l'últim membre. Així, per exemple, si en una patrulla en formació de columna, el líder, que pot estar cap al principi de la formació, dóna l'ordre d'aturar-se, el soldat que estigui després del líder, transmetrà aquesta ordre per veu directe al soldat següent, i així fins que tot la unitat rebi l'ordre.

## Malla de comunicació

Per poder operar eficaçment per ràdio, s'ha d'establir una malla de comunicacions estructurada, que assigni a cada unitat unes freqüències comunes i exclusives.

### Escamot

La malla per escamot és la següent:

  - **Escamot:** Una freqüència per tot l'escamot.
  - **Líders d'esquadres:** Una freqüència pels líders d'esquadres incloent comandància.
  - **Esquadres:** Una freqüència per cada esquadra, d'ús interna de la mateixa.
  - **Equips de foc:** Una freqüència per cada equip de foc, d'ús interna dels mateixos.

El sistema de comunicació que fem servir al grup, el TFAR, permet dos canals de recepció/transmissió de curt abast i dos canals de recepció/transmissió de llarg abast. De manera que un sol jugador por fer servir les quatre freqüències a l'hora.

Tot i així, portar 4 freqüències a l'hora pot ser massa feina per un soldat al camp de batalla, per tant s'han de delegar comunicacions. El repartiment quedaria així.

| **Rol**               | **Freqüències**                                             |
|---------------------- | ------------------------------------------------------------|
| **Líder**             | Freqüències de líders d'esquadres i equip de foc propi.     |
| **Operador de ràdio** | Freqüències d'escamot, esquadres i equip de foc propi.      |
| **Operador de ràdio** | Freqüències d'escamot, esquadres i equip de foc propi.      |

!!! note "Nota"

	El segon operador de ràdio només seria en el suposat d'una gran partida, poc probable.

#### Sent només una Esquadra

Si la partida només es composa d'una sola Esquadra, que sol ser lo habitual, es podria prescindir de l'Operador de ràdio, o fer-lo servir com a recolzament pel líder d'esquadra. El repartiment de freqüències en ambdós casos quedaria d'aquesta manera.

| **Rol**               | **Freqüències**                                             |
|---------------------- | ------------------------------------------------------------|
| **Líder**             | Freqüències de líders d'esquadres i equip de foc propi.     |
| **Operador de ràdio** | Freqüències d'esquadra, i equip de foc propi.               |

## Alfabet fonètic internacional

El codi internacional **ICAO (International Civil Aviation Organization)** és el que s’ha de fer servir per lletrejar en tot tipus de comunicació, això garanteix la comprensió del missatge i evita errors.

| **Lletra** | **Significat** |
|:-----:|:--------:|
| **A** | Apha     |
| **B** | Bravo    |
| **C** | Charlie  |
| **D** | Delta    |
| **E** | Echo     |
| **F** | Foxtrot  |
| **G** | Golf     |
| **H** | Hotel    |
| **I** | India    |
| **J** | Juliet   |
| **K** | Kilo     |
| **L** | Lima     |
| **M** | Mike     |
| **N** | November |
| **O** | Oscar    |
| **P** | Papa     |
| **Q** | Quebec   |
| **R** | Romeo    |
| **S** | Sierra   |
| **T** | Tango    |
| **U** | Uniform  |
| **V** | Victor   |
| **W** | Whiskey  |
| **X** | X-Ray    |
| **Y** | Yankee   |
| **Z** | Zulu     |

## Protocol operatiu de comunicació "POC"

Dintre del nostre **SOP** tenim el nostre propi protocol de comunicació, la manera que fem servir nosaltres per comunicar-nos a les missions. Aquest **POC** es el que indica no només quins mots es fan servir, sinó també com i quan es fan servir, d'aquesta manera és més fàcil comunicar-se i coordinar-se entre soldats, fent servir tots un mateix estàndard. Tens un resum del **POC** al final del manual.
