## María Teresa Rivera López
## 24000579

Este proyecto consiste en una aplicación web desarrollada con React y TypeScript, que permite a los usuarios explorar propiedades, ver detalles de cada una, comparar varias propiedades entre sí y visualizar sus imágenes.

Lab8 Parte1-Parte2
## Parte 1 – Property Comparison
- El usuario puede agregar propiedades a una lista de comparación.
- Las propiedades seleccionadas se guardan en localStorage.
- La tabla resalta automáticamente las mejores métricas entre las propiedades.
- El usuario puede eliminar propiedades de la comparación.

CompareButton.tsx
- Permitir al usuario agregar o eliminar una propiedad de la lista de comparación.
- Limita la comparación a máximo tres propiedades.
- Guarda las propiedades seleccionadas en localStorage.

ComparePage.tsx
- Mostrar una tabla comparativa de las propiedades seleccionadas.
- Compara diferentes características de las propiedades:
- Permite eliminar propiedades directamente desde la tabla en remove.

PropertyCard.tsx
- Se agrego el botton de compare que aparece en cada card de propiedad.



## Parte 2 – Image Gallery
- Muestra todas las imágenes de la propiedad como miniaturas.
- Permite abrir cualquier imagen en pantalla completa.
- Permite navegar entre imágenes.

ImageGallery.tsx
- Mostrar todas las imágenes de la propiedad como una cuadrícula de miniaturas y 
permitir abrirlas en un visor.
- Cuando el usuario hace clic en una miniatura, se abre el visor de imágenes.

ImageModal.tsx
- Mostrar la imagen seleccionada en pantalla completa y permitir navegar entre todas las imágenes.
- Muestra un contador de imágenes (ejemplo: 3 de 10).
- Permite usar el teclado:
- También se puede cerrar haciendo clic fuera de la imagen.

PropertyDetailPage.tsx
- Agrego la nueva estructura de las imagenes

Link del video: https://youtu.be/mNjLLBGk9MQ

Cada modificacion tiene comentado la parte 1 o parte 2 correspondiente.
Con ayuda de IA pude agilizar parte del proyecto y la documentacion, asi como comprender mejor el funcionamiento de Android, 
al igual que su estructura al hacer una app y en que carpetas colocarlas.
