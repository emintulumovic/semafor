# Semafor

Simulacija semafora na raskrsnici urađena u Flowcode-u. Projekat uključuje semafor za vozila i semafor za pješake koji rade zajedno kao jedan sistem.

## Kako radi

Program radi u beskonačnoj petlji i prolazi kroz sve faze semafora po redoslijedu. Kad vozila imaju zeleno, pješački semafor je na crvenoj. Prije nego što se vozilima promijeni faza, pali se žuto kao signal da se pripreme za zaustavljanje. Nakon toga vozila dobivaju crveno, a pješaci zeleno i mogu prelaziti. Kad istekne taj interval, sistem se vraća na početak i ciklus se ponavlja. Trajanje svake faze je određeno kašnjenjem unutar programa.

## Tehnologije

- Flowcode
- PIC mikrokontroler

## Autor

Emin Tulumović, ETŠ Tuzla
