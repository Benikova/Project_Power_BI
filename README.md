# zuzi_b /Discord/

# Project_Power_BI

V predchádzajúcich projektoch (Engeto - Projekt SQL: Dostupnosť základných potravín širokej verejnosti). Som cez SQL dotazy zodpovedala na požadované výskumné otázky, ktorými som porovnala dostupnosť potravín, prostredníctvom cien a priemerných príjmov za sledované časové obdobie v ČR a ostatných európskych krajinách. Následne som niektoré spracovala a vizualizovala prostredníctvom programu Power BI.

Zadání projektu:
Zpracovaní a vizualizace dat o mzdách a cenách potravin v ČR a jejích vývoj v letech 2000 – 2020. Porovnaní procentuálního meziročního nárůstu HDP, cen a mezd v letech 2003 – 2018.


**Vývoj průměrné hrubé mzdy za jednotlivá odvětví v ČR za období 2000 – 2020.**
Priemerná hrubá mzda v ČR v období 2000 - 2020 takmer kontinuálne rastie. 
Najnižšia hrubá mzda v roku 2000 bola v odvetví Ubytovanie, stravovanie a pohostinstvo vo výške 6 698 Kč, v tomto roku najvyššiu priemernú mzdu mali v odvetví Peňažníctvo a poisťovníctvo vo výške 28 289 Kč. Priemerná hrubá mzda bola zaznamenaná vo výške 13 709 Kč. 
V roku 2010 bola stále najnižšia mzda v odvetví Ubytovanie, stravovanie a pohostinstvo vo výške 12 139 Kč a najvyššia 51 418 Kč v Peňažníctvo a poisťovníctvo. Priemerná mzda v hospodárstve je tvorená vo výške 25 072 Kč.
V roku 2015 sa trend mení a najvyššiu priemernú mzdu dostávajú v odvetví Informačné a komunikačné činnosti, na chvoste hospodárstva sa nič nemení. 
V roku 2020 trend vývoja pokračuje a najnižšiu priemernú mzdu tvorí Ubytovanie, stravovanie a pohostinstvo vo výške 16 694 Kč. Najvyššiu Informačné a komunikačné činnosti až vo výške 64 493 Kč. V tomto období priemerná mzda v ČR už činí 35 699 Kč. 
 
Spracovaním dát z dátovej sady czechia_payroll a s ňou prepojených dát som prostredníctvom spojnicového a skupinovo stĺpcového grafu zobrazila priemernú hrubú mzdu v jednotlivých odvetviach. Prostredníctvom plošného grafu som zobrazila vývoj priemernej hrubej mzdy a tiež najnižšiu (priemernú) hrubú mzdu a najvyššiu (priemernú) hrubú mzdu. Filtrácia dát je možná prostredníctvom prierezu odvetvia na 19 odvetví a časovej hierarchie na roky a štvrťroky



**Vývoj průměrné ceny potravin v ČR za období 2006 – 2018.**
Počas sledovaného obdobia 2006 – 2018 priemerné ceny vybraných potravín v ČR rastú. Ich takmer kontinuálny rast prerušuje rok 2009, kde nastal najprudší pokles priemerných cien, až o 6,81% oproti roku 2008. 
Najvýraznejší pokles zaznamenávame pri cene Pečiva pšeničného bieleho až 29% a Pšeničnej múky hladkej 23%. V nasledujúcich rokoch ceny opäť rastú. Ďalšie výrazné kolísanie cien zaznamenávame pri Konzumných zemiakoch 1 kg, v roku 2012 klesli o 22%, v 2013 narástli o 60% a 2014 opäť klesajú o 20%. Za zmienku stojí aj nárast ceny Vajec slepačích čerstvých v roku 2012 o 55%. Najvýraznejšie klesla cena Paradajok červených guľatých 1 kg, v roku 2006 priemerná cena bola 57,83 Kč a v roku 2018 44,49 Kč. Zaujímavá je aj cena Papriky v roku 2006 35,31 Kč a v roku 2007 už stojí 68,79 Kč. 
Najvýraznejší nárast cien všetkých potravín je v roku 2017, kde potraviny priemerne rástli o 9,98% oproti roku 2016.
 
