# Tutorial uso GITHUB 

Github es una plataforma para hospedaje de repositorios GIT, que ofrece un control de versiones,
funcionalidad para la coolaboración.

## Pasos taller

1. Crear cuenta en github. https://github.com/

2. Crear llave SSH para la autenticación de operacions git y github.

    `ssh-keygen -t ed25519`

3. Copiar llave publica a listado de llaves SSH en github. https://github.com/settings/keys

4. Crear repositorio remoto para hospedar repositorio local.

5. Sincronizar cambios de repositorio local a repositorio remoto.

6. Clonar repositorio remoto en PC's de desarrolladores.

```bash    
    # Clonar el repositorio remoto en una carpeta local.
    git clone git@github.com:hmedrano/repositorio-ejemplo.git
```

7. Crear una rama de desarrollo en repositorio local.

```bash
    # Ejemplo comandos a utilizar, 
    # Crear una nueva rama, y cambiarse a esa rama.
    git checkout -b nombre-nueva-rama
```

8. Agregar cambios y someter una nueva version.  **Importante: Hacer los cambios en su rama de desarrollo, no en main!**

```bash
    # Hacer cambios, en esta nueva rama
    git commit -a -m 'descripcion cambios'
```

9. Subir rama y cambios a repositorio remoto.

```bash
    # Subir cambios a repositorio remoto
    git push
```

10. Hacer una solicitud de "Pull Request" desde la interface de github.

11. Aceptar el "Pull Request", haciendo "Merge Pull Request" desde la interface de github.

12. Crear un issue y corregir.

13. Crear un fork de un repositorio github.

