# 📋 Todo Machine - React Todo App

Una aplicación moderna y funcional de gestión de tareas (Todo App) construida con **React.js**, desarrollada como parte del [Curso de Introducción a React.js](https://platzi.com/reactjs) de Platzi.

## 🚀 Demo en Vivo

📱 **Accede a la aplicación aquí:** [https://devzuela.github.io/react-todo-machine/](https://devzuela.github.io/react-todo-machine/)

## ✨ Características

- ✅ Crear, editar y eliminar tareas
- 🔍 Buscar tareas por texto
- ☑️ Marcar tareas como completadas
- 📊 Contador de tareas completadas y pendientes
- 🎨 Interfaz moderna y responsiva
- 💾 Almacenamiento persistente con Local Storage
- 🌓 Diseño profesional y limpio

## 🛠️ Tecnologías Utilizadas

### React Hooks & Features
- **`useState`** - Manejo de estado en componentes funcionales
- **`useEffect`** - Efectos secundarios y ciclo de vida
- **`useContext`** - Context API para estado global
- **`useLocalStorage`** - Hook personalizado para persistencia de datos

### Tecnologías
- **React 18** - Biblioteca de UI
- **React Hooks** - Lógica de componentes modernos
- **CSS3** - Estilos personalizados y responsive
- **Local Storage API** - Persistencia de datos
- **Create React App** - Herramienta de configuración

## 🏃 Primeros Pasos

### Requisitos previos
- Node.js (versión 14 o superior)
- npm o yarn

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/devzuela/react-todo-machine.git
cd react-todo-machine

# Instalar dependencias
npm install
```

### Desarrollo

```bash
# Inicia la aplicación en modo desarrollo
npm start
```

La aplicación se abrirá en [http://localhost:3000/todo-machine](http://localhost:3000/todo-machine) en tu navegador.

## 📦 Scripts Disponibles

### `npm start`

Ejecuta la aplicación en modo desarrollo.\
Abre [http://localhost:3000/todo-machine](http://localhost:3000/todo-machine) para verla en tu navegador.

La página se recargará cuando hagas cambios.\
También verás errores de linting en la consola.

### `npm run build`

Compila la aplicación para producción en la carpeta `build`.\
Hace bundling correcto de React en modo producción y optimiza el build para el mejor rendimiento.

El build está minificado y los nombres de archivos incluyen hashes.\
¡Tu app está lista para ser deployada!

### `npm run deploy`

Publica la aplicación en GitHub Pages automáticamente.\
Requiere tener configuradas las credenciales de GitHub.

```bash
npm run deploy
```

## 📂 Estructura del Proyecto

```
src/
├── App/                      # Componente principal de la aplicación
├── CreateTodoButton/         # Botón para crear nuevas tareas
├── EmptyTodos/              # Mensaje cuando no hay tareas
├── Modal/                   # Modal para crear/editar tareas
├── TodoContext/             # Context API y hooks personalizados
│   ├── index.js            # Proveedor de contexto
│   └── useLocalStorage.js   # Hook para persistencia de datos
├── TodoCounter/             # Contador de tareas completadas/pendientes
├── TodoForm/                # Formulario para crear tareas
├── TodoIcon/                # Iconos de las tareas (completar, eliminar)
├── TodoItem/                # Item individual de una tarea
├── TodoList/                # Lista de tareas
├── TodoSearch/              # Buscador de tareas
├── TodosError/              # Componente de error
├── TodosLoading/            # Componente de carga
└── index.js                 # Punto de entrada
```

## 🎓 Conceptos de React Aprendidos

### React Hooks
- **useState**: Manejo de estado en componentes funcionales
- **useEffect**: Efectos secundarios (fetch, suscripciones, etc.)
- **useContext**: Consumo de Context API para estado global

### Patrones
- **Componentes Funcionales**: Uso de functional components
- **Props**: Paso de datos entre componentes
- **Lifting State Up**: Elevar estado a componentes padres
- **Context API**: Manejo de estado global sin prop drilling
- **Custom Hooks**: Creación de hooks personalizados

## 🔧 Configuración de Despliegue

La aplicación está configurada para desplegarse en GitHub Pages. El `homepage` en `package.json` apunta a:

```json
"homepage": "https://devzuela.github.io/react-todo-machine/"
```

## 📝 Notas

- La aplicación usa **Local Storage** para persistir los datos, por lo que las tareas se guardan localmente en tu navegador
- Los estilos están optimizados para ser responsivos y funcionar en dispositivos móviles
- Todos los componentes son reutilizables y modulares

## 📚 Recursos

- [React Documentation](https://reactjs.org/)
- [React Hooks Documentation](https://reactjs.org/docs/hooks-intro.html)
- [Create React App Documentation](https://create-react-app.dev/)
- [Platzi - Curso de Introducción a React.js](https://platzi.com/reactjs/)

## 👨‍💻 Autor

Desarrollado durante el Curso de Introducción a React.js de Platzi

---

¡Mucha suerte aprendiendo React! #NuncaParesDeAprender
