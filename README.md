# 🍰 Paula Oktabska – Digital Card

Wizytówka jako czysty HTML – działa na każdym urządzeniu, zero problemów z linkami.

## 🚀 Deploy na GitHub Pages (za darmo, 2 minuty)

### 1. Nowe repozytorium
- Wejdź na github.com → **New repository**
- Nazwa: `paula-card` (lub dowolna)
- Ustaw jako **Public**
- Kliknij **Create repository**

### 2. Wrzuć plik
```bash
git init
git add index.html
git commit -m "launch card"
git branch -M main
git remote add origin https://github.com/TWOJA_NAZWA/paula-card.git
git push -u origin main
```

### 3. Włącz GitHub Pages
- W repozytorium → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / folder: **/ (root)**
- Kliknij **Save**

### 4. Twój URL za ~1 minutę:
```
https://TWOJA_NAZWA.github.io/paula-card/
```

---

## ✏️ Edycja danych

Otwórz `index.html` i zmień:
- imię, tytuł
- numery telefonu / WhatsApp
- adres e-mail
- URL do DEMO

---

## Dlaczego HTML zamiast Streamlit?

Streamlit Cloud blokuje otwieranie linków z iframe (znany bug, nienaprawiony).
Czysty HTML na GitHub Pages = zero ograniczeń, szybsze ładowanie, lepsza SEO.
