# Simple Survival – Erste Schritte

Willkommen auf dem Server! Diese Seite hilft dir, das Modpack gut zum Laufen zu bringen,
und erklärt die wichtigsten Mods und Tasten.

---

## 1. Arbeitsspeicher (RAM) einstellen

Das Pack hat sehr viele Mods und eine große Sichtweite (Distant Horizons). Mit zu wenig RAM ruckelt es oder stürzt ab.

| Dein PC hat … | Für Minecraft einstellen |
|---|---|
| 16 GB | **8 GB** |
| 32 GB oder mehr | **10–12 GB** |

Nicht mehr als etwa die Hälfte deines gesamten RAMs vergeben, Windows/Linux und der Browser brauchen auch etwas.

**Modrinth App:** **Zahnrad** → **Synced settings** → **Java and memory** →
„Memory allocation“ auf den Wert oben stellen.

**Prism Launcher:**  **Bearbeiten** → **Einstellungen** → Reiter **Java** →
Haken bei „Speicher“ → **Maximale Speicherzuweisung** auf den Wert oben stellen.

---

## 2. Garbage Collector (ZGC) einschalten

Java räumt regelmäßig den Speicher auf. Der Standard dafür verursacht bei vielen Mods kurze Ruckler.
**ZGC** räumt nebenbei auf, ohne das Spiel anzuhalten. Distant Horizons empfiehlt ihn ausdrücklich.

Füge bei den **Java-Argumenten** deines Launchers (direkt unter der RAM einstellung) Folgendes hinzu:

```
-XX:+UseZGC
```

**Modrinth App:** Instanz → **Einstellungen** → **Java und Speicher** → **Java-Argumente** →
eigene Argumente aktivieren und `-XX:+UseZGC` eintragen.

**Prism Launcher:** Instanz → **Bearbeiten** → **Einstellungen** → Reiter **Java** →
Haken bei „Java-Argumente“ → `-XX:+UseZGC` eintragen.

---

## 3. Shader und Wolkenhöhe

Der Shader (Complementary Reimagined mit Euphoria Patches) ist nach dem ersten Start automatisch aktiv.

**Wolken höher stellen** (empfohlen, damit die Wolken nicht in den Bergen hängen):
**Optionen → Grafikeinstellungen → Shaderpakete → Shader-Einstellungen** →
im Bereich **Atmosphäre / Wolken** die **Wolkenhöhe** der ersten Wolkenschicht auf **280** stellen.
(Die Bezeichnungen können je nach Shader-Version leicht abweichen.)

---

## 4. Distant Horizons (Weitsicht)

Distant Horizons zeigt die Landschaft weit über die normale Sichtweite hinaus.

- Beim **ersten Beitreten** lädt der Server die Fernsicht nach und nach. Das kann einige Minuten dauern, danach ist sie lokal gespeichert.
- Ruckelt es, im DH-Menü (Knopf in den Grafikeinstellungen) die **Qualität** oder die **Weitsicht** senken.

---

## 5. Wichtige Tasten

| Taste                                | Funktion                              | Mod                      |
| ------------------------------------ | ------------------------------------- | ------------------------ |
| **M**                                | Weltkarte                             | Xaero's World Map        |
| **Y**                                | Minikarten-Einstellungen              | Xaero's Minimap          |
| **B** / **U**                        | Wegpunkt setzen / Wegpunkte verwalten | Xaero's Minimap          |
| **Z**                                | Minikarte vergrößern                  | Xaero's Minimap          |
| **Ä**                                | Claims & Party-Menü                   | Open Parties and Claims  |
| **V**                                | Voice-Chat-Menü                       | Simple Voice Chat        |
| **N**                                | Mikrofon stumm/an                     | Simple Voice Chat        |
| **Maus-Seitentaste 5**               | Ping setzen („Hier!“)                 | Ping Wheel               |
| **C** (halten)                       | Zoom                                  | Tweakeroo                |
| **F4**                               | Freecam                               | Tweakeroo                |
| **X**                                | Ausweichrolle                         | Combat Roll              |
| **R**                                | Item-Schnellauswahl                   | Item Swapper             |
| **K**                                | Skill-Tree                            | Pufferfish's Skills      |
| **I**                                | Elytra-Rollsteuerung an/aus           | Do a Barrel Roll         |
| **H**                                | Haltbarkeitsanzeige an/aus            | Durability Viewer        |


---

## 6. Ein paar Mods kurz erklärt

- **Rezepte nachschauen (REI):** Im Inventar mit der Maus über ein Item → **R** zeigt das Rezept,
  **U** zeigt, wofür man es braucht. Rechts ist die Item-Liste mit Suchfeld.
- **Lootr:** Truhen in Strukturen haben für **jeden Spieler eigenen Loot**. Du musst also niemandem etwas wegnehmen.
- **Gräber:** Wenn du stirbst, landen deine Sachen in einem **Grab** an der Todesstelle statt auf dem Boden.
- **Grundstücke (Open Parties and Claims):** Auf der Weltkarte (**M**) bzw. im Menü (**Ä**) kannst du  Chunks beanspruchen. Dort kann dann niemand anderes abbauen oder Truhen öffnen.
- **Blockinfo (Jade):** Oben am Bildschirm siehst du, worauf du schaust. Mit **Shift** mehr Details.
- **Rezeptkonflikte (Polymorph+):** Gibt es für eine Crafting-Anordnung mehrere Ergebnisse, erscheint  neben dem Ergebnis ein Knopf zum Auswählen.
- **Bauen (Tweakeroo):** Mit gedrückter **Strg** werden Blöcke versetzt platziert, mit gedrückter **Alt**  gedreht. Mit **Alt** siehst du außerdem den Inhalt einer Kiste oder Shulkerbox, auf die du schaust.
- **Voice Chat:** Standardmäßig wird übertragen, sobald du sprichst. Lautstärken und Mikrofon im **V**-Menü.
- **Kampf (Better Combat):** Waffen haben eigene Schlagbewegungen. **X** zum Ausweichen.
- **Skills (Pufferfish's Skills):** Mit **K** öffnest du den Skill-Baum und verteilst Punkte.

Viel Spaß auf dem Server!
