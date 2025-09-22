# Mow The Lawn - Fűnyírás visszajelző alkalmazás

Egy egyszerű webes alkalmazás, amely lehetővé teszi a fűnyírási feladatok befejezésének jelentését és értesítések küldését.

## 🌐 Élő alkalmazás

Az alkalmazás elérhető a következő címen az alábbi kulcs segítségével
**https://gaborschnierer.github.io/mowthelawn/?key=3SRQotIXKECVGbwIXKzS1QnuHku13zpdrsX0u6KhXCVSxVip3MlGn0MiVWXe17Y6**

## Funkcionalitás

- **Dátum kiválasztás**: Válaszd ki a fűnyírás tényleges dátumát
- **Feladat befejezés jelentése**: Jelöld be, hogy elvégezted a fűnyírást
- **Automatikus értesítés**: A rendszer értesítést küld a befejezésről
- **Magyar nyelvű felület**: Teljes mértékben magyar nyelven

## Technikai részletek

- **Frontend**: Vanilla HTML, CSS, JavaScript
- **Backend**: Google Apps Script
- **Hosting**: GitHub Pages
- **Adattárolás**: Google Sheets
- **Értesítések**: Gmail API
- **Böngésző kompatibilitás**: Modern böngészők

## Backend rendszer

A backend Google Apps Script alapú, amely:

- **Google Sheets integráció**: A fűnyírási feladatok egy Google Sheets táblázatban vannak tárolva
- **Automatikus ütemezés**: Amikor egy feladat készre van jelölve, a következő fűnyírás dátuma automatikusan kiszámításra kerül szezonális időközök alapján
- **Email értesítések**: Automatikus emlékeztetők és értesítések küldése Gmail-en keresztül
- **API kulcs védelem**: Biztonságos hozzáférés API kulcs alapú autentikációval
- **Több felhasználó**: Lakás-alapú felelősségi rendszer különböző email címekkel
- **Időzített emlékeztetők**: Automatikus emlékeztetők küldése 0 és 3 nappal a határidő előtt

---

*🌱 Tartsd rendben a gyeped!*