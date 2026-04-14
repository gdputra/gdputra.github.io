---
title: "Teams"
permalink: /teams/
---

I have been privileged to collaborate with highly motivated students and colleagues, enabling us to conduct quality research together.

<div class="team-slider" id="team-slider">
	<style>
		#team-slider {max-width:600px;margin:0 auto;position:relative}
		#team-slider .slides {position:relative;overflow:hidden;width:600px;height:400px;margin-bottom:1rem}
		#team-slider .slides img {position:absolute;top:0;left:0;width:600px;height:400px;object-fit:cover;opacity:0;transition:opacity .6s}
		#team-slider .slides img.active{opacity:1}
		#team-slider .controls{text-align:center}
		#team-slider .dot{display:inline-block;width:10px;height:10px;margin:0 4px;background:#ccc;border-radius:50%;cursor:pointer}
		#team-slider .dot.active{background:#333}
		#team-slider .nav-btn{position:absolute;top:50%;transform:translateY(-50%);background:rgba(0,0,0,0.5);color:#fff;border:none;padding:8px 12px;cursor:pointer;border-radius:4px;z-index:2}
		#team-slider .nav-btn:hover{background:rgba(0,0,0,0.65)}
		#team-slider .prev{left:8px}
		#team-slider .next{right:8px}
	</style>
	<div class="slides">
        <img src="../images/carousel/trustcom-2025.jpeg" alt="Trustcom 2025" data-caption="Maulidi at IEEE Trustcom 2025 in Guiyang, China.">
        <img src="../images/carousel/skripsi-2025.jpeg" alt="Skripsi Team 2025" data-caption="Our undergraduate research team - 2025.">
		<img src="../images/carousel/metacom-2025.jpeg" alt="Metacom 2025" class="active" data-caption="Our group at IEEE Metacom 2025 in Seoul, South Korea.">
		<img src="../images/carousel/icbc-2025.jpg" alt="ICBC 2025" class="active" data-caption="Our group at IEEE ICBC 2025 in Pisa, Italy.">
		<img src="../images/carousel/skripsi-2024.jpg" alt="Skripsi Team 2024" data-caption="Our undergraduate research team - 2024.">
		<img src="../images/carousel/skripsi-2023.png" alt="Skripsi Team 2023" data-caption="Our undergraduate research team - 2023.">
	</div>
	<button class="nav-btn prev" aria-label="Previous">‹</button>
	<button class="nav-btn next" aria-label="Next">›</button>
	<div class="controls">
		<span class="dot active" data-index="0"></span>
		<span class="dot" data-index="1"></span>
		<span class="dot" data-index="2"></span>
        <span class="dot" data-index="3"></span>
        <span class="dot" data-index="4"></span>
        <span class="dot" data-index="5"></span>
	</div>
	<div class="slide-caption" id="team-slider-caption" style="text-align:center;font-style:italic;color:#555;margin-top:0.5rem"></div>
	<script>
		(function(){
			var i=0;
			var slides=document.querySelectorAll('#team-slider .slides img');
			var dots=document.querySelectorAll('#team-slider .dot');
			var captionDiv=document.getElementById('team-slider-caption');
			function show(n){
				slides.forEach((s,idx)=>s.classList.toggle('active',idx===n));
				dots.forEach((d,idx)=>d.classList.toggle('active',idx===n));
				i=n;
				captionDiv.textContent = slides[n] && slides[n].dataset && slides[n].dataset.caption ? slides[n].dataset.caption : '';
			}
			function resetInterval(){clearInterval(intervalId);intervalId = setInterval(next,3000);}
			function next(){i=(i+1)%slides.length;show(i);resetInterval();}
			function prev(){i=(i-1+slides.length)%slides.length;show(i);resetInterval();}
				dots.forEach(d=>d.addEventListener('click',e=>show(Number(e.target.dataset.index))));
				var prevBtn=document.querySelector('#team-slider .prev');
				var nextBtn=document.querySelector('#team-slider .next');
				if(prevBtn) prevBtn.addEventListener('click',prev);
				if(nextBtn) nextBtn.addEventListener('click',next);
				show(0);
				intervalId = setInterval(next,3000);
			})();
	</script>
