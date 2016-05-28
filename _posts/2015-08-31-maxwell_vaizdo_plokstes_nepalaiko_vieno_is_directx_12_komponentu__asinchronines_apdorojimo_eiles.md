---
layout: post
status: publish
published: true
title: "„Maxwell“ vaizdo plokštės nepalaiko vieno iš DirectX 12 komponentų - asinchroninės
  apdorojimo eilės"
author:
  display_name: BC00
  login: BC00
  email: matasx@one.lt
  url: ''
author_login: BC00
author_email: matasx@one.lt
wordpress_id: 8920
wordpress_url: http://localhost/site/new/maxwell_vaizdo_plokstes_nepalaiko_vieno_is_directx_12_komponentu__asinchronines_apdorojimo_eiles/
date: '2015-08-31 23:19:23 +0300'
date_gmt: '2015-08-31 23:19:23 +0300'
categories:
- Naujienos
---
<p style="text-align: justify;">
	&bdquo;nVidia&ldquo; padangėje matomas dar vienas skandalas. Nors kompanija tvirtino, kad jų &bdquo;Maxwell&ldquo; architektūros vaizdo plok&scaron;tės yra pilnai suderinamos su DirectX 12 API, bet atviras &bdquo;Oxide Games&ldquo; lai&scaron;kas atskleidė apie asinchroninės apdorojimo eilės palaikymo trūkumą.</p>
<p style="text-align: justify;">
	Visai neseniai pasirodžiusi &bdquo;Ashes of the Singularity&ldquo; žaidimo beta versija, turinti DirectX 12 testavimo įrankį, atvėrė tikrą žaizdą &bdquo;nVidia&ldquo; kompanijai, nes panaudojus DirectX12 API jų vaizdo plok&scaron;tės ne tik kad neįgijo spartos prieaugio, bet kartais greitaveika net sumažėdavo. Tuo tarpu AMD vaizdo plok&scaron;tėms perėjus nuo DirectX 11 prie DirectX 12 jos parodė nemažą spartos &scaron;uolį. &bdquo;nVidia&ldquo; tada teigė, kad &scaron;is testas neparodo visos tiesos ir nėra visi&scaron;kai tikslus.</p>
<p style="text-align: justify;">
	&Scaron;iandien paskelbtas &bdquo;Oxide Games&ldquo; lai&scaron;kas atvėrė karčią tiesą. Žaidimų kūrėjų kompanija teigia, kad jie patyrė spaudimą i&scaron; &bdquo;nVidia&ldquo;, kuri norėjo, kad i&scaron; DirectX12 testavimo įrankio būtų pa&scaron;alintos kai kurios funkcijos, tiksliau asinchroninis apdorojimas (async compute). To kompanija pra&scaron;ė ne veltui, nes daryti testai kalbėjo patys už save. Įjungus DirectX 12 sparta nedidėjo, kaip tai nutiko AMD atveju. &bdquo;Oxide Games&ldquo; taip pat teigia, kad jie bandė pritaikyti asinchroninį apdorojimą ir &bdquo;Maxwell&ldquo; architektūros plok&scaron;tėms, nes tvarkyklės pateikė, kad &scaron;i funkcija yra palaikoma. Bet įjungus &scaron;į apdorojimo metodą, sparta ne tik kad nepadidėdavo, bet net sumažėdavo. Todėl nustačius, kad testą atlieka &bdquo;Maxwell&ldquo; vaizdo plok&scaron;tė asinchroninis apdorojimas yra i&scaron;jungiamas. &bdquo;Oxide Games&ldquo; priėjo i&scaron;vadą, kad &bdquo;Maxwell&ldquo; vaizdo plok&scaron;tės tiesiog nepalaiko asinchroninio apdorojimo aparatiniu lygiu, kuris yra viena i&scaron; DirectX 12 sudedamųjų dalių bei atne&scaron;a nemažą spartos prieaugį.</p>
<p style="text-align: justify;">
	<img alt="" src="http://technews.lt/userfiles/AMDexplainsasynccompute.png" style="width: 520px; height: 474px;" /></p>
<p style="text-align: justify;">
	AMD i&scaron;girdusi tokias naujienas suskubo visus ap&scaron;viesti, kodėl asinchroninis apdorojimas yra labai svarbus. Panaudojus &scaron;į apdorojimo metodą užduotys turi skirtingą prioritetą - tai atne&scaron;a mažesnę gai&scaron;tį, didesnius kadrus per sekundę, be to lengviau i&scaron;naudoti visus grafikos procesoriaus resursus. AMD ta proga sukūrė savo skaidres, kuriose paprastai paai&scaron;kina kaip veikia asinchroninis apdorojimas. Tam buvo pasitelktas gatvės modelis. Kaip matome, atsiradus tu&scaron;čiam tarpui apdorojama sekanti užduotis. Seniau užduotis atkeliaudavo ir būdavo apdorojamos i&scaron; eilės, su DirectX 12 kiekvienai užduočiai bus priskiriamas prioritetas, taip pirma atliekant svarbesnes užduotis. Naudojant asinchroninį apdorojimą bus galimos trys užduočių eilės: grafinė eilė(pateikimas), apdorojamoji eilė (fizika, ap&scaron;vietimas, po to apdaromieji efektai) ir kopijavimo eilė (duomenų perdavimai). Kiekvienoje eilėje užduotys gali turėti skirtingą prioritetą, taip leidžiant grafikos procesoriui i&scaron;naudoti savo resursus kuo optimaliau. AMD mano, kad asinchroninis apdorojimas gali suteikti iki 46 % didesnę spartą.</p>
<p style="text-align: justify;">
	<img alt="" src="http://technews.lt/userfiles/AMDexplainsasynccompute2.png" style="width: 520px; height: 277px;" /></p>
