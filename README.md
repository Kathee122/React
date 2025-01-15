# React Project Documentation

## Cómo correr el proyecto

Para ejecutar este proyecto, sigue los siguientes pasos:

1. **Clonar el repositorio**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
   ```

2. **Instalar Node.js y npm**
   Si no tienes Node.js y npm instalados, sigue estos pasos:
   - Descarga e instala Node.js desde su sitio oficial: [https://nodejs.org/](https://nodejs.org/).
   - Verifica que están correctamente instalados ejecutando los siguientes comandos:
     ```bash
     node -v
     npm -v
     ```
     Esto debería mostrar las versiones instaladas de Node.js y npm.

3. **Instalar dependencias**
   Una vez tengas Node.js y npm instalados, ejecuta:
   ```bash
   npm install
   ```

4. **Iniciar el servidor de desarrollo**
   Una vez instaladas las dependencias, inicia el servidor de desarrollo con:
   ```bash
   npm run dev
   ```
   El proyecto estará disponible en [http://localhost:5173](http://localhost:5173).

---

## Funcionalidades implementadas

1. **Visualización de usuarios**:
   - El sistema muestra una lista de usuarios obtenidos desde una API externa.

2. **Visualización de publicaciones por usuario**:
   - Al hacer clic en un usuario, se navega a una página donde se muestran sus publicaciones.

3. **Diseño responsivo basado en Bootstrap**:
   - Se utiliza Bootstrap para garantizar un diseño atractivo y funcional en diferentes tamaños de pantalla.

4. **Estilos personalizados con CSS**:
   - Se agregaron detalles específicos con CSS para personalizar la apariencia del proyecto.

---

## Decisiones técnicas

1. **Framework utilizado: React + Vite**
   - Se seleccionó Vite para aprovechar su velocidad en el entorno de desarrollo y sus capacidades modernas de construcción.

2. **Consumo de API con Axios**
   - Se utilizó Axios para realizar peticiones HTTP debido a su simplicidad y manejo de promesas.

3. **Bootstrap para el diseño**
   - Se eligió Bootstrap como framework de CSS para acelerar el desarrollo de una interfaz responsiva y atractiva.

4. **Uso de CSS personalizado**
   - Se aplicaron estilos adicionales con CSS para ajustes específicos que no se podían lograr fácilmente con Bootstrap.

5. **Organización de componentes**
   - El proyecto está estructurado con componentes reutilizables para facilitar la mantenibilidad y escalabilidad.

6. **Rutas dinámicas**
   - Se configuraron rutas dinámicas para mostrar las publicaciones de cada usuario en páginas separadas.
