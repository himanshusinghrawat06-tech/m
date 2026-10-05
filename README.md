<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>GrowthLab | Digital Marketing Agency</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#fff;--bg2:#fafafa;--tx:#111;--mut:#6b7280;--pri:#111;--acc:#111;--card:#fff;--bd:#ececec;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
:root[data-theme="dark"]{--bg:#fff;--bg2:#fafafa;--tx:#111;--mut:#6b7280;--card:#fff;--bd:#ececec}
html{scroll-behavior:smooth;scroll-padding-top:calc(env(safe-area-inset-top,0px) + 70px)}
*{box-sizing:border-box}
body{margin:0;background:#fff;color:var(--tx);font-family:'Poppins',system-ui,sans-serif;line-height:1.7;font-weight:400}
a{color:inherit;text-decoration:none}
.w{max-width:1080px;margin:0 auto;padding:0 24px}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:9;background:#fff;border-bottom:1px solid var(--bd)}
nav{display:flex;align-items:center;justify-content:space-between;height:68px;gap:12px}
.logo{font-weight:600;font-size:20px;letter-spacing:-.02em}.logo span{color:var(--mut)}
nav ul{display:flex;gap:28px;list-style:none;margin:0;padding:0;font-size:14px;color:var(--mut)}
nav ul a:hover{color:var(--tx)}
.btn{display:inline-block;background:#111;color:#fff;padding:11px 24px;border-radius:6px;font-weight:500;font-size:14px;border:1px solid #111;cursor:pointer}
.btn.o{background:#fff;color:#111;border-color:var(--bd)}.btn.o:hover{border-color:#111}
.btn.a{background:#111}
@media(max-width:820px){nav ul{display:none}}
.hero{background:#fff;padding:90px 0 70px}
.hg{display:grid;grid-template-columns:1.2fr 1fr;gap:56px;align-items:center}
.tag{color:var(--mut);font-weight:500;font-size:12px;letter-spacing:.14em;text-transform:uppercase}
h1{font-size:clamp(32px,5vw,52px);line-height:1.12;margin:14px 0 18px;font-weight:600;letter-spacing:-.03em}
h1 em{font-style:normal;color:var(--mut)}
.hero p{color:var(--mut);max-width:500px}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin:28px 0}
.mini{display:flex;gap:36px;flex-wrap:wrap;margin-top:32px;padding-top:24px;border-top:1px solid var(--bd)}
.mini b{display:block;font-size:20px;font-weight:600}.mini span{font-size:13px;color:var(--mut)}
.card{background:#fff;border:1px solid var(--bd);border-radius:12px;padding:28px}
form{display:grid;gap:12px}
input,select,textarea{width:100%;padding:12px 14px;border-radius:6px;border:1px solid var(--bd);background:#fff;color:var(--tx);font:inherit;font-size:14px;outline:0}
input:focus,select:focus{border-color:#111}
form h3{margin:0 0 6px;font-weight:600}
@media(max-width:820px){.hg{grid-template-columns:1fr}}
section{padding:90px 0}
.alt{background:var(--bg2);border-top:1px solid var(--bd);border-bottom:1px solid var(--bd)}
.sh{text-align:center;max-width:600px;margin:0 auto 52px}
.sh h2{font-size:clamp(24px,4vw,34px);margin:10px 0;font-weight:600;letter-spacing:-.02em}
.sh p{color:var(--mut);margin:0}
.grid{display:grid;gap:20px}
.g4{grid-template-columns:repeat(auto-fit,minmax(230px,1fr))}
.g3{grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
.ic{width:40px;height:40px;border-radius:8px;border:1px solid var(--bd);display:grid;place-items:center;font-size:18px;margin-bottom:16px;filter:grayscale(1)}
.card h3{margin:0 0 8px;font-size:17px;font-weight:600}.card p{margin:0;color:var(--mut);font-size:14px}
.card a.l{display:inline-block;margin-top:14px;font-weight:500;font-size:14px;border-bottom:1px solid #111}
.num{width:34px;height:34px;border-radius:50%;border:1px solid #111;display:grid;place-items:center;font-weight:500;font-size:14px;margin-bottom:16px}
.about{display:grid;grid-template-columns:1fr 1fr;gap:56px;align-items:center}
.about ul{padding:0;list-style:none;color:var(--mut);margin:16px 0 24px}.about li{padding:4px 0}.about li:before{content:"— ";color:#111}
.ph{aspect-ratio:4/3;border-radius:12px;background:var(--bg2);border:1px solid var(--bd);display:grid;place-items:center;color:var(--mut);font-size:14px;text-align:center;padding:20px}
@media(max-width:820px){.about{grid-template-columns:1fr}}
.chips{display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
.chips span{padding:8px 18px;border:1px solid var(--bd);background:#fff;border-radius:999px;font-size:14px}
.stats{text-align:center}.stats b{font-size:36px;font-weight:600;display:block;letter-spacing:-.02em}.stats span{color:var(--mut);font-size:14px}
.price{position:relative;text-align:center}
.price.pop{border:1.5px solid #111}
.pop:before{content:"MOST POPULAR";position:absolute;top:-11px;left:50%;transform:translateX(-50%);background:#111;color:#fff;font-size:10px;letter-spacing:.1em;font-weight:500;padding:3px 12px;border-radius:999px}
.amt{font-size:42px;font-weight:600;margin:8px 0;letter-spacing:-.03em}
.price ul{list-style:none;padding:0;margin:16px 0 24px;text-align:left;font-size:14px;color:var(--mut)}
.price li{padding:7px 0;border-bottom:1px solid var(--bd)}
.free{font-size:11px;color:var(--mut);letter-spacing:.06em}
.t p{font-size:15px;color:var(--tx)}.t b{display:block;margin-top:14px;font-size:13px;font-weight:500;color:var(--mut)}
details{border-bottom:1px solid var(--bd);padding:18px 0}
summary{cursor:pointer;font-weight:500}
details p{color:var(--mut);margin:10px 0 0;font-size:14px}
.band{background:#fff;color:var(--tx);text-align:center;padding:90px 0;border-top:1px solid var(--bd)}
.band h2{margin:0 0 10px;font-weight:600;font-size:clamp(24px,4vw,34px);letter-spacing:-.02em}
.band p{color:var(--mut);margin:0 0 24px}
footer{background:#fff;color:var(--mut);padding:56px 0 24px;font-size:14px;border-top:1px solid var(--bd)}
.fg{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:32px}
footer h4{color:#111;margin:0 0 10px;font-weight:600}footer a{display:block;padding:3px 0}footer a:hover{color:#111}
.cp{border-top:1px solid var(--bd);margin-top:36px;padding-top:18px;text-align:center;font-size:13px}
.wa{position:fixed;right:18px;bottom:calc(18px + env(safe-area-inset-bottom,0px));background:#111;color:#fff;width:50px;height:50px;border-radius:50%;display:grid;place-items:center;font-size:22px;z-index:9;filter:grayscale(1)}
</style>
</head>
<body>
<header><div class="w"><nav>
<a class="logo" href="#">Growth<span>Lab</span></a>
<ul><li><a href="#services">Services</a></li><li><a href="#process">Process</a></li><li><a href="#why">Why Us</a></li><li><a href="#faq">FAQ</a></li><li><a href="#contact">Contact</a></li></ul>
<a class="btn" href="#contact">Free Consultation</a>
</nav></div></header>

<div class="hero"><div class="w hg">
<div>
<div class="tag">Digital Marketing Agency</div>
<h1>Get More Customers. <em>Grow Your Business Online.</em></h1>
<p>SEO, Google Ads, social media and websites that turn visitors into enquiries. Simple strategy, honest reporting, real results.</p>
<div class="cta"><a class="btn" href="#contact">Get a Free Consultation</a><a class="btn o" href="#services">See Services</a></div>
<div class="mini"><div><b>2+ Years</b><span>Experience</span></div><div><b>4</b><span>Happy Clients</span></div><div><b>1</b><span>Website Delivered</span></div></div>
</div>
<div class="card"><form id="q">
<h3>Get a Free Consultation</h3>
<select id="s" required><option value="">Select service *</option><option>SEO</option><option>Google Ads / PPC</option><option>Social Media Marketing</option><option>Website Design</option><option>Not sure, need advice</option></select>
<input id="n" placeholder="Your name *" required><input id="p" type="tel" placeholder="Phone number *" required>
<button class="btn" type="submit">Send on WhatsApp</button></form></div>
</div></div>

<section id="services" class="alt"><div class="w">
<div class="sh"><div class="tag">Services</div><h2>What I Can Do For Your Business</h2><p>Everything you need to get found, get clicks and get customers.</p></div>
<div class="grid g4">
<div class="card"><div class="ic">🔍</div><h3>SEO</h3><p>Rank higher on Google with on-page, technical and local SEO so the right people find you.</p></div>
<div class="card"><div class="ic">🎯</div><h3>Google Ads / PPC</h3><p>Targeted ad campaigns that bring ready-to-buy customers while keeping your cost per lead low.</p></div>
<div class="card"><div class="ic">📱</div><h3>Social Media Marketing</h3><p>Content and campaigns on Instagram, Facebook and LinkedIn that build your brand and generate leads.</p></div>
<div class="card"><div class="ic">💻</div><h3>Website Design</h3><p>Fast, mobile-friendly websites and landing pages built to convert visitors into enquiries.</p></div>
</div></div></section>

<section id="process"><div class="w">
<div class="sh"><div class="tag">Process</div><h2>Simple Steps to Results</h2></div>
<div class="grid g4">
<div class="card"><div class="num">1</div><h3>Understand</h3><p>We discuss your business, audience, goals and budget.</p></div>
<div class="card"><div class="num">2</div><h3>Plan</h3><p>A clear marketing plan with channels, timeline and targets.</p></div>
<div class="card"><div class="num">3</div><h3>Execute</h3><p>Campaigns, SEO and content go live and are tested.</p></div>
<div class="card"><div class="num">4</div><h3>Report &amp; Improve</h3><p>Regular reports and ongoing optimization for better results.</p></div>
</div></div></section>

<section id="why" class="alt"><div class="w">
<div class="sh"><div class="tag">Why Us</div><h2>A Small Agency With Personal Attention</h2></div>
<div class="grid g3">
<div class="card"><h3>Direct Access</h3><p>You work directly with the person running your marketing. No middlemen, no confusion.</p></div>
<div class="card"><h3>Transparent Pricing</h3><p>Clear scope and clear costs from the start. No hidden charges.</p></div>
<div class="card"><h3>Focus On Results</h3><p>Every rupee spent is tracked, so you always know what is working.</p></div>
</div>
<div class="grid g3 stats" style="margin-top:20px">
<div class="card"><b>2+</b><span>Years of Experience</span></div><div class="card"><b>4</b><span>Happy Clients</span></div><div class="card"><b>1</b><span>Website Delivered</span></div>
</div></div></section>

<section id="faq"><div class="w" style="max-width:760px">
<div class="sh"><div class="tag">FAQs</div><h2>Frequently Asked Questions</h2></div>
<details open><summary>How soon will I see results?</summary><p>Google Ads can bring enquiries within days. SEO and social media are long-term and usually show clear growth in 3 to 6 months.</p></details>
<details><summary>How much does it cost?</summary><p>It depends on your goals and the services you pick. Book a free consultation and I will share a clear quote.</p></details>
<details><summary>Do you also build websites?</summary><p>Yes. I design simple, fast, mobile-friendly websites and landing pages made for lead generation.</p></details>
<details><summary>Will I get reports?</summary><p>Yes. You get regular, easy-to-read reports showing traffic, leads and campaign performance.</p></details>
</div></section>

<div class="band" id="contact"><div class="w"><h2>Ready to Grow Your Business?</h2><p>Message me and get a free consultation. No pressure.</p>
<a class="btn" href="https://wa.me/917217712125?text=Hi%2C%20I%20want%20to%20know%20about%20your%20digital%20marketing%20services.">Chat on WhatsApp</a> <a class="btn o" href="mailto:hello@yourdomain.com">hello@yourdomain.com</a></div></div>

<footer><div class="w"><div class="fg">
<div><div class="logo" style="margin-bottom:8px">Growth<span>Lab</span></div>Digital marketing and web design for growing businesses.</div>
<div><h4>Services</h4><a href="#services">SEO</a><a href="#services">Google Ads</a><a href="#services">Social Media</a><a href="#services">Website Design</a></div>
<div><h4>Contact</h4><a href="tel:+917217712125">+91 72177 12125</a><a href="mailto:hello@yourdomain.com">hello@yourdomain.com</a><span>Your City, India</span></div>
</div><div class="cp">© 2026 GrowthLab. All rights reserved.</div></div></footer>
<a class="wa" href="https://wa.me/917217712125" aria-label="WhatsApp">💬</a>
<script>
document.getElementById('q').addEventListener('submit',function(e){e.preventDefault();
var t='Hi, I am '+n.value+'. I am interested in '+s.value+'. My number: '+p.value;
window.open('https://wa.me/917217712125?text='+encodeURIComponent(t),'_blank');});
</script>
</body>
</html>
