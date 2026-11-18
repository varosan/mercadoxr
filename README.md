# ExperienciaXR - Mercado Central de Talca

Alvaro Garrido Moraga · Realidades Extendidas y Experiencias Inmersivas · UGM · 2026

## 1 · Qué es

Recorrido virtual donde el usuario navega por el exterior e interior para 
(re)experimentar pasear por este edificio y conservar en una memoria virtual el entrar en el mercado y mirar la estructura que se apreciaba en años anteriores.


## 2 · Cómo se usa

- Enlace a la escena: https://varosan.github.io/mercadoxr/
- Dispositivo pensado: computador, teclas flechas (wasd) y mouse
- Al entrar: el usuario ve el frontis principal ubicado en la calle 1 sur en la ciudad de Talca, específicamente entre las calles 4 y 5 oriente.

## 3 · Cómo está hecha

- Herramienta: A-Frame, publicado en GitHub Pages.
- Archivos que usé:

  - **modelos/arbol1.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D
  - **modelos/arbol2.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D
  - **modelos/interior.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D
  - **modelos/mercado.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D
  - **modelos/piso.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D
  - **modelos/puerta_arriba.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D
  - **modelos/puerta.glb**: modelo 3D. Origen: Alvaro Garrido Moraga - Diseño 3D

  - **audio/ave2.mp3**: sonido de un objeto. Origen: freesound.org. Licencia: CC0
  - **audio/mercado.mp3**: sonido de un objeto. Origen: freesound.org. Licencia: CC0
  - **audio/puerta.wav**: sonido de un objeto. Origen: freesound.org. Licencia: CC0
  - **audio/sonido_ave.mp3**: sonido de un objeto. Origen: freesound.org. Licencia: CC0

## 4 · Decisiones

- Qué decidí y por qué: 
- Cambio realizado desde la solemne 1: en un principio se habia decidido solo por el edificio exterior, pero se agregó el recorrido del galpón interior para mejorar la experiencia y sea más inmersiva.

## 5 · Testing

Video del recorrido: https://youtu.be/TEQ_omPgpNU


### Abrir el enlace en ventana privada
- Resultado: proyecto abre sin problemas

### Dispositivo elegido
- Resultado: proyecto abre sin problemas, se reproducen los sonidos y funcionan las teclas WASD (y las flechas)
- Ajuste que hice: Bajar altura de cámara

### Interacciones, una por una
- Resultado: Clic en puerta para abrir funciona sin problemas, a veces demora en cargar 
- Ajuste que hice: incorporar para la siguiente etapa javascript para cargar la escena completa sin tener que recargar la página.

### Sonido con audífonos
- Resultado: Audio envolvente al girar la vista, el audio pasa de lado izquierdo a derecho.
- Ajuste que hice: transformar audios de wav a mp3 para bajar el peso de los archivos.

### Fluidez del recorrido
- Resultado: paseo realizado desde el computador usando tecla flechas (wasd) y mouse.
- Ajuste que hice: para la próxima etapa incorporar limites y colisiones, y experiencia de caminar con el celular para mover el modelo.

### Entrar como si fuera la primera vez
- Resultado: Entretenido dar la vuelta al mercado, la música y sonidos agregan una atmósfera. La interacción con la puerta es como un viaje al pasado. 
- Ajuste que hice: aunque falten límites, fue entretenido entrar por los pequeños pasillos laterales.

## 6 · Uso de IA

- Qué le pedí a la IA: ir recordando cómo usar <a-frame>, se solicitó ayuda para incorporar luces, objetos y audio.
- Qué hice yo y qué cambié de lo que me entregó: comparar con el contenido de la asignatura para crear código más sencillo, javascript,atributos o clases que no iba a utilizar ya que la IA por defecto agrega detalles para que quede perfecto, como un usuario experimentado.

## 7 · Pendientes para el examen

- Lo que falta en el proyecto:

- limites y colisiones
- texturas
- animaciones
- audio interior y exterior
- pileta central (pérgola)
- distribucion de algunos locales
- arcos interiores (vigas)
- mejorar modelado de árboles
- interacciones con más puertas u objetos