


> Written with [StackEdit](https://stackedit.io/).
> # Despliegue en Azure

1. Ir al [Azure Portal](https://portal.azure.com).
2. Iniciar sesión.
3. Crear un recurso.
4. Escribir en el buscador interno: *Aplicación web estática*.
5. Seleccionar el servicio de *Aplicación web estática*.
6. Hacer clic en *Crear*.
7. En el campo de nombre (3er campo), ingresar el nombre: *Pokedex*.
8. En el tipo de plan, dejarlo en *Estándar*.
9. Iniciar sesión con *GitHub*.
10. Hacer clic en el botón verde *Autorizar*.
11. Seleccionar el repositorio de GitHub: *Pokedex*.
12. Hacer clic en el botón *Revisar y crear*.
13. Hacer clic en *Crear*.
14. Hacer clic en *Ir a recurso* y luego en *Visitar sitio*.

## Agregar seguridad

1. Ir al menú lateral izquierdo y seleccionar *Configuración*.
2. Hacer clic en *Routes*.
3. Hacer clic en *Add*.
4. Agregar los siguientes encabezados de seguridad:
   - "x-frame-options": "DENY"
   - "permissions-policy": "geolocation=(), microphone=(), camera=()"
5. En el campo *Ruta*, ingresar: /* (esto aplica los encabezados a todas las URLs).
6. Hacer clic en el botón *Agregar*.
