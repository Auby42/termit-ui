#### Verze 4.0.0

- Žádné nové funkce, došlo ke změnám v infrastruktuře - aplikaci již nelze nasadit jako WAR, validace byla oddělena do
  samostatné služby.

#### Verze 3.5.1

- Opravena chyba mazání pojmu, pro který existují nepotvrzené výskyty v jiných zdrojích/pojmech.
- Zlepšení výkonu použitím větší cache.

#### Verze 3.5.0

- Přidána možnost zakázat veřejné prohlížení slovníků.
- Přidána možnost řídit anonymní přístup k prohlížení slovníku.
- Vylepšena práce s výskyty pojmů v souborech - při analýze po reuploadu souboru jsou použity existující výskyty.
- Různá výkonnostní vylepšení.

#### Verze 3.4.0

- Přidána podpora pro záznamy o smazání pojmů. Ty jsou zobrazovány i v grafu aktivity slovníku.
- Přidána možnost filtrovat v historii změn.
- Přidána podpora pro ukládání a anotaci souborů v různých jazycích v rámci jednoho slovníku.
- Přidána podpora pro import překladů pojmů ze souboru MS Excel.

#### Verze 3.3.0

- Přidána možnost stáhnout anotovaný soubor bez nepotvrzených výskytů.
- Upraveno fulltextové vyhledávání - nově se zobrazuje informace o atributu, ve kterém byla shoda nalezena.
- Do fasetového vyhledávání přidána možnost filtrovat dle příkladů (`skos:example`).

#### Verze 3.2.0

- Přidána podpora pro import slovníků z MS Excel.
- Vylepšení výkonu při opakované anotaci pojmů ve slovníku a validaci slovníku.
- Úpravy v UI anotátoru - je možné skrýt výskyty vybraného typu.
- Přidána možnost generovat identifikátory bez znaků s háčky a čárkami.

#### Verze 3.1.3

- Přidána možnost odeslat novému uživateli mail s pozvánkou (admin již nemusí uživateli nastavovat heslo).
- Je možné zobrazit i pojmy bez názvu v primárním jazyce instance.
- Formulář pro vytvoření nového atributu umožňuje vyplnit název a popis ve více jazycích.
- Opravy chyb, aktualizace knihoven.

#### Verze 3.1.2

- Přidána možnost resetovat zapomenuté heslo.
- Opravy chyb.

#### Verze 3.1.1

- Opravy chyb, aktualizace knihoven.

#### Verze 3.1.0

- Přidána možnost zvýraznit v anotátoru výskyty vybraného pojmu.
- Vylepšená opakovaná anotace souborů - zapamatování si již potvrzených výskytů i při (omezené) změně obsahu dokumentu.
- Úprava vizualizace výskytů v anotátoru.
- Filtrování v tabulkách ignoruje diakritiku.
- Opravy chyb, aktualizace knihoven.

#### Verze 3.0.4

- Opravy chyb.

#### Verze 3.0.3

- Přidána podpora pro vícejazyčné atributy slovníků.
- Zlepšena rychlost opakované anotace dokumentů.

#### Verze 3.0.2

- Přidána podpora pro nasazení s externí autorizační službou.
- Přidána možnost specifikovat soubor s taxonomií stavů/typů pojmů.

#### Verze 3.0.1

- Opraven problém s nastavováním pojmů se stejným významem.
- Technické úpravy uvnitř aplikace.

#### Verze 3.0.0

- Draft status pojmu nahrazen podporou pro množinu stavů.
- Odebrány některé nefunkční/nepoužívané funkce.
- Aktualizace požadované verze platformy Java.

#### Verze 2.18.0

- Implementováno facetové vyhledávání pojmů.
- Přidán link na generovanou dokumentaci REST API do paty stránky.
- Zefektivněno načítání názvů objektů.

#### Verze 2.17.0

- Přidána správa uživatelských skupin.
- Implementována podpora řízení přístupu ke slovníkům pro uživatele, skupiny a role.
- OpenAPI dokumentace REST API nyní součástí instance.
- Opravy chyb.

#### Verze 2.16.3

- Opravy chyb.

#### Verze 2.16.2

- Opravy chyb.
- Prvotní verze správy uživatelských skupin (bude dále využita při řízení přístupu ke slovníkům).

#### Verze 2.16.1

- Hodnoty dalších atributů, které reprezentují URL, jsou nyní zobrazeny jako klikatelné externí linky.
- Interní technická vylepšení.

#### Verze 2.16.0

- Excel export vytváří nyní sheety pro jednotlivé jazyky slovníku.
- Přidána možnost stáhnout soubor v současné verzi a ve verzi, ve které byl původně nahrán do TermItu.
- Opravy drobných chyb, zrychlení práce s anotátorem (po označení/potvrzení výskytu pojmu se již dokument znovu
  nenačítá).

#### Verze 2.15.0

- Rozšíření možností exportu o plný export (všechny atributy pojmů). Přepracován i Excel export.
- SKOS reimport nyní zachovává reference na dokument.

#### Verze 2.14.1

