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
   do Rabatu +8 min. **ALE audi nie zauważył: 202 z Rabatu kończy kursy o 18:00** (MF 06:00–18:00) —
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
  najpóźniejszy sensowny **20:12/20:14** → Valletta 20:38 → 13 20:55 → Ross ~21:22
  (plan miał „ostatni ~20:09 → Ross 20:45" — za wcześnie; kolacja odpowiednio 21:15/21:45).
  Wariant „zachód nad morzem" (201 19:37): 51 20:12/20:14 → Ross ~21:22.
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
