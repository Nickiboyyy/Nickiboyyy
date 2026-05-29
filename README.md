# 🌙 About Me

Hi, ich bin **!moonprincess**! ✨  
Ich arbeite an meinem Projekt **Lunora Online** und bin CEO bei **Lunora** sowie Volunteer bei **Satsuya**.
Ich lerne gerade **Python, Java, Html, javascript** und **CSS** um selbst an Projekten arbeiten zu koennen.

---
## 📊 My Developer Skills

Hier ist eine Übersicht meiner aktuellen Programmiersprachen und Fähigkeiten, basierend auf meinen Projekten (Discord-Bots, Minecraft-Plugins und Web-Development):

<table>
  <tr>
    <td width="180"><b>🐍 Python (Bots)</b></td>
    <td width="400"><progress value="80" max="100"></progress> <b>27%</b></td>
  </tr>
  <tr>
    <td><b>☕ Java</b></td>
    <td><progress value="50" max="100"></progress> <b>17%</b></td>
  </tr>
  <tr>
    <td><b>🌐 HTML5 & CSS</b></td>
    <td><progress value="30" max="100"></progress> <b>14%</b></td>
  </tr>
  <tr>
    <td><b>⚡ JavaScript</b></td>
    <td><progress value="20" max="100"></progress> <b>10%</b></td>
  </tr>
</table>

---
*🚀 Aktiv am Lernen und Entwickeln von neuen Systemen!*
---

# 🌐 Social Media

