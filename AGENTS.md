# Pokyny pre landnod-qgis-plugin-repository

Lokálny kontext platformy: `../landnod-platform/CURRENT.md` a `../landnod-platform/AGENTS.md`, ak sú dostupné.

Pred zmenou prečítaj [CURRENT.md](CURRENT.md). V celom workspace prečítaj aj [aktuálny rozsah platformy](https://github.com/landnod-dev/landnod-platform/blob/main/CURRENT.md). Pri samostatnom clone platia tieto lokálne pravidlá; chýbajúci kontext nedopĺňaj domnienkami.

- Účel: Budúci distribučný katalóg vydaných QGIS pluginov a dokumentácia publikovania XML a ZIP balíkov.
- Kódovanie prebieha iba lokálne na používateľovom počítači cez existujúce predplatné Codex. Nekonfiguruj ani nevolaj OpenAI API, cloudových kódujúcich agentov alebo bezobslužné agentné úlohy.
- Stav `deferred` v [roadmape platformy](https://github.com/landnod-dev/landnod-platform/blob/main/ROADMAP.md) znamená kontext, nie zadanie. Zima je obdobie prehodnotenia, nie spúšťač. Pre odložené funkcie nevytváraj preventívny kód, tabuľky, závislosti ani prázdne moduly.
- Explicitne zadanú aktuálnu alebo urgentnú úlohu vykonaj v jej rozsahu. Aktualizuj CURRENT.md podľa skutočného zadania; neaktivuj tým ostatné plány.
- Generovanie a nasadzovanie katalógu, zabezpečenie jeho prístupov a automatické aktualizácie sa teraz nenastavujú.
- Prístupy a osobné nastavenia patria do ignorovaných `.local/` súborov. Tajomstvá nevypisuj, nekomituj a nekopíruj do issue alebo dokumentácie. Živé dáta a produkčné dumpy nepatria do Gitu.
- Pred commitom prezri zmeny. Spúšťaj iba relevantné existujúce kontroly; chýbajúce testy alebo runtime uveď otvorene. Nevytváraj prázdne testy, ktoré iba predstierajú úspešnosť.
- Verziu a changelog navrhni podľa dopadu skutočnej zmeny; vydanie a deploy sú samostatné operácie podľa aktuálneho zadania.
