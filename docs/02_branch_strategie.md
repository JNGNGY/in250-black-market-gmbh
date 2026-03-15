# Branching-Strategie: GitHub Flow

## Übersicht

Wir verwenden **GitHub Flow** als Branching-Strategie. Diese Strategie ist einfach, effizient und eignet sich gut für kleinere Teams.

## Regeln

1. Der **main**-Branch ist immer stabil und deploybar
2. Für jede neue Funktion oder Bugfix wird ein **Feature-Branch** erstellt
3. Feature-Branches folgen der Namenskonvention:
   - `feat/<Beschreibung>` für neue Funktionen
   - `fix/<Beschreibung>` für Bugfixes
   - `docs/<Beschreibung>` für Dokumentation
4. Änderungen werden über **Pull Requests** in main gemerged
5. Pull Requests müssen vor dem Merge reviewed werden
6. Nach dem Merge wird der Feature-Branch gelöscht

## Workflow

1. Branch von main erstellen
2. Änderungen committen (mit konventionellen Commit-Nachrichten)
3. Push auf GitHub
4. Pull Request erstellen
5. Review und Merge
6. Branch löschen

## Vorteile

- Einfach zu verstehen und umzusetzen
- Klare Trennung zwischen stabiler und experimenteller Arbeit
- Pull Requests ermöglichen Code Reviews
