# league-sims-mashup 
# League of Legends x Die Sims 4 – Mashup (Arbeitstitel)

## Idee in einem Satz
Du baust Basis und Welt wie in Die Sims 4 und trittst danach mit League-of-Legends-Champions, Items und Skills gegen andere an.

## Spiele
- **Hauptspiel (Host):** Die Sims 4. Melty installiert den Mod dort hinein und startet das Spiel.
- **Zusatzspiel (Companion):** League of Legends. Champions, Items und Skills werden aus der installierten Kopie des Spielers gelesen. Es wird nichts davon mitgeliefert und League of Legends wird nicht verändert oder mit dem Mod gestartet.

## Spielgefühl
- Bauen: Basis und Welt gestalten wie in den Sims.
- Kämpfen: gegeneinander spielen wie in League of Legends, mit Champions, Items und Skills (Q/W/E/R).
- Mehrspieler: Spieler treten gegeneinander an (geplant). Maximale Spielerzahl und Verbindungsweg sind noch offen.

## Noch offen (Designfragen)
- Was passiert in der ersten Spielminute? (Baumodus, Champion wählen, Kampf zuerst oder Wellen und Verteidigung)
- Wie viele Spieler pro Partie?
- Was muss die erste spielbare Version mindestens können?

## Umsetzungsschritte
1. Verbindung zu Melty herstellen (`list_my_mods`, `game_info` für beide Spiele, `search_mashups`).
2. Installationsordner und echte Mod-Ordner von Die Sims 4 prüfen.
3. Design in JSON-Tabellen festhalten (Champions, Items, Skills, Welt-Objekte, Einhängepunkte ins Spiel).
4. Mod bauen und testen, mit zwei laufenden Instanzen für den Mehrspielertest.
5. Paket prüfen (`inspect_package`, `validate_recipe`, `one_click_check`) und als Entwurf bei Melty einreichen.
6. Echten Screenshot aufnehmen, hochladen und erst nach deiner Freigabe veröffentlichen.

## Status
Nur Konzept, noch kein Code. Melty war in der ersten Sitzung nicht erreichbar (Netzwerkfreigabe fehlte).
