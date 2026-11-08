# Ćwiczenie 22: Fizyczne podstawy elektrokardiografii

Źródło: F. Jaroszyk, *Biofizyka*, rozdz. 18.7.1 „Elektryczna i magnetyczna aktywność serca” (str. 644–658).

**Cel ćwiczenia:** zarejestrować EKG w odprowadzeniach Einthovena i Goldbergera, wyznaczyć wektor elektryczny serca (trójkąt Einthovena) i policzyć częstość pracy serca.

---

## 1. Potencjał elektryczny i napięcie

- **Potencjał elektryczny** V w punkcie pola to praca W potrzebna do przeniesienia ładunku próbnego q z nieskończoności (punktu odniesienia) do tego punktu, podzielona przez ten ładunek: **V = W / q**. Jednostka: wolt, 1 V = 1 J/C.
- Potencjał ładunku punktowego: V = k·Q / r, gdzie k = 1/(4πε₀).
- **Napięcie (różnica potencjałów)** między punktami A i B: **U = V_A − V_B = W_AB / q**.
- W EKG mierzy się **napięcia między punktami na skórze**, a nie potencjały bezwzględne. Rzędy wielkości to mV: załamek R ma ok. 1 mV, a kalibracja zapisu wynosi 1 mV.
- Potencjał błonowy komórki to różnica potencjałów wnętrze − zewnątrz, ΔV = V_w − V_z.

## 2. Dipol elektryczny, moment dipolowy, II prawo Kirchhoffa

- **Dipol** to dwa ładunki +q i −q o równej wartości, oddalone o l.
- **Moment dipolowy:** **p = q·l**. Jest to wektor skierowany od − do +. Jednostka: C·m.
- Pole dipola ma kształt „pętli” wychodzących z + i wchodzących do − (ryc. 18.34). Potencjał w odległym punkcie wynosi V ≈ k·p·cosθ / r² i zależy od kąta między osią dipola a kierunkiem do punktu. Z tego wynika, że **wychylenie w danym odprowadzeniu to rzut wektora dipola na oś tego odprowadzenia**.
- **Serce jako dipol:** każde pobudzone włókno to mikrodipol. Część pobudzona jest ujemna na zewnątrz (−), a część niepobudzona dodatnia (+). Suma wektorowa wszystkich mikrodipoli daje **główny wektor elektryczny serca W**, który w czasie cyklu zmienia wartość i kierunek.
- **II prawo Kirchhoffa:** suma napięć (spadków potencjału) w zamkniętym oczku obwodu wynosi 0, ΣU = 0.
  - Dla odprowadzeń Einthovena:
    (V_L − V_P) + (V_P − V_N) + (V_N − V_L) = 0, czyli **I + (−II) + III = 0**, stąd **II = I + III** (prawo Einthovena).
  - Wniosek: wystarczą dwa odprowadzenia, a trzecie jest redundantne. W klinice rejestruje się wszystkie trzy, bo redundancja poprawia czytelność.

## 3. Układ bodźcowo-przewodzący, potencjały czynnościowe

**Droga pobudzenia (ryc. 18.24):**
węzeł zatokowo-przedsionkowy (SA) → wiązki międzywęzłowe (Bachmanna, Wenckebacha, Thorela) → węzeł przedsionkowo-komorowy (AV) → pęczek Hisa (lewa i prawa odnoga) → włókna Purkinjego → mięsień komór.

- Między przedsionkami a komorami leży **tkanka łączna, czyli izolator** (zły przewodnik). Pobudzenie przechodzi na komory **tylko przez węzeł AV i pęczek Hisa**.
- Komórki mięśnia sercowego łączą się **wstawkami o małym oporze**, więc pobudzenie szybko rozchodzi się po całym myocardium.
- **Automatyzm:** komórki rozrusznikowe same, spontanicznie się depolaryzują (powolna depolaryzacja spoczynkowa, prepotencjał). Nie mają stałego potencjału spoczynkowego.
  - SA (rozrusznik I rzędu): ok. **1,2 Hz, czyli ~70/min**
  - AV i dalsze (rozruszniki II i III rzędu): coraz wolniej, we włóknach Purkinjego ok. **0,5 Hz, czyli ~30/min**
  - Narzuca rytm najszybszy ośrodek, czyli SA.

**Potencjał czynnościowy komórki kurczliwej (ryc. 18.25):**

| Faza | Co się dzieje | Jony |
|---|---|---|
| Spoczynek | ok. −90 mV | pompa Na⁺/K⁺, dyfuzja K⁺, Na⁺, Cl⁻ |
| Depolaryzacja | szybki skok do ok. +20 mV | szybki napływ **Na⁺** do komórki |
| **Plateau** | potencjał utrzymuje się ~200–300 ms | napływ **Ca²⁺** (przewodność dla Ca²⁺ rośnie) |
| Repolaryzacja | powrót do −90 mV | spada przewodność dla Ca²⁺ i Na⁺, wypływ **K⁺** |

