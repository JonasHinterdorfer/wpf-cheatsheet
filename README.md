# WPF Cheat Sheet

Kompaktes WPF/MVVM-Cheatsheet für die Prüfung (max. 30 Seiten). Die Kapitel folgen dem Arbeitsablauf:

1. Ablauf-Checkliste + Platzhalter-Namen (`Item`/`Category`/`Detail`/`Tag`) zum Suchen/Ersetzen
2. Projekt und Vorlage (Datei-Vorlage, DB-Vorlage, ohne Vorlage)
3. Logik und Helper (Parser, Regex, Try-Muster, Dateien, CSV)
4. Datenbank und Import (Repository-Abfrage, ImportService, Konsolen-Import)
5. Model und ViewModel (Filter, Edit/Update, Laden/Speichern, Dialoge, Async)
6. Fenster, DI und Dialoge (App-Start, WindowNavigator)
7. XAML (Hauptfenster, Formular, DataGrid, Binding, Styles)
8. Custom Draw (OnRender mit Skalierung)
9. Unit-Tests und häufige Fehler

- [`WPF-Cheatsheet-de.adoc`](WPF-Cheatsheet-de.adoc) – AsciiDoc-Quelle
- [`WPF-Cheatsheet-de.pdf`](WPF-Cheatsheet-de.pdf) – fertiges PDF

PDF neu erzeugen:

```sh
asciidoctor-pdf WPF-Cheatsheet-de.adoc
```

Bei jedem Push einer `.adoc`-Datei auf `main` baut eine GitHub Action das PDF automatisch neu und committet es
(zusätzlich als Artifact im jeweiligen Workflow-Run verfügbar).
