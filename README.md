# Reconstrucción Semántica de Página Web  
**Taller de HTML Semántico**

Este proyecto consiste en reconstruir la estructura principal de una página web real utilizando únicamente HTML semántico, sin CSS, sin clases, sin IDs y sin elementos decorativos.  
El objetivo es organizar el contenido de forma clara, accesible y semánticamente correcta.

---

## 1. Página escogida
Elegí la **Super Mario Wiki (Fandom ES)** porque su página principal contiene:

- Encabezado claro  
- Navegación visible  
- Secciones temáticas bien diferenciadas  
- Artículos destacados  
- Noticias  
- Información secundaria  

Esto permite aplicar correctamente etiquetas semánticas sin copiar contenido literal.

---

## 2. Cómo identifiqué cada parte semántica

Analicé visualmente la estructura de la página y la separé en bloques lógicos:

### **✔ Header**
Incluye el título del sitio y una frase introductoria.  
Representa la identidad de la página.

### **✔ Nav**
Contiene los enlaces principales del sitio: Portada, Personajes, Juegos, Objetos, Lugares.  
Es la navegación global.

### **✔ Main**
Aloja todo el contenido principal del sitio. Dentro de él identifiqué:

- **Section: Bienvenida**  
  Introducción general al contenido del sitio.

- **Section: Artículo destacado**  
  Contiene un artículo completo sobre un personaje.

- **Section: Secciones principales**  
  Agrupa artículos sobre personajes, enemigos, objetos, juegos y lugares.

- **Section: Noticias recientes**  
  Incluye artículos cortos con información actualizada.

### **✔ Article**
Usado para cada bloque de contenido independiente que tiene sentido por sí mismo:  
personajes, enemigos, objetos, juegos, noticias, artículo destacado.

### **✔ Aside**
Incluye información secundaria como créditos del proyecto y notas adicionales.

### **✔ Footer**
Contiene información legal y de cierre del documento.

---

## 3. Por qué usé cada etiqueta semántica importante

### **strong**
Para resaltar nombres o conceptos clave dentro del contenido (ej. Mario, Luigi, Bowser).

### **em**
Para enfatizar palabras que requieren tono especial, como nombres de enemigos o términos relevantes.

### **u**
Para destacar nombres de lugares importantes (ej. Reino Champiñón).

### **mark**
Para resaltar objetos icónicos dentro del universo Mario (ej. Super Champiñón).

### **blockquote**
Para incluir una cita famosa del personaje destacado.

### **cite**
Para referenciar obras o juegos donde aparece un personaje (ej. Donkey Kong).

### **abbr**
Para abreviar nombres de juegos o títulos largos (ej. SMK).

### **time**
Para marcar fechas relevantes como el año de lanzamiento de un juego.

### **address**
Para incluir información del autor del proyecto, ya que corresponde a datos de contacto o autoría.

Cada etiqueta fue usada **solo cuando el contenido lo justificaba**, no de forma artificial.

---

## 4. Qué partes decidí eliminar y por qué

La página original de Fandom incluye muchos elementos que **no forman parte del contenido real**, como:

- Publicidad  
- Banners de registro  
- Botones de redes sociales  
- Comentarios  
- Widgets interactivos  
- Elementos promocionales  
- Secciones automáticas de la plataforma  

Todos estos fueron eliminados porque:

- No aportan contenido informativo  
- No son parte del objetivo del taller  
- No deben incluirse según las instrucciones  
- No tienen valor semántico  
- No pertenecen a la estructura principal del sitio  

Solo reconstruí el **contenido real**, organizado de forma semántica y accesible.

---

## 📁 Estructura del repositorio

/index.html
/README.md


---

## ✔ Estado del proyecto
Reconstrucción completada utilizando únicamente HTML semántico, siguiendo las buenas prácticas de accesibilidad y estructura recomendadas.