- **Okres refrakcji bezwzględnej (RB)** jest bardzo długi i trwa prawie cały skurcz. Dzięki temu mięsień sercowy **nie może wejść w skurcz tężcowy**, a pobudzenia nie krążą wstecz.
- Fala depolaryzacji i repolaryzacji przesuwa się wzdłuż błony. Wywołuje prądy przesunięcia w błonie, prądy objętościowe wewnątrz komórki i prądy objętościowe w środowisku zewnątrzkomórkowym (ryc. 18.28). Te ostatnie dochodzą do powierzchni ciała i to je rejestruje EKG.

## 4. Wielkości fizyczne mierzone przez elektrokardiograf. Zasada działania

- **EKG** rejestruje w czasie **różnice potencjałów (napięcia, mV)** między punktami na powierzchni ciała, powstające w wyniku zmian pola elektrycznego wytwarzanego przez serce. Oś pozioma to **czas (s)**, oś pionowa to **napięcie (mV)**.
- EKG obrazuje **bioelektryczną, a nie mechaniczną** pracę serca (choć obie są powiązane, ryc. 18.33).
- **Budowa elektrokardiografu (ryc. 18.29):** elektrody → **układ przełączający** (wybór odprowadzenia) → **układ wzmacniający** (sygnał ma ~1 mV, trzeba go wzmocnić) → **układ rejestrujący** (papier lub ekran).
- Standard zapisu: **kalibracja 1 mV = 10 mm**, przesuw papieru **25 mm/s** (1 mm = 0,04 s) albo 50 mm/s (1 mm = 0,02 s).
- Przy niskich częstotliwościach pracy serca (zakres ELF) pole elektryczne E i magnetyczne H można rozpatrywać osobno. Pole E bada EKG, pole H magnetokardiografia (MKG, detektor SQUID, indukcja rzędu pT).

## 5. Zjawiska bioelektryczne serca a cechy EKG (ryc. 18.30)

Linia **izoelektryczna** to linia 0 mV, gdy w sercu nie ma różnic potencjałów: wszystko jest spolaryzowane albo wszystko zdepolaryzowane.

| Element | Odpowiada za | Czas (norma) |
|---|---|---|
| **Załamek P** | depolaryzacja przedsionków (najpierw prawego, potem lewego) | < 0,1 s |
| **Odstęp PQ** | przewodzenie przez węzeł AV i pęczek Hisa | — |
| **Odcinek/przedział PQ** | czas przejścia pobudzenia z przedsionków do komór | < 0,2 s |
| **Zespół QRS** | depolaryzacja komór (repolaryzacja przedsionków jest w nim „ukryta”) | < 0,12 s |
| **Odcinek ST** | okres szczytowego pobudzenia komór, wszystkie komórki komór zdepolaryzowane | — |
| **Załamek T** | repolaryzacja komór (wygaszanie pobudzenia) | — |
| **Załamek U** | (nie zawsze) repolaryzacja końcowych włókien układu przewodzącego | — |
| **Przedział QT** | elektryczny skurcz komór, zależy od częstości | 0,32–0,39 s przy 70/min |

- Wydłużony PQ oznacza opóźnione przewodzenie w węźle AV lub pęczku Hisa.
- Poszerzony QRS oznacza zaburzenie przewodzenia w komorach.
- QRS wyprzedza w czasie szczyt ciśnienia w komorze i aorcie. Koniec załamka T zbiega się z minimum objętości komory i maksimum fali tętna.

## 6. Odprowadzenia. Konstrukcja odprowadzeń. Trójkąt Einthovena

**Definicja odprowadzenia:** układ dwóch elektrod (lub elektrody i punktu odniesienia), między którymi mierzy się różnicę potencjałów. Oznaczenia elektrod: **PR** to prawa ręka, **LR** lewa ręka, **LN** lewa noga (prawa noga to uziemienie).

### a) Dwubiegunowe kończynowe, Einthoven

| Odprowadzenie | Elektrody | Napięcie |
|---|---|---|
| **I** | LR i PR | V_L − V_P |
| **II** | LN i PR | V_N − V_P |
| **III** | LN i LR | V_N − V_L |

Prawo Einthovena: **II = I + III**.

### b) Jednobiegunowe, Wilson

- Trzy kończyny łączy się przez **jednakowe oporniki R** we wspólny **punkt odniesienia PO** (potencjał ≈ 0, tzw. centralna końcówka).
- Elektroda badająca EP mierzy potencjał jednej kończyny względem PO, co daje odprowadzenia **VR, VL, VF**.

