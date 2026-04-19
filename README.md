# 32 Bits - Inventario de Videojuegos

Proyecto desarrollado como desafío del Bootcamp Frontend Developer de Talento Digital para Chile. Sistema de inventario para una tienda ficticia de videojuegos que permite visualizar, aumentar y disminuir el stock de cada juego, con gestión de estado centralizada mediante Vuex.

> **Nota:** Este es un proyecto académico, no una aplicación comercial real.

## Vista previa

[Ver en GitHub Pages](https://vnasp.github.io/bootcamp-vue2-32bits/)

## Funcionalidades

- Carga de inventario desde archivo JSON local vía Axios
- Tabla de juegos con código, nombre, stock y precio
- Botones para aumentar y disminuir stock por juego
- Indicador de color por fila
- Totalizadores: cantidad de juegos y stock total
- Formateo de precios en CLP
- Gestión de estado con Vuex (state, getters, mutations, actions)

## Tecnologías

- Vue.js 2
- Vuex 3
- Axios
- BootstrapVue
- Bootstrap 5

## Estructura

```
src/
├── App.vue          → Interfaz principal con tabla de inventario
├── main.js          → Punto de entrada con plugins (Vuex, BootstrapVue)
├── assets/img/      → Logo y fondo de la tienda
└── store/
    └── index.js     → Store Vuex con state, getters, mutations y actions
public/
└── juegos.json      → Datos del inventario (6 juegos)
```
