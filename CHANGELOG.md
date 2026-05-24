[birou=CHANGELOG white]

[hr][/hr][size=115][font=arialblack][center][b]CHANGELOG - JURNAL DE MODIFICARI[/b][/center][/font][/size][hr][/hr]

[list=none]
Acest document inregistreaza toate modificarile aduse manualelor din repository, in ordine cronologica inversa (cele mai recente primele). Fiecare intrare specifica fisierul, sectiunea si natura modificarii.
[/list]

[hr][/hr]

[size=120][b]2026-05-24 — Sesiunea 3[/b][/size]

[b]Cross-check general — probleme identificate si rezolvate:[/b]
[list]
[*][b]FIRE/RESCUE.md, Sectiunea 9.2 — CORECTATA:[/b] Calificarea minima pentru intrarea in hot zone era gresit specificata ca "Hazmat Operations (TIER I)". Conform MOP.md cap. 11.03, TIER I (Decontamination Specialist) opereaza in Warm Zone; cel care intra in Hot Zone este Hazmat Entry Technician (TIER II). Corectat la "Hazmat Technician (TIER II)" cu clarificarea explicita a diferentei TIER I vs hot zone.
[*][b]Technical Rescue Specialist — notata, nemodificata:[/b] Calificarea exista in MOP 5.07 dar lipseste din CALIFICARI.md. User a autorizat folosirea ei anterior.
[*][b]Apparatus Engineer — notata, nemodificata:[/b] Clasificat diferit in MOP 5.07 (Technical Specializations) fata de CALIFICARI (Primary Operations Specializari). Nu creeaza contradictie operationala.
[/list]

[size=110][b]EMS/ALS.md[/b][/size] - Capitol 6.2 (Medication Groups) — medicamente noi adaugate
[list]
[*][b]Cardiac/Pulse:[/b] Adaugat [b]Vasopressin[/b] (vasopresor alternativ epinefrinei in cardiac arrest, 40 UI IV/IO doza unica).
[*][b]Cardiac Specific:[/b] Adaugat [b]Procainamide[/b] (antiaritmic pentru VT cu puls stabil si FA cu durere scurta, alternativa amiodaronei).
[*][b]Pain Relief:[/b] Adaugat [b]Acetaminophen / Paracetamol (Tylenol)[/b] in forma IV pentru pacienti care nu pot lua oral sau cu contraindicatii la AINS.
[*][b]Poisoning & Overdose:[/b] Adaugat [b]Hydroxocobalamin / Cyanokit[/b] (antidot cianuri, indicat la victime incendii cu inhalare fum) si [b]Pralidoxime / 2-PAM[/b] (reactivator colinesteraza pentru intoxicatii cu organofosforice, administrat cu Atropine).
[*][b]Respiratory:[/b] Adaugat [b]Dexamethasone[/b] (corticosteroid cu durata lunga, pentru COPD/astm sever, anaphylaxis, edem laringian, crup); specificata combinatia Atrovent + Salbutamol pentru bronhospasm sever.
[*][b]Diabetic:[/b] Adaugat [b]Thiamine / Vitamin B1[/b] (administrata inaintea Dextrose la pacienti cu suspiciune etilism cronic, pentru preventie Wernicke).
[*][b]Nausea:[/b] Adaugat [b]Ondansetron / Zofran[/b] (antiemetic de electie in prespital, blocant 5-HT3, administrare IV/IM/SL).
[*][b]Allergies:[/b] Adaugat [b]Dexamethasone[/b] (complement corticosteroid pentru anaphylaxis).
[*][b]Seizures — grupa noua:[/b] Adaugata grupa separata pentru crize epileptice cu Diazepam, Midazolam, Lorazepam si [b]Levetiracetam / Keppra[/b] (antiepileptic de linia a doua pentru status epilepticus refractar la benzodiazepine, IV fara sedare semnificativa).
[/list]

[hr][/hr]

[size=120][b]2026-05-24 — Sesiunea 2[/b][/size]

[size=110][b]MOP.md[/b][/size] - Capitol 10 (Primary Operations Bureau)
[list]
[*][b]Sectiune noua - 10.04 Incident Commander — Desemnare si Autoritate:[/b] Adaugata dupa sectiunea 10.03 (Pozitii si Calificari). Include trei sub-sectiuni: 10.04.01 (regula generala IC = cel mai mare rank, exceptia pentru incidente specializate, procedura de Transfer of Command cu fraza standardizata), 10.04.02 (autoritatea si prioritatea IC pe canal, sectorizarea comunicatiilor pe Statia 713/714, subordonarea TAC channels fata de 712, procedura de revenire pe canal principal) si 10.04.03 (responsabilitatile IC la scena, cu fraze standardizate de anunt si raportare).
[/list]