- Systém nyní neodesílá týdenní přehled nových a upravených komentářů, když žádné změny v komentářích nejsou.
- Přidána podpora pro editaci názvů dokumentů a souborů.

#### Verze 2.14.0

- Přidána podpora stránkování komentářů a změn na hlavní stránce. Zvýraznění nových od poslední návštěvy.
- Zobrazení historie změn snapshotu.
- Možnost odesílát týdenní přehled nových a upravených komentářů administrátorovi a tvůrcům slovníků.
- Přidána podpora exportu slovníku v RDF/XML.
- Základní atributy pojmu rozšířeny o skos:notation a skos:example.
- Harmonizován výstup CSV/Excel a SKOS RDF exportu.

#### Verze 2.13.0

- Implementováno uživatelské rozhraní pro prohlížení a správu snapshotů slovníků a pojmů.
- Přidána podpora pro editaci pouze vybrané podmnožiny slovníků.
- Přidána podpora pro mapování slovníků do kontextů úložiště identifikovaných jiným IRI než IRI slovníků.

#### Verze 2.12.1

- Rozšířeny atributy dostupné u snapshotů pojmů ve veřejném rozhraní TermIt.
- Vylepšeno zobrazení editace ne-SKOS atributů.

#### Verze 2.12.0

- Přidána podpora pro snapshoty slovníků (a jejich pojmů). Tyto snapshoty reprezentují zakonzerovaný stav slovníku k
  datu vytvoření snapshotu. Funkcionalita má v tuto chvíli především backendovou podporu, v uživatelském rozhraní
  TermItu lze snapshot pouze vytvořit.

#### Verze 2.11.3

- Opraveny problémy v importu SKOS slovníků.
- Optimalizována stránka s detailem slovníku.
- Opraveny problémy s editací inferovaných vztahů pojmu.

#### Verze 2.11.2

- Oprava konfliktů stylování při zobrazení Markdown formátování.
- Sjednocení stylu komponent pro import slovníku.
- Oprava zobrazení tabulky s historií změn pojmů a slovníků.
- Zobrazení stavu pojmu (rozpracován/schválen) ve výsledcích fulltextového vyhledávání.
- Opravy výkonu a stability backendu.

#### Verze 2.11.1

- Přidána podpora pro Markdown formátování textu definice a poznámky pojmu a popisu slovníku.
- Zobrazení stavu pojmu (rozpracovaný/schválený) na detailu pojmu, s možností stav okamžitě přepnout.
- Optimalizace načítání seznamu všech pojmů ve slovníku.

#### Verze 2.11.0

- Odstraněna podpora pro správu obecných zdrojů z open-source verze.
- Opraveno zobrazení verze v Docker nasazení.

#### Verze 2.10.0

- Podpora filtrování výsledků vyhledávání pojmů podle slovníků.
- Přístup k souvisejícím pojmům ve veřejném API.
- Opraven problém s mazáním pojmu po odstranění jeho zdroje definice.

#### Verze 2.9.0

- Abecední řazení hodnot nemapovaných vlastností na detailu pojmu
- Opraveny problémy se zobrazením exactMatch, relatedMatch, broader na detailu pojmu
- Opraven import aby nepřijímal definice/poznámky/prefLabely/altLabely/hiddenLabely bez language tagu.

#### Verze 2.8.0

- Zjednodušena práce se souvisejícími pojmy.
- Přidána možnost exportovat glosář včetně pojmů z jiných slovníků, které jsou z něj referencovány.
- Optimalizace mazání souborů obsahujících anotace.
- Opraveny problémy se zpracováním různých typů uvozovek v textu souborů.

#### Verze 2.7.0

- Vylepšena podpora importu SKOS glosářů.
- Opraven export related/relatedMatch pojmů.
- Přidána podpora pro exactMatch, related, a relatedMatch pojmy ve veřejném REST API.
- Uživatel je nyní informován o maximální velikosti nahraného souboru a upozorněn v případě jejího překročení.
- Opraveny problémy s používáním anotátoru v Mozilla Firefox.

#### Verze 2.6.0

- Rozlišení pojmů pocházejících z různých slovníků badgem se zkratkou slovníku
- Slovník obsahuje informaci o počtu pojmů
- přepracován a rozšířen SKOS import
- Opravy chyb

#### Verze 2.5.1

- Použití skos:broadMatch místo skos:broader pro vazby do jiných slovníků
- Opravy menších chyb.

#### Verze 2.5.0

- Implementována podpora pro SKOS related, relatedMatch a exactMatch.
- Opravy menších chyb.

#### Verze 2.4.1

- Přepracován vzhled formulářů (nápověda se nově zobrazuje v popup okně).
- Upraven vzhled anotátoru.
- Zjednodušení infrastruktury aplikace.
- Opravy menších chyb.

#### Verze 2.4.0

- Na hlavní stránku byl přidán widget komentářů.
- Anotátor nyní zobrazuje slovník, kterým je soubor anotován a umožňuje vybrat slovník, který bude použit pro textovou
  analýzu.

#### Verze 2.3.1

