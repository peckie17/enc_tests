# enc_tests
Repositorio para tests de algoritmos de encriptación

## Pruebas incluidas
- UACI
- NPCR
- MSE
- Correlacion
  - pixeles horizontales adyacentes
- PSNR
- Entropia global
- Histograma

## Por hacer:
- Por ahora solo es la muestra de las métricas para imágenes en escala de grises
  - Para RGB Solo se está tomando un canal (rojo)
- Falta generalizarlo a imagenes de 3 canales
- Falta prueba de entropia por bloques, la cual es más confiable que la de entropía global
- En la  prueba de correlación, aun solo está para pixeles adyacentes horizontales  
  - Faltan verticales, diagonales
- Hacer una librería con las pruebas
- Prueba de sensibilidad de llave
- Incluir Chosen Plain Image Attack
- Incluir la DFA, pero esa estará para MATLAB
- Pruebas de Sbox
