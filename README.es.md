<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/lang-English-555?style=for-the-badge" alt="English"></a>
  <a href="README.es.md"><img src="https://img.shields.io/badge/idioma-Español-2b7cff?style=for-the-badge" alt="Español"></a>
</p>

# ReVanced Trove Mods

Mods de interfaz para Trove, que instala y actualiza [ReVanced Trove Launcher](https://github.com/PepeSegura/ReVanced-TroveLauncher)
(pestaña Mods). También puedes copiar un `.tmod` de `mods/` a `Trove\Live\mods` a mano.

| Mod | Qué cambia | Qué hace |
|---|---|---|
| ReVanced Inventory | Inventario y cofres | Inventario y cofres con estilo de tarjeta. Botón de ordenar también en los cofres, buscador (escribe en el chat) que salta a la pestaña correcta y clic derecho para guardar en el cofre. |
| ReVanced Chat | Chat | Chat con emojis y pestañas. Con el buscador del inventario o de la lista de amigos abierto, lo que escribes en el chat filtra esa ventana (o /bus texto). |
| ReVanced Friend List | Lista de amigos | Lista de amigos con favoritos arriba, botón Unirse siempre disponible, candado por amigo para las invitaciones de grupo (normal, aceptar o rechazar) y buscador por chat. |
| ReVanced Tooltip | Descripción de objetos | Descripción de objetos en una tarjeta clara: stats, habilidad, icono del objeto y comparación con lo que llevas puesto, en el idioma del juego. Los allies muestran la XP. |
| ReVanced Loot Collector | Recolector de botín | Botón «Keep new»: los objetos que aún no tienes en tu colección se bloquean para que «Collect All» no los convierta. |
| ReVanced Tiny Quest | Tiny Quest | La mesa de misiones y el panel de Tiny Quest muestran la XP que gana cada ally con la misión y si sube de nivel. |
| ReVanced Auto Tome Swap | Barra de tomo, menú y Colecciones | Cuando el tomo equipado se llena, equipa el siguiente solo: primero los legendarios, y tus favoritos en el orden de Colecciones. Además, en cada mundo nuevo vuelve a equipar tu montura, alas y barco (arregla los mods de monturas que se quedan bugueados). |
| ReVanced Auto Accept | Avisos del juego y ajustes | Acepta o rechaza los avisos del juego (invitaciones de grupo, club, intercambio…) al instante según tus reglas (el aviso ni llega a aparecer), usando los candados de la lista de amigos. Ventana de ajustes rediseñada. |
| ReVanced Loot Tooltips | Botín del suelo | Oculta las descripciones del equipo que cae al suelo, salvo los objetos que aún no tienes en tu colección. Efecto de botín de cristal. |
| ReVanced Hotbar | Barra inferior | Barra inferior rediseñada: vida y energía con sus números, segundos de recarga en cada hueco y rareza bajo cada objeto. Pasa el icono del objeto a la descripción. |
| ReVanced Charsheet | Hoja de personaje y gemas | Todos tus stats a la vez y el coeficiente que el juego no enseña; en las gemas, cómo de buena es cada tirada. Guarda nombre, PR y mastery de cada personaje para las tarjetas del launcher (también con dos cuentas abiertas a la vez). |
| ReVanced Player HUD | Barra del jugador | Barra del jugador con degradado rosa-rojo: PR, nivel de clase y siguiente nivel prime. Guarda tu PR y clase para las tarjetas del launcher. |
| ReVanced Delve Chunks | Brújula y mapa del mundo | Las salas y los chunks (2x2 salas) de la delve, como en delve-maps: cada sala se numera al entrar, en un panel abajo a la derecha y en el mapa del mundo, con tu posición y hacia dónde miras. Basado en Zakros UI - Compass y Zakros UI - Map and Minimap de Zakros (Aallyn), con su permiso; sustituye a los dos. |

`pack.json` lista cada mod con su SHA1: el launcher descarga un mod solo si falta o ha cambiado.

`cfgs/` tiene los ajustes por defecto, limpios, de los mods que los usan (cópialos en `%APPDATA%\Trove\ModCfgs` con Trove cerrado si instalas a mano; el launcher lo hace solo y nunca sustituye un cfg que ya tengas). El juego solo le pasa un ajuste a un mod si su clave ya existe en ese archivo.
