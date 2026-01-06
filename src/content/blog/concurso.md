---
title: "Primer concurso de creación de contenidos digitales PIXEL 2025"
description: "Reconocimiento al seguindo lugar de la categoria B en el primer concurso de creación de contenidos digitales para explicar, divulgar o enseñar matemáticas o computación PIXEL 2025"
pubDate: 2025-12-24
heroImage: "/pixel2025.jpg"
readingTime: "5 min"
tags: ["Divulgación Científica", "PIXEL 2025"]
---

# PIXEL 2025

Como parte de la celebración del creciente alcance que tienen los contenidos digitales en redes sociales, el Gobierno de Guanajuato, a través del Instituto de Inovación, Ciencia y Emprendimiento para la Competitividad y en colaboración con el Centro de Investigación en Matemáticas (CIMAT), presentaron el primer concurso de creación de contenidos digitales para explicar, divulgar o enseñar matemáticas o computación "PIXEL 2025". El cual tuvo dos categorias; A y B. La primera de ellas, enfocada a los estudiantes de secundaria y nivel medio superior. La segunda categoría, destinada para estudiantes de universidad, posgrados y egresados.

## Resultados

Como resultado de mi presentación, realizé un video sobre los fractales, un tema interesante y visualmente cautivador, con el cual obtuve el segunto lugar en la categoria B.

---
// 1. Define la URL de tu video de TikTok
const tiktokVideoUrl = "https://www.tiktok.com/@jerryaneck/video/7542620297795505415?is_from_webapp=1&sender_device=pc&web_id=7585262100432406028"; 

// 2. Obtenemos los datos de TikTok (miniatura, título, etc.)
let thumbnail = "/pixel2025.jpg"; // Imagen de respaldo (fallback)
let videoTitle = "Video de Fractales";

try {
  const response = await fetch(`https://www.tiktok.com/oembed?url=${tiktokVideoUrl}`);
  const data = await response.json();
  thumbnail = data.thumbnail_url;
  videoTitle = data.title;
} catch (e) {
  console.error("No se pudo obtener la miniatura de TikTok", e);
}
---

<div class="my-10 group">
  <a 
    href={tiktokVideoUrl} 
    target="_blank" 
    rel="noopener noreferrer"
    class="relative block overflow-hidden rounded-2xl border border-zinc-200 dark:border-zinc-800 bg-white dark:bg-zinc-900 shadow-md transition-all duration-300 ease-out hover:-translate-y-2 hover:shadow-2xl hover:border-zinc-400 dark:hover:border-zinc-600"
  >
    <div class="flex flex-col sm:flex-row">
      <div class="relative h-56 sm:h-auto sm:w-1/3 overflow-hidden bg-zinc-100 dark:bg-zinc-800">
        <img 
          src={thumbnail} 
          alt={videoTitle} 
          class="h-full w-full object-cover transition-transform duration-500 group-hover:scale-110"
        />
        <div class="absolute inset-0 flex items-center justify-center bg-black/20 group-hover:bg-black/10 transition-colors">
          <div class="rounded-full bg-white/90 p-3 shadow-lg group-hover:scale-110 transition-transform">
            <svg class="w-6 h-6 text-black" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12.53.02C13.84 0 15.14.01 16.44 0c.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.59-1.01V15.5c0 1.28-.18 2.58-.72 3.71-.54 1.14-1.39 2.12-2.49 2.73-1.09.61-2.41.87-3.66.82-1.25-.05-2.5-.42-3.53-1.12-1.03-.71-1.83-1.74-2.28-2.91-.46-1.16-.54-2.47-.28-3.68.26-1.21.89-2.33 1.83-3.14.94-.8 2.14-1.32 3.39-1.48v4.01c-.56.06-1.13.25-1.59.59-.46.34-.8.83-.97 1.37-.17.54-.16 1.13.01 1.66.17.54.51 1.01.97 1.33.46.32 1.02.48 1.59.46.57-.02 1.13-.21 1.57-.56.44-.35.75-.84.88-1.38.13-.54.11-1.12-.04-1.65V0h4.23z"/>
            </svg>
          </div>
        </div>
      </div>

 <div class="p-8 sm:w-2/3 flex flex-col justify-center">
        <div class="flex items-center space-x-2 mb-3">
          <span class="px-2 py-1 text-[10px] font-bold uppercase tracking-wider text-white bg-blue-600 rounded-md">2do Lugar</span>
          <span class="text-xs font-medium text-zinc-500">Categoría B • PIXEL 2025</span>
        </div>
        <h3 class="text-2xl font-bold text-zinc-900 dark:text-zinc-100 mb-2">
          Fractales: Explicación Premiada
        </h3>
        <p class="text-sm text-zinc-600 dark:text-zinc-400 leading-relaxed">
          Contenido diseñado para el concurso de divulgación del <strong>CIMAT</strong> y el Gobierno de Guanajuato . Este video explora la belleza matemática de los fractales mediante una narrativa visual clara y accesible.
        </p>
        <div class="mt-6 flex items-center text-sm font-bold text-zinc-900 dark:text-zinc-100 group-hover:text-blue-600 transition-colors">
          <span>Ver video en TikTok</span>
          <svg class="ml-2 w-4 h-4 transition-transform group-hover:translate-x-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path>
          </svg>
        </div>
      </div>
    </div>
  </a>
</div>