# glass-icons

# Glass Icons

Piękna, konfigurowalna biblioteka ikon z efektem szklanego morfizmu (glassmorphism), dostępna przez sieć CDN.

## 🚀 Instalacja

Wystarczy wkleić dwa poniższe linki wewnątrz tagu `<head>` i na dole `<body>` na swojej stronie internetowej. 
*(Pamiętaj, aby podmienić `TWOJA_NAZWA_UZYTKOWNIKA` na swój login z GitHuba).*

```html
<!-- W sekcji <head> dodaj style -->
<link rel="stylesheet" href="[https://cdn.jsdelivr.net/gh/TWOJA_NAZWA_UZYTKOWNIKA/glass-icons@main/glass-icons.css](https://cdn.jsdelivr.net/gh/TWOJA_NAZWA_UZYTKOWNIKA/glass-icons@main/glass-icons.css)">

<!-- Na dole dokumentu dodaj skrypt JS -->
<script src="[https://cdn.jsdelivr.net/gh/TWOJA_NAZWA_UZYTKOWNIKA/glass-icons@main/glass-icons.js](https://cdn.jsdelivr.net/gh/TWOJA_NAZWA_UZYTKOWNIKA/glass-icons@main/glass-icons.js)"></script>

```css

:root {
    /* Gradient podstawowy (część nieprzezroczysta) */
    --normal-color-start: #FF512F;
    --normal-color-end: #DD2476;

    /* Gradient szkła (część przezroczysta - z końcówką HEX dla kanału alpha) */
    --glass-color-start: #ffffff99;
    --glass-color-end: #e0e0e099;

    /* Cień rzucany przez całą ikonę */
    --icon-shadow: rgba(0, 0, 0, 0.15);
    --icon-shadow-blur: 10px;
    --icon-shadow-offset-x: 0px;
    --icon-shadow-offset-y: 8px;
}
