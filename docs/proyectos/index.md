# Proyectos

Proyectos en curso e ideas en evaluación.

| Proyecto | Estado | Áreas involucradas |
|----------|--------|-----------------------|
| [Estacionamiento (Cochera 2.0)](estacionamiento.md) | En formulación | Electromecánica, Industrial, Civil, Sistemas, Sustentabilidad |
| [Asignación de espacios y aulas](asignacion-espacios.md) | Piloto en preparación | Sistemas, Mantenimiento |
| [Cámaras de seguridad](camaras-seguridad.md) | En formulación | Infraestructura, Sistemas |
| [Jefatura del Área (Operaciones TIC)](jefatura.md) | En formulación | Operaciones TIC, Secretaría |
| [Gestión de RAE](gestion-rae.md) | En formulación | Sostenibilidad, Administración |
| [Programa de becarios y pasantes](becarios-pasantes.md) | En formulación | Sistemas, Secretaría |
| [Diplomatura en Ciberseguridad](diplomatura-ciberseguridad.md) | En preparación | Oferta académica |

## ¿Tenés una idea de proyecto?

Contanos tu idea y la revisamos. Dejá tu propuesta acá abajo:

<form class="idea-form" onsubmit="return enviarIdea(this)">
  <label>Tu nombre
    <input type="text" name="nombre" required placeholder="Nombre y apellido">
  </label>
  <label>Tu email <span class="opt">(opcional)</span>
    <input type="email" name="email" placeholder="tucorreo@ejemplo.com">
  </label>
  <label>Tu idea
    <textarea name="idea" rows="4" required placeholder="Contanos de qué se trata..."></textarea>
  </label>
  <button type="submit">Enviar idea</button>
  <p class="idea-nota">Se abrirá tu correo con el mensaje ya redactado para enviar.</p>
</form>

<script>
function enviarIdea(f){
  var n=f.nombre.value, m=f.email.value, t=f.idea.value;
  var user="cerutti_andres", dom="hotmail.com";
  var cuerpo="Nombre: "+n+"\nEmail: "+m+"\n\nIdea:\n"+t;
  var url="mailto:"+user+"@"+dom
        +"?subject="+encodeURIComponent("Idea de proyecto — "+n)
        +"&body="+encodeURIComponent(cuerpo);
  window.location.href=url;
  return false;
}
</script>
