# Sistema Proveedores Andres

Sistema de pedidos entre proveedor y comprador (en Bs), con catálogo, pedidos y dashboard compartidos en tiempo real mediante Firebase Firestore.

- **Firebase Hosting:** https://sistema-proveedores-andres.web.app
- **GitHub Pages:** https://dialgaluis.github.io/sistema-proveedores-andres/

## Estructura
- `docs/index.html` — la aplicación completa (HTML + CSS + JS)
- `firestore.rules` — reglas de seguridad de la base de datos
- `firebase.json` / `.firebaserc` — configuración de Firebase

## Publicar cambios
```bash
npx firebase-tools deploy
```
GitHub Pages se actualiza solo al subir cambios a `main`.
