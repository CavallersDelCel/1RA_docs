# Mètodes de tir

En aquest apartat veurem alguns mètodes tipus sobre com calibrar el fusell i corregir el tret.

Cal recordar que el rol de franctirador es un rol que requereix tant d'un nivell alt de planificació prèvia, com de també d'un gran nivell d'improvització sobre la marxa, es per això que els mètodes que aqui exposem, volen ser una simple ajuda i en cap cas una pauta que s'hagi de seguir al peu de la lletra.

### Mètode Quick Scope

Aquest mètode es útil per quan estem en moviment o estem en una zona on no esperem contacte immediat. Es el mètode que habitualment es fa servir per enfrontar-nos a contactes propers en zones de perill.

**Prèvi a l'acció:**

1. Delimitem l'àrea de perill proper des de la posició on ens trobem. Per a fer això obrim el mapa i analitzem fins a on tenim visual per circumstàncies del terreny (clarianes, boscos, tàlvegs, turons, etc). L'àrea ha de ser en 360 graus al nostre voltant (en forma de cercle per exemple). 
2. Prenem la distància al punt més llunyà des del qual ens podria fer foc efectiu un fuseller enemic (màxim uns 300-400 metres).
3. Prenem la temperatura ambient.
4. Calibrem la mira del fusell segons el valor de caiguda de la bala de la taula de rangs.
5. També es bò memoritzar els valors a distàncies més properes. Per exemple, 100, 200, 300 metres. O fins i tot en segments de 50 metres.

**Durant l'acció:**

L'acció amb aquest mètode es basa en la nostra capacitat de memoritzar les diferents correccions de caiguda i d'estimar les distàncies a ull ràpidament.

Quan detectem un contacte enemic, hem de recordar els valors de correcció a la distància màxima i els intermitjos i recalibrar constantment segons la distància. 

Es un mètode que requereix de molta pràctica i que habitualment es dona en distàncies curtes i en combat directe, per tant l'estrés es un factor important a tenir en compte i la precissió generalment tendeix a ser més baixa.

### Mètode de marksman

Aquest es el mètode més ràpid, simple i que requereix menys material i el que normalment fa servir el tirador designat. Tanmateix sol ser el menys precís i no apte per a trets a grans distàncies.

1. Obtenim la distància del blanc amb un telèmetre o l'aproximem.
2. Obrim la taula de rangs i estimem la columna de temperatura (si tenim alguna eina de mesura molt millor).
3. Calibrem només la caiguda de la bala que correspon.
4. Comprovem la direcció i força del vent.
5. Disparem.
6. Analitzem la caiguda de la bala i ajustem el tret amb la retícula.
7. Disparem.
8. Repetim el pas 5 i 6 fins que l'objectiu estigui abatut.

### Mètode ràpid de franctirador

Aquest es el mètode més ràpid que sol utilitzar el franctirador i un dels millors en relació a temps/precissió, molt recomanable sobretot si s'està operant sol. Es necessari disposar d'un Vector 21, Kestrel 4500, ATragMX i DAGR.

1. Abans de l'inici de l'operació, deixem peparats els apartats Gun i Atmsphr de la calculadora ATragMX.
2. Un cop a lloc, agafem el Vector 21 i obrim el DAGR (no MicroDAGR), anem a CONNECT TO i seleccionem Vector 21.
3. Observem l'objectiu amb el Vector 21 i premem TAB i R alhora per obtenir l'azimut i la distància (no cal anotar res).
4. Seguidament i sense deixar d'enfocar l'objectiu amb el Vector toquem TAB dos cops amb certa separació per obtenir l'angle d'inclinació (tampoc cal anotar res).
5. Obrim l'ATragMX i observarem que a l'apartat Target s'han omplert les dades d'azimut, distància i angle d'inclinació automàticament.
6. Completem la resta d'informació amb la User Screen 1 del Kestrel.
7. Actualitzem els valors atmosfèrics amb la User Screen 2 del Kestrel (només si cal).
8. Calibrem el fusell amb els valors de d'elevació i vent.
9. Disparem.
10. Analitzem la caiguda de la bala i corregim el tret.
11. Repetim els dos passos anteriors fins que l'objectiu estigui abatut.

### Mètode per a Multi Target Engagement

