# landnod-qgis-plugin-repository

Distribučný katalóg QGIS pluginov. Budúci distribučný katalóg vydaných QGIS pluginov a dokumentácia publikovania XML a ZIP balíkov.

**Stav: kostra projektu; komponent zatiaľ nie je spustiteľný ani vydaný.** Generovanie a nasadzovanie katalógu, zabezpečenie jeho prístupov a automatické aktualizácie sa teraz nenastavujú.

Začni súbormi [CURRENT.md](CURRENT.md), [AGENTS.md](AGENTS.md) a [prehľadom štruktúry](docs/structure.md). Celkový kontext a odložené zámery spravuje `landnod-platform`. Pri clone celého ekosystému je [platforma o dve úrovne vyššie](../../README.md).

Repozitár je určený pre private organizáciu `landnod-dev`. Vývoj momentálne prebieha lokálne cez existujúce predplatné Codex. Nie je nakonfigurovaný OpenAI API prístup, agent na pozadí ani aktívny workflow.

Prístupy ukladaj iba do ignorovaného `.local/`; vzor konfigurácie smie obsahovať len názvy položiek a neplatné ukážkové hodnoty. Ani private repozitár nie je úložiskom živých dát či produkčných záloh.

V tomto spoločnom workspace sú vzory názvov konfiguračných položiek v [platform/config/examples](../../config/examples/); skutočné hodnoty patria do ignorovaného adresára `landnod-platform/.local/secrets/`. Lokálne súbory sa nepoužívajú automaticky, kým príslušný nástroj nedostane explicitne nastavenú konfiguráciu.
