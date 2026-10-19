# Landing Page - Sevilla FC

Proyecto de desarrollo de una **Landing Page** responsiva dedicada al **Sevilla Fútbol Club**. La página ofrece un recorrido visual e interactivo por la identidad, la historia, los logros, la plantilla y los patrocinadores de la entidad nervionense, estructurada en una sola página (*Single Page Application*) con navegación fluida y soporte para modo claro y oscuro.

---

## Archivos Principales del Proyecto

* **[index.html](index.html)**: Código fuente principal de la aplicación web. Desarrollado con **HTML5 semántico**, **Bootstrap 5.3**, estilos personalizados en Vanilla CSS y JavaScript para el control interactivo del cambio de tema y el menú hamburguesa. Totalmente adaptado para pantallas de escritorio, tablets y dispositivos móviles.
* **[MOCKUP.jpg](MOCKUP.jpg)**: Imagen de diseño conceptual y esquema de referencia inicial. Ilustra la estructura base que guio la composición de la web: barra de navegación superior corporativa, disposición del contenido (título y texto a un lado, imagen al otro) y la fila inferior con tarjetas de datos destacados.

---

## Estructura y Secciones (Navbar)

La navegación principal se compone de **5 secciones clave** accesibles desde la barra de navegación superior (*Navbar*), la cual incorpora menú hamburguesa colapsable en dispositivos móviles y un selector interactivo de **Modo Oscuro / Modo Claro**:

1. **Historia (`#historia`)**
   * Orígenes del club desde su fundación el 25 de enero de 1890 y la figura de su primer presidente, Edward Farquharson Johnston.
   * Tres tarjetas de datos destacados: más de 80 temporadas en Primera División, el Himno del Centenario (2005) y la designación de Mejor Club del Mundo (2006 y 2007).

2. **Títulos (`#titulos`)**
   * Vitrina de trofeos oficiales nacionales e internacionales con los años de conquista:
     * **7 UEFA Europa League** (2006, 2007, 2014, 2015, 2016, 2020, 2023).
     * **1 Supercopa de Europa** (2006).
     * **1 Liga Española** (1946).
     * **5 Copas del Rey** (1935, 1939, 1948, 2007, 2010).
     * **1 Supercopa de España** (2007).

3. **Estadio (`#estadio`)**
   * Imagen panorámica del **Estadio Ramón Sánchez-Pizjuán** ("La Bombonera de Nervión") y reseña histórica sobre el emblemático mosaico de Preferencia creado para el Mundial de 1982.
   * Tres tarjetas con la información técnica esencial del recinto:
     * **Nombre Oficial**: Ramón Sánchez-Pizjuán.
     * **Inauguración**: 7 de septiembre de 1958.
     * **Aforo**: 43.883 espectadores.

4. **Plantilla (`#plantilla`)**
   * Presentación del primer equipo masculino organizado por posiciones: **Porteros**, **Defensas**, **Mediocentros** y **Delanteros**.
   * Tarjetas fotográficas con el **nombre** y el **número de dorsal** de cada jugador, con tipografía fluida adaptativa que evita solapamientos tanto en vista de escritorio como en móvil.

5. **Patrocinios (`#patrocinio`)**
   * Presidencia del patrocinador técnico principal (**Adidas**) y galería con los 10 patrocinadores y socios comerciales oficiales (*Socios.com, CaixaBank, Cruzcampo, MatchWornShirt, Viagogo, Say TV, Scalpers, Coca-Cola, Robles y Andalucía*).
   * Todos los logotipos cuentan con enlaces directos a sus sitios web y efectos de hover sutiles.
   * **Distribución responsiva**: Los patrocinadores se muestran en una sola fila centrada en escritorio y organizados en una cuadrícula de dos en dos (2 columnas) en dispositivos móviles sin barras de desplazamiento.
   * Lema icónico sevillista: **"NUNCA TE RINDAS"** en tipografía corporativa.
   * Pie de página final con enlaces a las redes sociales oficiales del club (*X/Twitter, Instagram, Facebook, YouTube y TikTok*) y aviso legal de derechos reservados.

---

## Características Técnicas y Diseño

* **Diseño Responsivo**: Rejilla fluida y puntos de ruptura de Bootstrap adaptados a cualquier resolución.
* **Tipografía Corporativa**: Integración de la fuente tipográfica `MontecatiniPro`.
* **Modo Oscuro / Claro**: Conmutador dinámico que conmuta hojas de estilo (`styles.css` y `dark.css`), iconos y mosaicos de fondo.
