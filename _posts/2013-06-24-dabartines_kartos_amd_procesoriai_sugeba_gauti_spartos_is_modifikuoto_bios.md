---
layout: post
status: publish
published: true
title: Dabartinės kartos AMD procesoriai sugeba gauti spartos iš modifikuoto BIOS
author:
  display_name: BC00
  login: BC00
  email: matasx@one.lt
  url: ''
author_login: BC00
author_email: matasx@one.lt
wordpress_id: 7633
wordpress_url: http://localhost/site/new/dabartines_kartos_amd_procesoriai_sugeba_gauti_spartos_is_modifikuoto_bios/
date: '2013-06-24 11:51:26 +0300'
date_gmt: '2013-06-24 11:51:26 +0300'
categories:
- Naujienos
---
<p style="text-align: justify;">
	Nepateisinusios lūkesčių centriniams AMD procesoriams skirtos &bdquo;Bulldozer&ldquo; bei &bdquo;Piledriver&ldquo; architektūros sulaukė daug kritikos. Ir nors abu architektūriniai sprendimai demonstruoja padorią spartą daugiagijėse programose, &bdquo;Intel&ldquo; i&scaron;lieka ai&scaron;kiu lyderiu. Pasirodo, įne&scaron;ti spartos &scaron;ios kartos AMD centriniams procesoriams, tuo pačiu ir APU, galima ne tik optimizuojant pačią programą, bet ir &bdquo;&scaron;lifuojant&ldquo; BIOS, ką būtent ir atrado vienas suomių entuziastas.</p>
<p style="text-align: justify;">
	Nesąmoningo atradimo metu buvo i&scaron;siai&scaron;kinta, kad &bdquo;Bulldozer&ldquo; ir vėlesnių architektūrų procesoriai turi aktyvuotą NRAC bloką bei tam tikrus užblokuotus registrus. Tokia savybė neegzistuoja jokiuose dokumentuose ir jos įdiegimo prasmę sužinoti labai sunku. Suomių entuziasto, pasivadinusio Stilt, nuomone, tai gali būti susiję su galimos klaidos (angl. errata) apėjimu, mat sunku patikėti, kad tai galėtų būti dizaino problema: lėtai, bet tvarkingai veikiančios instrukcijos egzistuoja nuo pirmųjų &bdquo;Zambezi inžinerinių pavyzdžių ir jas taip pat turi visai neseniai i&scaron;leisti &bdquo;Richland&ldquo; APU.</p>
<p style="text-align: justify;">
	<img alt="" src="http://technews.lt/userfiles/amd_performance_gain.png" style="width: 520px; height: 369px;" /></p>
<p style="text-align: justify;">
	&bdquo;Xbitlabs&ldquo; atlikta trumpa studija atskleidė, kad aktyvavus registrus ir i&scaron;jungus NRAC bloką A10-6800K sparta SuperPi teste pakyla, atitinkamai, 14.7 ir 18.7 % . Nors SuperPi ir i&scaron;lieka labai populiariu spartos matavimo ta&scaron;ku, aplikacija yra pritaikyta seniems x87 kodo skaičiavimams. Nepana&scaron;u, kad patobulintas BIOS atne&scaron;tų naudos &scaron;ių dienų programoms, kurių apdorojimui naudojamos SSE/AVX instrukcijos. Nors atradimas kol kas sugeba sumažinti tik SuperPi atlikimo laiką, neatmetama galimybė, kad AMD procesoriai turi daugiau paslėptų savybių, galinčių pasitarnauti ie&scaron;kant taip trūkstamos spartos.</p>
