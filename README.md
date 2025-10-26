# Ex.07 Restuarant Website
## Date:26-10-2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
index.html
'''
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Harry Potter's Café | Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body class="home"> 
    
  <header>
    <div class="logo">⚡ Harry Potter's Café</div>
    <nav>
      <a href="index.html" class="active">Home</a>
      <a href="food.html">Dishes</a>
      <a href="chef.html">Chefs</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Harry Potter's Café</h1>
    <p>Step into a world of enchantment and flavor! Inspired by the magical universe of Hogwarts, our café brings you bewitching dishes, brewed potions, and desserts straight from the wizarding world.</p>
    <a href="food.html" class="btn">Explore the Menu ⚡</a>
  </section>

  <footer>
    <p>© 2025 Harry Potter's Café | Where Magic Meets Taste ✨</p>
  </footer>

</body>
</html>

'''
food.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Harry Potter's Café - Dishes</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<body class="food"></body>

<header>
  <div class="logo">⚡ Harry Potter's Café</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="food.html" class="active">Dishes</a>
    <a href="chef.html">Chefs</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <h2>Our Magical Dishes</h2>
  <div class="grid">
    <div class="card">
      <img src="HPFOOD1.webp" alt="Butterbrew Soup">
      <h3>Hogwarts Feast Combo</h3>
      <p>Warm buttery ale-based broth — comfort in a cauldron.</p>
    </div>

    <div class="card">
      <img src="HPFOOD2.jpg" alt="Pumpkin Pasties">
      <h3>Polyjuice Potion</h3>
      <p>Flaky golden pastry filled with sweet pumpkin and sage.</p>
    </div>

    <div class="card">
      <img src="HPFOOD3.jpeg" alt="Firewhisky Ribs">
      <h3>Deathly Hallows Potato Trio</h3>
      <p>Spicy ribs glazed with a fiery potion of Firewhisky.</p>
    </div>

    <div class="card">
      <img src="HPFOOD4.jpg" alt="Chocolate Frog Mousse">
      <h3>HP's SPL B'day CAKE</h3>
      <p>A sweet spell of rich chocolate mousse, pure wizard delight.</p>
    </div>
  </div>
</section>

<footer>
  © 2025 Harry Potter's Café — Brewed with magic and butterbeer ✨
</footer>

</body>
</html>

```
chef.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Harry Potter's Café - Chefs</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<body class="chef"></body>

<header>
  <div class="logo">⚡ Harry Potter's Café</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="food.html">Dishes</a>
    <a href="chef.html" class="active">Chefs</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <h2>Our magical Chefs</h2>
  <div class="grid">
    <div class="card">
      <img src="image copy 6.png" alt="Madam Marigold">
      <h3>Madam Marigold</h3>
      <p>Head Witch of Potions — specializes in enchanted broths.</p>
    </div>

    <div class="card">
      <img src="image copy 8.png" alt="Garrick Flame">
      <h3>Gordan Ramsay</h3>
      <p>Master of Fire Charms — grill expert known for smoky Firewhisky trio.</p>
    </div>

    <div class="card">
      <img src="image copy 7.png" alt="Seraphine Spice">
      <h3>Garrick Flame</h3>
      <p>Sweet Alchemist — creator of the sweety cakes.</p>
    </div>
  </div>
</section>

<footer>
  © 2025 Harry Potter's Café — Magic in every recipe 🪄
</footer>

</body>
</html>

```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Harry Potter's Café | Contact</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<body class="contact"></body>
  
  <header>
    <div class="logo">⚡ Harry Potter's Café</div>
    <nav>
      <a href="index.html">Home</a>
      <a href="food.html">Dishes</a>
      <a href="chef.html">Chefs</a>
      <a href="contact.html" class="active">Contact</a>
    </nav>
  </header>

  <section style="text-align:center; padding:80px 20px;">
    <h2>Contact Us</h2>
    <p style="margin:20px 0; font-size:20px; color:var(--muted);">
      We'd love to hear from you! Reach out to us through any of the methods below:
    </p>

    <div style="margin-top:40px; font-size:25px; line-height:2;">
      <p>📍 Address: 123 Diagon Alley, Wizarding District, London</p>
      <p>📞 Phone: +44 1234 567890</p>
      <p>📧 Email: hello@harrypotterscafe.com</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Harry Potter's Café | Where Magic Meets Taste ✨</p>
  </footer>

</body>
</html>

```
style.css
```
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@700&family=Cormorant+Garamond:wght@400;600;700&display=swap');

