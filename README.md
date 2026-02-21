# Andrei Ionescu — Portofoliu Web Developer

Portofoliu personal elegant și modern pentru Andrei Ionescu, dezvoltator web și consultant tehnic.

## 🌐 Prezentare Generală

Acest proiect reprezintă un site de prezentare (portofoliu) complet, dezvoltat cu HTML, CSS și JavaScript pur, fără framework-uri externe. Design-ul este rafinat, cu tipografie elegantă și animații subtile care oferă o experiență profesională și memorabilă vizitatorilor.

## ✨ Caracteristici

### Design & UX
- **Tipografie premium**: Combinație de Playfair Display (serif), DM Mono (monospace) și DM Sans (sans-serif)
- **Paletă de culori**: Tonuri de crem, paper, ink și accente de portocaliu/roșu
- **Navigație sticky**: Bară de navigație fixă cu efect de blur (glassmorphism)
- **Design responsiv**: Adaptat pentru toate dispozitivele

### Animații
- **Marquee/Ticker**: Bannere animate în partea superioară a paginii
- **Slide-up animations**: Elementele apar animat la încărcarea paginii
- **Scroll reveal**: Animații declanșate la scroll folosind IntersectionObserver
- **Hover effects**: Efecte interactive pe butoane, link-uri și elemente media

### Structura Paginii
1. **Hero Section**: Introducere cu nume, titlu și call-to-action
2. **Despre Mine**: Prezentare personală și experiență
3. **Servicii/Proiecte**: Showcase-ul proiectelor realizate
4. **Contact**: Formular de contact și informații de contact

## 🛠️ Tehnologii Utilizate

- **HTML5** — Structura semantică a paginii
- **CSS3** — Stilizare avansată, variabile CSS, animații
- **JavaScript (ES6+)** — Interactivitate și animații scroll
- **Google Fonts** — Tipografie externă

## 🚀 Cum să rulezi proiectul

1. Clonează sau descarcă acest repository
2. Deschide `index.html` în orice browser modern
3. Sau utilizează un server local (recomandat pentru performanță optimă):

```bash
# Cu Python
python -m http.server 8000

# Sau cu Node.js (dacă ai http-server instalat)
npx http-server
```

Apoi accesează `http://localhost:8000` în browser.

## 📁 Structura Fișierelor

```
.
├── index.html    # Pagina principală (conține și CSS/JS inline)
├── network.png   # Iconiță favicon
└── README.md     # Acest fișier
```

## 🎨 Personalizare

### Culori
Culorile pot fi modificate în secțiunea `:root` din CSS:

```css
:root {
  --cream:  #f5f2ec;
  --paper:  #faf8f4;
  --ink:    #1a1814;
  --accent: #c8460d;
}
```

### Fonturi
Fonturile sunt încărcate de la Google Fonts și pot fi schimbate în secțiunea `<link>` din `<head>`.

## 📝 Conținut

Textele sunt în limba română și pot fi editate direct în fișierul `index.html` pentru a reflecta informațiile personale dorite.

---

Creat cu ❤️ de Ionita Aurel Mihai
