# isaacs-kitchen
Isaac's Kitchen restaurant portfolio <nav>
  <a href="#home">Home</a>
  <a href="#menu">Menu</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>
</nav><h1 id="home">Isaac's Kitchen</h1>

<p>Delicious meals made fresh for you.</p>

<h2 id="menu">Our Menu</h2>

<button>Order Now</button>
<div class="food">
    <h3>Jollof Rice & Chicken</h3>
    <p>₦3,500</p>
</div>

<div class="food">
    <h3>Fried Rice & Chicken</h3>
    <p>₦4,000</p>
</div>
<div class="food">
  <h3>🍗 Jollof Rice & Chicken</h3>
  <p>₦3,500</p>
</div>

<div class="food">
  <h3>🍚 Fried Rice & Chicken</h3>
  <p>₦4,000</p>
</div>

<div class="food">
  <h3>🍝 Spaghetti</h3>
  <p>₦3,000</p>
</div>
<div class="food">
    

<h2 id="about">About Us</h2>
<button>Order Now</button>
<p>
We serve delicious, freshly prepared meals
for individuals, families and events.
</p>

<h2 id="contact">Contact Us</h2>

<p>📍 Makurdi, Benue State</p>
<p>📞 08136035069</p>email-tertesisaac@gmail.com
<p></p>body {
    * {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #fff8f0;
  color: #222;
  text-align: center;
}

/* Navigation */
nav {
  background: #222;
  padding: 18px 10px;
  position: sticky;
  top: 0;
  z-index: 100;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 12px;
  font-size: 17px;
  font-weight: bold;
}

nav a:hover {
  color: #ffb703;
}

/* Main heading */
h1 {
  font-size: 48px;
  margin: 50px 10px 15px;
  color: #d35400;
}

body > p {
  font-size: 20px;
  margin-bottom: 50px;
}

/* Section headings */
h2 {
  font-size: 34px;
  margin: 50px 0 30px;
  color: #d35400;
}

h3 {
  font-size: 24px;
  margin-bottom: 15px;
}

/* Food cards */
.food {
  background: white;
  padding: 25px;
  margin: 25px auto;
  max-width: 380px;
  border-radius: 15px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.12);
  transition: transform 0.2s, box-shadow 0.2s;
}

.food:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.18);
}

.food p {
  font-size: 20px;
  font-weight: bold;
  color: #d35400;
}

/* About section */
#about {
  margin-top: 70px;
}

#about + p {
  max-width: 600px;
  margin: auto;
  padding: 0 20px;
  font-size: 19px;
  line-height: 1.7;
}

/* Button */
button {
  background: #d35400;
  color: white;
  padding: 14px 30px;
  border: none;
  border-radius: 30px;
  font-size: 18px;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  background: #a84300;
  transform: scale(1.05);
}

/* Mobile */
@media (max-width: 600px) {
  h1 {
    font-size: 40px;
  }

  h2 {
    font-size: 30px;
  }

  nav a {
    margin: 0 7px;
    font-size: 15px;
  }

  .food {
    margin: 20px;
  }

