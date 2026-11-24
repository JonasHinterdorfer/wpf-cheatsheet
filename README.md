# WPF Cheat Sheet

Kompaktes WPF/MVVM-Cheatsheet für die Prüfung, ausgerichtet an der Musterlösung der Turtle-Aufgabe (aber neutral formuliert). Die Kapitel folgen dem Arbeitsablauf:

1. Ablauf-Checkliste + Platzhalter-Namen (`Item`/`Category`/`Detail`/`Tag`) zum Suchen/Ersetzen
2. Projekt und Vorlage (Datei-Vorlage, DB-Vorlage, ohne Vorlage)
3. Logik und Helper (Parser, Regex, Try-Muster, Dateien, CSV)
4. Datenbank und Import (Entities, Mapping-Klassen, Migrationen, Repository-Abfrage, Parser → ImportService → Program.cs)
5. Model und ViewModel (Haupt-ViewModel, Dialog-ViewModels mit Validierung, Design-Daten, Datei-Vorlage, Async)
6. Fenster, DI und Dialoge (App-Start, WindowNavigator)
7. XAML (Bausteine: Grid, StackPanel, ListView/DataGrid, UniformGrid, Dialoge, Binding, Styles)
8. Custom Draw (Control mit Skalierung zum Kopieren + anpassbarer Teil Daten → Linien)
9. Unit-Tests und häufige Fehler

- [`WPF-Cheatsheet-de.adoc`](WPF-Cheatsheet-de.adoc) – AsciiDoc-Quelle
- [`WPF-Cheatsheet-de.pdf`](WPF-Cheatsheet-de.pdf) – fertiges PDF

PDF neu erzeugen:

```sh
asciidoctor-pdf WPF-Cheatsheet-de.adoc
```

Bei jedem Push einer `.adoc`-Datei auf `main` baut eine GitHub Action das PDF automatisch neu und committet es
(zusätzlich als Artifact im jeweiligen Workflow-Run verfügbar).
