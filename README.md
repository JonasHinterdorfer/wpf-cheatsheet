# WPF Cheat Sheet

Kompaktes WPF/MVVM-Cheatsheet für die Prüfung. Beispielprojekt ist die Turtle-Aufgabe, die Snippets verwenden
neutrale Platzhalter (Tabelle am Anfang). Kapitel in Arbeitsreihenfolge:

1. Ablauf, Platzhalter, Projektstruktur (Turtle)
2. Logik und Helper (Regex, Try-Muster, Token-Parser, CSV)
3. Datenbank und Import (Entities, Mapping, Migration, Repository-Abfrage, Parser → ImportService → Program.cs)
4. Model und ViewModel (Haupt-ViewModel, Dialog-ViewModels, Datei-Vorlage, Async, Button-Raster)
5. Fenster, DI und Dialoge (App-Start, WindowNavigator)
6. XAML (Bausteine, ListView/DataGrid, ItemsControl mit DataTemplate, Binding, Styles)
7. Custom Draw (Control mit Skalierung + Daten → Linien)
8. Web API (Controller: DTOs, GET/POST, Statuscodes)
9. Unit-Tests und häufige Fehler

- [`WPF-Cheatsheet-de.adoc`](WPF-Cheatsheet-de.adoc) – AsciiDoc-Quelle
- [`WPF-Cheatsheet-de.pdf`](WPF-Cheatsheet-de.pdf) – fertiges PDF

PDF neu erzeugen:

```sh
asciidoctor-pdf WPF-Cheatsheet-de.adoc
```

Bei jedem Push einer `.adoc`-Datei auf `main` baut eine GitHub Action das PDF automatisch neu und committet es
(zusätzlich als Artifact im jeweiligen Workflow-Run verfügbar).
