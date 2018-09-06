# RETO 2.P02: Anima Tus Píxeles
Copia más abajo tus programas, cada uno en su parte del reto.

* Cada fotograma de animación debe durar 0.1s (10 fotogramas por segundo)
* Limitación: Sólo usar instrucciones siguientes: `3E`, `32`, `21`, `22`, `18`, `76`, `C3`

# PROGRAMAS

## Actividad 1: Mover el píxel rojo
Pixel que se mueve cíclicamente por los 4 primeros píxeles de pantalla
```
3E 88 32 00 C0 3E 30 76 3D 20 FC 3E 44 32 00 C0 3E 30 76 3D 20 FC 3E 22 32 00 C0 3E 30 76 3D 20 FC 3E 11 32 00 C0 3E 30 76 3D 20 FC 18 D2
```
PC: 4000

## Actividad 2: Barra de progreso de 4 colores
La barra de progreso se rellena alternativamente con cada uno de los colores
```
21 FF CC 22 00 C0 3E 30 76 3D 20 FC 3E 7F 32 00 C0 3E 30 76 3D 20 FC 3E 3F 32 00 C0 3E 30 76 3D 20 FC 3E 1F 32 00 C0 3E 30 76 3D 20 FC 3E 4C 32 01 C0 3E 30 76 3D 20 FC 3E 0C 32 01 C0 3E 30 76 20 FD 3E 87 32 00 C0 3E 30 76 3D 20 FC 3E C3 32 00 C0 3E 30 76 3D 20 FC 3E E1 32 00 C0 3E 30 76 3D 20 FC 3E F0 32 00 C0 3E 30 76 3D 20 FC 3E 84 32 01 C0 3E 30 76 3D 20 FC 3E C0 32 01 C0 3E 30 76 3D 20 FC 3E 70 32 00 C0 3E 30 76 3D 20 FC 3E 30 32 00 C0 3E 30 76 3D 20 FC 3E 10 32 00 C0 3E 30 76 3D 20 FC 3E 00 32 00 C0 3E 30 76 3D 20 FC 3E 40 32 01 C0 3E 30 76 3D 20 FC 3E 00 32 01 C0 3E 30 76 3D 20 FC C3 00 40
```
PC: 4000

## Actividad 3: Sprite animado (Ej: Cara sonriente)
4x4 píxeles mínimo para cada fotograma.
```
21 77 88 22 86 C4 21 00 EE 22 88 C4 21 33 CC 22 86 CC 21 11 CC 22 88 CC 22 88 D4 21 33 CC 22 86 D4 21 00 CC 22 86 DC 21 11 99 22 88 DC 21 77 F3 22 86 E4 21 FC FF 22 88 E4 21 FF 3F 22 86 EC 21 CF EE 22 88 EC 21 00 FF 22 86 F4 21 FF 00 22 88 F4 21 33 FF 22 86 FC 21 FF CC 22 88 FC 21 33 00 22 D6 C4 21 00 CC 22 D8 C4 21 33 00 22 D6 CC 21 00 CC 22 D8 CC 3E 30 76 3D 20 FC 3E 7F 32 86 C4 3E 3F 32 86 CC 3E 3F 32 86 D4 3E 0F 32 86 DC 3E 7F 32 86 E4 3E 30 76 3D 20 FC 3E 0F 32 85 C4 32 85 CC 32 85 D4 32 85 DC 32 85 E4 3E 30 76 3D 20 FC C3 00 40 
```
PC: 4000

# IMAGENES
Si quieres, puedes subir pantallazos y enlazarlos aquí.
![Actividad 1](/tuimagen1.png)
![Actividad 2](/tuimagen2.png)
![Actividad 3](/tuimagen3.png)
