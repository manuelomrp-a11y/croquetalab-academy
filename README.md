# CroquetaLab · Recetario artesanal Bolivia

Recetario web con **200 recetas caseras de premios** (100 para perros y 100 para gatos), con ingredientes comunes en mercados bolivianos. Está pensado para personas poco familiarizadas con la tecnología: letra grande, botones grandes, pocas opciones a la vez y todo guiado paso a paso.

## Cómo está organizado

- **Inicio**: se elige "Para mi perro" o "Para mi gato" con un toque.
- **Recetas**: se filtran tocando lo que hay en casa (carne o proteína y acompañamiento), sin escribir.
- **Ficha de receta**: cuántas dar al día según el tamaño de la mascota, ingredientes en medidas caseras (tazas, cucharadas, huevos) que se pueden marcar, horno o sartén, y el botón **Empezar a cocinar**.
- **Modo cocina**: un paso por pantalla, texto grande, alarma con sonido para cada tiempo y la pantalla se mantiene encendida.
- **Crear**: tres preguntas (mascota, proteína, acompañamiento) y la página arma la receta con cantidades y pasos.
- **Consejos**: alimentos prohibidos, cuántos premios dar, cocina segura, cuándo ir al veterinario, precios del mercado y fuentes.
- **Guardadas**: recetas favoritas y lista de compras que se puede marcar y enviar por WhatsApp.

Incluye a **Tony 🐶 (caniche) y Pelusa 🐱 (gatita carey)**, asistentes animados en un solo chat: responde Tony si la pregunta es sobre perros y Pelusa si es sobre gatos. Usan respuestas predefinidas, no utilizan IA externa ni envían datos a servidores.

La masa se une con una pasta de harina de arroz cocida con agua, así todos los ingredientes llegan cocidos al paso final.

## Advertencias

- Son **premios ocasionales**, no dietas completas ni terapéuticas. Ninguna receta ha sido validada clínicamente por nutricionistas veterinarios.
- El recetario no determina adecuación de taurina, calcio, fósforo, vitaminas o minerales.
- Los datos nutricionales son **estimaciones ilustrativas** basadas en ingredientes cocidos; no son análisis de laboratorio.
- Los costos son precios de ejemplo, **no cotizaciones verificadas** de Bolivia. Cada visitante puede reemplazarlos.
- La lista de compras pasa los pesos cocidos a peso de compra con factores de cocción aproximados (carnes en crudo, verduras peladas, arroz y avena secos).
- La guía de piezas por día usa la energía en reposo (70 × peso^0,75) × 1,6 en perros o × 1,2 en gatos, para adultos esterilizados de peso ideal, y limita los premios al 10 % de esas calorías. Es una referencia general, no una indicación veterinaria.
- Para sobrepeso, enfermedad renal, diabetes, pancreatitis, alergias, embarazo o crecimiento: consultar a un veterinario antes de cambiar la dieta.
- Favoritos, lista de compras, precios y preferencias se guardan solo en el navegador (localStorage). Las mezclas guardadas con el creador anterior pasan a "Guardadas" automáticamente.
- La conservación sugerida es conservadora: refrigerar 24–48 h a ≤4 °C o congelar en porciones; nunca asumir que las croquetitas horneadas son estables a temperatura ambiente.

## Fuentes de información general

- WSAVA: https://wsava.org/global-guidelines/global-nutrition-guidelines/
- ASPCA: https://www.aspca.org/pet-care/aspca-poison-control/people-foods-avoid-feeding-your-pets
- FDA: https://www.fda.gov/animal-veterinary/animal-health-literacy/tips-safe-handling-pet-food-and-treats
- USDA Food Safety: https://www.fsis.usda.gov/food-safety/safe-food-handling-and-preparation/food-safety-basics/safe-temperature-chart
- USDA FoodData Central: https://fdc.nal.usda.gov/
- Tufts Petfoodology: https://sites.tufts.edu/petfoodology/2016/07/14/should-you-make-your-own-pet-food-at-home/

## Publicación

GitHub Pages desde main / (root). Abra index.html para usar el recetario sin backend.