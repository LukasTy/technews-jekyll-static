---
layout: post
status: publish
published: true
title: Aptiktas Intel procesorių pažeidžiamumas
author:
  display_name: NForce
  login: NForce
  email: nforce25@gmail.com
  url: ''
author_login: NForce
author_email: nforce25@gmail.com
wordpress_id: 3308
wordpress_url: http://localhost/site/new/aptiktas_intel_procesoriu_pazeidziamumas/
date: '2009-03-22 20:13:51 +0200'
date_gmt: '2009-03-22 20:13:51 +0200'
categories:
- Naujienos
---
<p>Džoana Rutkovskaja (Joanna Rutkowska) paviešino informaciją apie <i>Intel</i> procesorių pažeidžiamumą, leidžiantį vykdyti kodą <i>SMM</i> režime su didesnėmis privilegijomis, nei <i>Ring 0</i> (<i>Ring 0</i> privilegijos yra aukščiausios privilegijos pasiekiamos tik operacinės sistemos branduoliui - <i>kernel'iui</i>).</p>
<div class="imgright"><img src="http://upload.wikimedia.org/wikipedia/en/thumb/2/2f/Priv_rings.svg/300px-Priv_rings.svg.png" border="1" /></div>
<p><i>SMM</i> (<i>System Management Mode</i>) - tai specialus, mažai aprašytas dokumentuose <i>Intel</i> procesorių darbo režimas, kuris pirmą kartą pasirodė procesoriuje <i>386SL</i>. Šiame režime yra sustabdomas normalus kodo vykdymas, ir speciali programinė įranga (paprastai <i>firmware</i> arba <i>debugger'is</i> su aparatinės įrangos palaikymu) yra vykdoma su aukštomis privilegijomis.</p>
<p><i>Exploit'ai</i> naudoja procesoriaus <i>cache</i> atmintį prieigai prie <i>SMRAM</i> - apsaugotos <i>SMM</i> režimo atminties. Iš dviejų pristatytų <i>exploit'ų</i> vienas daro <i>SMRAM dump</i> (įrašo į failą atminties turinį), o kitas paleidžia kodą <i>SMM</i> režime.</p>
<p>Panaudojus pažeidžiamumą galima sukurti <i>SMM-rootkit'us</i> (<i>rootkit</i> - tai programa skirta nuslėpti faktą, kad į kompiuterį buvo įsilaužta. Paprastai <i>rootkit'ai</i> yra naudojami nuslėpti faktui, kad hakeris gavo <i>root</i> teises operacinėje sistemoje) ir/arba operacinės sistemos apsaugos apėjimui. Yra žinoma, kad <i>Intel</i> jau pranešta apie šį pažeidžiamumą - jis jau yra ištaisytas pagrindinėje plokštėje <i>DQ45CB</i>, bet senesni modeliai lieka pažeidžiami.</p>
