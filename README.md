# 🚀 Dynamische Shoutout‑Liste für Streamer.bot

Dieses Projekt erweitert **Streamer.bot** um eine dynamische **Shoutout‑Liste**.  
Falls Benutzer in dieser Liste stehen, werden sie automatisch geshoutoutet, sobald sie in deinem Chat schreiben.

✅ **!so+ <username>** → Benutzer zur Liste hinzufügen  
✅ **!so- <username>** → Benutzer aus der Liste entfernen  
✅ **Automatischer Shoutout**, sobald ein Benutzer aus der Liste etwas im Chat schreibt


## 📦 Installation (via Import)

### Voraussetzungen
- [Streamer.bot](https://streamer.bot/) ist installiert
- Du hast Moderatorrechte auf deinem Twitch‑Kanal



### 🔧 Import‑Schritte

1. **Streamer.bot starten**

2. **Import starten**
   - Öffne in Streamer.bot: **Tools → Import**
   - Klicke auf **Import from File**
   - Wähle die bereitgestellte Datei `shoutout-system.sb` aus

3. **Import bestätigen**
   - Nach dem Import findest du neue Actions:
     - `SO-Add` (`!so+`)
     - `SO-Remove` (`!so-`)
     - `SO-Shoutout` (wird durch First Words Event ausgelöst)

4. **Globale Variable prüfen**
   - Gehe zu **Settings → Variables**
   - Stelle sicher, dass die globale Variable `so_list` existiert und **Persistant** ist  
     (falls nicht, lege sie leer an mit Typ `String` und aktiviere Persistant)

