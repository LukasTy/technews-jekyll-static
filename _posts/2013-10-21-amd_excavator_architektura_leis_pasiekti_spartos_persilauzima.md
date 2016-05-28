---
layout: post
status: publish
published: true
title: "„AMD Excavator“ architektūra leis pasiekti spartos persilaužimą?"
author:
  display_name: BC00
  login: BC00
  email: matasx@one.lt
  url: ''
author_login: BC00
author_email: matasx@one.lt
wordpress_id: 7819
wordpress_url: http://localhost/site/new/amd_excavator_architektura_leis_pasiekti_spartos_persilauzima/
date: '2013-10-21 11:42:54 +0300'
date_gmt: '2013-10-21 11:42:54 +0300'
categories:
- Naujienos
---
<p>
	Nors AMD ir yra parei&scaron;kiusi pasitraukianti i&scaron; itin auk&scaron;tos spartos centrinių procesorių kūrimo, daugelis konkurencijos auk&scaron;čiausiame sektoriuje pasiilgusių vartotojų tikisi nemažo spartos proveržio kartu su sekančios kartos &bdquo;Steamroller&ldquo; architektūra. Entuziastai net pažėrė keletą spėjimų (gandų lygio informacijos) apie &bdquo;Excavator&ldquo; branduolius, kurie turėtų turėti didžiulių pakitimų dėl naujai integruoto instrukcijų apdorojimo bloko.</p>
<p>
	Neseniai GCC bendruomenei pristatytas ir tik bendro lygio &bdquo;Excavator&ldquo; architektūros palaikymą &bdquo;Linux&ldquo; terpėje įgalinantis paketas gali atskleisti keletą paslapčių, kurias turės naujieji AMD procesoriai. Remiantis i&scaron; AMD atitekėjusia informacija, &bdquo;Excavator&ldquo; palaikys SSE4.1, SSE4.2, AES, PCLMUL, AVX, BMI, F16C, MOVBE, AVX2, BMI2, RDRND bei kitas instrukcijas. Ateities aplikacijoms, žinoma, svarbiausii, tampa AVX2, kuris įdiegtas į &bdquo;Intel Haswell&ldquo; procesorius.</p>
<p>
	&Scaron;ių instrukcijų implementacija reikalauja kardinalaus aparatinės įrangos pertvarkymo. Dabartinis &bdquo;Bulldozer&ldquo; architektūros slankiojančio kablelio blokas geba susitvarkyti tik su 128 bitų sveikųjų skaičių operacijomis, tuo tarpu AVX2 galimybės praplatėja iki 256 bitų SIMD instrukcijų. Nenuostabu, kad AMD reikalingas kardinaliai atnaujintas arba net nuo nulio surinktas slankiojančio kablelio blokas, kuris yra dalinamasis tarp dviejų aritmetinių/loginių blokų dabartiniame &bdquo;Bulldozer&ldquo; modulyje.</p>
<p>
	Tokie pakitimai 2015-2016 metais turėtų leisti pasiekti dramati&scaron;ką spartos proveržį didžiojoje dalyje pažangių aplikacijų. Visgi atrodo, kad &bdquo;Intel&ldquo; nežada pasiduodi instrukcijų kare, mat &bdquo;Skylake&ldquo; architektūros procesoriai jau turės AVX 3.2 paketą, kuris dirba su 512 bitų instrukcijomis.</p>
<p>
	<img alt="" src="http://technews.lt/userfiles/slide-1.png" style="width: 520px; height: 357px;" /></p>
