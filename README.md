<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayurveda Hospital</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f1e7;
            color: #333;
        }
        header {
            background-image: url('https://source.unsplash.com/1600x900/?ayurveda,nature');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        header p {
            font-size: 1.2em;
        }
        nav {
            background-color: #4caf50;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #3e8e41;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            text-align: center;
            color: #4caf50;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 10px;
            margin-top: 20px;
        }
        footer a {
            color: #4caf50;
            text-decoration: none;
        }
        @media (min-width: 600px) {
            .services, .gallery {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                gap: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Ayurveda Hospital</h1>
        <p>Healing through the ancient science of Ayurveda</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>Our Ayurveda Hospital blends ancient traditions with modern expertise to provide holistic care. With our experienced practitioners and serene environment, we help you find balance in body, mind, and spirit.</p>
    </section>
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div>
            <h3>Abhyanga (Oil Massage)</h3>
            <p>A rejuvenating full-body massage with herbal oils.</p>
        </div>
        <div>
            <h3>Shirodhara</h3>
            <p>A soothing therapy where warm oil flows gently on the forehead.</p>
        </div>
        <div>
            <h3>Panchakarma Detox</h3>
            <p>A complete detoxification program to cleanse your body.</p>
        </div>
        <div>
            <h3>Herbal Medicines</h3>
            <p>Customized herbal treatments for various ailments.</p>
        </div>
    </section>
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <img src="https://source.unsplash.com/600x400/?ayurveda,spa" alt="Ayurveda Spa">
        <img src="https://source.unsplash.com/600x400/?herbs,nature" alt="Herbal Medicines">
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 123 Ayurveda Lane, Wellness City</p>
        <p><strong>Phone:</strong> +1 234 567 890</p>
        <p><strong>Email:</strong> info@ayurvedahospital.com</p>
        <p><strong>Find us on Google Maps:</strong></p>
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.835434509857!2d144.9559253153168!3d-37.81720997975142!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642af0f11fd81%3A0xf0727d3d0d3f3a8!2sAyurveda%20Wellness%20Centre!5e0!3m2!1sen!2sus!4v1691743559172!5m2!1sen!2sus"
            width="100%"
            height="300"
            style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>
    <footer>
        <p>© 2024 Ayurveda Hospital | Designed with care.</p>
        <p>Follow us on <a href="#">Facebook</a> | <a href="#">Instagram</a></p>
    </footer>
</body>
</html>