:root {
  --paper: #f3e9d7;
  --accent: #e3971b;
  --muted: #e9e9e9;
  --card: rgba(17,19,26,0.85); 
}

* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: 'Cormorant Garamond', serif;
  color: var(--paper);
  font-size: 20px;
  line-height: 2;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

body.home { background-image: url('image copy.png'); }
body.food { background-image: url('image copy 2.png'); }
body.chef { background-image: url('image copy 3.png'); }
body.contact { background-image: url('image copy 5.png'); }

body::before {
  content: '';
  position: fixed;
  top: 0; left: 0; width: 100%; height: 100%;
  background: rgba(11,16,32,0.5);
  z-index: -1;
}

header {
  display: flex; justify-content: space-between; align-items: center;
  padding: 20px 30px; 
  position: sticky; top: 0;
  background: rgba(0,0,0,0.4); backdrop-filter: blur(6px);
  border-bottom: 1px solid rgba(255,255,255,0.1);
}

header .logo {
  font-family: 'Cinzel', serif;
  font-size: 50px; 
  color: var(--accent);
  text-shadow: 0 0 12px rgba(227, 177, 40, 0.9);
}

nav a {
  color: var(--accent); 
  text-decoration: none; 
  margin-left: 30px; 
  font-weight: 700;
  font-size: 40px; 
  transition: color 0.3s;
}
nav a:hover, nav a.active { color: var(--paper); }

.hero { text-align: center; padding: 120px 20px; }
.hero h1 { 
  font-family: 'Cinzel', serif; 
  font-size: 60px;
  color: var(--accent); 
  max-width: 2000px; 
  margin-bottom: 30px; 
  text-shadow: 0 0 8px rgba(176,139,73,0.7);
}
.hero p { 
  font-size: 30px; 
  color: var(--muted); 
  max-width: 1000px; 
  margin: 0 auto 30px; 
  
}

.btn {
  display: inline-block; 
  background: var(--accent); 
  color: #120802;
  font-weight: 700; 
  padding: 16px 28px; 
  border-radius: 12px; 
  text-decoration: none;
  font-size: 40px;
  transition: transform 0.2s, box-shadow 0.2s;
}
.btn:hover { transform: scale(1.05); box-shadow: 0 0 12px var(--accent); }

section { padding: 100px 40px; max-width: 1000px; margin: auto; }
h2 { 
  font-family: 'Cinzel', serif; 
  color: var(--accent); 
  font-size: 70px; 
  margin-bottom: 35px; 
  text-align: center; 
  text-shadow: 0 0 6px rgba(176,139,73,0.6);
}

.grid {
  display: flex;
  flex-wrap: wrap;
  gap: 50px;
  justify-content: center;
}

.card {
  flex: 0 0 400px; 
  background: var(--card);
  border-radius: 20px; 
  overflow: hidden;
  text-align: center; 
  padding: 70px 10px; 
  transition: transform 0.3s, box-shadow 0.3s;
}
.card:hover { transform: translateY(-10px); box-shadow: 0 5px 20px rgba(176,139,73,0.6); }
.card img { width: 100%; height: 200px; object-fit: cover; border-radius: 8px; margin-bottom: 15px; }
.card h3 { margin-bottom: 10px; color: var(--accent); font-size: 50px; }
.card p { color: var(--muted); font-size: 24px; }

section.contact-info { 
  text-align: center; 
  padding: 100px 20px; 
  line-height: 2.2; 
  font-size: 22px; 
  color: var(--muted); 
}

footer { 
  text-align: center; 
  padding: 60px; 
  font-size: 35px; 
  color: var(--muted); 
  border-top: 1px solid rgba(255, 255, 255, 0.066); 
  margin-top: auto; 
}

@media (max-width: 768px) {
  .hero h1 { font-size: 48px; }
  .hero p { font-size: 20px; }
  nav a { margin-left: 20px; font-size: 18px; }
  .card { flex: 0 0 100%; }
}
@media (max-width: 480px) {
  .hero h1 { font-size: 36px; }
  .hero p { font-size: 18px; }
  .btn { font-size: 18px; padding: 14px 22px; }
  h2 { font-size: 32px; }
  section.contact-info { font-size: 20px; }
}

```

## OUTPUT:

![alt text](<Screenshot 2025-10-26 122302.png>)

![alt text](<Screenshot 2025-10-26 122316.png>)

![alt text](<Screenshot 2025-10-26 122350.png>)

![alt text](<Screenshot 2025-10-26 122359.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