- Opraveny problémy s voláním služby textové analýzy a ukládání souborů v Docker kontejneru.
- Opraveny problémy s přístupem k veřejnému prohlížení slovníků (expirovaný JWT, zobrazení definice).
- Optimalizace načítání pojmů.

#### Verze 2.3.0

- Přídána podpora pro vedení diskuse u pojmů (přihlášení uživatelé).
- Přidána podpora uživatelských rolí a základní autorizace. Uživatelé mohou mít omezená práva (pouze prohlížení a
  komentování), plná práva (prohlížení i editace) či administrátorská práva.
- Administrátor může měnit role uživatelů.
- Předdefinovaný administrátorský účet již není při startu generován, pokud v systém je alespoň jeden jiný
  administrátor.

#### Verze 2.2.0

- Zjednodušení práce s dokumenty a soubory a jejich vazbou na slovníky - např. k slovníku je nově možné připojit (nebo
  od něj odpojit) dokument i po jeho vytvoření.
- Vylepšena možnost přiřadit pojmu zdroj definice v dokumentu.
- Nová prohledávatelná tabulka podporující stránkování pro zobrazení slovníků a zdrojů.
- Podpora vícejazyčných popisů pojmů (skos:scopeNote).

#### Verze 2.1.3

- Titulek stránky se mění v závislosti na navigaci (usnadňuje hledání v historii).
- Opravena komunikace se službou textové analýzy při vytvoření nového pojmu.
- Opraveno nekonzistentní chování formuláře pro nahrání souboru.
- Opravena nesprávná vizualizace validačního skóre nového pojmu.

##### Verze 2.1.2

- Přepracovány obrazovky seznamu slovníků a zdrojů - nyní používají tabulku podporující stránkování a filtrování.
- Opraveny problémy s generováním nových identifikátorů.
- Optimizalizováno načítání výsledků validace.
- Řada dalších oprav.

##### Verze 2.1.1

- Úprava UI výsledků vyhledávání
- Opravy drobných chyb v uživatelském rozhraní

##### Verze 2.1.0

- Přidána podpora pro SKOS altLabel a hiddenLabel.
- Přidána podpora vícejazyčných atributů pojmu.
- Implementována validace kvality pojmů v rámci slovníku a vizualizace jejích výsledků.
- Implementována podpora Docker kontejneru.

##### Verze 2.0.0

- Nový design uživatelského rozhraní.
- Přidána možnost nastavit pojmu několik rodičovských pojmů.
- Optimalizace komponenty anotátoru.
- Těsnější podpora modelu SKOS.
- Přidána možnost prohlížet slovníky a pojmy bez přihlášení.

##### Verze 1.3.0

- Implementována podpora propojení pojmu se zdrojem jeho definice v souboru.
- Přidána možnost zjistit pojmy příbuzné skrze definici a ontologické vazby.
- Vizualizace pojmů nepoužitých k anotaci žádného zdroje.
- Implementována možnost vytvářet nové uživatele v administraci.

##### Verze 1.2.1

- Přidána podpora pro úpravy metadat zdrojů.
- Implementována základní správa uživatelů a možnost editace vlastního profilu.
- Implementována možnost zakázat registraci nepřihlášeným uživatelů.
- Implementována podpora pro vytváření dokumentových slovníků.
- Řada opravených chyb a vylepšení kódu.
- Ontologický model nyní používá prvky z DC terms místo starších DC elements.

##### Verze 1.2.0

- Přidána podpora pro závislosti mezi slovníky (slovník může importovat jiné slovníky).
- Pojmy mohou mít rodiče (skos:broader) z importovaného slovníku.
- Nově je možné stáhnout obsah souboru, který byl předtím nahrán do systému.
- Vylepšena přesnost fulltextového vyhledávání.

##### Verze 1.1.2

- Implementováno nahrávání souborů do systému.
- Podpora pro výběr slovníku pro textovou analýzu.
- Pojmům přidán atribut skos:definition, vyjadřující normativní definici.
- Automatické přiřazení pojmů vyskytujících se (na základě textové analýzy) v souboru souboru samotnému.
- Zdrojový kód publikován na [GitHub](https://github.com/kbss-cvut).

##### Verze 1.1.1

- Zobrazení legendy v anotátoru obsahu souboru.
- Hierarchická vizualizace seznamu zdrojů dat.
- Zobrazení pojmů přiřazených a vyskytujících se ve zdroji dat.
- Zobrazení zdrojů, kterým je pojem přiřazen či se v nich vyskytuje.

##### Verze 1.1.0

- Optimalizace výkonu aplikace.
- Opravy drobných chyb (především v uživatelském rozhraní).

##### Verze 1.0.0

- Podpora správy datových zdrojů a přiřazování pojmů k těmto zdrojům.
- Tvorba nových pojmů na základě výsledků textové analýzy.
- Úprava struktury hlavní stránky aplikace.
- Možnost přiřadit k pojmu či slovníku libovolnou vlastnost mimo standardní model.

##### Verze 0.4.0

- Export glosáře do CSV/Excel.
- Podpora fulltextového vyhledávání.
- Vylepšení přesnosti výsledků textové analýzy.