La majoria de mètodes estan centrats en els trets precissos a un sol objectiu. Però hi ha situacions en les que hem d'abatre un gran nombre d'objectius a distàncies diferents i no tenim temps per a obtenir les dades específiques de cada un.

1. Observem l'objectiu més proper i el més llunyà.
2. Obtenim la distància de cadascun d'ells i les anotem (Vector 21).
3. Obtenim la temperatura amb el Kestrel 4500.
4. Obrim la taula de rangs i anotem el valor de caiguda de la bala del més llunyà i del més proper. Restem els valors per trobar la diferencia de caiguda que hi ha.
5. Calibrem l'elevació per a l'objectiu més llunyà i disparem. *
6. Anem reduïnt l'elevació progressivament i anem abatent els objectius intermitjos.
7. Finalment abatem el més proper amb la calibració que ja haviem obtingut.

*No calibrem el vent ja que aquest varia molt segons l'angle d'inclinació i deriva, per tant corregirem aquest factor a ull. Tampoc es bo utilitzar la calculadora per aquest mateix motiu.

### Mètode estàndard individual

Es el mètode més habitual si ens trobem sols i tenim temps suficient per a fer els càlculs més a consciència. Aquest mètode es força més llarg que el mètode ràpid de franctirador però ens dona molta més seguretat i precissió.

1. Abans de l'inici de la missió completem l'apartat Gun de l'ATragMX i ajustem el coeficient C1 si cal.
2. Un cop a lloc, completem l'apartat Atmsphr de l'ATragMX amb les dades de la User Screen 2 del Kestrel 4500.
3. Observem l'objectiu amb el Vector 21 i obtenim distància, azimut i angle d'inclinació. Anotem.
4. Obtenim direcció i valors de velocitat mitjà i màxim del vent amb ajuda del Kestrel.
5. Completem l'apartat Target amb les dades obtingudes.
6. Si l'objectiu es mou, utilitzem l'eina TS de l'ATragMX per a estimar la seva velocitat.
7. Analitzem el resultat obtingut i el comparem amb els valors de la taula de rangs.
8. Calibrem elevació i deriva a la mira del fusell.
9. Disparem.
10. Analitzem la caiguda de la bala, situem el centre de la mira sobre on ha impactat i estimem l'error amb els mils de la retícula.
11. Recalibrem i tornem a disparar.
12. Seguim aquest procediment fins que l'objectiu estigui abatut.

### Mètode estàndard en binomi

Finalment en cas d'operar en binomi, cal entendre la separació de tasques que realitza l'observador i el franctirador. Tot i que pot semblar una tasca més lenta, també dona certa seguretat ja que hi ha dos persones que poden repassar els càlculs i hi ha menys càrrega de feina individual, cosa que suposa més relaxament i per tant més possibilitats d'èxit.

1. Abans de l'inici de la missió, l'observador i el franctirador fan un briefing específic on s'ultimen detalls sobre com es coordinarà el binomi.
2. L'Obervador ha de completar l'apartat Gun del seu ATragMX amb les dades que li dongui el franctirador, i recalcular els coeficients C1 o fer una prova amb la Truing Tool.
3. Un cop a lloc, el franctirador i l'observador se situen un al costat de l'altre mirant a l'objectiu. Han d'estar suficientment a prop per a poder sentir-se parlant molt baix.
4. L'Observador desplega el telescopi portatil.
5. L'Observador observa tots els blancs i els ordena per prioritat. Si cal es marquen al mapa i es coordina amb el franctirador perque estigui al cas d'on es troben tots els objectius. 
6. L'Observador calcula les dades balístiques de cadascun dels objectius fent servir el mètode que més convingui.
7. L'Observador comunica el primer objectiu al franctirador i les dades d'elevació i deriva en clicks o mils.
8. El franctirador calibra el fusell i avisa abans de disparar, seguidament obre foc. L'Observador en aquest moment ha d'estar observant amb el telescopi.
9. L'Observador veu on ha impactat la bala i situa el centre de la retícula sobre l'impacte. Calcula ràpidament la correcció en clicks en elevació i deriva i els comunica al franctirador.
10. El franctirador recalibra la mira i torna a disparar.
11. Es torna a repetir el procediment tantes vegades com calgui.