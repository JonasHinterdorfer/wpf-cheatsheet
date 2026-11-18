# WPF Cheat Sheet – POSE 5CHIF

Spickzettel mit nützlichen WPF/MVVM-Code-Snippets (Layouts, Binding, Commands, Styles, Trigger, Templates, Timer).

- [`WPF-Cheatsheet-de.adoc`](WPF-Cheatsheet-de.adoc) – AsciiDoc-Quelle
- [`WPF-Cheatsheet-de.pdf`](WPF-Cheatsheet-de.pdf) – fertiges PDF

PDF neu erzeugen:

```sh
asciidoctor-pdf WPF-Cheatsheet-de.adoc
```

Bei jedem Push einer `.adoc`-Datei auf `main` baut eine GitHub Action das PDF automatisch neu und committet es
(zusätzlich als Artifact im jeweiligen Workflow-Run verfügbar).
