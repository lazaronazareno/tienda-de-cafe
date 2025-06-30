# Imágenes de Tutoriales - Tienda de Café

## Instrucciones para obtener las imágenes reales

Las imágenes de tutoriales se basan en el sitio web oficial de Tienda de Café:
https://tiendadecafe.com.ar/tutoriales/

### URLs de imágenes identificadas:

1. **ESPRESSO**
   - URL: https://tiendadecafe.com.ar/wp-content/uploads/2021/10/Sin-título-1.jpg
   - Archivo local: `images/tutoriales/espresso.jpg`
   - Dimensiones recomendadas: 460x306px

2. **PRENSA FRANCESA**
   - Buscar imagen apropiada de prensa francesa
   - Archivo local: `images/tutoriales/prensa-francesa.jpg`
   - Dimensiones recomendadas: 306x460px

3. **CHEMEX**
   - Buscar imagen apropiada de Chemex
   - Archivo local: `images/tutoriales/chemex.jpg`
   - Dimensiones recomendadas: 306x460px

4. **AEROPRESS**
   - Buscar imagen apropiada de AeroPress
   - Archivo local: `images/tutoriales/aeropress.jpg`
   - Dimensiones recomendadas: 306x460px

5. **MOKA**
   - URL: https://tiendadecafe.com.ar/wp-content/uploads/2021/10/Tienda-de-Café-tutorial_281-scaled-460x306.jpg
   - Archivo local: `images/tutoriales/moka.jpg`
   - Dimensiones recomendadas: 460x306px

6. **FILTRO DE PAPEL**
   - URL: https://tiendadecafe.com.ar/wp-content/uploads/2021/10/Tienda-de-Café-tutorial_119-scaled-460x306.jpg
   - Archivo local: `images/tutoriales/filtro-papel.jpg`
   - Dimensiones recomendadas: 460x306px

### Pasos para implementar:

1. Descargar las imágenes de las URLs proporcionadas
2. Redimensionar según las dimensiones recomendadas
3. Optimizar para web (formato JPG, calidad 80-85%)
4. Guardar en la carpeta `images/tutoriales/` con los nombres exactos
5. Eliminar los archivos `.placeholder` una vez que tengas las imágenes reales

### Fallback:
- Si una imagen no carga, se mostrará automáticamente un placeholder con el nombre del método
- El sistema está diseñado para ser resiliente a errores de carga de imágenes

### Estructura de archivos esperada:
```
images/
├── tutoriales/
│   ├── espresso.jpg
│   ├── prensa-francesa.jpg
│   ├── chemex.jpg
│   ├── aeropress.jpg
│   ├── moka.jpg
│   └── filtro-papel.jpg
```

### Notas técnicas:
- Las imágenes usan `loading="lazy"` para mejorar el rendimiento
- Hay manejo de errores con `onerror` que activa el fallback
- Los placeholders mantienen la identidad visual del sitio
- Las transiciones y efectos hover están optimizados para ambos casos
