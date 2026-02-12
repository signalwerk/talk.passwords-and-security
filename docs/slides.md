---
theme: signalwerk
title: Passwörter & Security
---

```fm
style: negative
background: true
```

## Hello _👋_

# {{process.content.frontmatter.title}}

_Ein kurzer Überblick_

<footer>

2026 · Zurich · Stefan Huber

</footer>

--s--

## Grundprinzip

# Sicherheit ist Teamarbeit

- **Du** schützt deine Accounts und Daten
- **Wir** bauen Systeme, die Fehler verzeihen
- **Meldet** Probleme oder Vorfälle, damit wir diese besser verstehen und verhindern können

--s--

## Wie bloss soll ich mir das merken?

# Passwort-Manager

- Apple oder Drittanbieter
- Speichert & generiert Passwörter
- Autofill statt Copy/Paste
- Synchronisiert sicher über Geräte

--s--

## Das eine Passwort, das du dir merkst

# Master-Passwort

- Einzigartig
- Sicheres Passwort verwenden
- Nicht in Notizen/Browser/Chat speichern

> Wenn dein Computer-Account kompromittiert wird, könnte (je nach Setup) dein Passwort-Manager ebenfalls gefährdet sein. Daher beides absichern.

--s--

## Was ist ein sicheres Passwort?

# Nicht in kurzer Zeit zu erraten

- Hohe Entropie (Chaos)
- Länge unbekannt
- Verwendete Zeichen unbekannt

--s--

## Hohe Entropie (Chaos)

- Niemals: gleiche Passwörter, Muster, Firmenname, Jahreszahlen, ...
- Stattdessen: zufällige Kombinationen aus einem Passwort-Manager generieren lassen

> Wenn du dir das Passwort merken kannst, ist es wohl nicht sicher genug!

<footer>

Siehe auch: [xkcd: Password Strength](https://xkcd.com/936/)

</footer>

--s--

## Passwort Sicherheit

- Beispiel A: `Te4mEns3mb1e`
- Beispiel B: `AbstimmungSchwungEntwicklungMenschheit`

--s--

## `Te4mEns3mb1e`

> Euer Laptop wäre nach weniger als einer Sekunde geknackt.

etwa ~10⁷ Versuche

<div style="font-size: 0.8em;">

- Team → sehr übliches englisches Wort
- Ensemble → englisches Wort
- a zu 4 → übliche Substitution
- e zu 3 → übliche Substitution
- i zu 1 → übliche Substitution

</div>

<footer>

Quelle: [zxcvbn](https://lowe.github.io/tryzxcvbn/)

</footer>

--s--

## `AbstimmungSchwungEntwicklungMenschheit`

> Euer Laptop wäre nach Jahrhunderten noch nicht geknackt.

etwa 10³⁷ Versuche

<div style="font-size: 0.8em;">

- Der aktive Wortschatz ist sehr gross
- Bei einer Zusammensetzung von 4 Wörtern steigt die Entropie exponentiell

</div>

<!--
<div style="font-size: 0.5em;">

| Rate          | Geschätzte Zeit  | Beschreibung                                 |
| ------------- | ---------------- | -------------------------------------------- |
| 10B / Sekunde | **Jahrhunderte** | Offline-Angriff, schneller Hash, viele Kerne |
| 10k / Sekunde | Jahrhunderte     | Offline-Angriff, langsamer Hash, viele Kerne |
| 10 / Sekunde  | Jahrhunderte     | ungedrosselter Online-Angriff                |
| 100 / Stunde  | Jahrhunderte     | gedrosselter Online-Angriff                  |

</div>
-->

<footer>

Quelle: [zxcvbn](https://lowe.github.io/tryzxcvbn/)

</footer>

--s--

## Erklärung

```
Aachen
Ab
abgerufen
abrufen
...
```

Anzahl der Wörter in deinem aktiven Wortschatz (~15000)

--s--

## Erklärung

```
AachenAachen
AachenAb
Aachenabgerufen
Aachenabrufen
...
```

15000 × 15000 = 225 000 000 Versuche

15000 × 15000 × 15000 × 15000 = 10³⁷ Versuche

--s--

## Two-Factor Authentication (2FA)

- etwas wissen (passwort)
- etwas haben (2FA-Token, Smartphone)
- ...

--s--

## Two-Factor Authentication (2FA)

- Schützt dich auch bei geleakten Passwörtern
- Bevorzugt: **Authenticator-App** oder **Security Key**
- Weniger gut: SMS (besser als nichts, aber angreifbarer)

--s--

## Passkeys

- Ihr müsst etwas kryptografisch sicheres haben (ähnlich wie ein Schlüssel/Passwort)

--s--

```fm
style: negative
background: true
```

## exit 0; thx

# _Fragen?_
