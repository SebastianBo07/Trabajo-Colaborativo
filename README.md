# Trabajo-Colaborativo
# Se realizan paginas web con colaboración y distintos temas;

# Integrantes: Sebastian bolaños, Hayder Valois, Camilo Zuñiga, sebastian Romero;

# Temas seleccionados:
# Sebastian Bolaños: Inteligencia artificial y automatización;
# Hayder Valois: Ciudades Inteligentes;
# Camilo Zuñiga: Computación cuantica 
# Sebastian romero: Blockchain

# Reparto: 
# Sebastian Bolaños: Index.html;
# Camilo zuñiga: Tema2.html
# Hayder Valois: Tema3.html
# Sebastian Romero: Tema4.html

## Validación HTML 

### Página 1 

Errores encontrados: No se encontraron errores 
Correcciones realizadas: 

### Página 2 

Errores encontrados: El nav no tenia el team bien colocado por error de comunicación.

<nav>
    <a href="index.html">Inteligencia artificial y automatización</a>
    <a href="tema2.html">Computación cuantica</a>
    <a href="tema3.html">Ciudades Inteligentes</a>
    <a href="tema4.html">Blockchain</a>
</nav>

Correcciones realizadas: 

<nav>
    <a href="index.html">Inteligencia artificial y automatización</a>
    <a href="tema2.html">Computación cuantica</a>
    <a href="tema3.html">Ciudades Inteligentes</a>
    <a href="tema4.html">Computación en la nube</a>
</nav>

### Página 3 

Errores encontrados: No tenia lista ordenada.

<ul>
    <li>Sensores de tráfico.</li>
    <li>Sensores de calidad del aire.</li>
    <li>Sensores de temperatura.</li>
    <li>Sensores de iluminación.</li>
    <li>Sensores para controlar el consumo de agua.</li>
</ul>

Correcciones realizadas: 

<ol>
    <li>Sensores de tráfico.</li>
    <li>Sensores de calidad del aire.</li>
    <li>Sensores de temperatura.</li>
    <li>Sensores de iluminación.</li>
    <li>Sensores para controlar el consumo de agua.</li>
</ol>

### Página 4 

Errores encontrados: No tenia linea la tabla para diferenciarse.

<table>
    <caption>Modelos de servicio en la nube y ejemplos</caption>
    <thead>
        <tr>
        <th>Modelo</th>
        <th>Descripción</th>
        <th>Ejemplos</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>IaaS (Infraestructura como servicio)</td>
            <td>Ofrece servidores, redes y almacenamiento virtualizados.</td>
            <td>Amazon EC2, Microsoft Azure VM, Google Compute Engine</td>
        </tr>
        <tr>
            <td>PaaS (Plataforma como servicio)</td>
            <td>Ofrece un entorno para desarrollar y desplegar aplicaciones sin gestionar servidores.</td>
            <td>Google App Engine, Heroku, Azure App Service</td>
        </tr>
        <tr>
            <td>SaaS (Software como servicio)</td>
            <td>Entrega aplicaciones ya construidas listas para usar desde el navegador.</td>
            <td>Google Workspace, Microsoft 365, Dropbox</td>
        </tr>
    </tbody>
</table>

Correcciones realizadas:

<table border="1">
    <caption>Modelos de servicio en la nube y ejemplos</caption>
    <thead>
        <tr>
        <th>Modelo</th>
        <th>Descripción</th>
        <th>Ejemplos</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>IaaS (Infraestructura como servicio)</td>
            <td>Ofrece servidores, redes y almacenamiento virtualizados.</td>
            <td>Amazon EC2, Microsoft Azure VM, Google Compute Engine</td>
        </tr>
        <tr>
            <td>PaaS (Plataforma como servicio)</td>
            <td>Ofrece un entorno para desarrollar y desplegar aplicaciones sin gestionar servidores.</td>
            <td>Google App Engine, Heroku, Azure App Service</td>
        </tr>
        <tr>
            <td>SaaS (Software como servicio)</td>
            <td>Entrega aplicaciones ya construidas listas para usar desde el navegador.</td>
            <td>Google Workspace, Microsoft 365, Dropbox</td>
        </tr>
    </tbody>
</table> 

## Paleta de color multitemática
- **Primary:** `#0f172a` (Azul profundo: Computación Cuántica e IA)
- **Secondary:** `#0284c7` (Azul cian: Programación en la Nube)
- **Accent:** `#10b981` (Verde esmeralda: Ciudades Inteligentes y sostenibilidad)
- **Background:** `#f8fafc` (Fondo claro general)
- **Surface:** `#ffffff` (Superficie de contenedores)
- **Text:** `#334155` (Texto principal)

**Justificación:** 
La paleta unifica visualmente los cuatro pilares tecnológicos del equipo (IA, cuántica, nube y ciudades inteligentes) utilizando tonos oscuros de alta tecnología combinados con cian y un acento verde que representa la conectividad y el desarrollo urbano sostenible, garantizando un contraste óptimo bajo la normativa WCAG.

## Prueba de cascada
- **Resultado del selector de elemento:** El título toma el color azul definido por la regla general de la etiqueta `h2`[cite: 2].
- **Resultado de la clase:** El título cambia a color verde al aplicarle la clase `.demo-title`, debido a que las clases tienen mayor especificidad que los selectores de elemento[cite: 2].
- **Resultado del ID:** El título cambia a color morado al incorporar el selector `#demo-title`, ya que los selectores ID poseen un peso y especificidad superior a las clases[cite: 2].
- **Resultado del estilo inline:** El título se muestra de color naranja al añadir un atributo `style` directamente en el elemento HTML, superando a las reglas normales de la hoja externa[cite: 2].
- **Explicación:** El algoritmo de la cascada y la especificidad resuelven los conflictos de estilo priorizando los selectores según su peso (Elemento < Clase < ID < Estilo inline), permitiendo que el navegador determine de forma predecible qué regla se aplica[cite: 2].