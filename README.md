# BAT-Man-Meta: Integrations-Repository

Dieses Repository dient als Hauptrepository für das BAT-Man Projekt und integriert die Repositories aller 4 Gruppen als Submodules.

## Gruppen-Repositories

### Gruppe 1: AT (authentication)
- **Repository:** `BAT-Man-AT`
- **URL:** https://github.com/CookieakaKrizzpy/BAT-Man-AT.git
- **Status:** ✅ Hinzugefügt

### Gruppe 2: [Dashboard]
- **Repository:** `[Zu ergänzen]`
- **URL:** `[Zu ergänzen]`
- **Status:** ⏳ Ausstehend

### Gruppe 3: [SQL]
- **Repository:** `[Zu ergänzen]`
- **URL:** `[Zu ergänzen]`
- **Status:** ⏳ Ausstehend

### Gruppe 4: [GUI]
- **Repository:** `[Zu ergänzen]`
- **URL:** `[Zu ergänzen]`
- **Status:** ⏳ Ausstehend

## Verwendung

### Klonen mit allen Submodules
```bash
git clone --recursive https://github.com/CookieakaKrizzpy/BAT-Man-Meta.git
```

### Submodules nach dem Klonen initialisieren
```bash
git submodule init
git submodule update
```

### Neue Gruppe hinzufügen
```bash
git submodule add [URL] [Verzeichnisname]
```

### Alle Submodules aktualisieren
```bash
git submodule update --remote
```

## Struktur
```
BAT-Man-Meta/
├── README.md
├── .gitmodules
├── BAT-Man-AT/          # Gruppe 1
├── [Gruppe2-Name]/      # Gruppe 2
├── [Gruppe3-Name]/      # Gruppe 3
└── [Gruppe4-Name]/      # Gruppe 4
```
