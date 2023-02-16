# chat
for chat
13. Nõrkvoolu-, serveri ja UPSi ruumid
13.1 Kasutatav alusdokumentatsioon

Juhul, kui antud juhendi nõuded ja alusdokumentatsiooni nõuded on vastuolus, tuleb järgida rangemaid nõudeid.

Kvaliteedinõuded

LVI 30-10231 Sähkö- ja elektroniikkatilojen ilmastointi. Ilmastoinnin mitoitusperusteet.
2008 ASHRAE Environmental Guidelines for Datacom Equipment 
Hoone tehnosüsteemide RYL 2002 “Ehitustööde üldised kvaliteedinõuded. Osa 1“
Hoone tehnosüsteemide RYL 2002 “Ehitustööde üldised kvaliteedinõuded. Osa 2“
13.2 Nõrkvoolu- ja serveriruumi asukoht hoone planeerimisel

Asukoha kriteeriumid hoones ja üldised nõuded

Nõrkvooluruumi asukoha valikul tuleb peaasjalikult jälgida elektriohutusest ja turvalisusest tulenevaid aspekte. Samuti on oluline, et antud ruumid ei jääks maapinnast madalamale või vahetult katuste alla. Kui kriteeriumid ei ole (arhitektuurist lähtuvalt) täidetavad, tuleb antud ruumide väljaehitamisel teha kõik, mis võimalik, et näiteks nii sade- kui ka pinnaseveed ei tungiks ruumi ja muu turvalisus (nt välisrünnaku vastu) oleks tagatud. Samuti tuleb asukoha valikul jälgida, et nõrkvooluruumid ei asetseks suure põlemiskoormusega ruumide naabruses.

Nõrkvoolu- ja serveriruumid peavad olema omaette tuletõkkesektsioonid ≥EI60. Nõrkvoolu-, serveri- ja tehniline ruum tuleb varustada vähemalt 2x6 kg CO2 B-tuleohutuseklassiga kustutiga ja vajadusel ka gaaskustutussüsteemiga. Samuti peab kõigis loetletud ruumides olema nõuetekohane ATS süsteem.

Kuni kahe maapealse korrusega hoone korral võib kogu hoones olla üks nõrkvoolu- või serveriruum. Kolme ja enama korrusega hoone puhul peab igal korrusel olema nõrkvooluruum, mis on vajadusel kasutajate vahel jagatud. Kõik nõrkvooluruumid peavad asuma teineteise peal kohakuti.

Serveriruum ei tohi paikneda keldrikorrusel, esimesel korrusel ega hoone viimasel korrusel. Üldiselt ei tohiks serveriruum piirneda välisseinaga. Kui see ei ole võimalik, tuleb ehitada serveriruumi välisseina poolsesse külge tehniline koridor, mille minimaalne laius on 800 mm, takistuste (nt postide) kohalt võib minimaalne vahe olla 400 mm.

Kahekorruselise hoone puhul võib serveriruum paikneda teisel korrusel vaid juhul, kui serveriruumi rackide kohale ehitatakse täiendav sadevett eemale juhtiv katus ja põrand on tõstetud min 200 mm.

Nõrkvooluruumis tuleb põrandal kasutada maandatud antistaatilist põrandakatet. Nii nõrkvoolu- kui ka serveriruum peavad olema tolmuvabad.

Ruumi valgustus peab rackikappide vahel tagama põrandal valgustugevuse 500 lx. Valgustid peavad olema IP23 ja elektroonilise süüteseadmega klassiga A2.

UPSid tuleb projekteerida ja ehitada nõrkvoolu ja/või serveriruumidesse või PJK ruumidesse. Kui see ei ole võimalik, on UPSi ruumi asukoha kriteeriumiteks hoones samad nõuded, mis nõrkvooluruumil. Täpsemate andmete puudumisel tuleb serveri- ja jahutusseadmete ruumi õhumüraks arvestada ≥80dB(A).

13.3 Nõuded nõrkvooluruumi(de)le

Nõrkvooluruum(-id) soojuseraldusega kuni 10kW

Nõrkvoolu ruumiks on ruum, milles on maksimaalselt 4 racki 42U 19″ või mille summaarne soojuseraldus on maksimaalselt 10 kW (projekteerimisel tuleb arvestada ka süsteemi miinimumvõimsusega, mille ütleb tellija). Täpsemate andmete puudumisel tuleb ühe rackikapi soojuseralduseks lugeda 3-5 kW. Antud rackides ja ruumis paiknevad telefoni- ja arvutivõrgu (edaspidi lühend ATK) ristühenduspaneelid, võrguühenduse aktiivseadmed, videovalve seadmed, telefonijaam, raadioside aktiivseadmed, antennivõimendid ja UPS. Täpsem racki maht ja sisu sõltub nõrkvoolusüsteemide ülesehitusest.