👉 [Hier findest du alle meine Links](https://satsuya.de/linktree/Moon)

### My Discord:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/HDKZHX65Hf)

![Discord Profile](https://lanyard.cnrad.dev/api/1397554915097837671)

---

# 🌟 Lunora

Willkommen bei **Lunora** – wo Innovation und Gaming in einem einzigartigen Netzwerk verschmelzen!

Lunora ist mehr als nur ein Name; es ist eine Bewegung, eine Gemeinschaft und ein Zentrum für Kreativität. Wir haben uns zur Aufgabe gemacht, die nächste Generation von Entwicklern zu fördern und gleichzeitig eine unvergleichliche Gaming-Erfahrung zu bieten.

### Was ist Lunora?
Im Kern ist Lunora ein dynamisches Netzwerk, das zwei Leidenschaften miteinander verbindet: die Kunst des Programmierens und die unendlichen Möglichkeiten von Minecraft. Wir glauben fest daran, dass die besten Talente durch praktisches Lernen und eine unterstützende Umgebung entstehen. 

Deshalb bieten wir eine umfassende Plattform, auf der du die faszinierende Welt des Programmierens von Grund auf erlernen kannst. Egal, ob du ein kompletter Anfänger bist oder deine bestehenden Kenntnisse vertiefen möchtest – unsere Ressourcen, Mentoren und Projekte sind darauf ausgelegt, dich auf deiner Reise zu begleiten.

### Unser Minecraft-Netzwerk
Parallel zu unseren Bildungsangeboten betreiben wir ein riesiges Minecraft-Netzwerk, das als Spielwiese für Kreativität, Zusammenarbeit und spannende Abenteuer dient. Hier kannst du das Gelernte direkt anwenden, eigene Projekte entwickeln, mit anderen Spielern interagieren und Teil einer lebendigen Community sein. Von fesselnden Minispielen bis hin zu epischen Bauwerken – unser Minecraft-Netzwerk ist der perfekte Ort, um deine Ideen zu verwirklichen und neue Freunde zu finden.

### Unsere Vision
Bei Lunora geht es darum, Brücken zu bauen: zwischen Lernenden und Lehrenden, zwischen Theorie und Praxis, und zwischen Code und Kreativität. Wir möchten einen Raum schaffen, in dem jeder sein volles Potenzial entfalten kann, sowohl als Programmierer als auch als Gamer. Tritt Lunora bei und werde Teil einer Community, die Wissen teilt, Talente fördert und gemeinsam die digitale Welt von morgen gestaltet!

**Bereit, deine Reise zu beginnen? Werde Teil von Lunora – wir freuen uns auf dich!**

### ⛓️‍💥 Lunora Socials
* 🎵 **TikTok:** [Lunora Network](https://www.tiktok.com/@lunora.network.de?_r=1&_t=ZG-93nPkYtytSj)
* 🔮 **Twitch:** [Hier Twitch-Link einfügen]()

---

# 🔥 Minecraft Ruins

Du bist ein Fan von **Fantasy RP** und **Magie**? Dann bist du bei uns genau richtig!  
Willkommen auf **Minecraft Ruins**! Bei uns findest du genau dein perfektes Fantasy-RP-Erlebnis. 🏰✨

---
# 🌙 Lunora Network Aiko System Bot (Discord)

Ein hochmodularer, professioneller Discord-Bot, entwickelt für das MooncoreNetwork. Lunora vereint Moderation, Entertainment und System-Management in einer skalierbaren Architektur.

## 🛡️ Kern-Systeme & Sicherheit

### 1. Globales Identity-System
Jeder Nutzer erhält bei der ersten Interaktion eine bot-weite, 8-stellige ID. Diese dient der serverübergreifenden Identifizierung (Stored in `global_user_map.json`), unabhängig von Namensänderungen oder Server-Wechseln.

### 2. Dezentrale Datenverwaltung (`lib/data_manager.py`)
Im Gegensatz zu monolithischen Datenbanken nutzt dieser Bot ein guild-spezifisches JSON-System.
- **Speicherort:** `/data/{guild_id}.json`
- **Vorteil:** Hohe Performance, einfache Backups pro Server und strikte Datentrennung.

### 3. CEO-System & Panic-Mode
Ein mehrstufiges Sicherheitssystem:
- **Panic-Mode:** Sperrt sofort alle Bot-Interaktionen global (außer für autorisierte CEOs).
- **Auto-Reset:** Der Panic-Mode deaktiviert sich nach 12 Stunden automatisch, falls kein manueller Eingriff erfolgt.
- **Master-User:** In `lib/permissions.py` ist eine Master-ID hinterlegt, die Hard-Override-Rechte besitzt.

---

## 📋 Vollständige Befehlsreferenz

### 🛠️ System & Moderation
| Befehl | Beschreibung | Berechtigung |
|:-------|:-------------|:-------------|
| `/botinfo` | Zeigt technische Statistiken und die aktuelle Serveranzahl. | Jeder |
| `/mail <user>` | Öffnet ein Modal, um eine offizielle Team-Mitteilung per DM zu senden. | Manage Messages |
| `/role add <user> <role>` | Weist einem Mitglied eine Rolle zu (Hierarchie-Check inkludiert). | Manage Roles |
| `/role remove <user> <role>` | Entfernt eine Rolle von einem Mitglied. | Manage Roles |
| `/role info <user>` | Detaillierte Auflistung aller Rollen eines Nutzers. | Jeder |
| `/role list` | Zeigt eine Statistik aller Rollen und deren Mitgliederzahl. | Jeder |
| `/ceo login` | Autorisiert einen CEO für System-Eingriffe. | CEO-Status |
| `/permission add` | (Intern) Fügt Berechtigungen für spezifische Befehle hinzu. | Administrator |

### 🏠 Willkommens- & Verlassens-System
| Befehl | Beschreibung |
|:-------|:-------------|
| `/setwelcomechannel` | Legt den Kanal für Beitrittsnachrichten fest. |
| `/setwillkommens` | Konfiguriert das Embed (Titel, Beschreibung, Banner, Farben). |
| `/testwillkommens` | Sendet eine Test-Nachricht in den konfigurierten Kanal. |
| `/setleavechannel` | Legt den Kanal für Austrittsnachrichten fest. |
| `/setverlassen` | Konfiguriert die Nachricht für Nutzer, die den Server verlassen. |
| `/setwillkommen` | (Line-basiert) Erlaubt alternative Willkommens-Nachrichten in mehreren Kanälen. |

**Unterstützte Platzhalter:** `{user}`, `{user_id}`, `{user_name}`, `{guild}`, `{member_count}`, `<>` (für Zeilenumbruch).

### 💋 Social & XP (Kiss-System)
| Befehl | Beschreibung |
|:-------|:-------------|
| `/kiss <user>` | Küsst einen Nutzer. Erhöht die Kuss-XP und sendet ein zufälliges GIF. |
| `/kiss-multi <mentions>` | (Admin) Küsst mehrere Nutzer gleichzeitig für Massen-XP. |
| `/kiss-special` | Ein spezieller Kuss-Befehl für Zero Two. |
| `/kuss_leaderboard` | Zeigt die Top 10 Nutzer mit den meisten Kuss-XP auf dem Server. |
| `/kiss_xp_add <user> <amount>`| Fügt einem Nutzer manuell Kuss-XP hinzu (Admin only). |

### 🎮 Entertainment & Fun
| Befehl | Beschreibung |
|:-------|:-------------|
| `/zaehlen start <channel>` | Aktiviert das Counting-Game im Zielkanal. |
| `/zaehlen stopp <channel>` | Deaktiviert das Counting-Game. |
| `/crypto <coin>` | Ruft aktuelle Kurse von CoinGecko ab. |
| `/poll` | Erstellt eine interaktive Umfrage. |
| `/mock <text>` | Wandelt Text in mOck-sChReiBwEiSe um. |

---

## 🏗️ Architektur für Entwickler

### Modulares Laden
Der Bot nutzt spezialisierte Loader in `/lib`, um Komponenten beim Start zu registrieren:
1.  **Commands:** Automatische Instanziierung von Klassen in `/commands`.
2.  **Events:** Dynamische Bindung von Discord-Events an Handler in `/events`.
3.  **Tasks:** Asynchrone Hintergrund-Loops in `/tasks`.
4.  **Modals:** UI-Komponenten in `/modals`.

### Global Registry (`lib/global_registry.py`)
Verwende `g_data`, um auf globale Instanzen zuzugreifen, ohne Zirkel-Importe zu riskieren:
```python
from lib.global_registry import g_data
cfg = g_data.get("cfg")
```

## Adding Commands

Erstelle eine Datei in `/commands/`, z.B. `ping.py`:
```python
class Command:
    def __init__(self, client, cfg):
        @client.tree.command(name="ping")
        async def ping(interaction):
            await interaction.response.send_message("Pong!")
```

## Adding Events
Erstelle eine Datei in `/events/`, z.B. `logger.py`:
```python
from lib.load_events import register_event
async def on_message(msg): ...
async def setup(client, cfg):
    register_event("on_message", on_message)
```

## Library Reference (short)
- `lib/data_manager.py` — CRUD Operationen für Guild-JSONs.
- `lib/permissions.py` — Zentrale Prüfung von Admin- und Master-Rechten.
- `lib/global_registry.py` — Singleton Store für bot-weite Objekte.
- `lib/configuration_file.py` — YAML Parser für die `config.yml`.

---

## ⚙️ Installation

1.  `config.yml` erstellen (Token, Sync-Guild eintragen).
2.  Abhängigkeiten: `pip install discord.py pyyaml colorama requests pytz`.
3.  Start: `python main.py`.

*Entwickelt für MooncoreNetwork. Alle Daten werden lokal im `/data` Verzeichnis gespeichert.*


---

# 🤝 Partner

## ⚔️ Elysium Online
👉 [Tritt dem Elysium Discord bei](https://discord.gg/t8q98UwNTa)

Du bist ein Fan von *Sword Art Online* und suchst ein Minecraft-Erlebnis, das diesem Gefühl nahekommt? Dann bist du bei uns genau richtig! Wir erschaffen einen einzigartigen Minecraft-Server, der sich stark am beliebten Anime orientiert.

Tauche ein in eine Welt voller Abenteuer, in der dein Überleben davon abhängt, wie gut du dich an neue Spielmechaniken anpasst. Von der ersten Sekunde an wirst du das Gefühl haben, direkt in Aincrad gelandet zu sein – allerdings mit einem eigenen, frischen Twist.

Bevor wir die Tore für das große Abenteuer öffnen, veranstalten wir **Bau-Events**, bei denen du aktiv an der Gestaltung unserer Welt mitwirken kannst. Hilf uns dabei, ikonische Orte zu erschaffen und deine Spuren in der Geschichte unseres Servers zu hinterlassen.

Bereit, dein Schicksal in die Hand zu nehmen und dich den Herausforderungen zu stellen? Schließe dich uns an und werde Teil einer epischen Reise!

### 🌍 Willkommen auf Elysium – Das Minecraft-Netzwerk
In der Welt von Elysium wurden alle Städte über der ersten Ebene von Monstern überrannt. Deine Aufgabe als Spieler ist es, diese verlorenen Gebiete zurückzuerobern und die Welt wieder sicherer zu machen.

Elysium ist nicht nur ein MMO-Abenteuer, sondern ein vielseitiges Minecraft-Netzwerk, das verschiedene Spielstile unter einem Dach vereint. Im Zentrum steht der epische Hauptserver, aber es gibt immer wieder spannende Events und temporäre Spielmodi auf unseren Unterservern!

Dein Abenteuer beginnt in der großen Startstadt auf Ebene 1, wo du alles findest, was du für deine Reise brauchst. Hier stehen dir unser Team und die Gamemaster bei Fragen zur Seite und NPCs bieten dir die Möglichkeit, Items zu handeln.

### 🎮 Hauptserver: Dein MMO-Abenteuer
* 🗺️ **Der Weg nach oben:** Um eine neue Ebene freizuschalten, musst du dich einem epischen Boss-Kampf stellen. Besiege den Boss und der Weg zur nächsten Stadt wird freigeschaltet.
* 🏠 **Häuser & Währung:** Mit der Ingame-Währung Col (du startest mit 1.000 Col) kannst du dir auf den Ebenen Häuser kaufen. Wenn du die Inneneinrichtung anpassen möchtest, helfen dir die Gamemaster gerne. *Wichtig: Die Grundstruktur des Hauses darf dabei nicht verändert werden.*
* ⚔️ **Ausrüstung & Gilden:** Dein Inventar wird serverübergreifend gespeichert, sodass du deine Gegenstände behältst, egal auf welcher Ebene du dich befindest. Außerdem kannst du eigene Gilden gründen, um gemeinsam mit anderen Spielern zu kämpfen.
* ⚙️ **Custom-Features:** Elysium bietet dir ein einzigartiges Spielerlebnis mit Custom Items und einem angepassten Chat-System. Der Chat-Radius ist auf 30 Blöcke begrenzt, aber mit dem Proximity-Chat kannst du dich mit Spielern in deiner Nähe unterhalten.
* 🦊 **Ressourcen & Pets:** Für alle Ressourcen gibt es eine separate Farmwelt, die regelmäßig zurückgesetzt wird. Später wird es sogar die Möglichkeit geben, einige der speziellen Mobs des Servers als Pets zu halten.

### 🔗 Unterserver: Vielfalt im Netzwerk
Als Teil des Elysium-Netzwerks bieten wir dir regelmäßig wechselnde und saisonale Unterserver, um für Abwechslung zu sorgen:

* 🏆 **Community-Events:** Sei dabei, wenn wir spezielle Spielmodi wie einen *Craft Attack* Server hosten, auf dem du mit anderen Spielern in einer Vanilla- oder Modded-Welt kooperieren und konkurrieren kannst.
* ⏳ **Temporäre Modi:** Freue dich auf Event-Server wie Skyblock-Saisons, Minigames-Wochenenden oder thematische Kreativ-Welten.
* 🔄 **Verbindung:** Du wechselst bequem zwischen dem Hauptserver und den Unterservern, behältst jedoch deine wichtigsten Netzwerk-Fortschritte (wie Ränge oder kosmetische Items) über alle Modi hinweg.

Mit regelmäßigen Updates für den Hauptserver und spannenden Events auf den Unterservern sorgt das Elysium-Team dafür, dass dein Abenteuer immer spannend bleibt. Bei Fragen steht dir unser schnelles Hilfesystem über Tickets im Discord oder den Ingame-Befehl `/gm` zur Verfügung.