[size=110][b]MOP-PARTII.md[/b][/size] - Capitol 19 (Politici de Comunicare)
[list]
[*][b]Sectiunea 19.06.02 Frecvente — reescrisa complet:[/b] Adaugate canalele specifice cu descrieri: Statia 712 (Dispatch / Canal Principal), Statia 713 (IC1/TAC1), Statia 714 (IC2/TAC2). Fiecare canal are rolul, conditiile de utilizare si relatia cu canalul principal.
[*][b]Sectiune noua - 19.06.03 Format de Comunicare Radio:[/b] Adaugata intre 19.06.02 si 19.07. Explica cele doua formate: transmisie generala (Rank Prenume Nume, mesaj) si transmisie cu destinatar (Rank Prenume Nume towards Rank Prenume Nume, mesaj). Include exemple concrete pentru fiecare format si procedura de confirmare a receptiei.
[*][b]Sectiunea 19.08 Terminologie — extinsa semnificativ:[/b] Redenumita "Terminologie si Coduri de Raspuns". Adaugate si reformulate codurile: Code 0 (Emergency Traffic / Canal Liber, cu fraza de anunt de trei ori), Code 1 (non-urgent), Code 2 (urgent, lumini doar), Code 3 (urgenta, lumini + sirene), Code 4 (scena securizata). Adaugati termeni noi: Mayday, PAR (Personnel Accountability Report).
[/list]

[hr][/hr]

[size=120][b]2026-05-24 — Sesiunea 1[/b][/size]

[size=110][b]FIRE/RESCUE.md[/b][/size] - Rescrierea completa a manualului
[list]
[*][b]Modificare generala:[/b] Manualul a fost transformat din concept manual (draft) intr-un manual operational complet, similar ca structura si nivel de detaliu cu ENGINE.md, TRUCK.md si SQUAD.md.
[*][b]Sectiuni noi adaugate:[/b] 1. PPE (echipament standard + echipament specific Rescue), 2. Tools & Equipment (Extrication / Stabilizare / Rope & Confined Space / Scene Support), 3. Division Assignment (actualizat), 4. Vehicle Extrication (cu sub-proceduri detaliate), 5. Structural Collapse (collapse patterns, shoring, victim removal), 6. Confined Space Rescue (atmospheric testing, entry protocol, non-entry rescue, emergency egress), 7. Rope Rescue / High-Angle (anchor system, patient packaging, lower vs raise cu comenzi standardizate), 8. Mayday Support / RIT Assist, 9. Hazmat Support.
[*][b]Calificari invalide inlocuite:[/b] "Structural Collapse Awareness" si "Confined Space Rescue" nu existau in MOP sau CALIFICARI - au fost inlocuite cu "Technical Rescue Specialist" (existent in MOP 5.07).
[*][b]Referinte divizii corectate:[/b] "Division 2 HSOD" → "Division 2: HSOD - Hazmat, Special Operations & Disaster Response"; "Division 3 Wildland & Environmental Operations" → "Division 3: Wildland & Environmental Operations". Toate referintele la divizii verifica acum contra MOP.md si CALIFICARI.md.
[/list]

[size=110][b]agent.md[/b][/size] - Adaugare reguli noi
[list]
[*][b]Sectiune noua - Validarea Referintelor (Divizii, Rankuri, Calificari):[/b] Regula ca orice divizie, rank sau calificare trebuie verificata in MOP.md SI CALIFICARI.md inainte de a fi folosita. Daca exista in ambele → se foloseste; daca nu → se opreste si se intreaba utilizatorul.
[*][b]Sectiune noua - Cross-Check:[/b] Explicatia completa a ce trebuie verificat intr-un cross-check (divizii, rankuri, calificari, contradictii procedurale, consistenta TIER, chain of command) si ce trebuie sa contina un raport de cross-check.
[/list]

[size=110][b]MOP.md[/b][/size] - Capitol 5
[list]
[*][b]Sectiune noua - 5.11 Cum se Obtin Calificarile:[/b] Adaugata dupa sectiunea 5.10 (Administration). Explica procesul in 4 pasi: contactarea Division 6, verificarea eligibilitatii, parcurgerea instruirii si inregistrarea oficiala de catre Certification Officer.
[/list]

[size=110][b]MOP-PARTII.md[/b][/size] - Capitol 15 (Division 6)
[list]
[*][b]Sectiune noua - 15.05 Cum se Solicita o Calificare:[/b] Adaugata dupa sectiunea 15.04 (Programe de Training). Acelasi proces in 4 pasi, cu nota suplimentara despre recertificari periodice.
[/list]

[size=110][b]CALIFICARI.md[/b][/size]
[list]
[*][b]Sectiune noua - Cum se Obtine o Calificare:[/b] Adaugata ca divbox inaintea primei sectiuni de calificari. Rezuma procesul de 4 pasi direct in registrul de calificari, pentru acces rapid.
[/list]

[hr][/hr]

[list=none]
[size=85][color=#888888]Changelog generat automat. Orice modificare ulterioara trebuie adaugata manual la inceputul acestui document, dupa linia [hr].[/color][/size]
[/list]

[/birou]
