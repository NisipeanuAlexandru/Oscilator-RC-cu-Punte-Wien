# README - Oscilator RC cu Punte Wien

## Descriere Generală
Oscilatorul RC cu punte Wien este un circuit utilizat pentru generarea de semnale sinusoidale de frecvență reglabilă. Acesta este alcătuit dintr-o rețea RC în configurație Wien și un amplificator cu control automat al amplitudinii (TEC-J). Circuitul este destinat utilizării în diverse aplicații electronice unde este necesară o sursă de semnal sinusoidal stabilă și ajustabilă.

## Caracteristici Tehnice
- **Frecvență de oscilație reglabilă**: 0,5N - 3N kHz
- **Sarcină la ieșire**: N kΩ
- **Control automat al amplitudinii**: realizat cu TEC-J
- **Amplitudinea oscilației la ieșire**: [20/1,5N] V
- **Domeniul temperaturilor de funcționare**: 0 - 70°C
- **Semnalizare a tensiunilor de alimentare**: LED

## Funcționalitate
Oscilatorul Wien utilizează o rețea de rezistențe și condensatori pentru a stabili frecvența de oscilație. Acesta include:
1. **Rețeaua Wien (RC)** - determină frecvența semnalului de ieșire.
2. **Amplificator operațional sau tranzistor** - menține oscilațiile în circuit.
3. **Control automat al amplitudinii** - stabilizează amplitudinea oscilatorului printr-un element de feedback, cum ar fi un TEC-J (Thermally Controlled Junction).
4. **Sistem de semnalizare LED** - indică prezența tensiunii de alimentare.

## Tehnologii de Realizare
Oscilatorul poate fi realizat utilizând două metode:
- **SMT & PCB**: Tehnologie avansată pentru performanță ridicată și fiabilitate (100 puncte max.)
  - Placă PCB FR4, dublu strat, dimensiuni 40x40mm
  - Componente SMD de tip 0805
  - Tranzistoare bipolare și TEC-MOS în capsule SMD (SOT23, D-PAK)
  - Layer special pentru marcaje și identificare
- **THT & Perfo-board**: Tehnologie mai simplă, accesibilă pentru prototipare rapidă (70 puncte max.)
  - Componente montate pe perfo-board
  - Necesită plan de plantare detaliat

## Simulare și Testare
- Se utilizează software-ul OrCAD pentru simulare și proiectare PCB.
- Se verifică funcționarea în intervalul de temperaturi specificat.
- Se validează fișierele Gerber și Excellon pentru fabricație PCB.

## Concluzie
Oscilatorul RC cu punte Wien este un circuit stabil și eficient pentru generarea semnalelor sinusoidale. Alegerea între SMT & PCB sau THT & Perfo-board depinde de cerințele aplicației și de nivelul de complexitate dorit în realizarea practică.

