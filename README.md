# AppSecLab Landing Page

Profesjonalny landing page dla AppSecLab - firmy świadczącej usługi bezpieczeństwa aplikacji.

## Zawartość

Landing page zawiera następujące sekcje:

1. **Hero Section** - Przyciągająca uwagę sekcja główna z przyciskami CTA
2. **Usługi** - Szczegółowy opis 6 kluczowych usług:
   - Audyt Bezpieczeństwa
   - Testy Penetracyjne
   - Szkolenia
   - Secure Code Review
   - DevSecOps
   - Compliance & Certyfikacje
3. **O nas** - Informacje o firmie, statystyki i certyfikaty
4. **Korzyści** - Dlaczego warto zainwestować w AppSec
5. **Proces** - 5-etapowy proces współpracy
6. **Kontakt** - Formularz kontaktowy i dane kontaktowe
7. **Footer** - Stopka z linkami i informacjami

## Funkcjonalności

- 📱 Fully responsive design (mobile, tablet, desktop)
- 🎨 Nowoczesny design z gradientami i animacjami
- ⚡ Płynne przewijanie do sekcji
- 📝 Funkcjonalny formularz kontaktowy
- 🎭 Animacje fade-in przy przewijaniu
- 🔍 SEO-friendly struktura HTML

## Technologie

- HTML5
- CSS3 (z CSS Grid i Flexbox)
- Vanilla JavaScript
- Brak zależności zewnętrznych

## Jak uruchomić

Wystarczy otworzyć plik `index.html` w przeglądarce lub skonfigurować dowolny serwer HTTP:

```bash
# Prosty serwer Python
python -m http.server 8000

# Lub użyj Live Server w VS Code
```

Następnie otwórz: `http://localhost:8000`

## Struktura plików

```
.
├── index.html      # Główny plik HTML
├── style.css       # Wszystkie style CSS
├── script.js       # JavaScript dla interakcji
└── README.md       # Ta dokumentacja
```

## Personalizacja

### Kolory
Zmień zmienne CSS w pliku `style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #0f172a;
    --accent-color: #f59e0b;
}
```

### Kontakt
Zaktualizuj dane kontaktowe w sekcji `#contact` w pliku `index.html`:

- Email: `kontakt@appseclab.pl`
- Telefon: `+48 123 456 789`

### Formularz kontaktowy
Obecnie formularz jest demo. Aby podpiąć do backendu, zmodyfikuj funkcję w `script.js`:

```javascript
contactForm.addEventListener('submit', function(e) {
    e.preventDefault();
    // Dodaj tutaj integrację z backendem
});
```

## Optymalizacja

- Wszystkie style są w jednym pliku CSS (można rozdzielić dla większych projektów)
- Użyto natywnego JavaScript bez jQuery
- Obrazy zastąpione emoji dla szybszego ładowania (można dodać prawdziwe ikony)
- Minimalny rozmiar plików dla szybkiego ładowania

## Browser Support

- Chrome (ostatnie 2 wersje)
- Firefox (ostatnie 2 wersje)
- Safari (ostatnie 2 wersje)
- Edge (ostatnie 2 wersje)

## Przyszłe ulepszenia

- [ ] Integracja z backendem dla formularza
- [ ] Dodanie prawdziwych ikon SVG
- [ ] Blog/aktualności
- [ ] Dodanie case studies
- [ ] Integracja z Google Analytics
- [ ] Dodanie chatbota

## Licencja

© 2025 AppSecLab. Wszelkie prawa zastrzeżone.
