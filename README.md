# Simulador Water Transfer 3D

Simulación 3D de un acueducto temporal de manguera layflat de 12" para water transfer: captación en río, cinco rebombeos (bomba en marcha + backup, cisterna de gasoil de 5.000 L, telemetría) y tanque de destino con ingreso por cuello de cisne.

**Autor:** Lic. Víctor Javier Paredes

## Qué muestra
- Traza de 18,6 km sobre relieve de estepa (valle, cañadón, bardas, meseta, zanjón), con exageración vertical ×6.
- Hidráulica calibrada con el manual *Water Transfer en Vaca Muerta* (cap. 4): 1.050 m³/h, fricción 29,2 m/km (C ≈ 160), velocidad 3,99 m/s.
- Presión en cada punto = línea piezométrica − cota del terreno.
- Panel **Perfil piezométrico** con verificación de criterios: impulsión ≤ 12 kg/cm², succión 1,5–1,7, margen ≥ 0,7 en crestas, velocidad < 4 m/s, golpe de ariete (a = 250 m/s), tiempo de cierre, caída estática ≤ 100 m por tramo.
- Escenario **sin R5** para mostrar por qué hace falta la quinta estación.
- Válvulas: volante verde = abierta, rojo = cerrada (bomba de backup). Ventosas, desagote y cruce de ruta con caño camisa.

## Cómo usarlo
Abrir `index.html` en un navegador moderno. No requiere instalación; carga Three.js r147 desde jsDelivr.

### Publicar con GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → `main` / root. Queda en `https://<usuario>.github.io/simulador-water-transfer-3d/`.

## Nota
Los nombres de locaciones son genéricos (CAP, R1…R5, DEST). Los valores son ilustrativos y deben verificarse con la ficha técnica del fabricante y lecturas de campo.
