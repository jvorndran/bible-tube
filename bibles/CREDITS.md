# Bible text sources

Downloaded from eBible.org on 2026-10-25, using the official USFX editions:

- English: **World English Bible Classic**, 2020 stable text edition (`eng-web`), with the 66-book protocanon extracted from the publisher's full ecumenical book set. [Public-domain notice](https://ebible.org/eng-web/copyright.htm), [source archive](https://ebible.org/Scriptures/eng-web_usfx.zip).
- Español: **Reina-Valera 1909** (`spaRV1909`). [Public-domain notice](https://ebible.org/spaRV1909/copyright.htm), [source archive](https://ebible.org/Scriptures/spaRV1909_usfx.zip).
- Português: **Bíblia Portuguesa Mundial** (`porbrbsl`). [Public-domain notice](https://ebible.org/porbrbsl/copyright.htm), [source archive](https://ebible.org/Scriptures/porbrbsl_usfx.zip). The publisher identifies this translation as a draft still under revision; the app displays this status.

Each bundled edition contains the 66-book Protestant canon and 1,189 chapters. The source may include blank verse slots where a numbered verse is omitted in that translation's textual tradition. The app identifies empty slots rather than filling them from a different translation. Notes, headings, cross references, Strong's markup and other non-verse material are excluded. Typography and whitespace are normalized; the text itself is not paraphrased. World English Bible is a trademark of eBible.org.

`scripts/import-bibles.py` reproduces the normalized JSON from the downloaded USFX archives. Editorial guide summaries in the app are separately labeled and are not Scripture.
