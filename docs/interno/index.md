---
level: interno
---

# Sección interna

!!! warning "Contenido protegido"
    Esta página está cifrada y solo puede verse con la clave.

Acá va el material de trabajo interno: actas de reunión, borradores, contactos,
información que no es para difusión general.

## Cómo funciona

- Esta página se cifra al publicar el sitio (cifrado AES en el navegador).
- La clave **no está en el repositorio**: se define como secret de GitHub
  (`UTN_CLAVE_INTERNO`) y se inyecta al publicar.
- Se pueden definir más niveles con claves distintas (una para docentes,
  otra para el equipo del proyecto, etc.) agregándolos en `password_inventory`
  dentro de `mkdocs.yml` y marcando las páginas con `level: <nombre>`.
