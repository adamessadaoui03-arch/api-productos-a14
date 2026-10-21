# Instalación

## 1. Software necesario

- [Node.js](https://nodejs.org) (incluye `npm`)
- Git

Comprueba que están instalados:

```bash
node --version
npm --version
git --version
```

## 2. Obtener el proyecto

```bash
git clone https://github.com/adamessadaoui03-arch/api-productos-a14.git
cd api-productos-a14
```

## 3. Instalar dependencias

```bash
npm install
```

## 4. Iniciar la aplicación

```bash
npm start
```

Debe aparecer en consola: `API disponible en http://localhost:3000`

## 5. Comprobar el funcionamiento

```bash
curl http://localhost:3000/api/productos
curl http://localhost:3000/api/productos/1
curl http://localhost:3000/api/productos/99
```

El último comando devuelve un error 404 (`Producto no encontrado`), lo cual es correcto.
