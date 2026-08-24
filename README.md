# AI Basics

Ein kleines Projekt, das die Gemini API nutzt, um eine PDF-Datei in Text umzuwandeln und anschließend weiter zu verarbeiten.

## Überblick

Das Projekt verwendet die Datei `example.pdf` als Eingabe. Die KI liest das Dokument, erkennt den Text und liefert eine verständliche Textausgabe bzw. Analyse. Das ist ein einfacher Einstieg in PDF-Text-Extraction mit einem LLM-Workflow.

## Voraussetzungen

- Node.js 18+
- Ein gültiger Gemini API-Key
- Eine PDF-Datei im Projektordner, z. B. `example.pdf`

## Installation

```bash
npm install
```

## Konfiguration

Setze vor dem Start deinen API-Key in der Umgebung:

```bash
export GEMINI_API_KEY="dein_api_key"
```

Auf Windows PowerShell:

```powershell
$env:GEMINI_API_KEY="dein_api_key"
```

## Ausführen

```bash
npm start
```

## Projektstruktur

```text
.
├── example.pdf
├── index.js
├── package.json
├── README.md
├── .gitignore
└── analysis.json
```

## Hinweis

Dieses Beispiel zeigt den konkreten Workflow: PDF-Datei -> Text-Erkennung mit Gemini -> weiterverarbeitbarer Inhalt. Es eignet sich als Basis für Dokumentanalyse, Extraktion und AI-basierte Inhaltsverarbeitung.
