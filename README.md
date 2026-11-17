# PROVEEDORES-ANDRES

Sistema de pedidos entre proveedor y comprador (en Bs), con catálogo, pedidos y dashboard compartidos en tiempo real mediante Firebase Realtime Database.

- **Firebase Hosting:** https://proveedores-andres.web.app
- **GitHub Pages:** https://dialgaluis.github.io/PROVEEDORES-ANDRES/

## Estructura
- `docs/index.html` — la aplicación completa (HTML + CSS + JS)
- `database.rules.json` — reglas de seguridad de la base de datos (Realtime Database)
- `firebase.json` / `.firebaserc` — configuración de Firebase

## Publicar cambios
```bash
npx firebase-tools deploy
```
GitHub Pages se actualiza solo al subir cambios a `main`.
