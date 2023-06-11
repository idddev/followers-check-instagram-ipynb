# followers-check-instagram-ipynb
Scrapper y analizador de seguidores de Instagram hecho en Python con Jupyter Notebook.

Utiliza Selenium para navegar por la app web de Instagram y obtener los datos de los seguidores de un usuario.

Se debe crear un archivo `credentials.json` con las credenciales de acceso a Instagram en formato:

```json
{
    "username": "username",
    "password": "password"
}
```

Estas credenciales se autocompletan en el formulario de Login de Instagram. Una vez logueado, se navega a la página del usuario y se obtiene la lista de seguidores.