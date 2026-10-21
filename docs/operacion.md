# Operación y resolución de problemas

## Iniciar la API

```bash
npm start
```

## Detener la API

Pulsa `Ctrl + C` en la terminal donde se está ejecutando.

## Comprobar que responde

```bash
curl http://localhost:3000/api/productos
```

## Identificar errores

Los errores aparecen en la consola donde se ejecutó `npm start`.

## Incidencias comunes

| Problema | Comprobación | Posible solución |
|----------|--------------|------------------|
| `npm` no existe | `npm --version` | Instalar Node.js/npm |
| Faltan dependencias | Revisar error al iniciar | Ejecutar `npm install` |
| Puerto 3000 ocupado | Revisar procesos/puertos | Liberar el puerto |
