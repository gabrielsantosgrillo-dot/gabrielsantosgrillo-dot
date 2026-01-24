##  ¡Bienvenido a mi perfil!

Soy estudiante de **1º curso de Ingeniería Informática** en la **Universidad de Castilla-La Mancha**,
 **Campus de Ciudad Real**.

Me apasiona el desarrollo de software y actualmente tengo **muchos proyectos en mente**, tanto personales como académicos, con los que busco aprender, experimentar y mejorar mis habilidades como programador.

---

## Sobre mis proyectos
He explorado diversas plataformas y metodologías para el despliegue de aplicaciones, adaptándome a las exigencias de cada entorno:


En **Google Play Store**: Actualmente cuento con un proyecto en fase de Prueba Cerrada. Se trata de un juego de combate naval, desarrollado originalmente como una extensión de un trabajo universitario que decidí profesionalizar y publicar. Este proceso me ha permitido entender a fondo el ciclo de vida de una App y los estrictos requisitos de calidad de Google (como el cumplimiento de los 14 días con 20 testers, fase en la que me quedo encallado).

Experiencia con **Expo Go (React Native)**: Experimenté con el ecosistema de Expo para el desarrollo de aplicaciones nativas. Sin embargo, identifiqué que la dependencia de una aplicación externa para la ejecución y las limitaciones en la distribución, existe una gran facilidad para Android pero no para el resto de plataformas por lo que dificultaban la accesibilidad inmediata para los usuarios.

*Desarrollo Web y CI/CD*
Ecosistema **GitHub & Vercel** Ante los retos de las tiendas de aplicaciones, he optado por Vercel como mi plataforma principal de despliegue para mis últimos proyectos. Esta arquitectura me permite:
Mantener flujos de Integración Continua (CI/CD) conectando mis repositorios privados de GitHub.
Ofrecer acceso instantáneo a mis herramientas (como el compresor de imágenes o el edificio navideño) sin necesidad de instalaciones previas.
Documentar y evolucionar mi código de forma abierta, asegurando que el trabajo sea siempre accesible y funcional.

---

##  Proyectos

A continuación iré enlazando mis proyectos más importantes, y cuyo código tengo en **repositorios privados de Github**:

---
##  APLICACIONES DE GESTIÓN Y HERRAMIENTAS TÉCNICAS


### 🔹 Proyecto 1

**Publicado** https://concursofotografico.vercel.app/