</div>

## Research Associate

**Muhammad Shidiq** - <a href="https://www.linkedin.com/in/shidiq-muhammad-72972140/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Research associate in climate and energy modeling._

## Master's Students

**Maulidi Adi Prasetia** - <a href="https://id.linkedin.com/in/maulidi-adi" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Topic: multi-modal privacy preserving federated learning for mobile edge computing._

**Rahmat Ismoyo Putro** - <a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Topic: anomaly detection in AMR data with machine learning (PLN)._

**Godwin Amoako Atta** - <a href="https://gh.linkedin.com/in/godwin-amoako-atta-a0083699" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Topic: decentralized identities for secure communication._

**Muhammad Hilya S D Yasin** - <a href="https://www.linkedin.com/in/muhammad-hilya-surya-dilaga-yasin-533a92210/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Topic: Decentralized Physical Infrastructure Network (DePIN)._

## Bachelor's Students

**Fidelya Fredelina** - <a href="https://www.linkedin.com/in/fidelya-fredelina/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Undergraduate research project._

**Deren Tanaphan** - <a href="https://www.linkedin.com/in/derentanaphan/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Undergraduate research project._

**Adzka Bagus** - <a href="https://www.linkedin.com/in/adzka-bagus/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Undergraduate research project._

**Muhammad Grandiv Lava Putra** - <a href="https://www.linkedin.com/in/muhammad-grandiv-lava-putra-364b0324b/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Undergraduate research project._

## Research and Teaching Assistant

**Muhammad Khoirunas** - <a href="https://www.linkedin.com/in/khoirunas/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Current projects and research support._

**Theo Sanyoto** - <a href="https://www.linkedin.com/in/theo-immanuel-sanyoto-680b73327/" target="_blank"><i class="fab fa-linkedin"></i></a>  
_Teaching and project assistant._

## Past Members
Postgraduate
- Dimas Arief Rahman Kurniawan - <a href="https://www.linkedin.com/in/dimasark/" target="_blank"><i class="fab fa-linkedin"></i></a>  

Undergraduate

- Bintang Restu Bawono - <a href="https://www.linkedin.com/in/bintangrestubawono/" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Bagus Rakadyanto Oktavianto Putra - <a href="https://id.linkedin.com/in/bagus-rakadyanto-oktavianto-putra-0b0839221" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Aufa Nasywa Rahman - <a href="https://id.linkedin.com/in/aufarahman" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Franciscus Marselino Handoyo - <a href="https://id.linkedin.com/in/franciscus-marselino-handoyo-790822220" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Ahmad Zaki Akmal - <a href="https://id.linkedin.com/in/ahmad-zaki-akmal" target="_blank"><i class="fab fa-linkedin"></i></a>  

Short-term Project

- Polikarpus Arya Pradhanika - <a href="https://www.linkedin.com/in/polikarpus-arya-pradhanika/" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Muhammad Muqtada Alhaddad - <a href="https://www.linkedin.com/in/muhammad-muqtada-alhaddad-b02b44195/" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Muhammad Fathan Zahir - <a href="https://www.linkedin.com/in/muhammadfathanzahir/" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Muchammad Daniyal Kautsar - <a href="https://www.linkedin.com/in/mdaniyalk/" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Mochammad Novaldy Pratama Hakim - <a href="https://www.linkedin.com/in/novaldyph/" target="_blank"><i class="fab fa-linkedin"></i></a>  
- Maulana Anjari Anggorokasih - <a href="https://www.linkedin.com/in/maulana-anjari-anggorokasih/" target="_blank"><i class="fab fa-linkedin"></i></a>  