Nõrkvoolu ruumides peab olema dubleeritud otseaurustusega split jahutussüsteem. Jahutuseks ei tohi kasutada nn multisplit- või VRV-süsteemi, kus on üks välisosa ja mitu siseosa. Jahutusseadmete võimsus peab võrduma aktiivseadmetest, valgustitest, ventilatsiooni õhuvahetusest, elektrikilbist ja UPSist eralduva soojusvõimsuse summaga. Jahutusseadmete välisosad peavad paiknema kas hoone katusel või vähemalt 2,5 m kõrgusel maapinnast.

Kõikides nõrkvooluruumides tuleb tagada n+1 jahutusseadmega ruumitemperatuur nimivõimsusel +22°C ±2°C, täiendavalt peab olema reservis üks jahutusseade. Juhul kui seadmeid ei õnnestu kaskaadi ühendada, peab võrdse tööaja tagamiseks teostama ümberlülitused hooneautomaatika, eeldatava intervalliga 1 kuu. Võimaliku jahutusseadme rikke tuvastamiseks peavad ruumis olema elektroonilised temperatuuri, veelekke- ja niiskusandurid, mis on ühendatud valvesignalisatsiooni süsteemi ja hooneautomaatikasse ning visualiseeritud vastavalt „Osa 11, Hooneautomaatika“. Jahutusseadmed peavad olema vastavuses „Osa 5, Külmavarustus ja jahutus“ nõuetega. Jahutusseadmete siseosad peavad olema ≥G4 filtritega. 

Ruumiõhu niiskus ei ole määrava tähtsusega (lubatud vahemik  20-80% RH). Nõrkvooluruumides ei tohi olla vedelikke sisaldavaid torusid (nt vee, sprinkleri-, kanalisatsioonitorud).

Uks peab vastama standardi EVS-EN1627 RC2 nõuetele ja ruum peab olema eraldi valvestatav. Nii läbipääsu- kui ka valvesüsteem peab olema hoone turvasüsteemidega seotud.

Serveriruum soojuseraldusega 10-20 kW

Serveriruumiks loetakse ruumi, milles on vähemalt 5 racki 42U 19″ või mille soojuseraldus on 10 kW või rohkem (projekteerimisel tuleb arvestada ka süsteemi miinimumvõimsusega, mille ütleb tellija).

Serveriruum jagatakse kaheks eraldiseisvaks tuletõkkesektsiooniks: serveriruum ja serveriruumi teenindav tehniline ruum (edaspidi tehniline ruum). Serveriruumil peab olema läbipääsulüüs. Lüüsiks võib olla ka serveriruumi teenindav tehniline ruum. 

Kui serveriruumil on kaks või enam erinevat kasutajat, tuleb ruum eraldada täiendavalt võreseinaga selliselt, et erinevatele kasutajatele oleks tagatud enda serverite juurde eraldi sissepääs.

Serveriruumis tuleb jälgida samu tingimusi, mis eelmises punktis, kuid täiendavalt peavad olema täidetud järgmised nõuded:

Arhitektuurilised-ehituslikud nõuded:

Serveriruumi võib pääseda ainult lüüsi kaudu, milleks võib olla ka serveriruumi teenindav tehniline ruum.
Serveri- ja tehnilise ruumi sissemurdmiskindlus peab vastama minimaalselt standardi EVS-EN1627 klassile RC4 (erinevused tuleb tellijaga kooskõlastada).
Serveriruumis peab olema spetsiaalne antistaatiline põrandakattega ja maandatud (IEC 61000-4-2) tõstetud moodulpõrand, kõrgusega vähemalt 300 mm ja kandevõimega vähemalt 1000 kg/m2 (so ca 10 kN/m2). Tõstetud põranda all võivad kulgeda kaabliteed ja serveriruumi teenindavad jahutuse torustikud.
Rackikappide jahutamiseks ja ventileerimiseks peavad moodulpõrandas olema spetsiaalsed reguleeritavate avadega ventilatsioonirestid, mis peavad sobituma rackikappide tüübi ja parimat jahutusvõimsust võimaldava paigutusega.
Uksed peavad omama tolmukindlad. 
Ukselehe valgusava peab olema vähemalt 1 m.
Uksetihendid peavad tagama, et ruumi ei satuks niiskust ega tulekustutusvett.
Serviruum tuleb jagada külmaks ja soojaks tsooniks.
Nõuded sisekliimale ja jahutusseadmetele:

