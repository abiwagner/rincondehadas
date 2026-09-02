# 🧚 Rincón de Hadas — To Do List

Una libreta de tareas diaria, sin horarios ni complicaciones, con onda hadita 🌸🌿

Vivo, 100% en el navegador: no tiene backend, no tiene build, no tiene dependencias que instalar. Un solo archivo HTML que podés abrir directo o publicar con GitHub Pages.

## ✨ Qué tiene

- **Vista Día y vista Semana** — elegís cómo querés ver tus tareas. En la semana, sábado y domingo comparten una sola tarjeta de "finde".
- **Sin horarios** — cada día es una lista simple para anotar e ir tachando, como una agenda de bolsillo.
- **Horas opcionales por tarea** — si una tarea te tomó tiempo, tocás el ⏱ y le ponés las horas (podés usar medios, como 1.5). Las que no necesitás medir se quedan sin nada.
- **Mapa de constancia** — un heatmap tipo GitHub de las últimas 14 semanas: cuanto más verde el día, más tareas tachaste.
- **Horas de la semana** — un gráfico de barras con las horas cargadas día por día.
- **Racha 🔥** — cuántos días seguidos venís completando al menos una tarea.
- **Todo se guarda solo** — usa `localStorage` del navegador, no necesitás cuenta ni conexión.
- **Backup manual** — botones para descargar un `.json` con todas tus tareas y para volver a importarlo (por si se borra el caché, cambiás de compu, o querés tener una copia).

## 🚀 Cómo usarlo

### Opción 1: abrirlo tal cual
Descargá `index.html` y abrilo con doble clic en cualquier navegador. Ya funciona.

### Opción 2: publicarlo con GitHub Pages
1. Creá un repositorio nuevo en GitHub.
2. Subí el archivo `index.html` a la raíz del repo.
3. Andá a **Settings → Pages**.
4. En **Source**, elegí la rama principal (`main`) y la carpeta `/ (root)`.
5. Guardá. En un par de minutos tu web queda publicada en `https://tu-usuario.github.io/nombre-del-repo/`.

## 💾 Sobre los datos

Las tareas se guardan en el `localStorage` del navegador que estés usando, en esa computadora y ese navegador puntual. Esto quiere decir:

- Si borrás el caché o los datos del sitio, **se pierden las tareas**.
- Si abrís la web desde otro navegador o dispositivo, vas a ver una libreta vacía (no se sincroniza sola entre dispositivos).

Por eso están los botones de backup:

- **⬇ Descargar backup** — genera un archivo `.json` con fecha en el nombre, con todas tus tareas y horas guardadas hasta ese momento.
- **⬆ Importar backup** — subís ese archivo y elegís si querés **reemplazar** todo lo que tenés o **combinar** (útil si estás uniendo backups de dos dispositivos distintos).

Recomendación: hacete el hábito de descargar un backup de vez en cuando y guardarlo en algún lugar aparte (Drive, mail, una carpeta local), sobre todo antes de limpiar el navegador.

## 🎨 Personalización rápida

Todos los colores están definidos como variables CSS al principio del archivo (`:root`), así que podés cambiar la paleta sin tocar el resto del código:

```css
:root{
  --cream:#FFF7F1;
  --pink-soft:#F6D9E4;
  --pink-mid:#EDB4C9;
  --red-berry:#C6516B;
  --green-sage:#A9C4A5;
  --green-deep:#3E5B41;
  --ink:#3A2E33;
}
```

## 🛠️ Tecnología

HTML, CSS y JavaScript puro (vanilla), sin frameworks ni librerías externas — salvo las tipografías, que se cargan desde Google Fonts (Fraunces y Quicksand).

---

Hecho con magia y un poquito de ♥
