## Universidad Peruana de Ciencias Aplicadas
### Informe del Trabajo Final
Curso: Aplicaciones Web
Carrera: Ingeniería de Software
Sección: WX56
Profesor: Alberto Wilmer Sanchez Seña
Startup: LawConnect
Producto: LawConnect

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
En esta sección describimos los productos de software que hemos usado en el proyecto. 
### 5.1.1. Software Development Environment Configuration
* Project Management
  - Github: (https://github.com/)
    <p>Es donde organizamos el proyecto. Aquí está la organización, la cual contiene 4 repositorios: Informe, Landing Page, Frontend y Backend</p>
* Requirements Management
  - Pivotal Tracker: (https://www.pivotaltracker.com/)
    <p>Es un software que usamos para gestionar los proyectos y establecer las historias de usuario del proyecto</p>
* Product UX/UI Design
  - UXPressia: (https://uxpressia.com/)
    <p>Acá diseñamos las User Persona, User Journey Mapping y Empathy Mapping</p>
  - Figma: (https://www.figma.com/es-es/)
    <p>Acá hicimos los diseños de la landing page y de la aplicación web (wireframes, mockups y prototipos)</p>
* Software Development
  - Git: Es un software de control de versiones para desarrollar el proyecto
  - Github: Es un sistema de control de versiones de Git
  - HTML5: Es un lenguaje de marcado que sirve para estructurar la página
  - CSS3: Es un lenguaje de hojas de estilo en cascada que le da estilo a la página (hace que una página sea visualmente más atractiva)
  - JavaScript: Es un lenguje de programación que genera interactividad y dinamismo a una página web
  - VSCode: Es el editor de código fuente para el desarrollo de la landing page
  - Vue.JS: Es un framework de JavaScript para el desarrollo frontend de la aplicación web
* Software Deployment
  - Github Pages: Plataforma para desplegar la landing page
### 5.1.2. Source Code Management
<p>Utilizamos Github como plataforma, así como un sistema de control de versiones.</p>
<p>Para ello se creó una organización para el proyecto del equipo. En esta organización, se crearon 4 repositorios, los cuales corresponden al informe del proyecto, la landing page, el frontend y el backend.</p>

* Organización del proyecto: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56
* Informe: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56/Informe
* Landing page: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56/Landing-Page
* Frontend: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56/Frontend
* Backend: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56/Backend

<p>Usamos Gitflow para tener un mejor manejo del código usado en el proyecto. En Gitflow se establecieron dos ramas principales, las cuales son "main" y "Develop".</p>
<p>La rama "main" contiene la versión final del informe y de la landing page.</p>
<p>La rama "Develop" se usa para realizar los cambios hechos en el código sin afectar al "main". También se usa para integrar nuevas funcionalidades del proyecto.</p>
<p>Además, usamos la rama temporal "Feature" para llevar a cabo las nuevas funciones del proyecto sin que este afecte a las ramas principales. En nuestro caso, dividimos las "Feature" por capítulos para el informe. De esa manera tendremos un mejor orden y estructura del proyecto. Los "Feature" los nombramos de la siguiente manera: "Feature/Chapter#" donde el signo "#" representa el número del capítulo que se trabajó.</p>

<h3>Semantic Versioning 2.0.0</h3>
<p>Según el Semantic Versioning 2.0.0 (https://semver.org/), los "Releases" se nombran de la siguiente manera:</p>

* <b>MAJOR version</b>: Al realizar los cambios de APIs incompatibles
* <b>MINOR version</b>: Al agregar funcionalidades compatibles con versiones anteriores
* <b>PATCH version</b>: Al realizar correcciones de errores compatibles con versiones anteriores

<h3>Conventional Commits</h3>
<p>Para los textos de mensajes en commits se aplican los "Conventional Commits" (https://www.conventionalcommits.org/) de la siguiente manera (omitir las comillas simples):</p>

* <'type'>[optional scope]: <'description'>

Donde:
* <'type'>: Representa la palabra inicial que indica la clase de commit a emplear. Ejemplos: fix, feat, build, chore, docs, refactor, etc.
* [optional scope]: Representa el alcance del commit y no es obligatorio.
* <'description'>: Representa la descripción detallada del commit, así como las acciones realizadas

### 5.1.3. Source Code Style Guide & Conventions
En este apartado se indicarán las referencias que adoptaremos para nombrar elementos y algunas convenciones que emplearemos durante el proyecto:
<h3>HTML</h3>

* Usar letras en minúscula para nombrar elementos y atributos
* Siempre colocar entre comillas los valores de los atributos, especialmente si ese valor contiene espacios
* Especificar los atributos <i>alt</i> (nombre alternativo), <i>width</i> (anchura) y <i>height</i> (altura) para las imágenes
* No usar espacios en blanco alrededor del signo "="
* Usar cuatro espacios de sangría
* Nunca omitir el elemento <'title'><'title'>
* Eliminar los espacios en blanco finales
* Usar la sintaxis de HTML5
* Evitar el uso innecesario de atributos "id". En su lugar, usar atributos "class" para estilos y el atributo "data" para scripts
* Usar una nueva línea para cada elemento de bloque, lista o tabla y aplicar sangría a cada elemento secundario

Referencias:
- https://www.w3schools.com/html/html5_syntax.asp
- https://google.github.io/styleguide/htmlcssguide.html

<h3>CSS</h3>

* Usar nombres de clase genéricos o significativos, que representen el propósito del elemento
* Si el nombre de una clase tiene más de una palabra, siempre separarlas con un guión (-)
* Incluir siempre la inicial <b>0</b> en los valores. Ejemplo: font-size: 0.7em
* Usar notación hexadecimal de 3 caracteres en lo posible
* Evitar el uso de la declaración <b>!important</b>. En su lugar, usar la especificidad del selector
* Usar punto y coma (<b>;</b>) al final de cada declaración
* Usar un espacio después de los dos puntos (<b>:</b>) del nombre de una propiedad
* Usar comillas simples (<b>''</b>) en lugar de comillas dobles (<b>""</b>) para selectores de atributos y valores de propiedades

Referencia: https://google.github.io/styleguide/htmlcssguide.html

<h3>JavaScript</h3>

* Usar camelCase para nombrar funciones, métodos, variables, propiedades del objeto y para definir una instancia de objeto mediante un constructor
* Usar PascalCase para nombrar clases
* Usar UPPERCASE para nombrar constantes como <b>PI</b>
* Usar <b>extends</b> para hacer herencia
* Usar operadores de igualdad estricta "<b>===</b>" y desigualdad estricta "<b>!==</b>" en lugar de "<b>==</b>" y "<b>!=</b>"
* Usar espacios en blanco alrededor de los operadores (=, +, -, *, /) y después de las comas (,)
* Terminar la declaración con un punto y coma (;)

Referencias: 
- https://developer.mozilla.org/en-US/docs/MDN/Writing_guidelines/Writing_style_guide/Code_style_guide/JavaScript
- https://www.w3schools.com/js/js_conventions.asp

<h3>Vue.JS</h3>

* Usar nombres multi-palabra para nombrar componentes, excepto por "root App components" y "built-in components by Vue" como <"component">
* Usar el componente "<b>data</b>" como una función al usar la propiedad <b>data</b>
* Especificar las definiciones de <b>Props</b> lo más que se pueda, al menos especificar su tipo de dato
* Crear cada componente en su propio archivo
* Usar la nomenclatura kebak-case para nombrar los archivos de los componentes de Vue
* Incluir el nombre del componente padre como prefijo a aquellos componentes hijo que están fuertemente acoplados a su padre
* Nombrar los componentes con nombres completos en lugar de abreviaciones
* Usar camelCase al declarar nombres de propiedades
* Usar kebak-case al nombrar propiedades en plantillas y JSX
* Ocupar múltiples líneas para elementos con múltiples atributos, con un atributo por línea

Referencia: https://vuejs.org/v2/style-guide/

<h3>C#</h3>

* Usar las palabras clave del idioma para los tipos de datos en lugar de los tipos de tiempo en ejecución. Ejemplo: usar <b>string</b> en lugar de <b>System.String</b>
* Usar <b>int</b> en lugar de <b>unsigned types</b> para los tipos sin signo
* Usar la interpolación de string con el signo <b>$</b> para concatenar string cortos
* Usar <b>Func<></b> y <b>Action<></b> en lugar de definir tipos de delegados
* Usar la <b>I</b> mayúscula al inicio para nombrar nombres de interfaz
* Usar nombres descriptivos y con significado para nombrar clases, métodos y variables
* Usar PascalCase para nombrar clases, constantes, interfaces, delegados y métodos
* Usar camelCase para los parámetros de los métodos, así como para las variables locales

Referencias: 
- https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions
- https://learn.microsoft.com/es-es/dotnet/csharp/fundamentals/coding-style/identifier-names/

<h3>Gherkin</h3>

* Describir los escenarios usando los términos "<b>Given</b>", "<b>When</b>" y "<b>Then</b>" en líneas nuevas
* En el caso de que el escenario se haga más grande, usar sangría con el término "<b>And</b>" en un nuevo bloque o línea
* Usar verbos en tiempo presente al describir los pasos del escenario

Referencia: https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/

### 5.1.4. Software Deployment Configuration
<p>Para desplegar el landing page, se usará Github Pages, herramienta que nos permitirá desplegar la página a partir de un repositorio.</p> 
<p>Para ello creamos el repositorio de la landing page, luego configuramos aquel repositorio en el que se desplegará la landing page, subimos los archivos con su respectivo commit y copiamos el nombre del repositorio que se encuentra en la página de configuración. Ya estaría listo para visualizarse en el navegador.</p>

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

<table align="center"  border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 1</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            2024/08/28
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            03:00 PM
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad virtual por Discord
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Integrantes de X-Force
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            - Condori Lozano, Alessandro Ramiro <br/>
            - La Madrid Lozano, Ivan Jeanpierre <br/>
            - Paucar Meneses, Jeremy <br/>
            - Cossio Jimenez, Jimena Alessandra <br/>    
            - Pariona Lucas, Jose Manuel <br/>
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint n - 1</b>
            <b>Review Summary</b>
        </td>
        <td>
            Se definieron las historias de usuario para la landing page y para la aplicación web Law Connect.
            </br></br>
            La Landing Page se implementó exitosamente.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
        Hubo una buena comunicación entre los integrantes y cada uno de ellos aportó con ideas para el proyecto.
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 1 Goal</b>
        </td>
        <td>
            Desarrollar la landing page del proyecto
        </td>
      <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            5
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            6
        </td>
    </tr>
</table>

#### 5.2.1.2. Sprint Backlog 1
#### 5.2.1.3. Development Evidence for Sprint Review

<table>
  <tr>
   <td><strong>Repository</strong>
   </td>
   <td><strong>Branch</strong>
   </td>
   <td><strong>Commit Id</strong>
   </td>
   <td><strong>Commit Message</strong>
   </td>
   <td><strong>Commit Message Body</strong>
   </td>
   <td><strong>Commited on (Date)</strong>
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>8bda2cc
   </td>
   <td>feature:
   </td>
   <td>feat(repo): add README
   </td>
   <td>05/09/2024
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>e07f6e5
   </td>
   <td>feature:
   </td>
   <td>feat: add about us and img
   </td>
   <td>05/09/2024
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>f552720
   </td>
   <td>feature:
   </td>
   <td>feat: add scrollrevel.min.js
   </td>
   <td>05/09/2024
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>6024458
   </td>
   <td>feature:
   </td>
   <td>feat: add main.js
   </td>
   <td>05/09/2024
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>2337505
   </td>
   <td>feature:
   </td>
   <td>feat: add images
   </td>
   <td>05/09/2024
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>f1a0a7c
   </td>
   <td>feature:
   </td>
   <td>feat: add style.css
   </td>
   <td>05/09/2024
   </td>
  </tr>
  <tr>
   <td>Landing-Page
   </td>
   <td>main
   </td>
   <td>8bda2cc
   </td>
   <td>feature:
   </td>
   <td>feat: add index.html
   </td>
   <td>05/09/2024
   </td>
  </tr>
</table>

#### 5.2.1.4. Testing Suite Evidence for Sprint Review
En este sprint todavía no se desarrolla el Testing, solo la landing page
#### 5.2.1.5. Execution Evidence for Sprint Review
Por este primer sprint, se muestra las capturas de la landing page



## Home

<td><img src="/assets/home.png" alt="Imagen del home" width="1500"></td>

## About Us

<td><img src="/assets/aboutUs.png" alt="Imagen del about us 1" width="1500"></td>
<td><img src="/assets/aboutUs2.png" alt="Imagen del about us 2" width="1500"></td>

## Benefits 

<td><img src="/assets/benefits.png" alt="Imagen del benefits" width="1500"></td>

## Testimonies

<td><img src="/assets/testimonies.png" alt="Imagen de testimonies" width="1500"></td>

## Contact Us

<td><img src="/assets/ContactUs.png" alt="Imagen del contact us" width="1500"></td>

## Footer

<td><img src="/assets/footer.png" alt="Imagen del footer" width="1500"></td>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

**Link de la landing page desployada:** https://x-force-aplicaciones-web-grupo06-wx56.github.io/Landing-Page/

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para el desarrollo de la landing page, se usó lo siguiente:

* HTML: Para la estructura de la página web
* CSS: Para darle estilos a la página web
* JS: Para darle dinamismo a la página web
* Git: Es el sistema de control de versiones
* Github: Software online para almacenar repositorios Git

#### 5.2.1.8. Team Collaboration Insights during Sprint

Aquí se encuentra la captura de las contribuciones de la landing page

<td><img src="/assets/contributors.png" alt="Imagen de contribuciones"></td>

5.2.2.4. Testing Suite Evidence for Sprint Review 
Los archivos .feature desempeñan un papel fundamental a la hora de las practicas de desarrollo de software orientadas al comportamiento, como el Desarrollo Guiado por Comportamiento (BDD). Donde tienen la funcion de transmitir y automatizar las especificaciones encontradas en las historias de usuario ( User Stories). Para el Sprint 2 se se abordaron 2 historias de usuario para el Landing Page.
![image](https://github.com/user-attachments/assets/8185a126-3294-4572-922e-1fca3dda9356)
README.MD 23/09/2024
![image](https://github.com/user-attachments/assets/f6d14e6c-3506-4c19-b755-76442b99cd12)
5.2.2.8. Team Collaboration Insights during Sprint
Repositorio del Fronted: 

Repositorio del Landing Page: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56/Landing-Page/graphs/contributors
![image](https://github.com/user-attachments/assets/75cf7f3a-b2a1-4a73-9a05-d6d576b82748)

Repositorio del Informe: https://github.com/X-Force-Aplicaciones-web-Grupo06-WX56/Informe/graphs/contributors
![image](https://github.com/user-attachments/assets/f73ca9d4-8d57-4f3f-a7a1-419af9a7a7f7)
