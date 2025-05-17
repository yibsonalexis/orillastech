# 🌍 Orillas Tech - Página Web de la Fundación

Bienvenido al repositorio oficial de **Orillas Tech**, una fundación creada para enseñar programación a jóvenes en comunidades con acceso limitado a internet, energía y educación tecnológica. Esta web será el espacio donde compartiremos nuestra misión, historias de impacto y formas en las que otros pueden unirse a nuestra causa.

---

## 📄 Información de la Fundación

Puedes conocer más sobre el proyecto en el siguiente documento oficial:

👉 [Información completa de Orillas Tech](https://docs.google.com/document/d/16MaubenzVjxmRcPcp8QpsSW3d2yPCDw883gqJsczEio/edit?usp=sharing)

---

## 🚀 Estructura de Ramas

Usaremos el siguiente flujo de trabajo en Git:

- `main`: rama principal y estable (producción).
- `dev`: rama de desarrollo base para nuevas funcionalidades.
- `feature/*`: ramas hijas de `dev` para trabajar en tareas específicas.

### ➕ Cómo nombrar tus ramas:

Utiliza nombres descriptivos y en inglés, separados por guiones. Ejemplos:

```
feature/contact-form
feature/impact-section
feature/fix-navbar
```

---

## 🛠️ Clonar y trabajar en el proyecto

### 1. Clona el repositorio

```bash
git clone https://github.com/yibsonalexis/orillastech.git
cd orillastech
```

### 2. Cámbiate a la rama `dev`

```bash
git checkout dev
git pull origin dev
```

### 3. Crea tu rama de trabajo a partir de `dev`

```bash
git checkout -b feature/tu-funcionalidad
```

Ejemplo:

```bash
git checkout -b feature/contact-form
```

### 4. Haz tus cambios y guarda

```bash
git add .
git commit -m "Add contact form component"
```

> ✅ Usa mensajes de commit en inglés, claros y en presente.

### 5. Sube tu rama

```bash
git push origin feature/contact-form
```

---

## ✅ Buenas Prácticas

- No trabajes nunca directamente en `main` o `dev`.
- Usa ramas `feature/*` para tus desarrollos.
- Haz commits pequeños y frecuentes.
- Usa `git status` para ver los cambios antes de hacer commit.
- Asegúrate de que tu código esté limpio y funcione antes de subirlo.
- Siempre prueba en dispositivos móviles también.
