# Compatibilitat entre terminals

Com ja sabràs, tant la AN/PRC-152 com la AN/PRC-117F son compatibles mutuament per defecte. En canvi això no passa amb la AN/PRC-77 quan utilitzem una de les radios anteriorment esmentades. Això es degut a una incompatibilitat amb el paquet de trucada en el qual està configurat un terminal ja sigui per emetre (TX) o rebre (RX).

Alguns casos habituals:

- **PRC-77 a PRC-77**: per a que dos terminals puguin emetre i rebre, cal que estiguin els dos en mode *squelch* o no. Si hi ha un terminal en mode *squelch* i un altre sense, el segon rebrà les comunicacions del primer però no al revés.

- **PRC-77 a PRC-117 o PRC-152**: quan es tracta de comunicació entre una PRC-77 analògica i una radio més nova, com una PRC-117, cal que les dues tinguin el mode *squelch* desactivat tant per emetre com per rebre. Per defecte, les radios modernes porten el mode *squelch* activat en mode **CTCSS**, i desgraciadament al ser digitals no podem calibrar sempre el mode *squelch* exactament a 150 KHz, ja que funciona per franges. Per tant, el més senzill es desactivar el mode *squelch* de tots els terminals en aquest cas.
