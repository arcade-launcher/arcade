# A.R.C.A.D.E.

**A**lles **r**und um **C**omputerspiele: **A**uswahl, **D**ownload, **E**instellungen – ein Spiele-Launcher für Linux.

Spiele aus Steam, Epic, GOG, Amazon, Battle.net, Ubisoft, EA und Xbox Game Pass sowie Minecraft-Modpacks aus dem
Prism Launcher in einer Bibliothek. Du kannst Spiele
starten, die Grafik für jedes Spiel einstellen, Gratis-Spiele abholen und Preise in den Shops vergleichen. Hinweise aus ProtonDB helfen
dir einzuschätzen, ob ein Spiel unter Linux läuft.

> A.R.C.A.D.E. ist ein kostenloses privates Hobbyprojekt, nicht mit den genannten Anbietern verbunden. Verkauf und
> geschäftliche Nutzung sind verboten. Für Nutzung, Weitergabe und Haftung gilt die [Lizenz](LIZENZ.txt).

## Herunterladen

Die Pakete liegen unter **[Releases](../../releases/latest)**.

## Einrichten

### 1. Das passende Paket auswählen

| Dein System | Datei |
|---|---|
| Fedora ab 44, Nobara | `arcade-<Fassung>-1.fc44.x86_64.rpm` |
| Ubuntu ab 24.04, Linux Mint ab 22, Pop!_OS ab 24.04 | `arcade_<Fassung>-1_amd64.deb` |
| Arch, CachyOS, EndeavourOS, Manjaro | `arcade-<Fassung>-1-x86_64.pkg.tar.zst` |

Die Pakete sind für 64-Bit-PCs mit Intel- oder AMD-Prozessor gedacht. Auf einem echten Rechner wurde A.R.C.A.D.E.
unter Nobara mit KDE geprüft. Ubuntu 24.04 mit GNOME und Arch mit Xfce wurden nur in Prüfumgebungen getestet, nie
auf einem echten System. Auf anderen Systemen kann also noch etwas haken.

### 2. Installieren

Öffne im Ordner mit der heruntergeladenen Datei ein Terminal. Gib den Befehl für dein System ein. Wenn Linux nach
deinem Passwort fragt, gib dein Linux-Passwort ein. Die genauen Befehle für jede Fassung stehen auch auf ihrer
Downloadseite. Für Fassung 0.28.2:

Fedora, Nobara:

```bash
sudo dnf install ./arcade-0.28.2-1.fc44.x86_64.rpm
```

Ubuntu, Linux Mint, Pop!_OS:

```bash
sudo apt install ./arcade_0.28.2-1_amd64.deb
```

Arch, CachyOS, EndeavourOS, Manjaro:

```bash
sudo pacman -U ./arcade-0.28.2-1-x86_64.pkg.tar.zst
```

Die Paketverwaltung installiert die Programme, die A.R.C.A.D.E. zum Starten braucht. Weitere Werkzeuge für einzelne
Anbieter lädt A.R.C.A.D.E. bei Bedarf nach. MangoHud für die Bildrate und GameMode für den Leistungsmodus sind
optional.

### 3. Erster Start

Beim ersten Start begrüßt dich ein kurzer Assistent. Darin kannst du die Anbieter auswählen und direkt anmelden,
danach zeigt dir eine kleine Tour die wichtigsten Stellen. Mit **ÜBERSPRINGEN** geht es gleich zur Tour. Alles lässt
sich später nachholen, wie unten beschrieben.

1. Im Startmenü **A.R.C.A.D.E.** öffnen (unter „Spiele“).
2. Steam: A.R.C.A.D.E. erkennt deine Spiele anhand der Bibliotheksdaten auf deinem Rechner. Das funktioniert auch
   mit Steam als Flatpak.
3. Für die anderen Anbieter: Klicke oben rechts auf das Zahnrad **⚙**. Es öffnen sich die **OPTIONEN**, dort der
   Reiter **ANBIETER**.
   - Epic, GOG, Amazon: **ANMELDEN** – du meldest dich auf der Seite des Anbieters an.
   - Battle.net, Ubisoft, EA: Klicke auf **EINRICHTEN**, danach auf **ÖFFNEN**. Melde dich im Anbieterprogramm an
     und installiere dort das gewünschte Spiel. A.R.C.A.D.E. zeigt die dort installierten Spiele in der Bibliothek an.
     Später öffnest du die Anbieterprogramme auch oben über **LAUNCHER ▾**.
   - Xbox Game Pass: **ANMELDEN** mit deinem Microsoft-Konto. Danach dauert es etwa eine Minute, bis die
     Game-Pass-Spiele erscheinen.
   - Minecraft: Ist der Prism Launcher installiert, erscheinen deine Modpacks von selbst. Mods und Updates richtest
     du weiter in Prism ein.
