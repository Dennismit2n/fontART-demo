# fontART Designer — Testversion ✍️

**Deine Handschrift als richtige Schriftart.** Du malst die Buchstaben mit Maus, Stift oder Finger; fontART rechnet sie in eine `.ttf`-Datei um, die du in Windows installierst und danach in Word, LibreOffice oder Canva benutzt.

Dieses Repository ist die Heimat der **kostenlosen Testversion** für Windows. Es enthält keinen Quellcode — fontART ist das eine Werkzeug dieser Werkstatt, das nicht quelloffen ist, und der Abschnitt [Rechte](#rechte) sagt, warum.

![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-a21caf) ![Testversion](https://img.shields.io/badge/Testversion-60%20Minuten%20je%20Start-c026d3) ![Export](https://img.shields.io/badge/Export-nur%20a%E2%80%93z-e879f9) ![Portabel](https://img.shields.io/badge/Portabel-ohne%20Installation-eac54f)

**→ [Neueste Fassung herunterladen](https://github.com/Dennismit2n/fontART-demo/releases/latest)** · [English version of this file](README.md) · [Anleitung und Neuigkeiten](https://dennismit2n.github.io/werkstatt.html#fontart)

---

## Vor dem Herunterladen: Windows wird warnen

Die Datei ist nicht mit einem Herausgeber-Zertifikat signiert. Deshalb zeigt Windows SmartScreen einen blauen Kasten: **„Der Computer wurde durch Windows geschützt — unbekannter Herausgeber“**. Über **„Weitere Informationen“** und dann **„Trotzdem ausführen“** geht es weiter.

Diese Warnung bedeutet keinen Virus, sondern dass für ein Zertifikat noch niemand bezahlt hat. Wem das nicht reicht, der sollte die Datei nicht starten — das ist eine völlig vernünftige Haltung, und es gehört hierher geschrieben, statt dich daran vorbeizureden.

## Was die Testversion kann — und was nicht

| | |
|---|---|
| ✏️ **Alle Werkzeuge sind offen** | Malen, Konstruktionslinien, Geist-Glyph zum Vergleichen, Seitenabstände, Kerning-Vorschläge, Kerning-Editor, Tipptest, Reife-Analyse, Zeichentabelle. Nichts ist ausgegraut, um dich zu ärgern. |
| 💾 **Speichern und Laden gehen vollständig** | Dein Projekt ist eine `.fontart.json`-Datei. Speichern, wieder laden, weitermachen — auch nachdem die Uhr abgelaufen ist. |
| ⏳ **60 Minuten je Start** | Die Uhr läuft mit dem Programm und lässt sich nicht anhalten; ein kleingeklapptes Fenster zählt weiter. Ist die Zeit um, hören Malen und Exportieren auf. Speichern geht weiter — deine Zeichnung ist also nie verloren. |
| 🔤 **Der Export gibt a–z aus, sonst nichts** | In der Schriftdatei stehen nur die Kleinbuchstaben. Großbuchstaben, Zahlen, Umlaute, ß und Satzzeichen darfst du malen — sie wandern bloß nicht mit in die Datei. |
| 🏷️ **Die Schrift heißt immer „fontART DEMO“** | Was du ins Namensfeld tippst, wird beim Export übergangen. Zwei Demo-Schriften können deshalb nicht nebeneinander liegen: Windows sähe zweimal denselben Namen. |
| 🚫 **Ein Ausgang statt sechs** | Nur `.ttf`. Kein `.woff`, kein Musterblatt, kein Komplett-Paket, keine Fett- oder Kursiv-Beilage, kein Übungsblatt, kein Video-Mitschnitt — das ist in dieser Fassung nicht gesperrt, sondern gar nicht erst eingebaut. |

## In drei Schritten

1. Die `.exe` **[herunterladen](https://github.com/Dennismit2n/fontART-demo/releases/latest)** und starten. Installiert wird nichts; die Datei läuft, wie sie ist, und lässt sich genauso einfach wieder löschen.
2. Ein Zeichen aus der Leiste wählen und die **schwarze Fläche** des Buchstabens malen, nicht seine Umrisslinie. Fang mit `n` und `o` an — die beiden legen den Rhythmus der ganzen Schrift fest. Zittert die Hand, hilft der **Stabilisator**.
3. **⬇ Export › .ttf.** In Windows Rechtsklick auf die Datei, *Für alle Benutzer installieren*. Danach steht deine Schrift in Word unter **fontART DEMO**.

## Datenschutz

fontART geht nicht ins Netz. Nicht im Sinne von „wir versprechen, nichts zu senden“, sondern: Es steckt kein Code darin, der es könnte. Eine Suche über das ganze Programm nach `fetch`, `XMLHttpRequest`, `WebSocket` und `sendBeacon` findet **nichts**. Kein Besucherzähler, keine Update-Prüfung, keine Absturzmeldung, kein Schriftenkatalog, der befragt wird.

Die einzige Adresse im Programm ist der Verweis auf die Anleitung in der Werkstatt — und der öffnet sich nur, wenn du ihn anklickst, in deinem eigenen Browser.

Deine Zeichnungen liegen im Arbeitsspeicher und in der Datei, die du selbst speicherst. Hochgeladen wird nichts, weil es nichts gibt, wohin.

## Die Vollversion

Die Vollversion zeichnet alle **333 Zeichen** statt 26 — Groß- und Kleinbuchstaben, Zahlen, Umlaute, ß, Satzzeichen, dazu Griechisch, Kyrillisch und die japanischen Silbenschriften —, sie trägt den Namen, den du eintippst, und sie kennt die Ausgänge, die hier fehlen: `.woff` für Webseiten, Musterblatt, Komplett-Paket, Fett- und Kursiv-Beilagen, Ligaturen, PUA-Symbole, Farbschatten, Übungsblätter und Video-Mitschnitte.

Sie ist in Arbeit. **Wann sie fertig ist und auf welchem Weg sie zu haben sein wird, steht noch nicht fest.** Wer diesem Repository folgt, bekommt es mit, sobald es so weit ist. Es gibt keine Warteliste, keinen Newsletter, und die Testversion wird dich nie nach deiner E-Mail-Adresse fragen.

Warum ausgerechnet dieses eine Werkzeug etwas kosten soll, wo der Rest der Werkstatt kostenlos und quelloffen ist: [die Anleitung beantwortet das ehrlich](https://dennismit2n.github.io/werkstatt.html#fontart).

## Rechte

**Das hier ist nicht quelloffen.** Der Quellcode von fontART wird nicht veröffentlicht, und es wird kein Recht eingeräumt, das über Folgendes hinausgeht: Du darfst die Testversion kostenlos benutzen, privat wie geschäftlich, und die unveränderte `.exe` weitergeben, an wen du willst. Alles andere — zurückentwickeln, verändern, weiterverkaufen — ist nicht erlaubt.

**Was du malst, gehört dir.** Die Schriften, die du exportierst, sind ohne Einschränkung deine: benutzen, damit Gemachtes verkaufen, verschenken. Weder die Testversion noch die Vollversion erhebt einen Anspruch auf deine Arbeit.

© 2026 Dennis (Dennismit2n) · [Weitere kleine Werkzeuge](https://dennismit2n.github.io/)
