
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COMPUTER RANGER EMPIRE</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            background-color: #f0f2f5;
            background-image: url('1.png');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
        }
        .content-wrapper {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            margin: 20px;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 30px 0;
        }
        .shop-name {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.8rem;
            color: #0066cc;
            letter-spacing: 1px;
            text-transform: uppercase;
            margin: 0;
            padding: 20px 0;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #2c3e50;
            border-bottom: 2px solid #0066cc;
            padding-bottom: 10px;
            display: inline-block;
        }
        .content-section {
            margin-bottom: 40px;
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .services-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .service-photo {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            transition: transform 0.3s;
            border: 2px solid #ddd;
        }
        .service-photo:hover {
            transform: scale(1.03);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        .service-caption {
            text-align: center;
            margin-top: 10px;
            font-weight: 500;
            color: #2c3e50;
        }
        .map-container {
            margin: 25px 0;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            border: 1px solid #ddd;
        }
        .map-frame {
            width: 100%;
            height: 400px;
            border: 0;
        }
        .action-buttons {
            display: flex;
            gap: 15px;
            margin-top: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .google-link {
            display: inline-block;
            background-color: #4285F4;
            color: white;
            padding: 12px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
        }
        .google-link:hover {
            background-color: #3367D6;
            transform: translateY(-2px);
        }
        .whatsapp-link {
            display: inline-block;
            background-color: #25D366;
            color: white;
            padding: 12px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
        }
        .whatsapp-link:hover {
            background-color: #128C7E;
            transform: translateY(-2px);
        }
        .contact-info {
            background-color: #f9f9f9;
            padding: 25px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #777;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 8px;
        }
        .business-hours {
            margin-top: 20px;
        }
        .hours-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        .hours-table td {
            padding: 10px;
            border-bottom: 1px solid #eee;
        }
        .hours-table tr:last-child td {
            border-bottom: none;
        }
        .services-list {
            background: linear-gradient(135deg, #0066cc 0%, #004d99 100%);
            color: white;
            padding: 15px 20px;
            border-radius: 8px;
            margin: 15px 0;
            font-weight: 500;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        @media (max-width: 768px) {
            .shop-name {
                font-size: 2rem;
            }
            .content-wrapper {
                margin: 10px;
                padding: 15px;
            }
            .services-gallery {
                grid-template-columns: 1fr;
            }
            .map-frame {
                height: 300px;
            }
        }
    </style>
</head>
<body>
    <div class="content-wrapper">
        <header>
            <div class="shop-name">COMPUTER RANGER EMPIRE</div>
        </header>

        <!-- OUR SERVICES SECTION -->
        <section class="content-section">
            <h2>Our Services</h2>
            <p>Professional solutions for all your tech needs:</p>
            
            <!-- Added the requested services list -->
            <div class="services-list">
                Laptop repair, Desktop Repair, Computer service, Laptop battery change, 
                laptop keyboard change, laptop screen change, Desktop parts and all type of computers services
            </div>
            
            <div class="services-gallery">
                <!-- Service 1 -->
                <div class="service-item">
                    <img src="s1.jpg" alt="Computer Repair Service" class="service-photo">
                    <div class="service-caption">Computer Repair</div>
                </div>
                
                <!-- Service 2 -->
                <div class="service-item">
                    <img src="s2.jpg" alt="Laptop Maintenance" class="service-photo">
                    <div class="service-caption">Laptop Maintenance</div>
                </div>
                
                <!-- Service 3 -->
                <div class="service-item">
                    <img src="s3.jpg" alt="Desktop New Setup" class="service-photo">
                    <div class="service-caption">Desktop New Setup</div>
                </div>
                
                <!-- Service 4 -->
                <div class="service-item">
                    <img src="s4.jpg" alt="Hardware Upgrade" class="service-photo">
                    <div class="service-caption">Hardware Upgrade</div>
                </div>
            </div>
        </section>

        <!-- VISIT US SECTION WITH EMBEDDED MAP ONLY -->
        <section class="content-section">
            <h2>Visit Us</h2>
            <div class="map-container">
                <iframe class="map-frame" 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3983.72253866531!2d101.6036362118593!3d3.167605453022896!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31cc4f8b0151d235%3A0x241608d4c67b7d1c!2sComputer%20Ranger%20Empire!5e0!3m2!1sen!2sde!4v1738426556150!5m2!1sen!2sde" 
                        allowfullscreen="" 
                        loading="lazy" 
                        referrerpolicy="no-referrer-when-downgrade">
                </iframe>
            </div>
            
            <div class="action-buttons">
                <a href="https://www.google.com/maps/place/Computer+Ranger+Empire/@3.1676001,101.6062165,17z/data=!3m1!4b1!4m6!3m5!1s0x31cc4f8b0151d235:0x241608d4c67b7d1c!8m2!3d3.1676001!4d101.6062165!16s%2Fg%2F11pzw7_ky7?hl=en-GB&entry=ttu&g_ep=EgoyMDI1MDUwNy4wIKXMDSoASAFQAw%3D%3D" 
                   class="google-link" 
                   target="_blank">
                    Get Directions
                </a>
            </div>
        </section>

        <!-- CONTACT US SECTION -->
        <section class="content-section">
            <h2>Contact Us</h2>
            <div class="contact-info">
                <p><strong>Phone:</strong><br>
                <a href="https://wa.me/601139326396" class="whatsapp-link" target="_blank">
                    WhatsApp: +60 11-3932 6396
                </a></p>
                
                <div class="business-hours">
                    <strong>Business Hours:</strong>
                    <table class="hours-table">
                        <tr>
                            <td>Tuesday - Sunday</td>
                            <td>10:00 AM - 8:00 PM</td>
                        </tr>
                        <tr>
                            <td>Monday</td>
                            <td>Closed</td>
                        </tr>
                    </table>
                </div>
            </div>
        </section>

        <footer>
            <p>&copy; <script>document.write(new Date().getFullYear())</script> COMPUTER RANGER EMPIRE. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
