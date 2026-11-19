# Skills für Kaltakquise

Elf Anleitungen für Ihren KI-Assistenten, auf Deutsch, von [Leadscraper](https://www.leadscraper.de/skills).
Ein Skill ist eine Textdatei, die Ihrem Assistenten sagt, wie er eine Aufgabe erledigt. Diese elf führen vom
Wunschkunden bis zur Auswertung der Antworten.

## Installieren

Alle Skills:

```
npx skills add deimanncom/kaltakquise-skills
```

Einen Skill:

```
npx skills add deimanncom/kaltakquise-skills --skill anlass-finden
```

Ohne Befehl: Datei öffnen, herunterladen und in Ihrem Assistenten als Skill ablegen oder als Anweisung einfügen.

## Die Skills

### Wen anschreiben

- [`wunschkunden-beschreiben`](skills/wen-anschreiben/wunschkunden-beschreiben/SKILL.md): Beschreibt aus Website und eigenen Angaben eines Unternehmens, welche Firmen es zuerst per Kaltakquise ansprechen sollte und welche nicht.
- [`firmenliste-pruefen`](skills/wen-anschreiben/firmenliste-pruefen/SKILL.md): Prüft eine Liste von Firmen gegen die Beschreibung der Wunschkunden und sortiert jede in passt, passt nicht oder unklar, mit Grund und Quelle.
- [`ansprechpartner-finden`](skills/wen-anschreiben/ansprechpartner-finden/SKILL.md): Findet für eine Firma die Person, die über das Angebot entscheidet, nur aus öffentlichen Quellen der Firma, und sagt offen, wenn sich niemand belegen lässt.
- [`anlass-finden`](skills/wen-anschreiben/anlass-finden/SKILL.md): Prüft für eine einzelne Firma, ob es gerade einen belegten Anlass gibt, sie anzuschreiben, und nennt Quelle und Datum.

### Was schreiben

- [`erstes-anschreiben`](skills/was-schreiben/erstes-anschreiben/SKILL.md): Schreibt die erste E-Mail an eine Firma aus einem belegten Anlass, kurz, persönlich und mit einer einfachen Frage am Ende.
- [`nachfassen`](skills/was-schreiben/nachfassen/SKILL.md): Schreibt zwei bis drei Nachfass-Mails zu einem ersten Anschreiben, jede mit einem neuen Gedanken statt „wollte nur nachhaken“, und sagt, wann Schluss ist.
- [`betreffzeile`](skills/was-schreiben/betreffzeile/SKILL.md): Schlägt Betreffzeilen für ein Anschreiben vor, die aussehen wie von einem Kollegen und nicht wie Werbung, und empfiehlt eine.
- [`anschreiben-pruefen`](skills/was-schreiben/anschreiben-pruefen/SKILL.md): Überarbeitet eine geschäftliche E-Mail an einen Interessenten oder Kunden so, dass sie klingt wie von einem Menschen am Telefon und nicht wie von einer KI.

### Antworten und Zahlen

- [`antworten-einordnen`](skills/antworten-und-zahlen/antworten-einordnen/SKILL.md): Ordnet Antworten auf Anschreiben in feste Gruppen ein (Interesse, Rückfrage, Verweis, später, kein Bedarf, Abmeldung, Abwesenheit, unzustellbar) und nennt für jede den nächsten Schritt.
- [`rueckfrage-beantworten`](skills/antworten-und-zahlen/rueckfrage-beantworten/SKILL.md): Beantwortet eine Rückfrage auf ein Anschreiben (Preis, Ablauf, Beispiele) ehrlich im ersten Satz und führt in derselben Mail zu einem Gespräch.
- [`kampagne-auswerten`](skills/antworten-und-zahlen/kampagne-auswerten/SKILL.md): Wertet die Zahlen einer Kaltakquise-Kampagne aus, findet die eine Stelle, an der am meisten verloren geht, und schlägt genau eine Änderung als nächsten Test vor.

Ob Sie eine Firma anschreiben dürfen, klären die Skills nicht. Dafür fragen Sie am besten Ihren Rechtsbeistand.

Wer das nicht selbst machen will, bekommt von uns ein [kostenloses Kaltakquise-Konzept](https://www.leadscraper.de/outbound-plan/).
