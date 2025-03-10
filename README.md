<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SweetSweets - Live Dessert Stations</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8e6e0; }
        header { background: #ffcccb; padding: 20px; text-align: center; }
        .logo { width: 150px; }
        .container { width: 90%; margin: auto; text-align: center; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 20px; }
        .station { background: white; padding: 10px; border-radius: 10px; cursor: pointer; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1); }
        .station img { width: 100%; border-radius: 10px; }
        footer { background: #333; color: white; text-align: center; padding: 10px; }
    </style>
</head>
<body>
    <header>
        <img src="sweetsweets_logo.jpg" alt="SweetSweets Logo" class="logo">
        <h1>SweetSweets - Live Dessert Stations</h1>
        <p>We Bring Quality to Convenience</p>
    </header>

    <section class="container">
        <h2>Our Live Dessert Stations</h2>
        <div class="grid">
            <div class="station" onclick="location.href='chocolate_fountain.html';">
                <img src="chocolate_fountain.jpg" alt="Chocolate Fountain">
                <h3>Chocolate Fountain</h3>
            </div>
            <div class="station" onclick="location.href='boba_tea.html';">
                <img src="boba_tea.jpg" alt="Boba Tea">
                <h3>Boba Tea</h3>
            </div>
            <div class="station" onclick="location.href='waffle_sticks.html';">
                <img src="waffle_sticks.jpg" alt="Waffle Sticks">
                <h3>Waffle Sticks</h3>
            </div>
            <div class="station" onclick="location.href='rolled_ice_cream.html';">
                <img src="rolled_ice_cream.jpg" alt="Rolled Ice Cream">
                <h3>Rolled Ice Cream</h3>
            </div>
            <div class="station" onclick="location.href='karak_chai.html';">
                <img src="karak_chai.jpg" alt="Karak Chai">
                <h3>Karak Chai</h3>
            </div>
        </div>
    </section>

    <footer>
        <p>Contact us at: info@sweetsweets.com | Follow us on social media</p>
    </footer>
</body>
</html>
