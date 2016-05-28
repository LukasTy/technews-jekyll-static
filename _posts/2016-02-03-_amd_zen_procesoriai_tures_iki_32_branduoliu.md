---
layout: post
status: publish
published: true
title: "„AMD Zen“ procesoriai turės iki 32 branduolių"
author:
  display_name: Mindaugas Klumbis
  login: Katonas
  email: katonasf1@yahoo.com
  url: ''
author_login: Katonas
author_email: katonasf1@yahoo.com
wordpress_id: 9249
wordpress_url: http://localhost/site/new/_amd_zen_procesoriai_tures_iki_32_branduoliu/
date: '2016-02-03 10:10:30 +0200'
date_gmt: '2016-02-03 10:10:30 +0200'
categories:
- Naujienos
---
<p>
	<em><a href="https://lkml.org/lkml/2016/1/29/78">Pavie&scaron;intame</a></em> &bdquo;Linux&ldquo; pataisyme pastebėta įdomi informacija, kuri teigia, kad &bdquo;AMD Zen&ldquo; procesoriai turės iki 32 fizinių branduolių. Tuo pačiu atskleidžiami pana&scaron;umai tarp &bdquo;Zen&ldquo; ir &bdquo;Zeppelin&ldquo; kodinių pavadinimų.</p>
<p>
	&bdquo;Zeppelin&ldquo; kodinis pavadinimas primą kartą buvo paminėtas praėjusių metų rugpjūtį, o &bdquo;Linux&ldquo; atnaujinimas &scaron;iuos procesorius identifikuoja kaip priklausančius &bdquo;17h model 00h&ldquo; &scaron;eimai.</p>
<p>
	+ core_complex_id = (apicid &amp; ((1 &lt;&lt; c-&gt;x86_coreid_bits) - 1)) &gt;&gt; 3;</p>
<p>
	+ per_cpu(cpu_llc_id, cpu) = (socket_id &lt;&lt; 3) | core_complex_id;</p>
<p>
	Pagal atskleistą kodą manoma, kad vienas fizinis branduolys gebės dirbti dviem gijomis dėka SMT technologijos. Branduolių kompleksas, kitaip žinomas kaip modulis, bus sudarytas i&scaron; keturių branduolių, kurie dalinsis tam tikrai resursais. Tolimesnė eilutė nusako, kad viename silicyje galėsime pamatyti iki 8 branduolių kompleksų, kas būtų lygu 32 fiziniams branduoliams.</p>
<p>
	Priminsime, kad &bdquo;Zen&ldquo; procesoriai bus gaminami naudojant 14 nm litografiją, o jų pristatymas numatytas &scaron;ių metų gale. APU procesoriai pasirodys kiek vėliau, 2017 metų pradžioje. Naujieji AMD procesoriai palaikys DDR4 atmintį ir bus montuojami į AM4 lizdo pagrindines plok&scaron;tes. AMD žada, kad &scaron;ie procesoriai pasiūlys apie 40 % daugiau spartos per taktą lyginant su dabartiniais AMD procesoriais.&nbsp;</p>
<p style="text-align: center;">
	<a href="http://technews.lt/userfiles/AMD-40-IPC-Zen-Zen-.jpg"><img alt="" src="http://technews.lt/userfiles/AMD-40-IPC-Zen-Zen-.jpg" style="width: 464px; height: 261px;" /></a></p>
