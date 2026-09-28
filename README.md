# Vino entre dos tierras

Dashboard de las catas de vino de Pedro Pablo, David, Emilio y Sergio.

- `index.html`: toda la web (HTML, CSS y JS en un solo archivo). Se publica con GitHub Pages.
- Datos, fotos y la función de IA (`ficha-vino`) viven en Supabase, proyecto **Vinos entredostierras**.
- Para ver la web en local basta con abrir `index.html` en el navegador.
- `supabase/functions/ficha-vino/index.ts`: copia de la función de IA desplegada en Supabase (solo como referencia).
- Acceso con usuario y contraseña (Supabase Auth). Solo los 4 del grupo pueden ver y editar.
