# Catálogo B2B IDEUS · XSPACE

Web pública del catálogo de clientes (https://catalogo.ideus.com).

- `index.html` se genera cada mañana desde `build_catalogo.py` (no editar a mano).
- Los productos y precios de cada cliente van **cifrados con su contraseña** (AES-256-GCM, PBKDF2 600k): sin la contraseña no se pueden leer.
- Las contraseñas y la configuración **no** están en este repositorio.
