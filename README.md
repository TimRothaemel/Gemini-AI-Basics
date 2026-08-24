# AI Basics

Ein kleines Node.js-Projekt, das die Gemini API nutzt, um ein lokales JSON-Dokument zu analysieren und verständlich zusammenzufassen.

## Überblick

Das Projekt liest die Datei `analysis.json` ein und sendet den Inhalt als Prompt an das Gemini-Modell. So lässt sich leicht ein einfacher AI-Workflow mit realem Dateninput demonstrieren.

## Voraussetzungen

- Node.js 18+
- Ein gültiger Gemini API-Key

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
├── analysis.json
├── index.js
├── package.json
├── README.md
└── .gitignore
```

## Hinweis

Dieses Beispiel ist bewusst klein gehalten und dient als Einstieg in die Nutzung der Gemini API mit Node.js. Es kann als Basis für eigene AI-Tools, Analyse-Skripte oder Dokument-Workflows erweitert werden.
