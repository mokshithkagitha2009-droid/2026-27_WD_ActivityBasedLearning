TASK1:-
HTML:-
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav class="navbar">
        <h2 class="logo">MyPortfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home" class="hero">
    <div class="hero-content">
        <h3>Hello, I am</h3>
        <h1> KAGITHA MOKSHITH PANDU</h1>
        <h2>Web Developer & Student</h2>
        <p>
            Welcome to my personal portfolio website.
            I love coding, designing and learning new technologies.
        </p>
        <a href="#about" class="btn">Explore More</a>
    </div>

    <div class="profile">
        <img src="profile.jpg" alt="My Profile Photo">
    </div>
</section>

<section id="about" class="section">
    <h2>About Me</h2>
    <p>
        I am a passionate student interested in web development
        and programming. I enjoy creating websites and learning
        new technical skills.
    </p>
</section>

<section id="education" class="section">
    <h2>Educational Qualifications</h2>
    <div class="cards">
        <div class="card">
            <h3>Graduation</h3>
            <p>B.Tech / Degree</p>
            <p>NRI UNIVERSITY</p>
            <p>Year: 2026 - Present</p>
        </div>

        <div class="card">
            <h3>Intermediate</h3>
            <p>SRI SRINIVASA GRAVIITY</p>
            <p>Percentage: 85%</p>
        </div>

        <div class="card">
            <h3>School</h3>
            <p>NARAYANA</p>
            <p>Percentage: 90%</p>
        </div>
    </div>
</section>

<section id="skills" class="section">
    <h2>Technical Skills</h2>
    <div class="skills">
        <div>HTML <span>90%</span></div>
        <div>CSS <span>85%</span></div>
        <div>Python <span>75%</span></div>
        <div>Java <span>65%</span></div>
    </div>
</section>

<section id="hobbies" class="section">
    <h2>My Hobbies</h2>
    <div class="cards">
        <div class="card">Coding</div>
        <div class="card">Listening to Music</div>
        <div class="card">Reading Books</div>
        <div class="card">Playing Games</div>
    </div>
</section>

<section id="projects" class="section">
    <h2>My Projects</h2>
    <div class="cards">
        <div class="card">
            <h3>Portfolio Website</h3>
            <p>A personal website using HTML and CSS.</p>
        </div>

        <div class="card">
            <h3>Student Management System</h3>
            <p>A student information system using Python.</p>
        </div>

        <div class="card">
            <h3>Calculator</h3>
            <p>A simple calculator application.</p>
        </div>
    </div>
</section>

<section id="achievements" class="section">
    <h2>Achievements</h2>
    <div class="card">
        <p>🏆 Completed HTML and CSS Certification.</p>
        <p>🏆 Participated in College Technical Events.</p>
        <p>🏆 Completed Python Programming Course.</p>
    </div>
</section>

<section id="resume" class="section">
    <h2>My Resume</h2>
    <p>Click below to download my resume.</p>
    <a href="resume.pdf" download class="btn">
        Download Resume
    </a>
</section>

<section id="contact" class="section">
    <h2>Contact Me</h2>
    <p>Email: mokshithkagitha2009@gmail.com</p>
    <p>Phone: +91 7997666446</p>
    <p>Location: Andhra Pradesh, India</p>
    <a href="mokshithkagitha2009@gmail.com" class="btn">
        Send Email
    </a>
</section>

<footer>
    <p>© 2026 KAGITHA MOKSHITH PANDU. All Rights Reserved.</p>
</footer>

</body>
</html>
CSS:-


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav class="navbar">
        <h2 class="logo">MyPortfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home" class="hero">
    <div class="hero-content">
        <h3>Hello, I am</h3>
        <h1> KAGITHA MOKSHITH PANDU</h1>
        <h2>Web Developer & Student</h2>
        <p>
            Welcome to my personal portfolio website.
            I love coding, designing and learning new technologies.
        </p>
        <a href="#about" class="btn">Explore More</a>
    </div>

    <div class="profile">
        <img src="profile.jpg" alt="My Profile Photo">
    </div>
