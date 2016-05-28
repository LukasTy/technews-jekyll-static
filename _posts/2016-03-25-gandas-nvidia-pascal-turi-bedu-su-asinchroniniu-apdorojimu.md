---
layout: post
status: publish
published: true
title: 'Gandas: „nVidia Pascal“ turi bėdų su asinchroniniu apdorojimu'
author:
  display_name: Mindaugas Klumbis
  login: Katonas
  email: katonasf1@yahoo.com
  url: ''
author_login: Katonas
author_email: katonasf1@yahoo.com
wordpress_id: 9839
wordpress_url: http://www.technews.lt/portal/?p=9839
date: '2016-03-25 19:36:49 +0200'
date_gmt: '2016-03-25 17:36:49 +0200'
categories:
- Naujienos
---
<p style="text-align: justify;">Naujausias pranešimas, atsiradęs <a href="http://www.bitsandchips.it/52-english-news/6785-rumor-pascal-in-trouble-with-asyncronous-compute-code" target="_blank">„Bitsandchips“</a> tinklapyje, teigia, kad „nVidia Pascal“ architektūra, kaip ir dabar naudojama „Maxwell“, neturės pilnaverčio asinchroninio apdorojimo (angl. Async Compute) palaikymo ir kentės tuose žaidimuose, kur bus naudojamas šis Directx 12 komponentas.</p>
<p style="text-align: justify;">Trumpai tariant, „Pascal“ bus „Maxwell“ evoliucija, o ne revoliucija, todėl išlaikys pirmtako trūkumus, tokius kaip aparatinio lygio asinchroninio apdorojimo neturėjimą . Tiesa, „nVidia“ žada, jog su „Pascal“ stipriai išaugs sparta FP64 užduotyse.</p>
<p style="text-align: justify;">Spėjama, kad „nVidia“ pasitelks tiesioginę grafikos procesoriaus galią, norėdami kompensuoti galimus nesklandumus dėl asinchroninio apdorojimo neturėjimo.</p>
<p style="text-align: justify;">Tokiems gandams pasitvirtinus, „nVidia“ taptų labai priklausoma nuo tvarkyklių optimizacijų ir žaidimų kūrėjų malonės, kurie nuspręs kiek intensyviai naudoti asinchroninį apdorojimą.</p>
<p style="text-align: justify;">Priminsime, kuo naudingas asinchroninis apdorojimas. Panaudojus šį apdorojimo metodą, užduotys turi skirtingą prioritetą - tai atneša mažesnę gaištį, didesnius kadrus per sekundę, be to lengviau išnaudoti visus grafikos procesoriaus resursus. Paaiškinti, kaip veikia asinchroninis apdorojimas buvo pasitelktas gatvės modelis. Kaip matome, atsiradus tuščiam tarpui apdorojama sekanti užduotis. Seniau užduotis atkeliaudavo ir būdavo apdorojamos iš eilės, su DirectX 12 kiekvienai užduočiai bus priskiriamas prioritetas, taip pirma atliekant svarbesnes užduotis. Naudojant asinchroninį apdorojimą bus galimos trys užduočių eilės: grafinė eilė (pateikimas), apdorojamoji eilė (fizika, apšvietimas, po to apdorojamieji efektai) ir kopijavimo eilė (duomenų perdavimai). Kiekvienoje eilėje užduotys gali turėti skirtingą prioritetą, taip leidžiant grafikos procesoriui išnaudoti savo resursus kuo optimaliau.</p>
<p style="text-align: center;"><a href="http://www.technews.lt/portal/wp-content/uploads/2016/03/3-1.png"><img class="aligncenter wp-image-9848 size-large" src="http://www.technews.lt/portal/wp-content/uploads/2016/03/3-1-2048x1150.png" alt="3" width="720" height="404" /></a></p>
<p style="text-align: center;"><a href="http://www.technews.lt/portal/wp-content/uploads/2016/03/AMDexplainsasynccompute.png"><img class="aligncenter wp-image-9850 size-full" src="http://www.technews.lt/portal/wp-content/uploads/2016/03/AMDexplainsasynccompute.png" alt="AMDexplainsasynccompute" width="725" height="661" /></a></p>
