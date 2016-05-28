---
layout: post
status: publish
published: true
title: 'Windows 7: Kaip panaikinti „Send Feedback” užrašą ir Beta žymeklį'
author:
  display_name: SB
  login: SB
  email: sb.technews.lt@gmail.com
  url: ''
author_login: SB
author_email: sb.technews.lt@gmail.com
wordpress_id: 2985
wordpress_url: http://localhost/site/new/windows_7_kaip_panaikinti__send_feedback__uzrasa_ir_beta_zymekli/
date: '2009-01-10 16:12:50 +0200'
date_gmt: '2009-01-10 16:12:50 +0200'
categories:
- Naujienos
---
<div class="imgright"><img src="http://www.techspot.com/blog/wp-content/uploads/2009/01/sendfeedback.jpg" border="1"></div>
<p><br>Manau, kad pasirodžius vienai iš stabiliausių <i>Windows 7</i> versijų, pirmąjai <i>Beta</i> versijai, dažnas iš jūsų ją išbandęs pasrininko kaip pagrindinę operacinę sistemą. Ši operacinė ypač naudinga nešiojamųjų kompiuterių turėtojams, nes juose veikia žymiai našiau nei <i>Vista</i>. Tiesa, kaip ir ankščiau pasirodžiusios <i>Vista</i> bandomosios versijos, ir ši turi papildomų elementų, kurie jums gali rėžti akį, nors pačią sistemą idealiai susitvarkėte savo reikmėms. Tai testuotojams skirtas „Send Feedback“ užrašas ir <i>Windows 7 Build 7000</i> žymeklis apačioje, esantis dešinėje pusėje.<br />
<br><br />
<br><b>Kaip panaikinti „Send Feedback“ užrašą</b><br />
<br><br />
<br>1. Paleiskite Registro tvarkytuvą (įrašykite žodį „regedit“ starto „run“ komandos meniu)<br />
<br>2. Vėliau eikite čia - HKEY_CURRENT_USER&gt;Control Panel&gt;Desktop<br />
<br>3. Jei nėra reikiamo failo, susikurkite jį patys. Pridėkite naują DWORD (32-bit) failą ir jį pervadinkite į „FeedbackToolEnabled“ bei „Value data“ pažymėkite nuliu, nors dažniausiai ši reikšmė ir yra naudojama sukuriant naują failą.<br />
<br>4. Po sistemos perkrovimo ši problema turėtų būti dingusi.<br />
<br><br />
<br>Tiesa, turime ir alternatyvą. Galite iš <a class="ns" href="http://www.techspot.com/files/2009/FeedbackToolEnabled.reg">čia</a> parsisiųsti registro failą, jį spustelėti ir aktyvuoti. Perkrovus sistemą problema bus pašalinta.<br />
<br><br />
<br><b>Kaip panaikinti Beta žymeklį</b><br />
<br><br />
<br>Atliktį šį procesą šiek tiek sudėtingiau rankiniu būdu. Jums reikėtų pakeisti orginalųjį „user32.dll.mui” failą kitokiu, kurį redaguotumėte pats. Tiesa, mes taip pat turime sprendimą. Galite pamėginti parsisiųsti vieną iš <a class="ns" href="http://www.techspot.com/files/2009/Remove7Watermark.exe">įrankių</a>, kuris viską atliks už jus. Beje, tenka paminėti, kad šis įrankis tinka tik <i>Windows 7 Build 7000</i> versijai.<br />
<br><br />
<br><br />
<br></p>
