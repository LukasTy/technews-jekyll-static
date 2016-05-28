---
layout: post
status: publish
published: true
title: Grafinis GRUB nustatymų redagavimas
author:
  display_name: Suvirintojas
  login: Suvirintojas
  email: dovrim@yahoo.com
  url: ''
author_login: Suvirintojas
author_email: dovrim@yahoo.com
wordpress_id: 72
wordpress_url: http://localhost/site/new/grafinis_grub_nustatymu_redagavimas/
date: '2009-01-23 23:42:59 +0200'
date_gmt: '2009-01-23 23:42:59 +0200'
categories:
- Naujienos
---
<p>Jei jau rimtai užsiiminėjote su Linux su GRUB jums tikrai teko susipažinti.<br />
<br />Ir tai ko gero skausmingiausias dalykas į kurį atsimuša žmogus pradėjęs pažintį su Linux šiandien. </p>
<p>Nors GRUB tai pažangi programinė įranga, pradinis įkeliklis galintis įjungti kokią tik norime operacinę sitemą iskaitant ir tas kokių jūs net pavadinimų neesat gridėję, tačiau GRUB nustatymų keitimas yra labai tiesioginis. GRUB kūrėjai mums tiesiog siūlo perrašyti pradinės įkrovos skriptą pagal savo poreikius. Patyrusiems taip net patogiau, bet čia visai nepagalvota apie naujokus kurie jei padaro kokią nors kad ir menką klaidą tai dažniausiai pasėkmė yra nebeužsikraunantis kompiuteris.</p>
<p>Todėl čia gali labai praversti  <a class="ns" href="http://www.qt-apps.org/content/show.php/QGRUBEditor?content=60391">QGRUBEditor</a><br />
<br />Su šia programa galima nesunkiai kesiti nustatymus paprastoje ir visiems lengvai suprantamoje grafinėje aplinkoje. Pirmiausiai įsitikinkite ar nėra šios programos jūsų distribucijos šaltiniuse tarkim Synaptic tvarkyklėje. Jei nėra tai menka bėda. Parsisiuntę naujausią versiją iš nuorodos turėsite ją sukompiliuoti taip:<br />
<br />qmake-qt4<br />
<br />make<br />
<br />make install<br />
<br />Ir pirmiau turite įdiegti priklausomus paketus tai:<br />
<br />libqt4-core, libqt4-dev ir libqt4-gui.</p>
<p>Jei viskas pavyko tai jūs turite naują komandą:<br />
<br />qgrubeditor<br />
<br />Kuri atidaro štai tokį langą:</p>
<p><img src="http://www.technews.lt/upl/Failai/Qgrubeditor.png" /></p>
<p>Sėkmės tiuninguojant savo GRUB!</p>
<p>Bėje norėčiau, kad komentaruose parašytumėte ar patiko ar praktinės naudos davė jums toks straipsnis. Tada aš žinosiu ar rašyti tokių daugiau. </p>
<p></p>
