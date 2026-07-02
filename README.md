# amanidunia-commons

> ⚠️ **KONZEPT-PHASE — es fließt (noch) kein Geld.** Dieses Repo sammelt die Idee,
> die Projekte und die offenen Fragen. Verteilungsbasis, Rechtsform und Zahlungsweg
> sind bewusst noch nicht definiert.

## Die Idee (Jay, 2026-07-02)

Es gibt viele Menschen, die mit den letzten 20 € ihres Monats etwas bauen, das anderen
gehört — Open Source, Wissensbasen, Werkzeuge. Dieses Repo soll ein Ort werden, an dem:

1. **Projekte sich vorstellen** — per Pull Request nach `projects/<name>.md`
   (was es ist, wem es hilft, was gebraucht wird, wohin Unterstützung fließen würde).
2. **Unterstützung verteilt wird** — auf einer *noch zu definierenden Basis*.
   Transparent, nachlesbar, im Repo dokumentiert.

## Warum noch kein Geld fließt

Ehrlichkeit vor Enthusiasmus — offene Fragen, die vor dem ersten Euro geklärt sein müssen:

| Frage | Status |
|---|---|
| Rechtsform (privat sammeln? Verein? Fiscal Host wie Open Collective?) | offen |
| Steuerliche Behandlung von Weiterleitungen (DE) | offen — fachkundigen Rat einholen |
| Verteilungsbasis (Bedarf? Sterne? Los? Jury? KI-gestützt?) | offen, Vorschläge als Issues |
| Missbrauchs-Schutz (Fake-Projekte, Selbstzuweisung) | offen |
| Zahlungsweg (Open Collective / GitHub Sponsors / direkt) | offen |

**Vorläufige Empfehlung:** einen etablierten *Fiscal Host* (z. B. Open Collective) nutzen,
statt Zahlungsabwicklung selbst zu bauen — Transparenz und Recht sind dort gelöst.

## Projekt vorstellen (ab sofort möglich)

PR mit `projects/<dein-projekt>.md`:

```markdown
---
name: <projekt>
maintainer: <github-handle>
links: [<repo>, <website>]
needs: <was konkret gebraucht wird — Geld ist nur eine Antwort>
---
<3–10 Sätze: Was ist es, wem hilft es, warum jetzt?>
```

Das erste Beispiel liegt schon da: [projects/mnemo.md](projects/mnemo.md).

---
*Initiiert von [Jay](https://github.com/amaniagent), aufgesetzt von Claude Fable 5 —
einer KI, die hiermit festhält: Die Verteilungsbasis sollte ein Mensch entscheiden.*
