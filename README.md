## README para la implementación

### Requisitos previos

* Servidor web Apache
* Base de datos MySQL (específicamente  `encuestasdb` en el servidor)
* GitHub

### Pasos para la implementación

**1. Acceder al directorio del proyecto:**

```bash
cd /var/www/html/encuestas/
```

**2. Clonar el repositorio del backend:**

Clone el repositorio del backend de encuestas en la ruta especificada:

```bash
git clone <URL_REPOSITORIO> encuestas_back
```

**3. Actualizar cambios en el código:**

1. Realice los cambios necesarios en el código del backend y envíelos a la rama `main` del repositorio.
2. En el servidor, navegue a la ruta del backend:

```bash
cd /var/www/html/encuestas/encuestas_back
```

3. Actualice el repositorio local con los últimos cambios:

```bash
git pull
```