4. Klicke oben auf **BIBLIOTHEK** und wähle links ein Spiel aus. Siehst du **INSTALLIEREN**, klicke darauf und warte,
   bis die Installation abgeschlossen ist. Mit **SPIELEN** startest du ein installiertes Spiel. Bei geeigneten
   Game-Pass-Spielen gibt es auf der Spielseite in der Karte **GAME PASS UNTER LINUX** außerdem **IN DER CLOUD SPIELEN**.

Dein Anbieterpasswort gibst du nur auf der Anmeldeseite des Anbieters ein. Damit du angemeldet bleibst, werden
Anmeldedaten auf deinem Rechner gespeichert.

### 4. Neue Fassungen

Ist eine neue Fassung da, erscheint oben unter der Leiste der Hinweis „A.R.C.A.D.E. … ist da.“ Klicke auf
**AKTUALISIEREN**. Falls Linux nach deinem Passwort fragt, gib dein Linux-Passwort ein. Klicke anschließend auf **NEU STARTEN**. Kein Terminal nötig.

### Gratis und Shop

- **GRATIS:** Hier siehst du, welche Spiele es gerade umsonst gibt. Mit **ABHOLEN** öffnest du die Seite des Angebots,
  geholt wird dort. Hast du ein Spiel schon, klicke auf **HABE ICH**.
- **SHOP:** Mit **STEAM**, **EPIC** und **GOG** öffnest du den jeweiligen Shop. Im Feld „In allen Shops suchen …“
  suchst du in allen drei Shops auf einmal. Bei jedem Spiel stehen die Preise nebeneinander, der günstigste ist grün.
  Mit dem Stern kommt ein Spiel auf **DEINE WUNSCHLISTE**, dort siehst du, wenn der Preis sinkt.
- Shop-Seiten von Epic und GOG öffnen sich direkt in A.R.C.A.D.E. Mit **ZURÜCK** kommst du wieder ins Programm,
  **IM BROWSER ÖFFNEN** zeigt die Seite in deinem Browser. Steam öffnet immer das Steam-Programm. Bezahlt wird nur im
  Shop selbst.

### Gut zu wissen

- **Roter Hinweis oben rechts im Titelbild der Spielseite:** Der Schummelschutz dieses Spiels läuft unter Linux nicht
  oder sperrt Linux. Online spielen geht dann meist nicht, allein spielen klappt oft trotzdem.
- **Grafik eines Spiels einstellen:** Auf der Spielseite steht rechts die Karte **GRAFIK**. Mit **ÄNDERN** öffnet sich
  das Fenster mit den Einstellungen für dieses Spiel.
- **AMD-Grafikkarte ab der RX-7000-Serie:** Bei unterstützten Spielen wählst du dort in der Zeile **FSR-Fassung** die
  Option **FSR 4**. Dafür brauchst du GE-Proton und ein Spiel mit FSR 3.1.
- **NVIDIA-Grafikkarte:** Dort findest du auch die DLSS-Einstellungen für unterstützte Spiele. Für
  Zwischenbilder durch den Treiber wählst du unter **Zwischenbilder** die Option **TREIBER**. Bei **Reflex** zeigt dir
  das Programm den Status an.
- Öffnet A.R.C.A.D.E. Battle.net, Ubisoft Connect oder die EA App für dich, läuft das Anbieterprogramm beim Spielen im
  Hintergrund. Nach dem Spielen schließt A.R.C.A.D.E. es, sobald kein Download mehr läuft. Ein zuvor von dir
  geöffnetes Anbieterprogramm bleibt offen.

## Fehler melden

Fehler kannst du unter **[Issues](../../issues)** melden. Eine Antwort oder Behebung wird nicht zugesagt.

## Quelltext

Der Quelltext ist nicht öffentlich. Der Herausgeber entscheidet im Einzelfall, ob er ihn für nicht geschäftliche
Zwecke unter gesonderten Bedingungen bereitstellt.

## Wie A.R.C.A.D.E. entstanden ist

A.R.C.A.D.E. ist ein Hobbyprojekt. Programmiert wurde es mit Hilfe von KI (Claude von Anthropic). Idee, Planung,
Aussehen, Tests am echten Rechner und jede Abnahme kommen von einem Menschen.
