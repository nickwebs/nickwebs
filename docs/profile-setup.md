# Configuración y publicación

El README muestra una identidad personal breve. El nombre visible, la bio, la web y los pins se gestionan fuera del archivo. Esta entrega no modifica la cuenta ni los repositorios fijados.

## Propuesta de campos

- Nombre visible: **Izan**.
- Bio: **Desarrollo web. Interfaces claras y código cuidado.**
- Web: **https://iryx.es/**.

La bio tiene menos de 160 caracteres, el límite actual documentado por GitHub. No se propone añadir datos de contacto ni otra información personal.

## Publicar

GitHub muestra el README de perfil cuando existe un repositorio público con el mismo nombre que el usuario y un README.md no vacío en su raíz. Para esta cuenta, el destino es **nickwebs/nickwebs**.

1. Comprueba si el repositorio remoto existe. No se encontró durante la preparación local; ese estado puede cambiar.
2. Si no existe, créalo como público, llamado nickwebs, sin archivos iniciales que generen una historia distinta.
3. Desde la carpeta local nickwebs, revisa el estado Git, la rama y los remotos. Después de autorizar la publicación, añade origin con el destino correspondiente y sube la rama main.

```sh
git status
git branch --show-current
git remote -v
git remote add origin https://github.com/nickwebs/nickwebs.git
git push -u origin main
```

Si el remoto ya contiene trabajo, consérvalo: clónalo y compara antes de trasladar archivos. No uses force push ni reemplaces la historia existente.

4. Revisa el perfil real en GitHub: carga de imágenes, temas claro y oscuro, selección de la cabecera móvil, enlace a la web y ausencia de desbordamiento en 320, 375, 768 y 1440 px.

La previsualización local es una aproximación. La API de Markdown comprueba el HTML saneado, pero no verifica todos los filtros finales de rutas ni el proxy de imágenes del perfil publicado.

[Documentación de los README de perfil](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
