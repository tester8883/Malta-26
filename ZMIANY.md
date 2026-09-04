# Zmiany — hotel: Vegas Resort (St Julian's, Paceville)

Wszystkie 9 plików planu przeliczonych pod nową bazę: **Vegas Resort** (3⭐, Dragonara Road, Paceville, St Julian's).

## Co się zmieniło

1. **Hotel bazowy** — usunięto porównanie 4 opcji (Argento, Orbis Boutique Studios, ddream, THE OSiRiS)
   i wszystkie wzmianki o nich (sekcja „Gdzie nocować" → „Hotel", wiersze D1–D8, notki o wydarzeniach, streszczenia).
   W ich miejsce: jedna karta hotelu **Vegas Resort** z danymi i plusami/minusami.
2. **Przystanek autobusowy** — `Qaliet` → **San Giljan – Ross** (35.92161, 14.49049, ~5 min pieszo od hotelu).
   Obsługuje: **13/14/15** (Valletta), **222** (Ċirkewwa / Comino), **X2 / TD13** (lotnisko / okolice),
   więc wszystkie trasy planu (D1–D8) działają bez zmian tras.
3. **Przeliczone czasy piesze**:
   - do przystanku Ross: **~5 min** (było ~2 min do Qaliet / ~10 min do przystanku Ferries w Sliemi);
   - do plaży St George's Bay: **~5–7 min** (460 m; było 10 min);
   - do Spinola Bay: **~8–10 min** (było „przy hotelu");
   - do Portomaso Marina: ~8 min; do terminala Sliema (The Strand): ~25–30 min (było ~25–35 min od Argento).
4. **D2/D3** — wejście na 13/14/15 z Rossu zamiast dojścia do przystanku „Ferries (Sliema)";
   **D7** — dodany dojazd 13/14/15 z Rossu do Sliemy przed autobusem 202 (wcześniej było „pieszo na Ferries").
5. **D5** — autobus 222 wsiadany/wysiadany na Ross („222 → Sliema" → „222 → St Julian's (Ross)").
6. **D1/D8** — wysiadka/meldunek przy Vegas Resort, dopisek o check-in 15:00 / check-out 10:00.
7. **plan_mapka.html** — nowe GPS hotelu (35.92441, 14.49072), przystanek Ross (35.92161, 14.49049),
   trasa D1 zaczyna się od Vegas Resort, dopisane odległości.

## Dane hotelu (źródła)

| Parametr | Wartość | Źródło |
| --- | --- | --- |
| Gwiazdki / otwarcie | ⭐3, otwarty 2025 | trip.com, hotels-mt.com |
| Ocena | 8.4/10 „Very Good" (ok. 1360 opinii; 4.6/5 na On the Beach) | hotels-mt.com, onthebeach.co.uk |
| Adres | Dragonara Road, STJ 1622 (środek Paceville) | trip.com |
| Udogodnienia | śniadanie bufetowe, basen zewnętrzny, recepcja 24 h, restauracja, bar | hotels-mt.com, onthebeach.co.uk |
| Check-in / check-out | 15:00 / 10:00 | hotels-mt.com |
| Przystanek | San Giljan – Ross, ~5 min pieszo | hotels-mt.com, moovitapp.com |
| Plaża | St George's Bay ~460 m (~5–7 min) | trip.com / współrzędne |
| Port | 10–11 km od lotniska (~20 min autem; X2/TD2 autobusem) | trip.com |

## Uwagi do weryfikacji przed wyjazdem

- **Cena ~4 400 zł / 7 nocy (od ~150 €/noc)** jest **orientacyjna** na podstawie portali rezerwacyjnych —
  sprawdź aktualną ofertę dla terminu 29.09–06.10.
- **Paceville = hałas nocny** (nowe położenie vs cichsze Spinola) — w planach dodane zalecenie
  „pokój od cichej strony / wyżej" oraz ostrzeżenie o Defected Malta 1–4.10.
- Część opinii wspomina hałas robót w okolicy (nowe inwestycje) — do sprawdzenia w recenzjach tuż przed rezerwacją.

---

# Weryfikacja audytu rozkładów (202 / 74 / 222 / Comino) — 02.09.2026

Źródła: oficjalne rozkłady Malta Public Transport (publictransport.com.mt/mt/route/202|74|222), Direct Ferries,
cominoferries.com, bluelagoon.mt, ghawdex.pl. Rozkłady MPT pobrane 02.09 — **przed wyjazdem sprawdź je
ponownie w aplikacji Tallinja** (mogą się zmienić w trakcie sezonu).

## Werdykt punkt po punkcie

1. **Bus 202 (D7) — audyt częściowo błędny.** Odjazd **09:00 z przystanku Ross ISTNIEJE** (dni powszednie:
   06:28 · 06:58 · 07:28 · 07:58 · 08:30 · 09:00 · 09:30…); z przystanku Ferries (Sliema) odjazdy to
   08:50 / 09:20 (stąd wzięła się wątpliwość). **Poprawka w planach:** 202 wsiada się **bezpośrednio na
   Ross** (bez przesiadki 13/14/15 do Sliemy) — kurs 09:00, jazda ~50–55 min. Dzień NIE wymaga przesuwania.
2. **Bus 74 (D6) — audyt błędny co do odjazdu.** Z Valletty (A5) w NIEDZIELĘ odjazd to **08:35**
   (potwierdzone: 05:35 · 06:35 · 07:35 · **08:35** · 09:35…), potem dopiero 09:35 — więc 08:35 zostaje,
   a w planie dodano ostrzeżenie „nie spóźnij się, następny 09:35". **Trafne co do przyjazdu:** na miejscu
   (Panorama) jesteś ~09:20, więc rejs przesunięto **09:15 → 09:30** (kolejne punkty D6 o ~15 min).
3. **Bus 222 (D5) — audyt częściowo błędny, ale odkrył ważniejszy problem.** Czas Ross→Ċirkewwa wg
   rozkładu to **~40–60 min** (nie ~1 h, ani nie 75–110 min) → w planach **45–70 min**.
   **Ale:** „07:15" w ogóle nie istnieje! **W sobotę 222 z Rossu: 06:39 · 07:39 · 08:40 · 09:40** (co ~60 min).
   Poprawka: wyjście 07:30, kurs **07:39**, przyjazd Ċirkewwa ~08:25–08:50, prom ~09:00–09:30.
4. **Prom Comino 3.10 — potwierdzony, ale wymaga kontroli.** Sezon: operator Comino Ferries oferuje rejsy
   także jesienią/zimą, a Direct Ferries pokazuje **codzienne rejsy w październiku 2026** (09:10–16:10,
   co 30 min). Część przewodników podaje „do września" (dot. Melliħy/Marfy). W planach dodano:
   „potwierdź rozkład na 3.10". **Częstotliwość 222 w sobotę: co ~60 min** (z Ċirkewwy w dzień co ~15–20 min).

---

# Weryfikacja audytu #2 (D3 Ta' Pinu / D7 Dingli / D8 wylot + 12 nieścisłości) — 02.09.2026

Rozkłady z oficjalnej strony MPT (publictransport.com.mt/route/…): 307, 301, 308, 201, 88, 51, 53, 13, 85.
Datą kontrolną: D3 = czw 1.10, D7 = pon 5.10, D8 = wt 6.10.

## Werdykt punkt po punkcie (błędy istotne)

1. **D3 · Ta' Pinu — audyt CZĘŚCIOWO SŁUSZNY (ale nie „niewykonalna").** 307 z Victorii do Xaghry:
   **co 60 min** (11:05 · 12:05 · 13:05 · 14:05; kursu 12:45 nie ma). Z Xaghry do Victorii: **13:32 · 14:33 · 15:33 · 16:31**.
   Ta' Pinu (308 z Victorii: 14:55 → 15:05 → powrót 15:18; zwiedzanie ~10–13 min) **da się wcisnąć TYLKO**
   w wariancie: Ġgantija do ~14:20 → 307 **14:33** → 308 **14:55** → 301 **15:30** → Mġarr 15:43 → prom 16:45.
   Wariant PEWNY: wiatrak Ta' Kola (w cenie 10 €!) + 307 **15:33** → 301 16:00 → Mġarr 16:13 → prom 16:45.
   Poprawiono też: „wyjedź z Xagħry najpóźniej 15:23" — bzdura (to nie odjazd), zastąpione realnymi godzinami.
2. **D7 · 201 w oknie 18:45–19:15 — audyt SŁUSZNY (i odkrył wiadomo, że nie tylko 201!):**
   z Dingli w pon: **15:37 · 16:37 · 17:37 · 18:37 · 19:37 · 20:37** (co 60; okna 18:45–19:15 nie ma ✓),
   do Rabatu +8 min. **ALE wtedy przyjęto (bez weryfikacji!), że 202 z Rabatu nie ma kursów wieczornych** (MF 06:00–18:00) — ⚠️ **teza obalona w audycie #5 (patrz niżej) — 202 kursuje wieczorem!**
   cały plan „20:30 → 202 → Sliema" był błędny od początku. Nowy plan: Dingli 15:45–17:25 → 201 **17:37** →
   Rabat 17:45 → wieczorna Mdina + zachód z bastionów (~18:40) → **51 (ostatni ~20:09 z Rabatu)** → Valletta
   20:15 → 13/14/15 → Ross ~20:45. Wariant „zachód nad morzem": 201 19:37 → 51 20:09 (koszt: Mdina odpada).
3. **D8 · 88 — audyt BŁĘDNY co do rozkładu, trafny w zaleceniu.** We wtorek 88 z Valletty (A9): **co 20 min**
   (08:50 · 09:10 · 09:30 · 09:50 · 10:10; przyjazd lotniska +17 min) — **nie ma 45-minutowej dziury**
   (to audyt pomylił z inną linią/dniem). Mimo to wyjście przesunięte na **08:20–08:30** i celowanie w 88 **09:30**
   → lotnisko ~09:50; awaryjnie TD2/TD3 (~3 €, ~30 min).

## Nieścisłości mniejsze — weryfikacja

| # | Temat | Werdykt |
|---|---|---|
| 1 | Ġgantija godziny | ✅ audyt: **10:00–18:00** (1.03–31.10), ost. wejście 17:30; bilet 10 € **obejmuje wiatrak Ta' Kola** — poprawione |
| 2 | Prom Three Cities | ✅ w przybliżeniu: 2,50–3 € one way / 4,50–5 € return (zależnie od operatora), nocna 3,50/5,20; rejs ~5–10 min — poprawione |
| 3 | Winda Barrakka | ✅ audyt: **zjazd darmowy, wjazd 1 €**; z return-promem gratis w obie strony; X133 istnieje — poprawione (D3/D4 + budżet 0–1 €) |
| 4 | Comino ~45 min | ✅ audyt: przeprawa **~20–25 min** — poprawione w planie transportu |
| 5 | 222 w sobotę co 30–36 min | ⚠️ **audyt BŁĘDNY** (kier. Ross→Ċirkewwa w sobotę: **co 60 min** — 06:39·07:39·08:40; co ~30 działa tylko w dni robocze i na powrocie z Ċirkewwy) — plan pozostał przy 07:39 + „co ~60 min" |
| 6 | 74 niedziela 08:45 | ⚠️ **audyt BŁĘDNY**: niedziela z Valletty A5 = **08:35** (05:35–18:35 co 60; 08:45 nie występuje) — zostaje 08:35 |
| 7 | 202 czas 70–77 min | ⚠️ **audyt BŁĘDNY**: wg rozkładu Ross(MF) 09:00 → Saqqajja **09:52** (~52 min); 70–77 min to górna granica z korkami — plan: ~50–55 min |
| 8 | Mdina→Rabat | ✅ ~10–15 min — poprawione |
| 9 | 85 z Marsaxlokk | ✅ ok (85/81 → Valletta; nie zostawać po ~17:30) — dopisek w komentarzu planu |
| 10 | Blue Grotto→Marsaxlokk | ✅ realistycznie 1–1,5 h; obiad ~13:00 — bez zmian strukturalnych |
| 11 | powrót D3 | ✅ 16:45→17:30 potwierdzone; w St Julian's ~18:15–18:30 z korkami — dopisek |
| 12 | D1 88/przesiadka | ✅ 88 ~13:15 istnieje; +5–8 min na dworcu — bez zmian (plan już ma ~14:45–15:00) |
| 13 | hotel→Ross 600–700 m | ⚠️ **audyt BŁĘDNY**: GPS hotelu (35.92441,14.49072) → Ross (35.92161,14.49049) = **~310–400 m ≈ 4–6 min** (nie 600–700 m) — plan: „~5 min"; rano z bagażem licz 7–8 min |
| 14 | Gozo return 13–14 € | ⚠️ spekulacja (promocje zmienne); plan już wspomina „promocja do ~12 €" — bez zmian |
| 15 | Defected: UNO/Café del Mar | ✅ audyt: **UNO = Ta' Qali (Attard)**, **Café del Mar = St Paul's Bay**; Fort St Elmo + The Ditch = Valletta; daty 1–4.10.2026 — poprawione |

---

# Weryfikacja audytu #3 (D3 Ta' Pinu / D7 Dingli / D8 lotnisko + drobne) — 03.09.2026

Źródła: tabelaryczne rozkłady MPT z tej strony (277/301/308, 201, 88, 51, 53, 13/14 — pobrane
03.09.2026 z publictransport.com.mt; parsowane **stop-by-stop**, kurs `time shown` **i** `time hidden`),
metcheck.com dla zachodu słońca (Valletta), dane GPS hotelu→Ross z audytu #2.

## Błędy istotne — werdykt

1. **D3 · 307 „15:17, potem 16:47" — AUDYT BŁĘDNY w godzinach (kierunek poprawy słuszny).**
   307 to pętla: Victoria :05 (06:05·07:00·08:05…17:05, co 60) → Xagħra → powrót do Victorii.
   `15:17` = przystanek **Tigrija-1957** (środek pętli po Xaghrze, kurs 15:05), nie odjazd z Xaghry;
   `16:47` **nie istnieje** w rozkładzie. Realne odjazdy z Xaghry (przystanek **Xaghra-1967**):
   **13:32 · 14:33 · 15:33 · 16:31** → Victoria 13:44/14:45/15:45/16:43 (potwierdza audyt #2).
   Rekomendacja audytu (Ta' Kola jako pewny wariant + powrót 307 + prom 16:45) — **już była
   domyślna** po audycie #2; bez zmian merytorycznych. Winda Barrakka 0 € w dół + X133 —
   również już naniesione (D3/D4 + plan transportu, także „miej monetę" usunięte z transportu).
2. **D7 · 201 po zachodzie — AUDYT SŁUSZNY w kierunku; kierunek już zrealizowany po audycje #2.**
   Dingli→Rabat (MF): **15:37 · 16:37 · 17:37 · 18:37 · 19:37 · 20:37 · 21:37** → Saqqajja +7 min;
   okna 18:45–19:15 nie ma (audyt #2 to już ustalił). „~19:30" ≈ 19:37 ✓. Planowy wariant
   domyślny = dokładnie to, co audyt rekomenduje (Dingli 15:45–17:25, 201 17:37, zachód
   z bastionów Mdiny). Nowość audytu #3: **zachód słońca 5.10 w Valletcie = 18:42**
   (nie 18:40, nie 18:50–18:55 z audytu) — skorygowane wszędzie.
3. **D8 · „dziura 45 min między 09:15 a 10:00" — AUDYT BŁĘDNY w tym punkcie, ale… nasz plan
   miał błąd, którego audyt nie zauważył.** 88 (MF) z Valletty A9: **co 20 min** (08:50 · 09:10 ·
   09:30 · 09:50 · 10:10…), żadnej dziury; kurs 09:15 nie istnieje. **ALE** audyt #2 błędnie
   przyjął czas przejazdu „+17–20 min" — z tabeli stop-by-stop wynika **~35–37 min**
   (Valletta A9 09:10 → **Airport 3 09:47**; 09:30 → 10:07; pary 1:1 × 53 kursy).
   Poprawione: cel **09:10 → ~09:47** (2 h 45 przed odlotem 12:30), zapas 09:30 → 10:07
   (2 h 20), poślizg 09:50 → 10:27 (2 h — wtedy TD2/TD3). Wyjście 08:20–08:30 bez zmian.

## Drobne nieścisłości — werdykt

| # | Twierdzenie audytu | Werdykt |
|---|---|---|
| 1 | Ġgantija otwarte 10:00, nie ~09:00 | ✅ już poprawne (10:00–18:00, ost. wejście 17:30) |
| 2 | Prom TC ~4,50 € return (plan: 5 €) | ✅ racja — ujednolicono do **2,50–3 € / 4,50–5 €** (wszystkie tabele i budżety) |
| 3 | Comino ~20–25 min, nie 45 | ✅ już poprawne (audyt #2) |
| 4 | 202 Ross→Mdina ~60–70 min, wyjdź ~08:40 | ⚠️ częściowo: wg rozkładu 09:00→09:52 (~52 min); **korki 60–70 realne** — dodano „wg rozkładu ~50–55, z korkami 60–70”; wyjście 08:40–08:55 już w planie |
| 5 | Hotel→Ross ~7–9 min, nie 5 | ⚠️ GPS: ~310–400 m ≈ 5 min; **z bagażem rano licz 8–10** — dopisane przy wyjściach |
| 6 | Powrót z Gozo realnie ~18:20 | ✅ korki — dodane „do ~18:30" (D3 + sekcja promów) |
| 7 | UNO w Ta' Qali, nie St Julian's | ✅ już poprawne (audyt #2: Ta' Qali/Attard, Café del Mar St Paul's Bay, daty 1–4.10.2026) |

## Nowe korekty wykryte przy okazji (u źródła — plan był nieprecyzyjny)

- **301 Victoria→Mġarr = ~18 min** (nie ~13): 15:30→**15:48**, 16:00→**16:18** (audyt #2 pomylił
  kolumny; zapas do promu 16:45: 55 / 25 min — oba warianty nadal bezpieczne).
- **51 z Rabatu**: wygodny **19:44** (Saqqajja) → Valletta 20:15 → **13 o 20:25 → Ross ~20:52**;
  najpóźniejszy sensowny (stan na #4) **51 ≈20:12–20:14** → Valletta 20:38 → 13 20:55 → Ross ~21:22 ⚠️ patrz aktualizacja audyt #5 (202 wieczorem)
  (plan miał „ostatni ~20:09 → Ross 20:45" — za wcześnie; kolacja odpowiednio 21:15/21:45).
  Wariant „zachód nad morzem" (201 19:37): 51 ≈20:12–20:14 → Ross ~21:22 (aktualizacja: audyt #5).
- 301 Mġarr→Victoria: ~15 min (było ~12) w planie transportu.

---

# Weryfikacja audytu #4 (Defected / Grandmaster's Palace / 9 drobnych) — 03.09.2026

Źródła: rozkłady MPT stop-by-stop (r74/r222 z dniami sb+nd, r119, r201 nd, r88 sb/nd, r13/r14 —
pobrane 03.09.2026), pełna lista tras MPT (147 tras: **X2 nie istnieje**, są TD1–TD5/TD10/TD13,
TD2+TD3 = „San Giljan"), heritagemalta.mt (strony obiektów + opening-hours + sklep REST /store/c95),
allaboutmalta.com (08.2026, taryfy promów).

## Werdykt punkt po punkcie

**2.1 Defected Malta — lokalizacje już poprawne (audyt #2), ale błędny WIĄZEK przyczynowy pozostał.**
Plan już podawał właściwe venue (UNO Ta' Qali · Fort St Elmo Valletta · Café del Mar St Paul's Bay),
lecz nadal twierdził, że „w Paceville bywa wtedy wyjątkowo głośno"/„w okolicy St Julian's może być
głośno" — **korekta zastosowana**: główne venue są POZA Paceville (możliwe klubowe after-party),
a cichy pokój zostaje z właściwego powodu (Paceville = kluby nocą).

**2.2 Grandmaster's Palace — audyt CZĘŚCIOWO BŁĘDNY, wniosek trafny.**
- ⚠️ **Sala Tronowa NADAL zamknięta** — oficjalna strona HM (explore + opening-hours):
  „will remain closed to the public **until further notice**". Audyt twierdził, że „nie ma aktualnych
  informacji o zamknięciu" — to nieprawda.
- State Rooms: otwarte codziennie; zamknięte **do 13:30 tylko 25.09 / 28.10 / 18.11 / 2.12.2026**
  (dostępna tylko Armoury) — nasz D2 (śr 30.09) **nie** koliduje.
- Wniosek audytu (warto wejść, 12 €) — **słuszny**: plan zmieniony z „→ pomiń" na „✅ można wejść
  30.09" (otwarte codziennie ~10:00–18:00, śr do ~17:00 wg części źródeł — do potwierdzenia na
  heritagemalta.mt; ostatnie wejście ~30 min przed zamknięciem).

**3.1 Multisite Pass ~50 € — AUDYT BŁĘDNY.** Oficjalny sklep HM (produkt C95, REST API):
**60 € dorosły · 45 € senior/student · 30 € dziecko**, 30 dni od pierwszego użycia. Plan (60 €,
zakres 30–60 €) — poprawny. Werdykt „nie opłaca się" nadal słuszny: zestaw planu = 42 € < 60 €.

**3.2 Rabat Combo 14 → 12 € — SŁUSZNE.** Oficjalne ceny HM: St Paul's Catacombs **6,00 €** +
Domvs Romana **6,00 €** → 12 € (bilet łączony Rabat wg źródeł też 12 €). Poprawione wszędzie;
kaskada budżetu: K **~130 → ~128 €** (i ~119 → ~117 € przy Gozo Channel; zestaw HM ≈44 → **≈42 €**,
bez Ħaġar Qim 34 → 32 €), ZR baza 124–130 → 122–128 / opcje 140–150 → 138–148, LJ 98–105 → 96–103
i 95–102 → 93–100.

**3.3 74 niedziela 08:35/09:35 — AUDYT BŁĘDNY.** Niedziela: **:35 co 60 min** (05:35 … 19:35;
08:35 → Panorama 09:13; następny 09:35). Godziny „07:40/08:40/09:40" nie istnieją. Plan bez zmian.

**3.4 222 sobota — audyt SŁUSZNY co do częstości; przy okazji wykryty REALNY BŁĄD w D5!**
Sobota z Rossu: **06:27 · 06:57 · 07:28 · 07:58 · 08:30 · 09:00 · 09:31**, od ~09:45 co ~15 min.
**Kurs 07:39 NIE ISTNIEJE** (nasz audyt #1 „potwierdził" go błędnie); plan jechał 222 o 07:39.
**Poprawione: D5 — 222 o 07:28** (→ Ċirkewwa ~08:25), zapas 07:58 (→ ~08:55); doczyszczone
wszystkie pliki (tabela 222 w planie transportu też).

**3.5 88 pn–pt/sb–nd** — potwierdzone: pn–pt co 20 (wt ✓), sb+nd co 30 ✓. Bez zmian (D8 = wtorek).

**3.6 201 Rabat→Dingli ~8 min — SŁUSZNE** (Saqqajja 14:30 → Dingli 14:37 wg tabeli). Poprawione:
~20 min → ~8 min (wszystkie pliki).

**3.7 Taryfa nocna TC 2,80/4,80 — AUDYT BŁĘDNY.** Operator (allaboutmalta 08.2026): dzień
2,50–3 € / 4,50–5 €, **noc (od 19:30) 3,50 € / 5,20 €** — plan poprawny. 2,80/4,80 to pomieszanie
z promem Sliema (dzień 1,50/2,80; noc 1,75/3,30).

**3.8 Winda Barrakka 1 €** — zgodne; plan już: zjazd 0 €, wjazd 1 €, z return-promu w cenie.

**3.9 X2 → lotnisko — SŁUSZNE i POTWIERDZONE.** X2 nie ma na liście 147 tras MPT (są X1A/X299/X300,
TD1–TD5/TD10/TD13; TD2/TD3 = „San Giljan"). Poprawione §1 (hotel: Ross — „TD2/TD3 → lotnisko"),
plan_transportu, plan_zrownowazony, plan_mapka; notki D8: „X2 przeniesiono" → „**X2 już nie
kursuje** — direct = TD2/TD3 (poza kartą, ~3 €)".

**3.10 D2 bus 08:45 — SŁUSZNE.** Realne odjazdy z Rossu (pn–pt): 13 o 08:00/08:20/08:40/09:00,
14 o 08:09/**08:29**/08:49. Poprawione: celuj w **14 o 08:29** (Valletta ~08:50) → St John's o 09:00
realne; wiersz zmieniony 08:45 → 08:40 z godzinami.

**3.11 St John's ostatnie wejście ~16:00** — zgodne (potwierdzone wcześniej).

**D6 (nota audytu)** — zweryfikowane: **119 w niedzielę = co 60 min** z lotniska (:00; Marsaxlokk
~:27, przystanki Lucjan/Xerriex), łańcuch **201 (Wied 12:15 → lotnisko 12:28) → 119 (13:00 →
~13:27)** działa. Dodatkowo w planie: opcja **TD10** — w niedzielę Valletta A6 → Marsaxlokk
co ~10 min (09:15–16:35), +3 € poza kartą.

## Bonus — zweryfikowane ceny obiektów (oficjalne strony HM 03.09.2026)
Ġgantija **10 €** · Fort St Angelo **10,00 €** · Ħaġar Qim/Mnajdra **10,00 €** · katakumby **6,00 €** ·
Domvs **6,00 €** · Grandmaster's Palace **12 €** (60+ 10 €, dzieci 8 €, ostatnie wejście ~30 min przed
zamknięciem). Poradnik malta-spirit (Ġgantija 12 / St Angelo 12 / Ħaġar Qim 15 / combo 12) —
**błędny** co do pojedynczych cen (combo 12 € — zgadza się).

## Zmiany plików (9 plików; MD+HTML)
D5 (222 07:28), D2 (bus 08:29/08:40, Pałac), D6 (119/TD10), §1/X2, Rabat Combo 12 € + budżety,
201 ~8 min, Defected — łącznie 89 podstawień z asercjami (0 problemów).

---

# KOREKTA (14.09 wg informacji użytkownika + weryfikacja): Winda Barrakka — płatna w każdą stronę

**Werdykt #3.8 z audytu #4 („winda: w dół 0 €, wjazd 1 € — zgodne") oraz pkt 3 z audytu #2
(„zjazd darmowy") — WYCOFANE.** Użytkownik słusznie wskazał, że od jakiegoś czasu przejazd
windą jest płatny w **każdą stronę**.

Weryfikacja (03.09.2026): oficjalna strona operatora (vallettaferryservices.com) podaje ceny
tylko promów (dzień 3,00/5,00 €; noc od 19:30 3,50/5,20 €); aktualne ceny windy potwierdzają
recenzje i przewodniki 2026:
- **recenzje XI 2025 – VII 2026 (TripAdvisor):** „€1 **round trip**", „1 euro **both ways**",
  „bilet powrotny ważny tego samego dnia, **gotówka**", „€1 per person return (cash)";
- freemalta.com (2026): single **1,00 €** / return **1,50 €**;
- darmowy zjazd w dół (stara zasada „down free, up 1 €", wciąż powtarzana przez przestarzałe
  serwisy typu busatlas/travel) — **już nie obowiązuje**.

**Stan przyjęty w planach:** winda Barrakka = **1 € za bilet powrotny** (góra i dół, ten sam
dzień, gotówka) — płatna w każdą stronę; **z biletem return promu Valletta Ferry Services —
w cenie** (bez zmian); alternatywy bez zmian: darmowy **X133** z dworca (stanowisko A1,
zsynchronizowany z promami) lub ~10 min pieszo. Rozbieżność single 1 € / return 1,50 € przy
drobnicach — na miejscu kupić „return" (1 €).

Zmiany: 21 podstawień w 8 plikach (MD+HTML; plan_mapka bez windy — bez zmian); budżet
„0–1 €" → **„1–2 €"** (D3 i D4; w D4 gratis z return-promu). Nie dotyczy: ZMIANY.md (dziennik),
ta sekcja.


# Weryfikacja audytu #5 (11 drobnych + 4 ryzyka) — 03.09.2026

Weryfikacja u źródła: rozkłady MPT stop-by-stop (stan 03.09.2026: r202, r307, r308), gozohighspeed.com
(schedule + fares), stjohnscocathedral.com/visit, publictransport.com.mt (terms & conditions Explore).

## Werdykt: 7 poprawek trafnych, 4 błędne (odrzucone), 1 częściowo (dopisek)

| # | Zarzut audytu | Werdykt |
| --- | --- | --- |
| 1 | „202 z Rabatu nie ma kursów wieczornych — powrót 51" | ⚠️ **BŁĄD (nasz, z audytów #2/#3!)** — 202 MA kursy wieczorne: z Saqqajja **19:01/20:01/21:01** (pn–pt+sb/nd) → Ross ~20:01/20:52/21:52; kier. Sliema→Rabat do 23:25. Przyczyna: parser w #2 łapał tylko klasy `time hidden`, a wieczorne kursy 202 są `time shown`. **Plan przepisany: powrót z D7 = 202 o 20:01 bez przesiadki** (Saqqajja 19:01/20:01/21:01 → Ross ~20:01/20:52/21:52; 19:01 przy wcześniejszym wyjściu, 21:01 zapas); **51 19:44 zachowany jako alternatywa** (wyjście z murów ~19:30). |
| 2 | „307 Xaghra ~:23" | ❌ **odrzucone** — :23 to przystanek Massar; Xaghra-1967: **13:32/14:33/15:33/16:31** (plan OK) |
| 3 | „308 — powrót tym samym kursem może nie działać" | ❌ **odrzucone** — 308 to pętla jednokierunkowa: Victoria 14:55 → Ta' Pinu 15:05 → **Victoria 15:18** (ten sam autobus). Wniosek odwrotny: **Ta' Pinu PORZUCONE** (autobus zawraca od razu, zwiedzanie przy promie 16:45 niewykonalne — następny powrót 16:18 = przegapienie promu) |
| 4 | „katakumby 10 €" | ✅ **trafne** — oficjalnie **6 €** (jak Domus Romana); poprawione we wszystkich wierszach D7 + budżety/plan_mapka |
| 5 | „Explore: 7 dni — D8 rano nie objęty" | ✅ **trafne** — oficjalnie „7 consecutive days"; licznik = **dni kalendarzowe**. **Rozwiązanie: aktywacja karty dopiero D2 (30.09)** → pokrywa D2–D8 (do 06.10); D1 = TD2 (3 €, poza kartą). Pozostałe warianty opisane w notce |
| 6 | „Gozo Highspeed — wieczorem 21:45/22:45/23:45 codzienne" | ✅ **trafne** — potwierdzone (19.06–31.10: **Daily**); dodatkowo **00:45 pt–nd**; poprawione w 4 planach + transport + HTML |
| 7 | „St John's otwarcie 09:00" | ✅ **trafne** (plan już miał 09:00); **nowość: muzeum katedralne zamknięte (remont/rozbudowa)** — dopisane |
| 8 | „Gozo powrót 9,50–13 €" | ❌ **odrzucone** — oficjalne taryfy: Valletta⇄Gozo **7,50 €/jedna** (studenci 4,50; seniorzy 3,00); Sliema⇄Gozo 8,50 (Tallinja 6,50); Buġibba⇄Gozo 6,50; **brak rabatu powrotnego**. Plan ~15 € w obie zostaje |
| 9 | „Heritage ~50 € / Fort 12 €" | ❌ **odrzucone** — jak w #4: **60 € / 10 €** |
| 10 | „restauracje — sprawdź" | ➖ bez zmian (plan traktuje opisowo; brak checklisty „tuż przed wyjazdem" — wnioski w rozdziale „przed wyjazdem") |
| 11 | „dni tygodnia: pon–Mdina, śr–St John's, pon–katakumby, cichy pokój" | ➖ **bez zmian** — wszystko się zgadza (05.10 = poniedziałek ✓, 30.09 = środa ✓, pokój cichy już w planie) |

## Ryzyka → rozstrzygnięcia

- **Explore 7 dni vs D8** — patrz pkt 5: aktywacja 30.09; D1 = TD2.
- **D6 201 → lotnisko → 119 „zagmatwane"** — wariant działa (201 z Wied 12:15 → lotnisko 12:28 → 119 13:00 → Marsaxlokk ~13:27; 119 nd co 60 potwierdzony). Dodany tylko dopisek: **na Panoramę/Wied wsiadaj w 201 w stronę Luqa/lotniska** (w stronę Rabatu jedzie w przeciwnym kierunku).
- **Defected / Notte Bianca** — bez zmian (ustalenia #4: venue = UNO Ta' Qali / Fort St Elmo / Café del Mar).
- **Zachód 5.10 = 18:42** — bez zmian (metcheck).

## Czego NIE ruszono (potwierdzone wcześniej)

Ceny Gozo Highspeed 7,50 €/jedna (plan „~15 € w obie" ✓), St John's = katedra + Caravaggio dostępne
(muzeum w remoncie — wpisana uwaga), 51 19:44 zostaje jako awaryjny, D3 wraca promem 16:45
(wieczorne kursy Gozo bez wpływu na ten plan).

## Zmiany: 10 plików (4 plany MD + ZMIANY.md + 4 HTML + plan_mapka.html), 147/102 linii — pełne greppowanie

Kluczowe: teza o końcu kursów 202 (rzekome 18:00) → realne 19:01/20:01/21:01; wzorce „data wygaśnięcia
karty (~06.10/~13:00)" → start 30.09 (7 dni kalendarzowych); „10 €" (katakumby) → 6 €; „ostatnie kursy
wieczorne" → 21:45/22:45/23:45 codziennie 19.06–31.10 (+00:45 pt–nd);
Ta' Pinu → PORZUĆ (pętla 308); dopiski: muzeum katedralne (remont), kierunek 201 na D6.
Stare wzorce w planach: **grep = 0**.


# Weryfikacja audytu #5b (powtórzenie zarzutów, 04.09.2026)

Audyt #5b pokrywa się w ~90% z audytem #5 — jego zalecenia odnoszą się do stanu planu
SPRZED commita `b6a22d3` (dotyczy to m.in. „wiersz D7 10 €", „plan wraca 51 o 19:44",
„ostatni 20:45 i rzadki kurs ok. 22:00 (pt–sb)", „oszczędzasz ~6,5 € przy aktywacji w D1").
Poniżej status każdej pozycji po weryfikacji u źródła (MPT 03.09.2026 + strony oficjalne).

## Pozycje „DO KOREKTY"

| Pozycja | Werdykt | Uzasadnienie / działanie |
| --- | --- | --- |
| „202 nie ma kursów po 18:00", zalecenie „zachowaj powrót 51" | ✅ trafna obserwacja, ⚠️ zalecenie już przestarzałe | 202 MA kursy wieczorne (Saqqajja **19:01/20:01/21:01** → Ross ~20:01/20:52/21:52 — potwierdzone ponownie parserem MPT 03.09.2026). **W `b6a22d3` powrót D7 przepisany na 202 o 20:01 (bez przesiadki); 51 19:44 zostaje jako alternatywa** — czyli dokładnie odwrotnie niż sugeruje audyt, ale lepiej: ta sama godzina przyjazdu (Ross ~20:52) bez przesiadki. Weryfikacja wieczornych kursów 202/51 w Tallinja → dopisana do notki D7 i listy kontrolnej |
| St John's 09:00 vs 09:30 | ❌ 09:30 niepotwierdzone | Oficjalna strona (stjohnscocathedral.com/visit, 08.2026): **pon–sob 09:00–16:45**, ost. wejście 16:00; muzeum katedralne w remoncie. Plan ma 09:00; wskazówka audytu (sprawdź na stronie) → dopisana do listy kontrolnej |
| Katakumby „10 € w wierszu D7" | ✅ ale już poprawione | W `b6a22d3`: wszystkie wiersze D7 + plan_mapka = **6 €** (zgodnie z §5/§9 i budżetem) |
| 307 „odjazdy z Xaghry ~:23" | ❌ odrzucone | Rozkład (potwierdzony ponownie): Xaghra-1967 **13:32/14:33/15:33/16:31**; ~:23 to przystanek Massar-1965. Plan poprawny; weryfikacja w Tallinja → dopisana do listy kontrolnej |
| 308 „trasa jednokierunkowa, powrót może nie działać" | ⚠️ częściowo — już rozstrzygnięte, wniosek odwrotny niż audyt | 308 to pętla (Victoria **14:55** → Ta' Pinu **15:05** → Victoria **15:18**, ten sam autobus) — powrót działa, ALE autobus zawraca od razu, więc **zwiedzanie Ta' Pinu przy promie 16:45 jest niewykonalne → Ta' Pinu PORZUĆ** (w `b6a22d3`) |
| Wieczorne Gozo Highspeed | ✅ już poprawione | Potwierdzone: **21:45/22:45/23:45 codziennie 19.06–31.10** (+00:45 pt–nd); usunięte przestarzałe opisy ostatnich kursów wieczornych (w `b6a22d3`) |
| Heritage „Fort 12 € / Multisite ~50 €" | ❌ odrzucone | Oficjalnie (heritagemalta: 60 € Multisite 7 dni; Fort St Angelo **10 €**) — 12 € dotyczy **Pałacu Wielkiego Mistrza**, którego audyt myli z Fortem. Jak w `0fc2a5d` i `b6a22d3` |
| Explore a „Airport Direct" | ✅ już uwzględnione | Plan już od dawna: **TD/TD2/TD3 poza kartą (+3 €)**; §9 ostrzega o niespójności stron MPT; lista kontrolna → dopisane „potwierdź przy zakupie" |
| Restauracje (Fontanella, Ta' Rikardu, Liska) | ➖ orientacyjnie | §5a traktuje je opisowo; lista kontrolna → nowy wiersz „potwierdź godziny dzień wcześniej" |
| „Powrotne Gozo 9,50–13 €" | ❌ odrzucone | Oficjalne taryfy: **7,50 €/jedna** Valletta⇄Gozo (brak rabatu powrotnego; 8,50 przez Sliema, 6,50 z Tallinja). Kwota 9,50–13 € niepotwierdzona żadnym źródłem. Plan ~15 € w obie jest konserwatywny; lista kontrolna → „potwierdź finalną kwotę w checkoutcie" |

## Ryzyka

1. **Explore vs D8** — audyt zaleca: aktywacja D1 + płatne single na D8 („skreśl oszczędzasz ~6,5 €").
   **Rozwiązane LEPIEJ niż zalecenie:** aktywacja przesunięta na **30.09 (D2)** → karta pokrywa
   D2–D8 (do 06.10 włącznie), D1 = **TD2 (3 €, poza kartą)**. Notka „oszczędzasz ~6,5 €"
   już skreślona (obecnie ~3,5 €), single na D8 zbędne. (Dni: 29.09+7 kalendarzowych = do
   końca 05.10; start 30.09 → do końca 06.10 ✓.)
2. **D6 „201 → lotnisko → 119"** — audyt: „pewniejsze 74 → Valletta → 81/85; przez lotnisko tylko
   awaryjnie". Zweryfikowane w #4: 201 z Wied 12:15 → lotnisko 12:28 → 119 nd 13:00 →
   Marsaxlokk ~13:27 **działa i jest szybsze** (74 → Valletta → 81/85 to ~14:17+); oba warianty
   są w planie. W `b6a22d3` dodane ostrzeżenie o kierunku (201 w stronę **Luqa/lotniska** — to
   pokrywa realne ryzyko, które audyt słusznie zauważył). **Plan bazowy bez zmian.**
3. **Dni tygodnia** — potwierdzone bez zmian (md 05.10 = pon, St John's 30.09 = śr, katakumby pon;
   „nie zmieniaj Mdiny na niedzielę" — plan i tak tego nie robi).

## Co dodano w tej rundzie (poza `b6a22d3`)

- Lista kontrolna §9 (plan_kompletny.md + Plan_kompletny.html): wiersz **D3/D7 — weryfikacja
  307/202/51 w Tallinja**; wiersz **restauracje — potwierdź godziny**; dopiski do wierszy
  St John's (09:00 na stronie), Heritage (ceny na heritagemalta.mt), Gozo (kwota w checkoutcie),
  Explore (nie aktywuj w D1; TD poza kartą).
- Notka D7 (4 plany + 3 HTML): „sprawdź 201" → „sprawdź 201 oraz wieczorne kursy **202**
  (19:01/20:01/21:01) i awaryjną **51** (19:44/20:14)".
- Powtórne parsowanie u źródła (MPT 03.09.2026) dla raportu: 202, 307, 308 — wyniki zgodne
  z `b6a22d3`.

**Zmiany: 16 podstawień (2 MD + 4 HTML). Stare wzorce: grep = 0.**


# Decyzja: aktywacja Explore od razu (D1, 29.09) + TD2 na lotnisko w D8 — 04.09.2026

**Pytanie użytkownika:** „aktywować kartę D1 czy D2? w D1 nie ma co się spieszyć (check-in od 15:00) —
czy lepiej wrócić TD2/TD3 w D8 i dłużej pospać?"

## Werdykt: aktywacja w D1 (sugestia użytkownika przyjęta — słuszna)

| Kryterium | Wariant A: start D1 (29.09) | Wariant B: start D2 (30.09) |
| --- | --- | --- |
| Koszt | TD2 w D8: **3 €** | TD2 w D1: **3 €** |
| D1 | 88 + 13/14/15 na karcie (przesiadka w Valletcie — bez pośpiechu, check-in 15:00) | TD2 prosto (3 €) |
| D8 | **wyjście 09:00–09:05**, TD2 09:24 → **lotnisko ~10:02** (2 h 28 min przed), **zero przesiadki** | wyjście 08:20–08:30, 13/14/15 + 88 → lotnisko ~09:47 (przesiadka w Valletcie) |
| Sen w D8 | **~50 min dłużej** (śniadanie spokojnie, check-out do 10:00) | krócej |

**Koszt identyczny** (~3 € za TD2 i tak gdzieś płacisz), więc decyduje komfort: D8 = ostatni dzień,
liczy się sen i pewność — **TD2 jedzie bez przesiadki prosto z przystanku przy Rossie**.

## Potwierdzenie u źródła (MPT 03.09.2026, świeże pobranie stron TD2/TD3)

- **TD2 i TD3 to obie linie „San Giljan"** (Airport Direct z okolicy hotelu — pętla lotnisko→St Julian's→lotnisko).
- **TD2** — przystanek San Giljan: pn–pt **08:24 · 08:54 · 09:24 · 09:54 · 10:24** (co 30 min);
  lotnisko (Airport 3) **+38 min**: 09:24 → **~10:02**, 09:54 → ~10:32. (TD2 z lotniska do St Julian's
  działa analogicznie — w D1 niepotrzebny przy starcie karty.)
- **TD3** — San Giljan: 09:15 · 09:45 → lotnisko ~10:00 / ~10:30 (+45 min; wolniejsza, ale to zapas).
- W D8 awaryjnie: TD2 09:54 (→10:32, 2 h przed) lub single 13/14/15 + 88 (~4 €, wyjście 08:20).

## Zmiany

59 podstawień w 8 plikach (4 MD + 4 HTML): wiersze D1 (12:45/13:15) wracają na „kup + pierwsze
przyłożenie na 88 = start 29.09"; D8 przepisany na **TD2 09:24 → lotnisko ~10:02** (3 €, poza kartą)
z zapasami (09:54 / TD3 09:45 / single) i adnotacją „karta wygasła 05.10 — celowo"; tytuły D8
(„Wylot TD2 · karta do 05.10"); sekcje biletów i budżety („D1–D7; D8: TD2 +3 €", 25 € bez zmiany
— TD2 z istniejącego bufora Airport Direct); notka §2 z tabelą decyzyjną; checklista §9.
Stare wzorce wariantu B („nie aktywuj", „start 30.09", „D2–D8") w planach: **grep = 0**.

---

# Audyt #6 — historia zmian `Plan_kompletny.html` + weryfikacja u źródła (MPT 04.09.2026)

**Zakres:** prześledzenie 9 commitów pliku (d9ffb44 → 95dc35b), pełna lektura, weryfikacja rozkładów
TD2/TD3/301 (publictransport.com.mt), współrzędnych (OSM) i godzin otwarcia restauracji z planu.
Werdykt użytkownika: 12/13 zarzutów trafnych, 1 odrzucony (budżet ~128 € — poprawne zaokrąglenie
127,50–129 €), Barrakka (1 € bilet powrotny, płatna w obie strony) — potwierdzona, bez zmian.

## Uzupełnienie dziennika: commit `95dc35b` (04.09, „zmiany v6”)

Nie miał wpisu w ZMIANY.md. Zawartość: **Ta' Pinu wraca jako OPCJA** (nie „porzucone” jak w audycie #5):
wariant z późniejszym promem (308 14:55 → Ta' Pinu 15:05, następny 308 16:05 → Victoria 16:18 →
301 → Mġarr ~16:48 → prom 17:15 do Sliemy lub 17:45 do Valletty); **15:33 = wariant PEWNY**
(307 15:33 → Victoria 15:45 → 301 16:00 → Mġarr 16:18 → prom 16:45); wiersz D8 przepisany na TD2;
tabela „Układ dni” D8: „13/14/15 → 88” → „TD2 → lotnisko (3 €, poza kartą)”.

## Błąd istotny: TD2 NIE zatrzymuje się na przystanku San Giljan – Ross (1038)

Rozkład TD2 (Airport – St Julian's – Airport, co 30 min): … Miller 6403 → **San Giljan 923** →
Pembroke P&R 3547 → Ganado 2033 → **Paceville 2034 → Dragonara 2035 → Spinola 1039** → Miller 6402 →
Avjazzjoni 283 → **Airport 3 (2552)**. Rossa (1038/926) na trasie **nie ma**. „09:24” z planu to odjazd
z San Giljan 923 (Balluta/Spinola Rd, ~350 m od hotelu).

Najbliższy przystanek TD2 dla Vegas Resort (Dragonara Road): **Paceville – Dragonara 2035**
(35.92521, 14.49132; OSM) — **~100 m od hotelu**. Odjazdy pn–pt: 09:04 · **09:34** · 10:04
(Airport 3: 09:32 · **10:02** · 10:32; jazda ~28 min). Sobota/niedziela niemal identyczne.
**TD3** (co 30 min) staje na **San Giljan 1037** (sąsiad Rossa, 35.92233, 14.48770): 09:15 → ~10:00,
09:45 → ~10:30 — zostaje jako zapas „sprzed Rossa”.

**Zmiana we wszystkich planach (4 MD + 4 HTML + plan_mapka):** D8 = wyjście 09:15–09:20 → Dragonara
→ **TD2 09:34 → lotnisko ~10:02** (2 h 28 min przed odlotem); zapas TD2 10:04 → ~10:32 lub TD3 z San
Giljan 09:45 → ~10:30; single 13/14/15+88 bez zmian. Sekcje hotelu/biletów/checklisty: „TD2 staje przy
Rossie” → „TD2 z Dragonary ~100 m od hotelu (nie staje na Rossie)”. plan_mapka: nowy wiersz przystanku
Dragonara (2035) i korekta wiersza Ross (bez TD2/TD3).

## Pozostałe poprawki (Plan_kompletny.html + plan_kompletny.md)

| # | Było | Jest | Uwaga |
| --- | --- | --- | --- |
| 1 | nagłówek: „Explore pokrywa wszystkie autobusy D1–D8” | „D1–D7 (do 05.10); D8: TD2 3 €” | md miał już poprawnie |
| 2 | hotel: 13/14/15 „D2/D3/D4/D8”, TD2/TD3 „D1/D8” | 13/14/15 D2/D3/D4/D6 · 222 D5 · 202 D7 · TD2 D8 z Dragonary | D1 = 88, D8 = TD2 |
| 3 | D2: „08:35 do przystanku” + „celuj w 14 o 08:29” | wyjście **08:15–08:20**, wiersz busa **08:29** | logika godzin |
| 4 | D5: „07:30 wyjście” przed „07:28 autobus 222” | wyjście **07:15** (na przystanku ~07:20) | j.w. |
| 5 | D5/D7: „z bagażem ~8–10 min” | usunięte | dni bez bagażu |
| 6 | D3: „301 → Victoria (~12 min, co ~30 min)”; §7 „301/307/308 co ~60 min” | 301 **co ~15 min, ~15 min jazdy**; §7: 307/308 co 60, 301 co 15 | rozkład 301 (MPT) |
| 7 | D3 notka: „hotel → pokład ~60–70 min” | ~80 min (07:25 → 08:45) | zgodnie z tabelą |
| 8 | D3: wiersze „307 14:33/15:33” i „OPCJA Ta' Pinu” bez `</tr>` i komórki Mapa | domknięte; Mapa Ta' Pinu w wierszu opcji | HTML z 95dc35b |
| 9 | D3: link „Mapa” przy Ta' Kola → współrzędne Ta' Pinu (36.06154, 14.21597) | **Ta' Kola 36.04980, 14.26675** (+ wiersz w plan_mapka) | 5 km różnicy |
| 10 | D7: link „Mapa” przy Rossie → 35.91, 14.501 | Ross 35.92161, 14.49049 | ~2 km różnicy |
| 11 | D4 alternatywy: „Fort St Angelo (12 €)” | 10 € | 12 € = Pałac |
| 12 | §8: „TD… do wszystkiego w planie dojedziesz bez nich” | „w planie tylko TD2 na lotnisko w D8” | nieaktualne po TD2 |
| 13 | cele powrotów „→ Sliema” (D2/D3/D4/D6), „z Sliemy” (§9 Gozo) | „→ St Julian's (Ross)”, „z St Julian's” | opisy trasy „Sliema → Valletta” zostają |
| 14 | „Xaghra” ×3/×4 | „Xagħra” | pisownia |
| 15 | §5: „Klify Dingli (zachód słońca)”, „targ rybny ⭐” bez zastrzeżenia | dopiski zgodne z D6/D7 (zachód z Mdiny; targ po 12:45 zwinięty) | spójność z planem |
| 16 | D7 tytuł „zachód słońca NAD MORZEM na klifach Dingli” | „klify Dingli (po południu) → zachód z bastionów Mdiny” | tytuł vs treść |
| 17 | §9: brak kropki przed „Awaryjnie” | kropka | literówka |

**Bez zmian (świadomie):** budżet „~128 €” (127,50–129 €); Barrakka 1 € bilet powrotny w obie strony;
link „Mapa” w D1 (wiersz 88 → pin na Rossie = konwencja „mapa = cel wiersza”); opisy „13/14/15
Sliema → Valletta” (linia faktycznie jedzie przez Sliemę).

**Sprawdzone i OK:** dni tygodnia (29.09.2026 = wt; czw Gozo, pt Birgu, sob Comino + Notte Bianca 3.10,
nd Marsaxlokk, pon Mdina); restauracje z planu otwarte w zaplanowane dni (Café Riche pt 09:00–15:30 i
19:30–22:30, czw nieczynne; Il-Girbi pt 07:30–21:00, pon nieczynne; Ta' Ċetta czw 08:00–23:00).

**Przy okazji:** Plan_lajtowy.html (2 wiersze) i Plan_zrownowazony.html (3 wiersze) miały ten sam
brak `</tr>` w tabeli D3 — domknięte. Plan_transportu: wiersz „Hotel → Ross” bez „TD2/TD3 → lotnisko”.

**Zmiany: 9 plików planu + ZMIANY.md. Stare wzorce („przy Rossie”, „09:24 →”, „09:54 → ~10:32”,
„D2/D3/D4/D8”, „Fort St Angelo (12”, „z bagażem” w kompletnym, „35.91,14.501”): grep = 0.**
