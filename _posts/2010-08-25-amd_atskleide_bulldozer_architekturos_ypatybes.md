---
layout: post
status: publish
published: true
title: AMD atskleidė Bulldozer architektūros ypatybes
author:
  display_name: SB
  login: SB
  email: sb.technews.lt@gmail.com
  url: ''
author_login: SB
author_email: sb.technews.lt@gmail.com
wordpress_id: 5052
wordpress_url: http://localhost/site/new/amd_atskleide_bulldozer_architekturos_ypatybes/
date: '2010-08-25 20:09:03 +0300'
date_gmt: '2010-08-25 20:09:03 +0300'
categories:
- Naujienos
---
<div class="imgright"><img src="http://www.part.lt/img/95a9a08d57cb838172c0250277cdb46b839.jpg"  /></div>
<p>Advanced Micro Dvices šią savaitę atskleidė keletą detalių apie naują artėjančią Bulldozer mikroarchitektūrą, kuria bus paremti artėjantys naujos kartos centriniai procesoriai skirti staliniams kompiuteriams, serveriams ir darbo stotims.</p>
<p>AMD inžinieriai turėjo keletą užduočių. Viena iš jų – padaryti ne tik taip, kad Bulldozer architektūra galėtų kuo efektyviau išnaudoti kelių branduolių potencialą, bet tuo pačiu metu ir leistų procesoriams veikti su mažu energijos kiekiu taip pat nepadidinant paties lusto dydžio.</p>
<p>Kaip žinia, tradiciškai daugiau nei vieno branduolio procesoriai yra suprojektuoti taip: kiekvienas branduolys dirba savarankiškai (gauda ir iškoduoja instrukcijas, atlieka užduotis su slankaus kablelio ir sveikaisiais skaičiais) ir jie gali dalintis kai kuriais elementais, kaip L3 spartinančioji atmintis ar integruotu šiauriniu tiltu (atminties kontroleriu). AMD Bulldozer veiks kiek kitaip - čia branduoliai turės daugiau funkcinių elementų bei dalinsis ne tik laikinąja atmintimi ar atminties valdikliu, bet ir jais.</p>
<p>Naujas AMD Bulldozer architektūros modulis sudarytas iš dviejų atskirų ALU blokų (aritmetinių/loginių įtaisų), tačiau turi bendrą FPU (slankaus kablelio operacijų įtaisą). Tokiam "riebiam" moduliui bus siunčiami du duomenų srautai, panašiai, kaip Intel HyperThreading (SMT - Simultaneous MultiThreading) atveju. Netgi operacinė sistema vieną tokį modulį matys kaip du atskirus loginius branduolius. Visgi, lyginant su SMT, Bulldozer branduolyje įgyvendintas CMT (Chip-level MultiThreading) veiks kur kas sparčiau, paprasčiausiai dėl to, jog procesorius turi daugiau fizinių resursų.</p>
<p>AMD šiuo metu planuoja viename procesoriuje naudoti iki keturių tokių modulių. Kiekvienas jų turės savo antrojo lygio spartinančiąją atmintį, o trečiojo lygio spartinančiąja atmintimi dalinsis su kitais. </p>
<p>Tiesa, minėtas du branduolius atstojantis pagrindinis modulis nebus toks efektyvus (funkcinių elementų skaičius viename Bulldozer branduolyje bus mažesnis nei galėtų būti dviejuose atskiruose branduoliuose), kaip tradicinis variantas, tačiau naudos mažiau energijos ir užims mažiau vietos pačiame luste. Visgi tai taip pat reiškia, kad luste galima įtaisyti daugiau pagrindinių blokų smarkiai nepadidinant paties lusto ir jo energijos suvartojimo. Pasak AMD, vienas pagrindinis blokas turės apie 80% spartos, kokią rodo įprastas dviejų branduolių mikroprocesorius. Nepaisant to, antrasis ALU įtaisas branduolio užimamą plotą padidins vos 12 %.</p>
<p>„Mano nuomone, Bulldozer ir Bobcat architektūros nėra tik ypač geri techniniai sprendimai turtingoje AMD istorijoje, tačiau ir naudingi visai industrijai. Su CPU ir APU, kurie yra pagrįsti šiuo naujuoju branduolių įgyvendinimo principu, mes tikimės vartotojams suteikti naują kompiuterių formą ir spartesnius gaminius, nei bet kada ankščiau.“, - sakė Chekibas Akroutas, generalinis AMD plėtojimo skyriaus vadybininkas ir vyresnysis viceprezidentas.</p>
<p>Deja, tačiau AMD nusprendė nepasidalinti informacija susijusia su taktiniais dažniais ir L2 bei L3 spartinančiųjų atminčių dydžiais. Mes taip pat galime priminti, kad naujieji AMD Bulldozer architektūra pagrįsti centriniai procesoriai bus gaminami 32nm technologijos pagalba.<br /></p>
