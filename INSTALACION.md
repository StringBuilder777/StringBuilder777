# Cómo instalar el perfil

El paquete está preparado para el repositorio público `StringBuilder777/StringBuilder777`.

## Archivos

```text
StringBuilder777/
├── README.md
├── assets/
│   ├── contribution-snake-dark.svg
│   ├── contribution-snake.svg
│   ├── stats.svg
│   └── top-langs.svg
└── .github/
    └── workflows/
        └── profile-assets.yml
```

## Activación

1. Copia los archivos conservando exactamente esta estructura.
2. Sube los cambios a la rama `main`.
3. Abre la pestaña **Actions** del repositorio.
4. Ejecuta manualmente **Update profile visuals** si no comenzó con el push.
5. Comprueba que el workflow creó un commit `chore: update profile visuals`.

El workflow actualiza diariamente:

- La tarjeta general de estadísticas.
- La tarjeta de lenguajes públicos.
- Las variantes clara y oscura de la serpiente de contribuciones.

No requiere un token personal para estadísticas públicas: utiliza `GITHUB_TOKEN`. Si una política del repositorio impide el commit automático, revisa **Settings → Actions → General → Workflow permissions** y permite escritura en contenidos.

## Elementos omitidos a propósito

- No se publicó el correo asociado a la cuenta.
- No se agregaron LinkedIn, X o Discord porque el perfil no declara enlaces públicos.
- No se incluyeron trofeos: el endpoint público advierte que podría descontinuarse.
- WakaTime y Spotify requieren cuentas, tokens o integraciones adicionales.

Cuando tengas enlaces públicos de contacto, añádelos junto a los botones de portafolio y seguidores.
