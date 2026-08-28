# Hallo! 👋

Ich bin Thomas – ich entwickle kleine, nützliche Android-Apps für den Alltag.

## Meine Apps

Alle Apps sind **kostenlos, werbefrei und Open Source**. Die APKs sind überwiegend
für **ARM64-Geräte** gebaut (arm64-v8a) – das betrifft praktisch alle modernen
Android-Smartphones und -Tablets. Im jeweiligen Repo liegt immer die **aktuelle APK
unter Releases** – einfach herunterladen und installieren.

| App | Beschreibung |
|-----|-------------|
| [🎭 Imposter Party Suite](https://github.com/Asparagus11/ImposterPartySuite) | Offline-Party-Spiele für 3–15 Spieler (Imposter, Undercover, Spyfall). Ein Gerät wird herumgereicht. |
| [📍 POIMelder](https://github.com/Asparagus11/POIMelder) | Meldet Points of Interest auf dem Weg per Notification und Sprachansage (OSM-Daten). Für Radfahrer und Autofahrer. |
| [📡 CatchMe](https://github.com/Asparagus11/CatchMe) | Echtzeit-Ortung für Familien. Jedes Gerät synct seine Position über Nextcloud – kein fremder Server nötig. |
| [🍽️ FoodPlanner](https://github.com/Asparagus11/FoodPlanner) | Wöchentliche Speiseplanung mit automatischer Einkaufsliste (Zutaten minus Vorrat). Nextcloud-Sync. |
| [🌐 Kids Browser](https://github.com/Asparagus11/KidsBrowser) | Kindersicherer Browser mit elterlicher Allowlist/Blocklist. Filterconfig per Nextcloud synchronisierbar. |
| [🖼️ CleverGallery FOSS](https://github.com/Asparagus11/CleverGallery_FOSS) | Galerie-App mit KI-Tagging (Objekte + Personen), OCR und smarter Suche. Komplett offline. |
| [🤖 LLMTalkBuddy](https://github.com/Asparagus11/LLMTalkBuddy) | Voice-Chat mit LLM: Spracheingabe (Whisper) → KI-Antwort → Vorlesen (Piper). Plus Bildgenerierung und Vision. |
| [🗣️ LetsTalk](https://github.com/Asparagus11/LetsTalk) | Sprachlern-App für Alltagssätze (DE/EN/FR/SV) mit Wort-für-Wort-Übersetzung und TTS. |
| [⌨️ NeoType](https://github.com/Asparagus11/NeoType) | Privacy-first Keyboard (HeliBoard-Fork) mit lokaler Push-to-Talk-Diktierfunktion (Whisper). |

> ⚠️ Manche Repos sind noch in Vorbereitung – Links können erst funktionieren, wenn
> das jeweilige Repo auf GitHub angelegt ist.

## Prinzipien

**Nextcloud als Rückgrat.** Mir ist ein einfacher, selbst kontrollierter Datenaustausch
wichtig. Viele meiner Apps synchronisieren über **Nextcloud (WebDAV)** – keine fremden
Cloud-Dienste, keine Accounts bei Drittanbietern. Wer eine eigene Nextcloud braucht,
kann sie z.B. günstig bei [all-inkl.com](https://all-inkl.com) hosten.

**Europäische KI-Services.** Wo meine Apps ein LLM brauchen (z.B. LLMTalkBuddy),
nutze ich bevorzugt [Eden AI](https://www.edenai.co) – einen französischen Anbieter,
der viele Modelle über eine einheitliche API zugänglich macht.

**Offline first.** Sprachausgabe (TTS) und Spracherkennung (STT) laufen lokal auf dem
Gerät – mit [Sherpa-ONNX](https://github.com/k2-fsa/sherpa-onnx) (Piper für TTS,
Whisper für STT). Kein Internet nötig, keine Daten verlassen das Gerät.

## Entwicklung

Alle Apps wurden größtenteils mit **KI-Coding-Agenten** entwickelt – insbesondere
[Kiro](https://kiro.dev) und [OpenCode](https://opencode.ai). Das sind auch die
einfachsten Wege, die Apps weiterzuentwickeln:

```
Schau dir mal dieses Android-App-Projekt an und schaffe die Voraussetzungen
für den Bau einer APK-Datei (Android App). Baue mir anschließend die APK-Datei.
```

Wer gerne mit europäischen Services arbeitet: [OpenCode](https://opencode.ai) als
Coding-Agent und [Eden AI](https://www.edenai.co) als LLM-Provider sind eine gute
Kombination.

## Tech-Stack

- Kotlin + Jetpack Compose + Material3
- Sherpa-ONNX (TTS/STT)
- Nextcloud WebDAV
- Room, DataStore, WorkManager
- TensorFlow Lite (bei KI-Features)

## Unterstützung

☕ [Buy Me a Coffee](https://buymeacoffee.com/asparagus11)

## Kontakt

📧 thomas.ad.meyer@gmail.com