[ Leer Manual Usuario del Concurso Fotográfico](https://github.com/gabrielsantosgrillo-dot/JuegosCartas/blob/main/manuales/concursofotografico.md)

[ Leer Manual Técnico del Concurso Fotográfico](https://github.com/gabrielsantosgrillo-dot/JuegosCartas/blob/main/tecnico/concursofotografico.md)

**Nombre:** **Concurso Fotográfico**

Inicialmente el proyecto lo realice como complemento al Proyecto 4, aunque lo he evolucionado a multiconcurso.

Proyecto realizado como complemento al Proyecto 8. Es un concurso fotográfico,La aplicación esta preparada para múltiples usuarios

Observaciones: Logré integrar exitosamente MongoDB Atlas con Vercel tras superar retos de configuración en el entorno de ejecución, resolviendo errores críticos de resolución de módulos  y autenticación de red. La clave del éxito fue separar la lógica de servidor del cliente y, fundamentalmente, nunca incluir la cadena de conexión o la contraseña directamente en el código fuente. En su lugar, utilicé Variables de Entorno en el panel de Vercel, lo que garantiza que las credenciales permanezcan cifradas y protegidas, cumpliendo con los estándares de seguridad  para evitar filtraciones de acceso a la base de datos.

Límite máximo: 4.5 MB por imagen(no viene de MongoDB, sino de Vercel), e incluido un modulo para optimizar imagenes utilizando mi proyecto 1 y las imagenes se guarda aprox 500 KB  en formato base 64. en proximas versiones tratare de las imagenes guardarlas en Cloudinary y los datos en MONGODB ATLAS, debido a la limitación actual de MONGODB que con la configuración actual y ser una cuenta gratuita me permite unas 770 imagenes.
 
---

### 🔹 Proyecto 2 
*Publicado*  https://comprimir-imagenes.vercel.app/

[ Leer Manual Usuario de Ga-Optimo](https://github.com/gabrielsantosgrillo-dot/JuegosCartas/blob/main/manuales/comprimirimagenes.md)

[ Leer Manual Técnico del Ga-Optimo](https://github.com/gabrielsantosgrillo-dot/JuegosCartas/blob/main/tecnico/comprimirimagenes.md)

**Nombre de la aplicación:** **Ga-Optimo**

Debido a las necesidades de compresión del proyecto 1 se implemento esta herramienta de forma individual. Es una herramienta web para la compresión de imágenes desarrollada íntegramente con lógica en el lado del cliente.Se aprovecha la capacidad del navegador para manipular los datos localmente.

---

### 🔹 Proyecto 3
 **Publicado (en fase Test)**  https://correccionexamenes.vercel.app/

**Sistema de corrección de exámenes tipo test y desarrollo**

Proyecto realizado por encargo de mi padre. La aplicación cubre todas las fases del proceso:

**Configuración:**
- Definición de baremos complejos
- Puntos por acierto
- Penalización por fallo
- Notas de corte y decimales

**Generación de documentación (HTML / PDF):**
- Hojas de respuestas con marcas de sincronización
- Hojas de identificación del opositor
- Etiquetas con códigos de barras únicos (EAN-13)
- Plantillas transparentes (acetatos) para comprobación manual

**Gestión y administración (módulos):**
- **Control de opositores:**  
  Base de datos con importación/exportación JSON y vinculación DNI / EAN-13
- **Cotejo (verificación):**  
  Módulo de seguridad para validar resultados escaneados y añadir observaciones
- **Gestión de soluciones:**  
  Administrador de claves maestras con soporte para preguntas de reserva

---
##  APLICACIONES EDUCATIVAS / GUÍAS DIGITALES

### 🔹 Proyecto 4
**Publicado** https://viajeamalaga.vercel.app/

**Nombre:** **Fray Andrés en Málaga**

Proyecto encargado por mi madre. Con motivo de viaje escolar a Málaga
 
---
##  APLICACIONES DE ENTRETENIENTO

### 🔹 Proyecto 5  
*Publicado* https://juegocartastradicional.vercel.app/

**Nombre:** **Juegos de Cartas Españolas**

**Propósito:**  
Plataforma multijuego diseñada para cualquier tipo de dispositivo que rinde homenaje a los clásicos de la baraja española, especialmente a un juego de mi abuelito (**Giley**) y mi primo(**Culo**)

Sin necesidad de registro ni conexión. Juegas contra la máquina.

**Juegos incluidos:**
- **Cuatrola:** Juego estratégico 2 vs 2 con baraja de 20 cartas y sistema de retos (Solo, Cuatrola, Sextola).
- **Tute:** Clásico de 3 jugadores con reglas de arrastre, cánticos y cambios de triunfo.
- **Giley:** Juego de descarte enfocado en sumar puntos por palos.
- **Siete y Media:** Clásico de apuesta y riesgo contra la banca.
- **Culo:** Juego de descarte.
- 

---

### 🔹 Proyecto 6  
**Publicado** https://nomedeslalata.vercel.app/

**Nombre:** **¡No me des la lata!**

Homenaje a mi hermano. Es un juego de lógica y memoria visual con una estética de *estantería de bebidas*.

**Objetivo del juego:**
- Descubrir la secuencia exacta de latas generada aleatoriamente
- Colocar todas las latas en su posición correcta
- Resolverlo en el menor tiempo y número de movimientos posible

---

### 🔹 Proyecto 7  
 **Publicado**  https://juego-barcos.vercel.app/

**Juego de los Barcos**

El juego está desarrollado, como ampliación de un trabajo en la Universidad,  es un juego de barcos clásico donde he trabajado mucho en la interfaz y en crear una lógica de juego que sea difícil para el usuario

---
### 🔹 Proyecto 8  
**Publicado** https://ahorcado-personalizado.vercel.app/

**Nombre:** **Ahorcado Personalizado**

Ahorcado Personalizado lo he diseñado para que de forma interactiva se adivina palabras ofrece retos infinitos a través de tres modalidades:  Aleatoria, Temática (basada en cualquier concepto que imagines) y Modo Manual para listas personalizadas. Con un límite de 6 fallos, el juego integra un sistema de pistas inteligentes y definiciones educativas al finalizar cada partida, logrando un equilibrio perfecto entre entretenimiento clásico y aprendizaje moderno en una interfaz optimizada .

---
### 🔹 Proyecto 9  
**Publicado** https://campoamor10.vercel.app/

**Nombre:** **Edificio Navideño**

Proeycto realizado por mi vinculación con los vecinos de la Calle Campoamor, 10 de Puertollano. Edificio Navideño es una experiencia interactiva diseñada para celebrar la Navidad en la comunidad de Campoamor 10 en Puertollano, que combina la narrativa tradicional con divertidos desafíos digitales. A través de una interfaz optimizada para cualquier dispositivo, los usuarios pueden explorar las plantas de un edificio para descubrir cinco mini-juegos temáticos que restauran la "magia" de cada planta y enfrentarse en una batalla final contra un muñeco de nieve travieso, todo funcionando de manera 100% local y privada para garantizar una experiencia segura, fluida y llena de espíritu navideño.
 
---

##  En qué estoy trabajando

Mis proyectos están enfocados en:

* Aprender nuevas tecnologías
* Mejorar buenas prácticas de programación
* Resolver problemas reales
* Construir aplicaciones útiles y de entretenimiento

Actualmente estoy enfocado en el desarrollo web moderno, explorando arquitecturas SPA y metodologías de despliegue continuo.

Aunque la mayoría de mis proyectos actuales se encuentran en **repositorios privados** (por motivos  de desarrollo), aquí detallo el stack tecnológico con el que construyo mis aplicaciones:

#### 💻 Tech Stack & Herramientas

**Core & Frontend:**
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

**Estilos & UI:**
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Lucide](https://img.shields.io/badge/Lucide_Icons-black?style=for-the-badge&logo=lucide&logoColor=white)

**Infraestructura & Despliegue:**
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

Mis aplicaciones son Single Page Applications (SPA) optimizadas para dispositivos móviles, utilizando React Router para la navegación y una arquitectura basada en componentes.

---
## Contacto

Si te interesa colaborar, dar feedback o simplemente charlar sobre desarrollo:

* 💬 GitHub Issues / Pull Requests
* 📧 gabrielsantosgrillo@gmail.com

---

 *Este perfil irá creciendo junto con mis conocimientos y proyectos.*
