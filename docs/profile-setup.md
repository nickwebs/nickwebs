# Configuración y actualizaciones

El README está publicado en el [perfil de nickwebs](https://github.com/nickwebs). Los archivos se mantienen en el [repositorio nickwebs/nickwebs](https://github.com/nickwebs/nickwebs), en la rama main.

El nombre visible, la bio, la web y los pins se gestionan fuera del archivo. La publicación del README no modifica esos campos ni los repositorios fijados.

## Propuesta de campos

- Nombre visible: **Izan**.
- Bio: **Desarrollo web. Interfaces claras y código cuidado.**
- Web: **https://iryx.es/**.

La bio tiene menos de 160 caracteres, el límite actual documentado por GitHub. No se propone añadir datos de contacto ni otra información personal.

## Actualizar el perfil

GitHub muestra el README.md de la raíz porque el repositorio es público y tiene el mismo nombre que el usuario. Mantén esa estructura y conserva los recursos en assets/.

1. Edita los textos o recursos necesarios, siguiendo maintenance.md.
2. Revisa el diff y las variantes visuales. Añade al commit únicamente las rutas modificadas; el ejemplo siguiente corresponde a un cambio de texto en README.md.
3. Publica el commit en main cuando la actualización esté lista.

```sh
git status --short
git diff --check
git diff
git add -- README.md
git diff --cached
git commit -m "Update profile introduction"
git push origin main
```

Si otra copia ha publicado cambios, recupéralos y compáralos antes de integrar tu actualización. No uses force push ni reemplaces la historia existente.

4. Revisa el perfil real: carga de imágenes, temas claro y oscuro, selección de la cabecera móvil, enlace a la web y ausencia de desbordamiento en 320, 375, 768 y 1440 px.

Una previsualización local es una aproximación. La comprobación en el perfil publicado permite verificar también las rutas y la entrega real de las imágenes.

[Documentación de los README de perfil](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
