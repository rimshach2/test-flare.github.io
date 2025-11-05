---
layout: default
title: Test FLARE
permalink: /team/
---
<link rel="stylesheet" href="{{ '/assets/css/team.css' | relative_url }}">
## Meet the People Behind Test FLARE
<div class="tab-container">
   <button class="tab-button active" onclick="openTab(event, 'people')">People</button>
   <button class="tab-button" onclick="openTab(event, 'academic')">Academic Partners</button>
   <button class="tab-button" onclick="openTab(event, 'industrial')">Industrial Partners</button>
</div>
<div id="people" class="tab-content" style="display:block">
   <div class="team-list">
      <div class="person">
         <img src="/phil.jpg" alt="Prof. Phil McMinn" width="200">
         <div class="person-name"><a href="https://mcminn.info/">Prof. Phil McMinn</a></div>
         <div class="person-role">Principal Investigator</div>
         <p class="person-bio">
            Prof. Phil McMinn iis well-known for his work in search-based software engineering (SBSE) and testing. His 2004 survey of search-based test data generation in the STVR journal is the most cited paper in software testing since 1992, while his 2010 IEEE TSE paper comparing search algorithms for test data generation is the most cited paper in software performance since 2010. He was named one of the top 15 most impactful mid-career software engineering researchers worldwide for 2010-2017, and has won seven best/distinguished paper awards at ASE, GECCO, ICST, ISSTA and SSBSE.
         </p>
      </div>
      <div class="person">
         <img src="/owain.jpg" alt="Dr. Owain Parry" width="200">
         <div class="person-name"><a href="https://o-parry.github.io/">Dr. Owain Parry</a></div>
         <div class="person-role">Research Associate</div>
         <p class="person-bio">
            Dr. Owain Parry is an early-career researcher with a proven track record in the field of flaky tests. He received his PhD in 2023 with a thesis on flaky tests titled <em>Understanding and Mitigating Flaky Software Test Cases. </em> He is the first author of six published papers on the topic, including a systematic literature survey of flaky tests that appeared in the ACM TOSEM journal.
         </p>
      </div>
      <div class="person">
         <img src="/rimsha.jpeg" alt="Rimsha Chaudhry" width="200">
         <div class="person-name">Rimsha Chaudhry</div>
         <div class="person-role">Associate</div>
         <p class="person-bio">
            Is a current PhD student at the University of Sheffield. Her research focuses on understanding and mitigating flaky tests—tests that produce inconsistent results without changes to the code.
         </p>
      </div>
   </div>
</div>
<div id="academic" class="tab-content academic-section" style="display:none">
   <div class="partner-card">
      <a href="https://www.fim.uni-passau.de/en/chair-for-software-engineering-ii" target="_blank"><strong>Prof. Gordon Fraser</strong></a>
      <p>Has published over 200 papers on software engineering and testing, regularly publishing in the top venues in software engineering.</p>
   </div>
   <div class="partner-card">
      <a href="https://www.cs.cmu.edu/~mhilton/" target="_blank"><strong>Prof. Michael Hilton</strong></a>
      <p>Researches software engineering and testing. His papers regularly appear at the top international software engineering conferences including ICSE, ASE, and FSE. He has particular expertise in flaky tests and is one of the most-cited authors on the topic.</p>
   </div>
   <div class="partner-card">
      <a href="https://www.gregorykapfhammer.com/" target="_blank"><strong>Prof. Gregory Kapfhammer</strong></a>
      <p>Researches software engineering and testing and has published over 60 papers, including ones in the IEEE TSE and ACM TOSEM journals, and the ASE, FSE, GECCO, ISSTA, and ICST conferences. He is an Associate Editor of the Journal of Software: Evolution and Process.</p>
   </div>
</div>
<div id="industrial" class="tab-content industrial-section" style="display:none">
   <div class="partner-card">
      <strong>Our Industrial Collaborators</strong>
      <p>We proudly collaborate with leading industry partners who help us advance research and innovation in software testing.</p>
      <ul class="partner-list">
         <li><a href="https://www.microsoft.com/" target="_blank">Microsoft</a></li>
         <li><a href="https://www.duolingo.com/" target="_blank">Duolingo</a></li>
         <li><a href="https://www.bjss.com/" target="_blank">BJSS</a></li>
         <li><a href="https://www.virtuoso.qa/" target="_blank">Virtuoso</a></li>
         <li><a href="https://cirata.com/" target="_blank">Cirata</a></li>
      </ul>
   </div>
</div>
<script>
   function openTab(evt, tabName) {
     var i, tabcontent, tablinks;
     tabcontent = document.getElementsByClassName("tab-content");
     for (i = 0; i < tabcontent.length; i++) {
       tabcontent[i].style.display = "none";
     }
     tablinks = document.getElementsByClassName("tab-button");
     for (i = 0; i < tablinks.length; i++) {
       tablinks[i].className = tablinks[i].className.replace(" active", "");
     }
     document.getElementById(tabName).style.display = "block";
     evt.currentTarget.className += " active";
   }
</script>
