/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f9f4; /* Light green background */
    color: #333;
}

header {
    background-color: #2e7d32; /* Dark green */
    color: white;
    padding: 20px 0;
    text-align: center;
}

header .logo h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

header .logo p {
    font-size: 1rem;
    font-style: italic;
}

.hero {
    background: url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero-content h2 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.hero-content .btn {
    background-color: #2e7d32;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1rem;
}

.hero-content .btn:hover {
    background-color: #1b5e20;
}

/* Instagram Section */
.instagram {
    text-align: center;
    padding: 40px 20px;
    background-color: #e8f5e9; /* Lighter green */
}

.instagram h2 {
    font-size: 2rem;
    margin-bottom: 10px;
}

.instagram p a {
    color: #2e7d32;
    text-decoration: none;
    font-weight: bold;
}

.instagram p a:hover {
    text-decoration: underline;
}

.instagram-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
    margin-top: 20px;
}

.instagram-gallery img {
    width: 300px;
    height: 300px;
    object-fit: cover;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.instagram-gallery img:hover {
    transform: scale(1.05);
}

footer {
    background-color: #2e7d32;
    color: white;
    text-align: center;
    padding: 20px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}

.footer-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}

.contact-info span {
    font-size: 1rem;
    display: flex;
    align-items: center;
    gap: 5px;
}

.contact-info a {
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
}

.contact-info a:hover {
    text-decoration: underline;
}