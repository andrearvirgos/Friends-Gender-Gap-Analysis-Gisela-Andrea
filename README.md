# THE O·N·E WITH THE GENDER GAP 
> **¿Es el audiovisual un reflejo fiel de nuestras conquistas sociales?** > Un estudio detallado sobre la evolución de la paridad en la serie más icónica de los 90.

---

## Resumen del Proyecto
Este proyecto nace de un **rol-play estratégico** donde actuamos como analistas de evolución social. A través del procesamiento de datos de los guiones de *Friends* (1994-2004), auditamos la brecha de género tanto en la narrativa (frente a la cámara) como en la toma de decisiones creativas (detrás de la cámara).

Utilizamos el **Test de Bechdel** como marco filosófico para evaluar si la serie simplemente "cumple" o si realmente ofrece una representación equitativa.

## Dashboards: "The One with the Insights"

### 1. The One with the Gender Gap
* **Foco:** Análisis de paridad global de los 6 protagonistas.
* **Key Insight:** Descubrimos una paridad casi matemática del **49% (Mujeres) vs 51% (Hombres)** en volumen de voz, mantenida con una estabilidad asombrosa a lo largo de 10 años.

### 2. The One where they Talk
* **Foco:** Densidad de diálogos y segmentación temática.
* **Metodología:** Aplicamos una **capa de lógica de negocio en DAX** para categorizar diálogos en 5 ejes: *Amor y Relaciones, Trabajo y Dinero, Comida y Cocina, Familia y Ocio y Vida Social*.
* **Key Insight:** Aunque ellos hablan un 2% más, **ellas lideran la narrativa temática**, demostrando que el peso de la historia recae sobre los personajes femeninos.

### 3. The One with the Creators
* **Foco:** Auditoría del Staff técnico (Guion y Dirección).
* **Key Insight:** La paridad de la pantalla se rompe en el set. Los datos revelan la brecha real de la industria de los 90, con una presencia masculina dominante en los puestos de liderazgo creativo.

### 4. The One with the Deep Dive
* **Foco:** Zoom a la Temporada 8 (La más vista de la historia).
* **Key Insight:** Correlacionamos la valoración de la audiencia con la diversidad de los equipos de guion, demostrando que **la diversidad no es solo justicia, es calidad de producto**.

---

## Metodología Técnica

### Limpieza y Preparación (Data Wrangling)
* **Líneas Brutas:** 60.360 (Incluye ruido de guion y secundarios).
* **Corpus Neto:** 55.070 líneas (Filtrado exclusivo para los 6 protagonistas para evitar sesgos).
* **Normalización:** Limpieza de acotaciones de escena y normalización de términos en inglés.

### Inteligencia de Datos (DAX & Business Logic)
Se desarrollaron medidas y columnas calculadas para:
* Categorización por palabras clave (Keywords).
* Cálculo de ratios de participación dinámica.
* Formateo condicional dinámico (Amarillo para ellas / Morado para ellos).

---

## Conclusiones y Próximos Pasos
Este proyecto es el primero de una serie de estudios sobre el audiovisual. 
* **Hallazgo principal:** *Friends* fue excepcional en su paridad de protagonistas, pero un reflejo de su época en su equipo técnico.
* **Next Steps:** * Auditoría de personajes secundarios (Janice, Gunther, etc.).
    * Comparativa con series de los 2000 y 2010 (*Los Soprano*, *Breaking Bad*) para medir el progreso social.
    * Análisis de departamentos técnicos (Sonido, Vestuario, Maquillaje).

---

## Autoras
* **Gisela Barroso** - *Analista de Datos*
* **Andrea R.Virgós** - *Analista de Datos*
