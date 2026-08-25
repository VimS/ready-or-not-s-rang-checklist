# 🎮 Ready or Not - S-Rang Checkliste

Eine interaktive Checkliste zum Tracken deines Fortschritts beim S-Rang aller 29 Missionen in **Ready or Not**.

## ✨ Features

- ✅ **29 Missionen** - Alle Missionen inkl. DLCs
- 📊 **Live-Fortschritt** - Statistiken und Balkenleiste
- 💾 **Auto-Speicher** - Daten werden lokal im Browser gespeichert
- 🎯 **Kategorisiert** - Sortiert nach Kampagne & DLC
- 💡 **Tipps** - Für besonders knifflige Missionen
- 📱 **Responsive** - Funktioniert auf Desktop, Tablet & Mobile
- ⚡ **Offline** - Funktioniert ohne Internetverbindung

## 🚀 Verwendung

### Online (GitHub Pages)
Öffne die Website direkt im Browser - keine Installation nötig!

**URL:** `https://username.github.io/ready-or-not-s-rang-checklist`

### Lokal
```bash
# Repository clonen
git clone https://github.com/username/ready-or-not-s-rang-checklist.git
cd ready-or-not-s-rang-checklist

# Mit Live Server öffnen (VS Code Extension) oder einfach index.html im Browser öffnen
```

## 📋 Missionen

### Hauptkampagne (18)
Thank You, Come Again • 23 Megabytes A Second • Twisted Nerve • The Spider • A Lethal Obsession • Ides of March • Sinuous Trail • Ends of the Earth • Greased Palms • Valley of the Dolls • Elephant • Rust Belt • Sins of the Father • Neon Tomb • Buy Cheap, Buy Twice • Carriers of the Vine • Relapse • Hide and Seek

### Home Invasion DLC (3)
Dorms • Narcos • Lawmaker

### Los Sueños Stories (2)
Stolen Valor • Hunger Strike

### Dark Waters DLC (3)
Mirage at Sea • Leviathan • 3 Letter Triad

### Boiling Point DLC (3)
No Good Deed • All Gods Burn • A New America

## 💾 Datenspeicherung

Die Checkliste speichert deine Fortschritte automatisch im **Browser-Speicher (localStorage)**:
- Geräte-spezifisch (nicht synchronisiert zwischen Geräten)
- Persönlich (keiner außer dir sieht deine Daten)
- Länger speicherbar (bis du den Cache löschst)

**Daten exportieren:** Kopiere den Quellcode aus der Browser-Konsole:
```javascript
localStorage.getItem('ron-s-rang-data')
```

## 🔧 Entwicklung

Änderungen direkt in `index.html` vornehmen. Die Datei ist selbstständig und benötigt keine Build-Tools.

### Missionen hinzufügen
Im `<script>`-Bereich, in dem `missions` definiert ist:
```javascript
{ 
  id: 30, 
  name: 'Missionsname', 
  map: 'Map-Name', 
  category: 'Kategorie', 
  difficulty: 'easy|medium|hard', 
  tip: 'Optionaler Tipp oder null'
}
```

## 🤝 Zusammenarbeit

Du kannst anderen GitHub-Nutzern Zugriff geben:

### Collaborators hinzufügen (Privates Repo)
1. Gehe zu deinem Repository auf GitHub
2. **Settings** → **Collaborators** (oder **Collaborators and teams**)
3. Klicke **Add people**
4. Gib GitHub-Username, E-Mail oder vollständigen Namen ein
5. Wähle die Berechtigung (Push access recommended)
6. Die Person erhält eine Einladung

### Verschiedene Berechtigungsstufen
- **Pull**: Nur lesen
- **Push**: Lesen + Bearbeiten (empfohlen für Collaborators)
- **Admin**: Alles, inklusive Settings

## 📝 Lizenz

Frei verwendbar - gerne auch modifizieren und teilen!

## 🐛 Probleme?

- **Fortschritt weg?** → Browser-Cache wurde geleert (localStorage)
- **Styling fehlerhaft?** → Browser-Cache leeren (Strg+Shift+Del)
- **Funktioniert nicht?** → JavaScript muss aktiviert sein

---

**Made with ❤️ für Ready or Not S-Rang Enthusiasten**
