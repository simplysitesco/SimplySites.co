[index.html](https://github.com/user-attachments/files/25961710/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SimplySites.co</title>
<style>
body { margin:0; font-family:'Segoe UI', sans-serif; background:#111; color:#fff; line-height:1.6; }
header { text-align:center; padding:100px 20px; background:linear-gradient(135deg,#6a11cb,#2575fc); background-size:400% 400%; animation:gradShift 12s ease infinite; }
header h1 { font-size:3em; margin-bottom:10px; }
header p { font-size:1.2em; }
section { max-width:900px; margin:50px auto; padding:25px; background:rgba(0,0,0,0.2); border-radius:12px; }
h2 { text-align:center; margin-bottom:20px; }
.services { display:flex; flex-wrap:wrap; justify-content:space-around; }
.service { flex:1 1 250px; margin:10px; padding:15px; background:rgba(255,255,255,0.1); border-radius:10px; text-align:center; }
form { display:flex; flex-direction:column; align-items:center; }
input, textarea { width:80%; padding:10px; margin-top:10px; border:none; border-radius:6px; }
button { padding:12px 25px; margin-top:15px; border:none; border-radius:8px; background:#fff; color:#2575fc; font-weight:bold; cursor:pointer; }
button:hover { background:#2575fc; color:#fff; }
footer { text-align:center; padding:30px; background:#222; margin-top:50px; font-size:0.9em; }
@keyframes gradShift { 0%{background-position:0% 50%;}50%{background-position:100% 50%;}100%{background-position:0% 50%;} }
@media(max-width:600px) { .services { flex-direction:column; } input, textarea { width:90%; } }
</style>
</head>
<body>

<header>
<h1>SimplySites.co</h1>
<p>Professional websites for your business — starting at $200</p>
</header>

<section id="services">
<h2>Our Services</h2>
<div class="services">
  <div class="service">
    <h3>Custom Website</h3>
    <p>Responsive, modern websites built for your business needs.</p>
    <p><strong>Price: $200</strong></p>
  </div>
  <div class="service">
    <h3>Website Upgrade</h3>
    <p>Update your old website with a fresh, modern look.</p>
    <p><strong>Price: $150</strong></p>
  </div>
  <div class="service">
    <h3>Landing Page</h3>
    <p>One-page website optimized for conversions and simplicity.</p>
    <p><strong>Price: $100</strong></p>
  </div>
</div>
</section>

<section id="contact">
<h2>Request a Website</h2>
<form action="https://formspree.io/f/xjgawqea" method="POST">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="email" name="email" placeholder="Your Email" required>
  <textarea name="message" placeholder="I’d like a website..." rows="5" required></textarea>
  <button type="submit">Send Request</button>
</form>
<p style="text-align:center; margin-top:10px;">All submissions go directly to your email.</p>
</section>

<footer>
<p>Contact us at: <a href="mailto:simplysites.co@gmail.com" style="color:#fff;">simplysites.co@gmail.com</a></p>
<p>© 2026 SimplySites.co</p>
</footer>

</body>
</html>
