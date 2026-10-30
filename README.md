# Ficha de verificación de calidad IDC

Landing page imprimible para la **Ficha Técnica de Verificación y Registro de Desviaciones** (Anexo A) y el **Checklist de Control de Calidad** (Anexo B), para procesos de impresión DTF textil e impresión 3D FDM rígida.

La ficha corresponde a la unidad didáctica **Publicación de Piezas Gráficas DP-B** e incluye el logotipo del Instituto de Educación Superior Público Diseño y Comunicación, además del pie de página **Mg Mario Quiroz Martinez**.

## Archivos

- `index.html`: formulario, estilos de pantalla e impresión, y funciones de guardado y recuperación local.
- `logo-idc.jpg`: logotipo institucional usado en la página y en la impresión/PDF.

## Uso

1. Abre `index.html` en un navegador moderno.
2. Completa los datos de identificación, la matriz de parámetros, el checklist y el dictamen.
3. Los campos y casillas se guardan automáticamente en el almacenamiento local de ese navegador y dispositivo. Al volver a abrir la página, se restauran los últimos datos guardados.
4. Pulsa **Guardar como PDF** o **Imprimir ficha**. En el diálogo de impresión, selecciona **Guardar como PDF** para crear el archivo. El PDF conserva el contenido introducido, el logotipo y el pie institucional.
5. Pulsa **Limpiar datos** si deseas borrar el registro guardado y empezar una ficha nueva.

## Consideraciones

- Los datos permanecen en el almacenamiento local del navegador; no se envían a un servidor ni se sincronizan entre dispositivos o navegadores.
- Mantén `logo-idc.jpg` en la misma carpeta que `index.html` para que el logotipo aparezca correctamente.
- El diseño adapta la ficha a pantallas pequeñas y prepara la impresión en tamaño A4 horizontal.
- La página no genera ni descarga el PDF en segundo plano: el usuario confirma la creación del archivo en el diálogo de impresión del navegador.
