# 🛒 LOOPIFY

ESTE ES UN PROYECTO DE E-COMMERCE DESARROLLADO CON **REACT.JS** PARA EL FRONTEND Y **FIREBASE FIRESTORE** COMO BASE DE DATOS EN TIEMPO REAL. LA APLICACIÓN PERMITE NAVEGAR POR UN CATÁLOGO DE PRODUCTOS, VER DETALLES, AGREGAR ÍTEMS AL CARRITO, REALIZAR COMPRAS Y REGISTRAR ÓRDENES.

---

## 🚀 CARACTERÍSTICAS

- **CATÁLOGO DE PRODUCTOS:**
  - VISUALIZA UNA LISTA DE PRODUCTOS OBTENIDOS DESDE FIRESTORE.
  - FILTRO DINÁMICO POR CATEGORÍAS USANDO `REACT ROUTER`.
  
- **CARRITO DE COMPRAS:**
  - AGREGA PRODUCTOS AL CARRITO.
  - CALCULA EL TOTAL DE LA COMPRA AUTOMÁTICAMENTE.
  - CONTROLA LA CANTIDAD DE PRODUCTOS.
  - PERMITE ELIMINAR ÍTEMS O VACIAR EL CARRITO POR COMPLETO.

- **ÓRDENES DE COMPRA:**
  - GENERA UNA ORDEN EN FIRESTORE CON LOS DATOS DEL COMPRADOR Y LOS ÍTEMS SELECCIONADOS.
  - ID ÚNICO PARA CADA ORDEN.
  - CONTROL DE STOCK EN TIEMPO REAL.

- **FORMULARIO DE COMPRADOR:**
  - SOLICITA AL USUARIO DATOS COMO NOMBRE, TELÉFONO Y CORREO ELECTRÓNICO ANTES DE FINALIZAR LA COMPRA.
  - VALIDACIÓN DE DATOS PARA EVITAR FORMULARIOS INCOMPLETOS.

---

## 🛠️ TECNOLOGÍAS UTILIZADAS

### FRONTEND
- **REACT.JS**: FRAMEWORK PARA LA CONSTRUCCIÓN DE LA INTERFAZ.
- **REACT ROUTER**: NAVEGACIÓN ENTRE LAS PÁGINAS.
- **CSS**: ESTILOS PERSONALIZADOS.

### BACKEND
- **FIREBASE FIRESTORE**: BASE DE DATOS EN TIEMPO REAL PARA ALMACENAR PRODUCTOS Y ÓRDENES.
- **FIREBASE SDK**: INTERACCIÓN CON FIRESTORE PARA OPERACIONES CRUD.

---

## 📂 ESTRUCTURA DEL PROYECTO

src/
├── components/
│   ├── Cart.js
│   ├── CartWidget.js
│   ├── Item.js
│   ├── ItemCount.js
│   ├── ItemDetail.js
│   ├── ItemDetailContainer.js
│   ├── ItemList.js
│   ├── ItemListContainer.js
│   ├── NavBar.js
├── context/
│   └── cartContext.js
├── firebase/
│   ├── config.js
│   ├── firestore.js
├── App.js
├── index.js
└── styles/
    └── index.css