Jahutusseadmete efektiivsemaks koormamiseks peab serveriruum olema jaotatud nn külmaks ja kuumaks tsooniks. Arvestuslik külma tsooni temperatuur +25 ⁰C, kuuma tsooni temperatuur +35 ⁰C.
Kasutada vee-glükooli baasil ja vabajahutussüsteemiga täppiskonditsioneere, mitte otseaurustussüsteemi. Vabajahutus tuleb valida välisõhutemperatuurile ≥+10⁰C. Täppiskonditsioneerid asuvad kas serveriruumi teenindavas tehnilises ruumis või kasutatakse nn in-row rackide vahelisi jahutusseadmeid.
In-row jahutusseadmeid võib kasutada üksnes ruumipuudusel ja tellijaga kokkuleppel.
Serveriruumi jahutussüsteem peab olema dubleeritud n+1 põhimõttel ja olema teineteisest täiesti lahus.
Täppiskonditsioneeride välisosad peavad paiknema kas hoone katusel või vähemalt 2,5 m kõrgusel maapinnast. Jahutusseadmete sissepuhe teostatakse tõstetud põranda alla ja väljatõmme lae alt. 
Jahutusseadmete kontrollerid peavad olema on-line UPS toitel. 
Täppiskonditsioneerid peavad olema aurniisutiga varustatud. 
Täppiskonditsioneeride energiaefektiivsus koos dry-cooleri ja pumbasõlmega peab olema EER≥3,2 ning in-row korral EER≥2,5.
Täppiskonditsioneerid peaksid soovituslikult omama kolmanda osapoole (nt Eurovent) sertifikaati. 
Täppiskonditsioneerid peavad olema varustatud kas KNX, Modbus, M-bus, LON või Bacnet väljundiga ning ühendatud hooneautomaatika võrku ja visualiseeritud. Üks täppiskonditsioneer peab suutma hoida serveriruumis nimivõimsusel töötades sisekliimat +25 °C±2 °C ja Rh=50±5%, teine seade on reservis. Täppiskonditsioneeride ühtlase tööaja tagamiseks peavad nad automaatselt iga kuu aja tagant ümber lülituma. Kõiki antud sätteid peab saama hooneautomaatikast muuta. 
Täppiskonditsioneeride dry-cooleri(te) müra ei tohi ületada Sotsiaalministri määruses nr 42 toodud parameetreid, need peavad olema maksimaalse (näiteks A-klassi) energiatõhususega ja omama sõltumatu kolmanda osapoole (nt Eurovent) sertifikaati. Dry-cooler tuleb valida välisõhutemperatuurile -35 °C - + 35 °C, 
Serveri- ja tehnilises ruumis peab olema sundventilatsioon. Ventilatsiooniga tuleb serveriruumis tagada 10-20 Pa ülerõhk võrreldes kõrvalasuvate ruumidega. Nii üldventilatsiooni sissepuhkel kui ka väljatõmbel peavad olema gaaskustutuse poolt juhitavad tuletõkkeklapid sulgumisajaga mitte rohkem kui 10 sekundit.
Tehnilise ruumi vesi ja kanalisatsioon:

Serveriruumi teenindavate jahutusseadmete juures peab olema põrandatrapp, kuhu ühendatakse täppiskonditsioneeride kondensaadi äravoolutorustik
Täppiskonditsioneeri auruniisuti ette tuleb paigaldada veetöötlusseade, mis vähendab katlakivi teket ja tagab seadme pikaajalise töö, näiteks veepehmendi ja/või elektromagnetiline veetöötlusseade.
Niisutusseadmete poolt tarbitava veekoguse mõõtmiseks tuleb paigaldada veemõõtja, mis on varustatud kas Modbus, M-bus, KNX, LON või Bacnet väljundiga ning ühendatud hooneautomaatika võrku ja visualiseeritud.
Hooneautomaatika:

Serveriruumis (jahutusvajadus vähemalt 10 kW) peab olema ruumi eri piirkondades vähemalt 3 temperatuuriandurit. Temperatuuriandurite aritmeetilise keskmisega visualiseeritakse temperatuuri häired. Lisaks peab temperatuuri häire jõudma valvekeskusesse ja hooneautomaatikasse.
Serveriruumis peab olema vähemalt üks veelekke andur, mille häire läheb hooneautomaatika süsteemi.
Serveriruumis peab olema õhuniiskuse andur, mille häire läheb hooneautomaatika süsteemi.
Hooneautomaatikaga tuleb läbi võrgukaardi siduda ja visualiseerida nii täppiskonditsioneerid, auruniisuti veemõõtja kui ka UPS(id).
Elektrivarustus:

