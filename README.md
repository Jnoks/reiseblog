# 🌍 Reiseblog – Gruppenarbeit

Responsive Website für einen Reiseblog. Erste Gruppenarbeit der Umschulung (Developer Akademie), Dauer: 1 Woche.

## Team

| Name | Bereich | GitHub |
|---|---|---|
| _Joel Naujoks_ | | @jnoks |
| _Abed Khodor_ | | @abedkhdr |
| _Jean-Pascal Steinmetz_ | | @Jean-Pascal Steinmetz |

## Setup

```bash
git clone git@github.com:Jnoks/reiseblog.git
```

## Projektstruktur

```
reiseblog/
├─ index.html
├─ styles/
│  ├─ variables.css    (Farben, Abstände, etc.)
│  ├─ fonts.css        (@font-face)
│  ├─ reset.css        (CSS-Reset)
│  └─ style.css        (Layout & Komponenten)
└─ assets/
   ├─ img/
   ├─ icons/
   └─ fonts/
```

## Konventionen

- **Branches:** `feature/name-in-kebab-case` (z. B. `feature/highlights-section`), Bugfixes: `bugfix/…`
- **Commits:** atomar, Typ-Prefix + Imperativ, z. B. `feat: add highlights section`, `fix: correct navbar overflow`, `chore: update gitignore`
- **CSS-Klassen:** kebab-case, englisch (`.highlight-card`)
- **Dateinamen:** kebab-case, klein, keine Umlaute
- **Mobile First:** Basis-Styles fürs Smartphone, Erweiterung per `min-width` (481 / 769 / 1280)
- **Einheiten:** Schrift in `rem`, Abstände am Element in `em`, feste Details in `px`; kein `100vw`, min. 16px Schriftgröße

## Workflow

1. Karte im GitHub-Projects-Board von **To Do** auf **In Progress** ziehen (max. 1 Karte pro Person In Progress)
2. Feature-Branch von `main` erstellen: `git switch -c feature/xyz`
3. Klein und atomar committen, täglich `git pull` auf `main` nicht vergessen
4. Fertig → Push → **Pull Request** erstellen (mit `Closes #Issue-Nummer` in der Beschreibung), Karte auf **Review**
5. Eine andere Person reviewt (Code kommentieren, nicht die Person)
6. Freigabe → Merge in `main` → Karte auf **Done**. Änderungswünsche → zurück zu In Progress

## Daily

Kurzer Austausch nach dem Live Call (max. 10 Min.): Was habe ich gestern gemacht? Was mache ich heute? Wo hänge ich? Blockaden sofort ansprechen.