Spracovaním dát z dátovej sady czechia_price a s ňou prepojených dát som prostredníctvom plošného grafu zobrazila vývoj cien v sledovanom období. Nárast cien jednotlivých potravín a ich percentuálny nárast je zobrazený za pomoci matice. Stĺpce sú tvorené cenou jednotlivých potravín v danom roku a percentuálnym nárastom ceny oproti minulému roku. Ďalšie filtrovanie je pomocou prierezu časového obdobia na rok, štvrťrok a mesiac.



**Vývoj HDP v evropských státech 2006 – 2018.**
Celosvetová finančná a hospodárska kríza vyvolala v roku 2009 vážnu recesiu. Už v roku 2008 je viditeľný pokles rastu HDP vo väčšine európskych krajín. Opätovný pomaly rast HDP nasleduje až v roku 2010. V roku 2012 a 2013 sa vývoj obrátil, rast HDP sa zastavuje a vykazuje pokles okolo 1 % oproti predchádzajúcemu roku. Až v roku 2014 a nasledujúce roky, v európskych krajinách HDP zaznamenáva rast.  
Z časového hľadiska rast HDP v jednotlivých európskych krajinách je odlišný. Počas sledovaného obdobia krajiny ako Albánsko, Poľsko nezaznamenali pokles rastu HDP. V malej miere Švajčiarsko. Najvýraznejší pokles rastu HDP v rokoch 2012-2014 zaznamenali krajiny ako Chorvátsko, Grécko, Portugalsko a Španielsko. Všetky ostatné krajiny najvýraznejší pokles rastu HDP mali počas krízy 2008 -2010.
 
Na analýzu vývoja HDP v európskych krajinách som použila dáta z czechia_secondary_final spracovanej pomocou SQL z pôvodnej dátovej sady. Pre grafické znázornenie rastu HDP z časového hľadiska som nasadila plošný graf, pre porovnanie a analýzu výšky HDP a jednotlivých krajín som vybrala skupinovo stĺpcový graf. Prostredníctvom matice môžeme vidieť výšku HDP jednotlivých krajín v rôznych rokoch. Na mape sú znázornené krajiny a ich výška HDP.



**Procentuální meziroční nárůst HDP, mezd a cen v ČR v letech 2006 – 2018.**
Priemerná hrubá mzda zaznamenáva najvyšší rast v rokoch 2008 o 8,06% a 2018 o 7,55%. V sledovanom období, nepretržitý rast mzdy prerušuje len rok 2013, kde mzda klesla o 1,58% oproti porovnávanému predchádzajúcemu roku 2012. 

Priemerná cena potravín zaznamenáva najvýraznejší pokles v roku 2009 o 6,81%. Zachytávame aj viacero menších poklesov, v rokoch 2015 a 2016 a to okolo 1%, ale v nasledujúcom roku 2017 už cena potravín rastie o 9,98%, čo je najvýraznejší rast v sledovanom období. 
Medziročný nárast HDP prerušuje taktiež rok 2009, kde HDP klesá o 4,66% a tiež v rokoch 2012 a 2013. Najvyšší nárast HDP je v roku 2007 o 5,57% a potom až v roku 2015, kde zaznamenávame nárast o 5,17% oproti roku 2014. 
Ak by sme hľadali vzťah medzi zmenami HDP, mzdami a cenami potravín, je zložitý a hlavne závislý na viacerých faktoroch, ako je inflácia, medzinárodné ekonomické prostredie, politika štátu a pod.
 
Dáta pochádzajú z už spomínanej dátovej sady, spracované za pomoci SQL dotazu a importované až dodatočne v CSV formáte do modelu.
Na grafické znázornenie vývoja som použila spojnicový graf a na číselne grafické znázornenie tabuľku. Dáta je opäť možné filtrovať za pomoci prierezu na jednotlivé roky.  