Serveriruumi elektritoide algab hoone peakilbist. Garanteeritud elektritoide tagatakse RLA kaudu diiselgeneraatori baasil. Diiselgeneraator varustab elektritoitega serveriruumi UPSi tarbijaid, valgustust ja serveriruumi täppiskonditsioneere. Diiselgeneraatori kütusemahuti maht peab tagama serveri ja serverit teenindavate tehnosüsteemide töö nimivõimsusel 24 tundi või olema minimaalse mahuga 200 liitrit. Diiselgeneraator peab olema valitud UPSide paralleeltöö eripära järgi. Diiselgeneraatori hooneautomaatikas visualiseeritavad parameetrid peavad vastama „Osa 11, Hooneautomaatika“ nõuetele. Diiselgeneraatori nõuded on kirjeldatud „Osa 9, Tugevvool“.
Soovituslikult tuleb rackide elektrivarustus lahendada tõstetud põranda alt ja nõrkvoolukaabeldus lae alt kaabliredelitel.
Serveri- ja tehnilises ruumis paiknevate elektriseadmete ja metalltarindite maandamiseks peab maandustakistus vastama standardile EVS-HD 60364-5-54.
Serveriruumi teenindaval elektrikilbil ja välissideahela(te)l peab olema II+III klassi liigpingepiirik.
UPSi tugiaeg on minimaalselt 10 minutit täiskoormusel (võimsustegur = 0,9). UPS-ile kehtestatud nõudeid vt täpsemalt tugevvoolu „Osa 9, Tugevvool“
Iga rackikapi rea vahel peab vähemalt üks valgusti olema varustatud 2 h akuseadmega.
Rackikapid:

Rackikappide minimaalne mõõt on 800x800 mm ja kõrgus 42 U. Rackikapil peavad nii ees kui taga olema võreuksed. Rackikappide teenindusvahemik eestpoolt on minimaalselt 1,2 m ja tagant 1,0 m
Rackikapid peavad vastama EIA-310D nõuetele.
Rackikapi toitepaneelideks tuleb kasutada 6x230 V SCHUKO paneele. Projekterimise käigus täpsustatakse C13 ja C19 pistikupesade paneelide maht ja monitooring.
Turvasüsteemid:

Nii serveriruumis kui ka serveriruumi teenindavas tehnilises ruumis peab olema ATS, läbipääsu-, valve – ja videovalvesüsteem. Nõrkvoolusüsteemidele kehtestatud nõuded on toodud „Osa 10, Nõrkvool“.
Serveriruumi valvesignalisatsioon peab moodustama omaette sõltumatult juhitava valveala. Valveala juhtimine käib eraldi klaviatuurilt.
Serveriruumi seinad ja uks on soovitav varustada seismoanduritega.
Serveriruumi valvesignalisatsiooni liikumisandureid kasutatakse maskimiskatsele reageerivate liikumisanduritega.
Valvesignalisatsioon peab olema projekteeritud ja ehitatud vastavalt standardile EVS-EN 50131 (turvakategooria 4) või selle uuendatud versioonile.
Läbipääsusüsteem peab olema projekteeritud ja paigaldatud vastavalt standarditele VdS 2358, EN 50133 –1 ja EN 50133-7.
Tuleohutusnõuded:

Vajadusel peab ruum olema varustatud gaaskustutussüsteemiga (lisaks tulekustutitele). Gaaskustutuse juhtimispult peab asuma serveriruumi teenindava tehnilise ruumi välisukse kõrval. Gaaskustutussüsteem peab olema liidetud hoone üldise ATS süsteemiga. Gaasiballoon peab asuma serveriruumi teenindavas tehnilises ruumis. Serveriruumi välispiirded (sein, põrand, lagi, uks, ventilatsioonitoru ja tuletõkke läbiviigud) peavad arvestama võimaliku gaaskustutusest tuleneva täiendava koormusega minimaalselt 60 kg/m².
Nii sissepuhke- kui ka väljatõmbetorustikule paigaldatakse serveriruumi piiretesse tuletõkkeklapid. Tuletõkkeklappide hooldamine tuleb ette näha tehnilise ruumi poolt.
Serveriruum soojuseraldusega alates 20 kW ja rohkem

