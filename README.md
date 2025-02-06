<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thorium Reserves in India</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        h1, h2 {
            margin-bottom: 15px;
            color: #0056b3;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            background: #fff;
        }
        .image {
            width: 100%;
            max-height: 300px;
            object-fit: cover;
            margin-top: 10px;
        }
        ul {
            list-style-type: disc;
            text-align: left;
            padding-left: 20px;
        }
        .btn {
            padding: 10px 15px;
            margin-top: 10px;
            cursor: pointer;
            border: none;
            background: #007BFF;
            color: white;
            display: inline-block;
            text-decoration: none;
        }
        iframe {
            width: 100%;
            height: 300px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <h1>Thorium Reserves in India</h1>
    <div class="container">

        <!-- Introduction Section -->
        <div class="section">
            <h2>Introduction</h2>
            <p>India has one of the world's largest thorium reserves, making it a potential global leader in thorium-based nuclear energy. The country has been developing thorium-based reactors as part of its three-stage nuclear power program.</p>
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Thorium.jpg" alt="Thorium" class="image">
        </div>

        <!-- Major Thorium Reserves -->
        <div class="section">
            <h2>Major Thorium Reserves in India</h2>
            <ul>
                <li><strong>Kerala (Chavara):</strong> Monazite-rich beach sands.</li>
                <li><strong>Tamil Nadu (Manavalakurichi):</strong> High thorium content in coastal sands.</li>
                <li><strong>Odisha (Bhubaneswar, Chatrapur):</strong> Large deposits in beach and river sands.</li>
                <li><strong>Andhra Pradesh (Vishakhapatnam, Srikakulam):</strong> Major monazite deposits.</li>
                <li><strong>Jharkhand (Hazaribagh, Singhbhum):</strong> Rich in uranium and thorium ores.</li>
            </ul>
        </div>

        <!-- Research & Development Centers -->
        <div class="section">
            <h2>Research & Development Centers</h2>
            <ul>
                <li><strong>Bhabha Atomic Research Centre (BARC), Mumbai:</strong> Leading thorium research.</li>
                <li><strong>Indira Gandhi Centre for Atomic Research (IGCAR), Kalpakkam:</strong> Developing fast breeder reactors.</li>
                <li><strong>Atomic Minerals Directorate for Exploration and Research (AMD), Hyderabad:</strong> Conducts surveys for thorium deposits.</li>
            </ul>
        </div>

        <!-- Map of Thorium Reserves -->
        <div class="section">
            <h2>Thorium Reserves Map</h2>
            <iframe src="https://www.google.com/maps/d/embed?mid=1SdpY1P5H9ls5R5YEkMYgyghZTt8" frameborder="0"></iframe>
        </div>

        <!-- Contact & Inquiry Section -->
        <div class="section">
            <h2>Contact & Inquiry</h2>
            <p>If you have any inquiries regarding thorium reserves, please contact us.</p>
            <form id="contactForm">
                <input type="text" id="name" placeholder="Your Name" required><br>
                <input type="email" id="email" placeholder="Your Email" required><br>
                <textarea id="message" rows="4" placeholder="Your Message" required></textarea><br>
                <button class="btn" type="submit">Send Message</button>
            </form>
        </div>

    </div>

    <script>
        // Form Submission (Mock Functionality)
        document.getElementById("contactForm").addEventListener("submit", function(event) {
            event.preventDefault();
            let name = document.getElementById("name").value;
            let email = document.getElementById("email").value;
            let message = document.getElementById("message").value;
            
            if (name && email && message) {
                alert(`Thank you, ${name}! Your inquiry has been received.`);
                document.getElementById("contactForm").reset();
            } else {
                alert("Please fill in all fields.");
            }
        });
    </script>

</body>
</html># Indiantourism.com-
