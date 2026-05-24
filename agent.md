# Agent Notes

Reguli pentru editarea manualelor din acest repository:

- Pastreaza formatul BBCode existent. Daca deschizi un tag cu `[b]`, il inchizi cu `[/b]`, nu cu `</b]` sau `</b>`.
- Aceeasi regula se aplica pentru toate tagurile BBCode: `[i]...[/i]`, `[u]...[/u]`, `[size]...[/size]`, `[center]...[/center]`, `[spoiler]...[/spoiler]`, `[list]...[/list]`.
- Nu amesteca HTML cu BBCode decat daca exista deja un motiv clar in fisier. Manualele sunt pentru forum/BBCode.
- Termenii tehnici principali raman in engleza, iar traducerea romana se pune in paranteza la prima folosire sau cand ajuta claritatea.
  Exemplu: `trauma dressing (pansament traumatic)`, `scene size-up (evaluarea scenei)`, `tourniquet (garou)`.
- Acronymele si rolurile consacrate nu se traduc fortat: `BLS`, `ALS`, `EMS`, `CPR`, `AED/DEA`, `IC`, `SCBA`, `RIT`, `Firefighter`, `Engineer`, `Paramedic`, `Incident Commander`.
- Corecteaza gramatica si formularile in romana, dar nu schimba sensul procedural fara motiv.
- Nu folosi bullet-uri hardcodate sau simboluri decorative corupte. Pentru liste reale foloseste `[list]` si `[*]`. Pentru separatoare inline foloseste `-`.
- Pastreaza fisierele in encoding UTF-8 corect. Daca apar secvente mojibake sau caractere corupte, opreste-te si curata textul inainte de a continua.
- Dupa editare, cauta taguri gresite cu un pattern de tip `</b`, `</i`, `</u` si verifica perechile pentru `quote`, `birou`, `spoiler` si `altspoiler`.

## Validarea Referintelor (Divizii, Rankuri, Calificari)

Inainte de a scrie sau edita orice referinta la o divizie, un rank sau o calificare, verific astfel:

1. Exista in **MOP.md**? (divizii: cap. 1.07 / 4.04; rankuri: cap. 1.06 / cap. 3; calificari: cap. 5)
2. Exista in **CALIFICARI.md**?
3. Daca exista in **AMBELE** → o folosesc fara ezitare.
4. Daca exista doar intr-unul sau in niciunul → **ma opresc si intreb** utilizatorul ce varianta sa folosesc.

Exemple:
- `Division 2: HSOD - Hazmat, Special Operations & Disaster Response` → MOP 1.07.02 ✓, CALIFICARI ✓ → valid
- `Hazmat Operations` → MOP 5.04 ✓, CALIFICARI (TIER I, Div.2) ✓ → valid
- `Structural Collapse Awareness` → absent din MOP si CALIFICARI → ma opresc si intreb

Aceasta regula se aplica la orice referinta: in text narativ, in liste de calificari, in sectiuni de Division Assignment si in crew/role descriptions.

## Cross-Check

Cand utilizatorul cere un **cross-check**, verific urmatoarele categorii in ordine:

1. **Divizii** — Fiecare referinta la o divizie sau birou trebuie sa existe exact ca in MOP.md (cap. 1.07, 4.04). Verific si formatarea: `Division 2: HSOD - Hazmat, Special Operations & Disaster Response`, nu `Division 2 HSOD` sau variante prescurtate neoficiale.

2. **Rankuri** — Fiecare rank mentionat (ex: Engineer, Lieutenant, Captain) trebuie sa existe in ierarhia din MOP.md (cap. 1.06, cap. 3). Verific ca atributiile asociate rankului sunt corecte (ex: nu atribui comanda unui Firefighter daca MOP o rezerva Captainului).

3. **Calificari** — Fiecare calificare trebuie sa existe in CALIFICARI.md si/sau MOP.md (cap. 5). Daca o calificare apare intr-un manual de aparatura dar nu exista in niciunul din documente, o semnalezi ca problema.

4. **Contradictii procedurale** — Verific daca procedurile dintr-un manual contrazic procedurile din altul. Exemple de contradictii tipice: un manual spune ca un Firefighter poate face X, dar MOP rezerva X pentru Engineer; sau doua manuale dau responsabilitati diferite aceluiasi rol la aceeasi scena.

5. **Consistenta TIER** — Daca se mentioneaza un nivel de calificare sau TIER, acesta trebuie sa fie consistent cu sistemul TIER din MOP (cap. 4.05) si cu CALIFICARI.md.

6. **Chain of Command** — Ierarhia de comanda la scena trebuie sa respecte ICS si rankurile din MOP (cap. 10.02).

Un raport de cross-check include:
- Ce documente au fost verificate
- Ce este corect si consistent
- Ce este **inconsistent sau absent**, cu localizare exacta (sectiune, linie, termen)
- Ce schimbare propun, cu referinta la sursa corecta din MOP sau CALIFICARI