### c) Jednobiegunowe wzmocnione, Goldberger

- Punkt odniesienia PO tworzy się przez **zwarcie dwóch pozostałych** kończyn, bez badanej, i mierzy napięcie między PO a trzecią kończyną.
- Odprowadzenia **aVR, aVL, aVF** („a” = augmented, wzmocnione).
- **Zaleta:** amplitudy załamków są **większe** (ok. 1,5 raza) niż w metodzie Wilsona.

### Trójkąt Einthovena

- Einthoven założył, że trzy punkty kończynowe (PR, LR, LN) tworzą w przybliżeniu **trójkąt równoboczny**, a serce, czyli dipol, leży w jego środku.
- Boki trójkąta to osie odprowadzeń I, II, III, ustawione względem siebie co 60°: I = 0°, II = +60°, III = +120°.
- Wychylenie w danym odprowadzeniu to **rzut wektora elektrycznego serca na oś (bok) trójkąta**.

## 7. Wektor elektryczny serca. Jak go wyznaczyć (ryc. 18.35, 18.36)

**Wektor elektryczny serca W** to wypadkowa (suma wektorowa) momentów dipolowych wszystkich pobudzonych włókien mięśnia sercowego. W każdej chwili cyklu ma inną wartość i kierunek.

**Konstrukcja graficzna dla załamka R (metoda Einthovena):**
1. Z zapisów odprowadzeń I, II, III odczytaj amplitudę załamka R (algebraicznie, czyli R minus Q i S, z uwzględnieniem znaku).
2. Na każdym boku trójkąta odłóż od środka boku odcinek o tej długości i z odpowiednim zwrotem. Powstają wektory R_I, R_II, R_III.
3. Z końców (i początków) tych wektorów poprowadź **prostopadłe** do boków.
4. Prostopadłe z początków przecinają się w jednym punkcie, a prostopadłe z końców w drugim. **Wektor łączący te punkty to główny wektor elektryczny serca W_R.**
5. W_R w przybliżeniu pokrywa się z **anatomiczną osią serca**.

Tak samo wyznacza się W_P, W_Q, W_S, W_T. Wektor zatacza w przestrzeni pętlę, co bada **wektorkardiografia**: dodaje się dwa kolejne, prostopadłe trójkąty Einthovena.

**Rachunkowo (oś elektryczna serca, kąt α względem odprowadzenia I):**

- z odprowadzeń I i III: **tg α = (I + 2·III) / (√3 · I)**
- z odprowadzeń I i aVF: **tg α ≈ aVF / I**
- wartość wektora: W = I / cos α

**Norma osi:** od ok. **−30° do +90°** (oś pośrednia ~+30° do +70°). Poniżej −30° to odchylenie w lewo (lewogram), powyżej +90° odchylenie w prawo (prawogram).

**Szybka ocena:** jeśli QRS jest dodatni w I i w aVF (lub II), oś jest prawidłowa.

## 8. Częstość pracy serca z zapisu EKG

Mierzy się **odstęp RR** (od szczytu R do następnego R).

- **HR [1/min] = 60 / RR [s]**
- Przy przesuwie **25 mm/s**: HR = **1500 / RR [mm]**, albo HR = 300 / liczba dużych kratek (5 mm) między R.
- Przy przesuwie **50 mm/s**: HR = **3000 / RR [mm]**.
- Przy nierównym rytmie bierze się średnią z kilku odstępów RR.
- Przykład: RR = 21 mm przy 25 mm/s → RR = 0,84 s → HR = 60 / 0,84 ≈ **71/min**.

Norma: 60–100/min. Poniżej 60 to bradykardia, powyżej 100 tachykardia.

---

### Ściąga na wejściówkę

- EKG = napięcie (mV) między punktami na skórze w funkcji czasu
- Serce = zmieniający się dipol, wektor W = suma mikrodipoli
- I = V_L − V_P, II = V_N − V_P, III = V_N − V_L; **II = I + III** (z II prawa Kirchhoffa)
- Wilson: wspólny punkt przez oporniki R; Goldberger: zwarte 2 kończyny, aVR/aVL/aVF, większe amplitudy
- P = depolaryzacja przedsionków, QRS = depolaryzacja komór, T = repolaryzacja komór, U = repolaryzacja włókien Purkinjego
- PQ < 0,2 s, QRS < 0,12 s, P < 0,1 s
- SA ~70/min, Purkinje ~30/min; plateau to Ca²⁺; długa refrakcja chroni przed tężcem
- Wektor = rzuty R z I, II, III na boki trójkąta, potem prostopadłe; oś w normie od −30° do +90°
- HR = 60/RR[s] = 1500/RR[mm] (25 mm/s)
