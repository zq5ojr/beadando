# DevOps Beadandó - Béres László

Ez a projekt egy konténerizált Nest.js webalkalmazás. A feladat célja egy modern DevOps folyamat (CI/CD alapok, Dockerizálás, Registry használat) gyakorlati bemutatása volt.

## 📋 Előfeltételek

A program futtatásához szükséges szoftverek:
* **Docker Desktop** (Futnia kell a háttérben!)
* **Git** (Csak ha a forráskódot is le akarod tölteni)

---

## 🚀 Azonnali futtatás (Felhasználóknak)

Ha nem szeretnél foglalkozni a kód letöltésével és építésével, hanem csak használni akarod az alkalmazást, futtasd az alábbi parancsot. Ez automatikusan letölti a kész csomagot a Docker Hub-ról.

**Nyisd meg a parancssort (CMD vagy PowerShell), és írd be:**

```bash
docker run -p 3000:3000 bereslacko/beadando-app:v1
```

**Ezután nyisd meg a böngésződet ezen a címen: 👉 http://localhost:3000**

**(A leállításhoz a parancssorban nyomj Ctrl + C-t).**