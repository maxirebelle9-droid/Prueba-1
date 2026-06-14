# Recetario Colaborativo para Aprender GitHub

Bienvenido/a a este proyecto de práctica.  
La idea es aprender a usar **Git**, **GitHub**, ramas, commits y Pull Requests creando entre todos un recetario colaborativo.

Cada participante puede agregar una receta, mejorar una existente o corregir errores del proyecto.

---

## 🎯 Objetivo del proyecto

Este repositorio sirve para practicar:

- Crear y clonar repositorios.
- Crear ramas de trabajo.
- Modificar archivos Markdown.
- Hacer commits claros.
- Subir cambios a GitHub.
- Crear Pull Requests.
- Revisar aportes de otros colaboradores.
- Resolver conflictos básicos.

---

## 🧠 ¿Qué vamos a construir?

Un recetario simple en formato Markdown con recetas aportadas por diferentes personas.

Ejemplo de receta:

```md
## 🍕 Pizza casera

**Autor/a:** Gabriel

### Ingredientes
- 500 g de harina
- 300 ml de agua
- 10 g de sal
- 5 g de levadura
- Salsa de tomate
- Queso

### Preparación
1. Mezclar la harina, el agua, la sal y la levadura.
2. Amasar hasta formar una masa suave.
3. Dejar reposar hasta que duplique su tamaño.
4. Agregar salsa y queso.
5. Hornear hasta que esté dorada.
```

---

## 📁 Estructura sugerida del proyecto

```txt
recetario-colaborativo/
│
├── README.md
├── recetas/
│   ├── pizza-casera.md
│   ├── empanadas.md
│   └── torta-de-chocolate.md
│
└── CONTRIBUTING.md
```

---

## 🚀 Cómo participar

### 1. Hacer un fork del repositorio

Presioná el botón **Fork** en GitHub para crear una copia del proyecto en tu cuenta.

---

### 2. Clonar el repositorio

Copiá la URL de tu fork y ejecutá:

```bash
git clone https://github.com/tu-usuario/recetario-colaborativo.git
```

Entrá a la carpeta del proyecto:

```bash
cd recetario-colaborativo
```

---

### 3. Crear una rama nueva

Antes de modificar algo, creá una rama con un nombre claro:

```bash
git checkout -b agregar-receta-pizza
```

Ejemplos de nombres de ramas:

```bash
agregar-receta-empanadas
corregir-ortografia-readme
mejorar-receta-torta
```

---

### 4. Agregar una receta

Dentro de la carpeta `recetas/`, creá un archivo Markdown con el nombre de tu receta.

Ejemplo:

```txt
recetas/pizza-casera.md
```

Usá esta plantilla:

```md
# Nombre de la receta

**Autor/a:** Tu nombre

## Descripción
Breve explicación de la receta.

## Ingredientes
- Ingrediente 1
- Ingrediente 2
- Ingrediente 3

## Preparación
1. Primer paso.
2. Segundo paso.
3. Tercer paso.

## Consejos
- Consejo opcional.
- Variación opcional.
```

---

### 5. Revisar los cambios

Para ver qué archivos modificaste:

```bash
git status
```

Para ver las diferencias:

```bash
git diff
```

---

### 6. Guardar los cambios con un commit

Primero agregá los archivos modificados:

```bash
git add .
```

Después creá un commit con un mensaje claro:

```bash
git commit -m "Agrega receta de pizza casera"
```

Buenos ejemplos de commits:

```bash
git commit -m "Agrega receta de empanadas"
git commit -m "Corrige errores de ortografía"
git commit -m "Mejora instrucciones para contribuir"
```

Malos ejemplos de commits:

```bash
git commit -m "cambios"
git commit -m "cosas"
git commit -m "update"
```

---

### 7. Subir la rama a GitHub

```bash
git push origin agregar-receta-pizza
```

---

### 8. Crear un Pull Request

En GitHub, abrí tu repositorio y presioná **Compare & Pull Request**.

En la descripción del Pull Request explicá brevemente qué hiciste:

```md
## Cambios realizados
- Agregué la receta de pizza casera.
- Incluí ingredientes, preparación y consejos.

## Tipo de cambio
- [x] Nueva receta
- [ ] Corrección
- [ ] Mejora de documentación
```