</section>

<section id="about" class="section">
    <h2>About Me</h2>
    <p>
        I am a passionate student interested in web development
        and programming. I enjoy creating websites and learning
        new technical skills.
    </p>
</section>

<section id="education" class="section">
    <h2>Educational Qualifications</h2>
    <div class="cards">
        <div class="card">
            <h3>Graduation</h3>
            <p>B.Tech / Degree</p>
            <p>NRI UNIVERSITY</p>
            <p>Year: 2026 - Present</p>
        </div>

        <div class="card">
            <h3>Intermediate</h3>
            <p>SRI SRINIVASA GRAVIITY</p>
            <p>Percentage: 85%</p>
        </div>

        <div class="card">
            <h3>School</h3>
            <p>NARAYANA</p>
            <p>Percentage: 90%</p>
        </div>
    </div>
</section>

<section id="skills" class="section">
    <h2>Technical Skills</h2>
    <div class="skills">
        <div>HTML <span>90%</span></div>
        <div>CSS <span>85%</span></div>
        <div>Python <span>75%</span></div>
        <div>Java <span>65%</span></div>
    </div>
</section>

<section id="hobbies" class="section">
    <h2>My Hobbies</h2>
    <div class="cards">
        <div class="card">Coding</div>
        <div class="card">Listening to Music</div>
        <div class="card">Reading Books</div>
        <div class="card">Playing Games</div>
    </div>
</section>

<section id="projects" class="section">
    <h2>My Projects</h2>
    <div class="cards">
        <div class="card">
            <h3>Portfolio Website</h3>
            <p>A personal website using HTML and CSS.</p>
        </div>

        <div class="card">
            <h3>Student Management System</h3>
            <p>A student information system using Python.</p>
        </div>

        <div class="card">
            <h3>Calculator</h3>
            <p>A simple calculator application.</p>
        </div>
    </div>
</section>

<section id="achievements" class="section">
    <h2>Achievements</h2>
    <div class="card">
        <p>🏆 Completed HTML and CSS Certification.</p>
        <p>🏆 Participated in College Technical Events.</p>
        <p>🏆 Completed Python Programming Course.</p>
    </div>
</section>

<section id="resume" class="section">
    <h2>My Resume</h2>
    <p>Click below to download my resume.</p>
    <a href="resume.pdf" download class="btn">
        Download Resume
    </a>
</section>

<section id="contact" class="section">
    <h2>Contact Me</h2>
    <p>Email: mokshithkagitha2009@gmail.com</p>
    <p>Phone: +91 7997666446</p>
    <p>Location: Andhra Pradesh, India</p>
    <a href="mokshithkagitha2009@gmail.com" class="btn">
        Send Email
    </a>
</section>

<footer>
    <p>© 2026 KAGITHA MOKSHITH PANDU. All Rights Reserved.</p>
</footer>

</body>
</html>
TASK2:-
HTML:-

<!DOCTYPE html>
<html>
<head>
    <title>Sweet Bakery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🍰 Sweet Bakery</h1>
    <p>Fresh Cakes & Delicious Pastries</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#offers">Offers</a>
    <a href="#contact">Contact</a>
</nav>

<section class="banner" id="home">
    <h1>Welcome to Sweet Bakery</h1>
    <p>Freshly Baked With Love!</p>
    <button>Order Now</button>
</section>

<section id="products">
    <h2>Our Products</h2>

    <div class="container">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?w=500">
            <h3>Chocolate Cake</h3>
            <p>Price: ₹650</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1488477181946-6428a0291777?w=500">
            <h3>Fruit Pastry</h3>
            <p>Price: ₹90</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1499636136210-6f4ee915583e?w=500">
            <h3>Cookies</h3>
            <p>Price: ₹150</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?w=500">
            <h3>Butter Bread</h3>
            <p>Price: ₹120</p>
            <button>Buy Now</button>
        </div>

    </div>
