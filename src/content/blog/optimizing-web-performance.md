---
title: "Primer concurso de creación de contenidos digitales PIXEL 2025"
description: "Reconocimiento al seguindo lugar de la categoria B en el primer concurso de creación de contenidos digitales para explicar, divulgar o enseñar matemáticas o computación PIXEL 2025"
pubDate: 2025-12-24
heroImage: "/pixel2025.jpg"
tags: ["performance", "web development", "user experience"]
---

# PIXEL 2025

Como parte de la celebración del creciente alcance que tienen los contenidos digitales en redes sociales, el Gobierno de Guanajuato, a través del Instituto de Inovación, Ciencia y Emprendimiento para la Competitividad y en colaboración con el Centro de Investigación en Matemáticas (CIMAT), presentaron el primer concurso de creación de contenidos digitales para explicar, divulgar o enseñar matemáticas o computación "PIXEL 2025". El cual tuvo dos categorias; A y B. La primera de ellas, enfocada a los estudiantes de secundaria y nivel medio superior. La segunda categoría, destinada para estudiantes de universidad, posgrados y egresados.

## Resultados

Como resultado de mi presentación, realizé un video sobre los fractales, un tema interesante y visualmente cautivador, con el cual obtuve el segunto lugar en la categoria B.

- **User Experience**: 53% of mobile users abandon sites that take longer than 3 seconds to load
- **Conversion Rates**: A 1-second delay in page load time can result in a 7% reduction in conversions
- **SEO**: Page speed is a ranking factor for search engines
- **Accessibility**: Fast websites are more accessible, especially for users with limited bandwidth

## Core Web Vitals

Google's Core Web Vitals are a set of specific factors that Google considers important for a webpage's overall user experience:

1. **Largest Contentful Paint (LCP)**: Measures loading performance. To provide a good user experience, LCP should occur within 2.5 seconds of when the page first starts loading.

2. **First Input Delay (FID)**: Measures interactivity. Pages should have a FID of less than 100 milliseconds.

3. **Cumulative Layout Shift (CLS)**: Measures visual stability. Pages should maintain a CLS of less than 0.1.

## Performance Optimization Techniques

### 1. Optimize Images

Images often account for most of the downloaded bytes on a webpage. Optimizing them can significantly improve load times:

- Use modern formats like WebP or AVIF
- Implement responsive images with `srcset` and `sizes` attributes
- Lazy load images below the fold
- Compress images without sacrificing quality

```html
<img 
  src="small.jpg" 
  srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 1500w" 
  sizes="(max-width: 600px) 500px, (max-width: 1200px) 1000px, 1500px" 
  alt="Description" 
  loading="lazy" 
/>
```
