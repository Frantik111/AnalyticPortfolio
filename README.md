# AnalyticPortfolio
Projekty zamerané na analýzu údajov, sú súčasťou mojej práce v SKY Carpet Slovakia s.r.o.

## Python + Pandas + JupiterStudio - Data Cleaning
- Čistenie kontaktných údajov z fakturačného systému
  - Odstránenie duplicít, prázdnych znakov
  - Korekcia názov (kapitalizácia)
  - Korekcia PSČ, Tel č., Email
  - Údaje sú vstupom pre Interný systém, ktorý programujem v Django (Python)

  
## Excel - Biznisová analýza obchodu s luxusnými kobercami
- Podiel segmentov na odbyte (Čo mi vytvára obrat - na ktorý segment kobercov sa sústrediť)
  - Triedenie produktov podľa segmentu
  - Podrobná analýza pokladničnej evidencie na ročnej báze
  - Identifikácia najúspešnejších produktov (ks, obrat, marža)
  - Identifikácia podielu jednotlivých segmentov na obrate
  - Zo získaných informácií som pripravil odporúčania pre konateľa, ktoré segmenty podporiť v rozvoji a ktoré utlmiť / odstrániť
- Preverenie úspešnosti / korekcia pravidiel služby
  - Firma ponúka možnosť si zapožičať koberec pred zakúpením (odstraňuje bariéry v nákupe)
  - Vyhodnotenie štatistiky zapožičania, ktoré následne konvertujú na predaj
  - Z údajov som identifikoval 3 cenové hladiny a správanie klienta,
  každá cenová hladina mala odlišné správanie / konverziu
  - Zo získaných informácií som pripravil odporúčania na úpravu pravidiel služieb
- Monitorovanie KPI výkonnosť predajcov
  - Podrobná analýza výkonnosti predajcov (10 rokov)
  - Vizuálna prezentácia, obzvlášť sa osvedčil Kumulatívny graf, keďže v porovnaní bolo vidieť výchylku vo výkonnosti jednotlivých predajcov
  - Identifikácia opakujúcich sa schém v oslabeného výkonu, ktoré vyústili v pohovor so zamestnancom
- Monitorovanie KPI výkonnosť jednotlivých predajní
  - Hrubá ako aj podrobná analýza jednotlivých predajní
  - Na základe pomeru nákladov a výkonu bola ukončená jedna z predajní
- Štatistika výkonnosti klientov a ich nákupného správania
  - Pre získanie informácií som spároval pokladňu, fakturačný systém, databázu klientov
  - Identifikácia najvýkonnejších klientov
  - Identifikácia opakujúcich sa nákupov
  - Identifikácia preferencie štýlu kobercov moderné, klasické, neutrálne
  - Identifikácia zliav poskytnutých klientom
  - V databáze je možné pozrieť históriu nákupu každého klienta
  - Podľa zistených informácií bol vytvorený zoznam pre aktívne oslovenie pomocou marketingových nástrojov (FB, Googe ADS, poštová zásielka, telefonický kontakt)


## Google Search Console / Google Looker
- Analýza návštevnosti webstránky
  - Identifikácia trendov sezónneho tovaru
  - Analýza SEO stratégie

  
## Iné
- Analýza cenotvorby konkurencie
  - Manuálna rešerš od stola / in-situ
  - Dodávateľská optika
  - Získanie údajov z marketingových nástrojov (Google ADS/Merchant Center)
  - Vzájomné porovnanie metód a vytvorenie odporúčania na úpravu stratégie predaja
- Hodnotenie investičného potencionálu novej pobočky / sťahovanie
  - Zber údajov spojené s lokalitou, prieskum trhu, hodnotenie nájomných podmienok
  - Predzmluvné rokovania
- Hodnota za peniaz
  - Kontinuálna stratégia hodnotenia čo dostanem za daný peniaz
  - Identifikácia možných optimalizácií
  - Identifikácia výkonnosti potencionálnych investícií

  
## Work in progress
- Analýza predajnosti produktov u dodávateľov
  - Pracujem na projekte v pythone + SQL + pandas, ktorý spracováva dodávateľské feedy
  - Na základe úbytku (nutná korekcia o prírastky)
  - Identifikácia najvýkonnejších produktov
  - Historický pohľad, predikcia predaja (aj sezóna), predikcia ďalšieho naskladnenia
  - Hodnotenie sily trhu podľa intenzity predaja
  - Identifikácia podielu našej sily u jednotlivých dodávateľov