</section>

<section class="offer" id="offers">
    <h2>Special Offers!</h2>
    <h3>15% Discount on All Cakes</h3>
    <p>Make your celebrations sweeter!</p>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Address: Vijayawada, Andhra Pradesh</p>
    <p>Phone: +91 9876543210</p>
    <p>Email: sweetbakery@gmail.com</p>
    <p>Opening Hours: 9 AM - 9 PM</p>
</section>

<footer>
    <p>© 2026 Sweet Bakery. All Rights Reserved.</p>
</footer>

</body>
</html>
css:-   

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #fff5ee;
}

header {
    background-color: #8b4513;
    color: white;
    text-align: center;
    padding: 25px;
}

nav {
    background-color: #d2691e;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 15px;
    font-weight: bold;
}

nav a:hover {
    color: yellow;
}

.banner {
    background-color: #ffe4c4;
    text-align: center;
    padding: 70px 20px;
}

.banner h1 {
    color: #8b4513;
    font-size: 40px;
    margin-bottom: 15px;
}

.banner p {
    margin-bottom: 20px;
}

button {
    background-color: #d2691e;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #8b4513;
}

#products {
    text-align: center;
    padding: 40px 20px;
}

#products h2 {
    color: #8b4513;
    margin-bottom: 25px;
}

.container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
}

.card {
    background-color: white;
    width: 230px;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 0 10px gray;
}

.card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
    border-radius: 8px;
}

.card h3 {
    color: #8b4513;
    margin: 12px;
}

.card p {
    margin-bottom: 12px;
}

.offer {
    background-color: #ffdab9;
    text-align: center;
    padding: 40px;
    color: #8b4513;
}

.offer h3 {
    margin: 15px;
}

.contact {
    background-color: #8b4513;
    color: white;
    text-align: center;
    padding: 30px;
}

.contact p {
    margin: 10px;
}

footer {
    background-color: #4b2410;
    color: white;
    text-align: center;
    padding: 15px;
}

@media (max-width: 600px) {
    nav a {
        display: inline-block;
        margin: 8px;
    }

    .banner h1 {
        font-size: 28px;
    }

    .card {
        width: 90%;
    }
}
TASK3:-     
HTML:-     

<!DOCTYPE html>
<html>
<head>
    <title>Foodie - Online Food Ordering</title>
    <link rel="stylesheet" href="task-2.css">
</head>
<body>

<header>
    <h1>🍔 Foodie</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#offers">Offers</a>
        <a href="#reviews">Reviews</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <h2>Delicious Food Delivered To Your Door</h2>
    <p>Fresh, tasty and affordable food at your fingertips!</p>
    <a href="#menu" class="btn">Order Now</a>
</section>

<section class="restaurant">
    <h2>Welcome to Foodie Restaurant</h2>
    <p>⭐ 4.8 Rating | 🕒 30 Minutes Delivery</p>
    <p>📍 Vijayawada | 📞 9876543210</p>
</section>

<section id="menu">
    <h2>Our Popular Menu</h2>

    <div class="food-container">

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=500" alt="Burger">
            <h3>Cheese Burger</h3>
            <p>Delicious cheese burger with fresh vegetables.</p>
            <h3>₹149</h3>
            <button>Order Now</button>
        </div>

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?w=500" alt="Pizza">
            <h3>Veg Pizza</h3>
            <p>Hot pizza with cheese and fresh toppings.</p>
            <h3>₹249</h3>
            <button>Order Now</button>
        </div>

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1563379091339-03246963d96c?w=500" alt="Biryani">
            <h3>Chicken Biryani</h3>
            <p>Traditional spicy chicken dum biryani.</p>
            <h3>₹199</h3>
            <button>Order Now</button>
        </div>

        <div class="food-card">
            <img src="https://images.unsplash.com/photo-1551024506-0bccd828d307?w=500" alt="Donuts">
            <h3>Chocolate Donut</h3>
            <p>Sweet and delicious chocolate donut.</p>
            <h3>₹99</h3>
            <button>Order Now</button>
        </div>

    </div>