Kehtivad samad nõuded, mis serveriruumile 10-20c kW, kuid täiendavalt tuleb ette näha:

Arhitektuurilised-ehituslikud nõuded:

Turvalüüs: paikneb serveriruumi tehnilise ruumi ja/või üldkäidava (näiteks koridori) ruumi vahel ja peab olema minimaalse pikkusega 2 m ja laiusega 1,2 m. Turvalüüsis on kaldpõrand korruse tasapinnast serveriruumi tõstetud põrandani ja kandevõimega minimaalselt 1500 kg. Turvalüüs peab olema omaette tuletõkkesektsioon ja uksed peavad olema varustatud läbipääsu mootorlukkudega. Turvalüüsi sisenemisel ei tohi serveriruumi uks avaneda enne välimise ukse sulgumist. Serveriruumist tulekahju korral väljumiseks peab olema võimalik ust nn libliktüüpi lukuga avada.
Serveriruumi täiendava elektromagnetilise varjestuse vajaduse korral peab serveriruum olema seestpoolt kaetud tsingitud terasplekiga, sh tuleb varjestada ka uks(ed), ventilatsioonitorustikud (sh avad), elektritoitekaabel ja nõrkvoolukaablid. Varjestus peab tagama sumbuvuse 10 KHz-1 GHz 40 dB. Serveriruum peab olema kõikidest nurkadest maandatud. Põrandal tuleb kasutada sileplekki, seinas ja laes peab soovituslikult olema profiilplekk. Plekkide liitekohad peavad olema kas neet- või poltühendusega. Ruuminurkade maandusühendus peab olema kaablikingaga. Varjestuse maandus ja potentsiaaliühtlustus tuleb teostada isoleeritud kollakas-rohelise juhtmega, minimaalse ristlõikega 16 mm². Pärast varjestuse väljaehitamist tuleb kontrollida võimalike kiirguslekete olemasolu ja need kõrvaldada.
Rackikapid:

Rackikappide minimaalne mõõt on 800x1200 mm ja kõrgus 42 U. Kõikidele rackikappidele peab olema tagatud ligipääs nii eest- kui tagantpoolt.
13.4 Serveriruumide kasutuselevõtt ja katsetamine

Veendumaks nõrkvoolu- ja serveriruumi tehnoseadmete ja ümberlülituste toimimise töökindluses, tuleb projekteerijal ja ehituse töövõtjal koostada serveriruumi testi ja kontrollimise kava (kooskõlastada tellijaga) ja viia läbi täiemahulised katsetused. Selleks paigaldatakse serveriruumi nimivõimsuse mahus elektrilised küttekehad (näiteks tööstuslikud õhupuhurid) – soojus- ja elektrilise nimikoormuse testimiseks – ja ühendatakse need serveriruumi varustava UPS-i toitele. Seejärel lülitatakse sisse elektriküte ja jahutusseadmed ning jälgitakse hooneautomaatika kaudu ruumi temperatuure ja õhuniiskust (kui niiskust reguleeritakse). 

Pärast serveriruumi temperatuuri stabiliseerimist imiteeritakse tagavara-jahutusseadme(-te) automaatset juurdelülitust ruumitemperatuuri tõusule. Kontrollima peab ka kaskaad ümberlülitust ja jahutusseadmete rikkeid. Kontrollitakse kõikide (temperatuuri, niiskuse ja jahutusseadme rike) häirete jõudmist hooneautomaatikasse.

Pärast serveriruumi jahutusseadmete toimimise katsetusi viiakse läbi elektrivarustuskindluse katsetus. Selleks lülitatakse hoone peakaitse välja, kuid samaaegselt peavad endiselt töötama nii elektriküttekehad kui ka jahutus. Väljalülituse aegselt jälgitakse etteantud aja jooksul RLA ümberlülitust ja diiselgeneraatori käivitumist. Samuti jälgitakse UPS seadme tööd. Seejärel lülitatakse tagasi peakaitse ning jälgitakse RLA ja diiselgeneraatori ümberlülitumist peakaitsmele. Imiteerida tuleb ka diiselgeneraatori rikkeid (õlirõhk, õli- ja veetemperatuurid, aku laadimine, kütuse nivood). Hooneautomaatikasse peavad jõudma UPS-i, RLA ja diiselgeneraatori olekud ja häired, serveriruumi temperatuurid ja niiskused, jahutusseadmete olekud ja häired, vee- ja elektriarvestite näidud jms.

See veebileht kasutab küpsiseid. Tutvu meie privaatsuspoliitikaga.
Selge
