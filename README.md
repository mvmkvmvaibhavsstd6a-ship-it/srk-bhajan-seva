<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SRK Bhajan Seva - Book Devotional Bhajans</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; color: #333; }
        header { background: linear-gradient(to right, #ff6b6b, #ffd93d); padding: 20px; text-align: center; color: white; }
        .container { max-width: 1200px; margin: 20px auto; padding: 20px; background: white; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .channel-link { font-size: 1.2em; color: #ff6b6b; text-decoration: none; }
        .videos { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
        iframe { width: 100%; max-width: 560px; height: 315px; }
        form { max-width: 600px; margin: 20px auto; }
        input, select, textarea { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ddd; border-radius: 5px; }
        button { background: #ff6b6b; color: white; padding: 12px 30px; border: none; border-radius: 5px; cursor: pointer; font-size: 1.1em; }
        footer { text-align: center; padding: 20px; background: #333; color: white; }
        @media (max-width: 768px) { .videos { flex-direction: column; align-items: center; } }
    </style>
</head>
<body>
    <header>
        <h1>🕉️ SRK Bhajan Seva 🕉️</h1>
        <p>Divine Bhajans for Your Soul | Subscribe: <a href="https://youtube.com/@srkbhajanseva" class="channel-link" target="_blank">@srkbhajanseva</a></p>
    </header>
    <div class="container">
        <section>
            <h2>Latest Bhajans</h2>
            <div class="videos">
                <!-- Embed your top videos here; replace video IDs -->
                <iframe src="https://www.youtube.com/embed/QeuxFDvHJoo" title="Latest Live Bhajan" frameborder="0" allowfullscreen></iframe>
                <!-- Add more: <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe> -->
            </div>
        </section>
        <section>
            <h2>Book Bhajan Service</h2>
            <p>Request bhajans for events, weddings, or personal devotion. We'll contact you within 24 hours.</p>
            <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST"> <!-- Free: formspree.io, replace YOUR_FORM_ID -->
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Phone Number">
                <select name="event_type">
                    <option>Wedding</option>
                    <option>Bhajan Session</option>
                    <option>Event/Function</option>
                    <option>Personal Request</option>
                </select>
                <input type="date" name="date" required>
                <textarea name="message" rows="5" placeholder="Event details, preferred bhajans, location..."></textarea>
                <button type="submit">Book Now</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2026 SRK Bhajan Seva | Devotional Service with Love 🙏</p>
    </footer>
</body>
</html>