</section>

<section class="offer" id="offers">
    <h2>🎉 Special Offers</h2>
    <p>Get 20% OFF on your first order!</p>
    <p>Use Coupon Code: FOOD20</p>
</section>

<section id="reviews">
    <h2>Customer Reviews</h2>
    <div class="review">
        <p>⭐⭐⭐⭐⭐</p>
        <p>"Very tasty food and fast delivery!"</p>
        <h4>- Rahul</h4>
    </div>
    <div class="review">
        <p>⭐⭐⭐⭐⭐</p>
        <p>"Amazing taste and excellent service."</p>
        <h4>- Priya</h4>
    </div>
</section>

<footer id="contact">
    <h2>Contact Us</h2>
    <p>Email: foodie@gmail.com</p>
    <p>Phone: 9876543210</p>
    <p>© 2026 Foodie Restaurant. All Rights Reserved.</p>
</footer>

</body>
</html>
CSS:-       

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #fff8f0;
    color: #333;
}

/* Header */
header {
    background: #ff5722;
    color: white;
    padding: 18px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

header h1 {
    font-size: 30px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
    font-weight: bold;
}

nav a:hover {
    color: #ffe082;
}

/* Home Section */
.hero {
    background: linear-gradient(#0008, #0008),
    url("https://images.unsplash.com/photo-1504674900247-0877df9cc836?w=1200");
    background-size: cover;
    background-position: center;
    text-align: center;
    padding: 110px 20px;
    color: white;
}

.hero h2 {
    font-size: 40px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 25px;
}

.btn {
    background: #ff5722;
    color: white;
    padding: 13px 28px;
    text-decoration: none;
    border-radius: 25px;
}

/* Restaurant */
.restaurant {
    text-align: center;
    padding: 35px 15px;
}

.restaurant h2 {
    color: #ff5722;
    margin-bottom: 15px;
}

.restaurant p {
    margin: 8px;
}

/* Food Menu */
#menu {
    padding: 40px 7%;
    text-align: center;
}

#menu h2, #reviews h2 {
    color: #ff5722;
    font-size: 30px;
    margin-bottom: 30px;
}

.food-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
}

.food-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    padding-bottom: 20px;
    box-shadow: 0 4px 12px #0002;
    transition: 0.3s;
}

.food-card:hover {
    transform: translateY(-8px);
}

.food-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.food-card h3 {
    margin: 15px 0;
    color: #e64a19;
}

.food-card p {
    padding: 0 12px;
    color: #666;
}

button {
    background: #ff5722;
    color: white;
    border: none;
    padding: 11px 25px;
    margin-top: 10px;
    border-radius: 20px;
    cursor: pointer;
    font-size: 15px;
}

button:hover, .btn:hover {
    background: #d84315;
}

/* Offers */
.offer {
    background: #ff7043;
    color: white;
    text-align: center;
    padding: 40px 15px;
    margin-top: 20px;
}

.offer h2 {
    font-size: 30px;
    margin-bottom: 15px;
}

.offer p {
    margin: 10px;
    font-size: 18px;
}

/* Reviews */
#reviews {
    text-align: center;
    padding: 45px 15px;
}

.review {
    display: inline-block;
    background: white;
    padding: 22px;
    margin: 10px;
    border-radius: 12px;
    box-shadow: 0 3px 10px #0002;
    max-width: 280px;
}

/* Footer */
footer {
    background: #292929;
    color: white;
    text-align: center;
    padding: 30px 15px;
}

footer p {
    margin: 10px;
}

/* Mobile Responsive */
@media (max-width: 600px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        display: inline-block;
        margin: 7px;
    }

    .hero {
        padding: 75px 15px;
    }

    .hero h2 {
        font-size: 28px;
    }

    .food-container {
        grid-template-columns: 1fr;
    }
} 

