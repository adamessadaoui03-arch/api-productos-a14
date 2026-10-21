# Procedimiento de despliegue

Pasos para pasar del código fuente a tener la API funcionando:

1. Obtener el código: `git clone https://github.com/adamessadaoui03-arch/api-productos-a14.git`
2. Entrar en la carpeta: `cd api-productos-a14`
3. Instalar dependencias: `npm install`
4. Iniciar la API: `npm start`
5. Comprobar que funciona:

```bash
curl http://localhost:3000/api/productos
```

## Checklist

- [ ] No se han incluido contraseñas ni secretos en el repositorio
- [ ] Los posibles ficheros con secretos están incluidos en `.gitignore`
- [ ] En producción debería utilizarse HTTPS
- [ ] Solo deberían exponerse los puertos necesarios

!!! note
    La aplicación de ejemplo no utiliza secretos ni base de datos. Estas comprobaciones se incluyen como pauta para futuros despliegues.
