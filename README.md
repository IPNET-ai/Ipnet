<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IPTV Subscriptions</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#plans">Plans</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h1>Welcome to IPTV Services</h1>
            <p>Stream your favorite channels in high quality.</p>
        </section>
        
        <section id="plans">
            <h2>Subscription Plans</h2>
            <div class="plan">
                <h3>Basic</h3>
                <p>$10/month</p>
            </div>
            <div class="plan">
                <h3>Standard</h3>
                <p>$20/month</p>
            </div>
            <div class="plan">
                <h3>Premium</h3>
                <p>$30/month</p>
            </div>
        </section>
        
        <section id="contact">
            <h2>Contact Us</h2>
            <form action="#" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 IPTV Service. All Rights Reserved.</p>
    </footer>
</body>
</html>