---

## 🧪 Actividades para practicar GitHub

### Nivel 1: Principiante

- Crear una receta nueva.
- Corregir una palabra mal escrita.
- Agregar tu nombre en la sección de colaboradores.

### Nivel 2: Intermedio

- Crear una rama nueva.
- Hacer un Pull Request.
- Revisar el Pull Request de otra persona.
- Sugerir una mejora usando comentarios.

### Nivel 3: Avanzado

- Resolver un conflicto entre dos recetas.
- Crear una plantilla para Pull Requests.
- Agregar una guía `CONTRIBUTING.md`.
- Organizar las recetas por categorías.

---

## 🧩 Ideas de recetas para aportar

- Milanesa napolitana
- Empanadas de carne
- Tarta de verduras
- Pizza casera
- Torta de chocolate
- Panqueques
- Ñoquis caseros
- Sopa paraguaya
- Chipa
- Arepas
- Feijoada
- Alfajores de maicena

---

## 📌 Reglas del proyecto

Para que el proyecto sea ordenado:

1. Cada receta debe estar en un archivo separado dentro de la carpeta `recetas/`.
2. El nombre del archivo debe estar en minúsculas y usar guiones.

   Ejemplo correcto:

   ```txt
   pizza-casera.md
   ```

   Ejemplo incorrecto:

   ```txt
   Pizza Casera.md
   ```

3. Cada receta debe tener ingredientes y preparación.
4. Los commits deben tener mensajes claros.
5. Antes de hacer un Pull Request, revisá que tu receta se lea bien.
6. Respetá el trabajo de los demás colaboradores.

---

## 👥 Colaboradores

Agregá tu nombre cuando hagas tu primera contribución:

- Gabriel
- Tu nombre aquí

---

## 🛠️ Comandos útiles de Git

| Acción | Comando |
|---|---|
| Ver estado del proyecto | `git status` |
| Ver cambios realizados | `git diff` |
| Crear una rama | `git checkout -b nombre-de-rama` |
| Cambiar de rama | `git checkout nombre-de-rama` |
| Agregar cambios | `git add .` |
| Crear commit | `git commit -m "Mensaje claro"` |
| Subir cambios | `git push origin nombre-de-rama` |
| Traer cambios del repositorio | `git pull` |

---

## 🧯 Problemas comunes

### Me equivoqué en el mensaje del commit

Podés corregir el último mensaje con:

```bash
git commit --amend -m "Nuevo mensaje correcto"
```

---

### No sé en qué rama estoy

Ejecutá:

```bash
git branch
```

La rama actual aparece marcada con un asterisco `*`.

---

### Git me dice que hay conflictos

Un conflicto ocurre cuando dos personas modifican la misma parte de un archivo.  
Para resolverlo:

1. Abrí el archivo con conflicto.
2. Buscá las marcas `<<<<<<<`, `=======` y `>>>>>>>`.
3. Elegí qué contenido conservar.
4. Guardá el archivo.
5. Hacé un nuevo commit.

---

## ✅ Checklist antes de enviar un Pull Request

- [ ] Mi receta está dentro de la carpeta `recetas/`.
- [ ] El archivo tiene nombre claro y en minúsculas.
- [ ] La receta tiene ingredientes.
- [ ] La receta tiene preparación paso a paso.
- [ ] Revisé la ortografía.
- [ ] Hice commit con un mensaje claro.
- [ ] Subí mi rama a GitHub.

---

## 📚 Qué se aprende con este proyecto

Al terminar este ejercicio vas a entender mejor cómo funciona un flujo real de colaboración en GitHub:

1. Una persona crea una rama.
2. Hace cambios en el proyecto.
3. Guarda esos cambios con commits.
4. Sube la rama a GitHub.
5. Crea un Pull Request.
6. Otra persona revisa los cambios.
7. El cambio se aprueba y se une al proyecto principal.

---

## 🏁 Conclusión

Este recetario no busca solamente juntar recetas.  
Busca que aprendas GitHub practicando con algo simple, visual y fácil de entender.

La mejor forma de aprender GitHub es colaborar, equivocarse, corregir y volver a intentar.

¡Buen provecho y buenos commits! 🍽️🚀
