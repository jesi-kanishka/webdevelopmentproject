TASK 1 :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carbon Footprint Calculator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f7f7f7;
        }
        h1 {
            text-align: center;
            color: #2e8b57;
        }
        .container {
            width: 50%;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            font-weight: bold;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #2e8b57;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #276745;
        }
        .result {
            margin-top: 20px;
            padding: 15px;
            background-color: #f0f8ff;
            border-radius: 5px;
        }
        .green-options {
            margin-top: 20px;
            background-color: #e1ffec;
            padding: 15px;
            border-radius: 5px;
            text-align: center;
        }
        .discount {
            color: #ff6347;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>Carbon Footprint Calculator</h1>

    <div class="container">
        <h2>Enter Your Journey Details</h2>
        <div class="form-group">
            <label for="transportation">Mode of Transportation:</label>
            <select id="transportation">
                <option value="car">Car</option>
                <option value="bus">Bus</option>
                <option value="train">Train</option>
                <option value="bike">Bike</option>
                <option value="walking">Walking</option>
            </select>
        </div>

        <div class="form-group">
            <label for="distance">Distance Traveled (in km):</label>
            <input type="number" id="distance" placeholder="Enter distance in kilometers">
        </div>

        <div class="form-group">
            <button onclick="calculateCarbonFootprint()">Calculate Carbon Footprint</button>
        </div>

        <div id="result" class="result" style="display:none;"></div>

        <div id="greenOptions" class="green-options" style="display:none;">
            <p>If you choose a greener option, you can receive a <span class="discount">10% discount</span> on your next trip!</p>
        </div>
    </div>

    <script>
        function calculateCarbonFootprint() {
            const transportation = document.getElementById('transportation').value;
            const distance = parseFloat(document.getElementById('distance').value);
            let carbonFootprint = 0;
            let ecoFriendly = false;

            if (isNaN(distance) || distance <= 0) {
                alert("Please enter a valid distance.");
                return;

   TASK 2:
   
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Journey Platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Travel Journey - Share Your Bus Adventures</h1>
            <nav>
                <ul>
                    <li><a href="#stories">Travel Stories</a></li>
                    <li><a href="#forums">Discussion Boards</a></li>
                    <li><a href="#tips">Travel Tips</a></li>
                    <li><a href="#community">Community</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Travel Stories Section -->
    <section id="stories">
        <div class="container">
            <h2>Travel Stories</h2>
            <p>Share your unique bus journey stories with the community.</p>
            <div class="story">
                <h3>My Journey Through the Mountains</h3>
                <p>It was a breathtaking trip through the mountain range...</p>
                <img src="mountain-journey.jpg" alt="Bus journey through mountains">
                <p><strong>Posted by:</strong> User123</p>
            </div>
            <button onclick="location.href='add_story.html'">Add Your Story</button>
        </div>
    </section>

    <!-- Travel Tips Section -->
    <section id="tips">
        <div class="container">
            <h2>Travel Tips</h2>
            <p>Helpful tips to make your bus journeys more comfortable.</p>
            <ul>
                <li>Always bring snacks and water for long trips.</li>
                <li>Keep a power bank to charge your devices on the go.</li>
                <li>Wear comfortable shoes for bus stops and long waits.</li>
            </ul>
            <button onclick="location.href='add_tip.html'">Share Your Tip</button>
        </div>
    </section>

    <!-- Discussion Boards Section -->
    <section id="forums">
        <div class="container">
            <h2>Discussion Boards</h2>
            <p>Join the conversation! Share advice and experiences with fellow travelers.</p>
            <div class="forum">
                <h3>Bus Routes in Europe</h3>
                <p>Discuss your experiences with bus routes across Europe...</p>
                <button onclick="location.href='forum_europe.html'">Join Discussion</button>
            </div>
            <div class="forum">
                <h3>Best Scenic Bus Rides</h3>
                <p>What are the most scenic bus routes you've been on?</p>
                <button onclick="location.href='forum_scenic.html'">Join Discussion</button>
            </div>
        </div>
    </section>

    <!-- Community Section -->
    <section id="community">
        <div class="container">
            <h2>Connect with the Community</h2>
            <p>Follow us on social media to stay connected with fellow travelers.</p>
            <div class="social-media">
                <a href="https://www.facebook.com" target="_blank">Facebook</a>
                <a href="https://www.instagram.com" target="_blank">Instagram</a>
                <a href="https://www.twitter.com" target="_blank">Twitter</a>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Travel Journey Platform. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

 
 TASK 3 :
 
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Chatbot for Customer Support</title>
    <style>
        /* Styling the chatbot */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7fc;
        }

        #chat-container {
            position: fixed;
            bottom: 0;
            right: 20px;
            width: 300px;
            height: 400px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            z-index: 1000;
        }

        #chat-header {
            background-color: #007bff;
            color: white;
            padding: 10px;
            text-align: center;
            font-size: 16px;
        }

        #chat-box {
            padding: 10px;
            height: 280px;
            overflow-y: auto;
            border-bottom: 1px solid #ccc;
        }

        #input-container {
            display: flex;
            padding: 10px;
        }

        #user-input {
            width: 80%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        #send-btn {
            width: 20%;
            padding: 8px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .message {
            margin-bottom: 10px;
        }

        .user-message {
            text-align: right;
            color: #007bff;
        }

        .bot-message {
            text-align: left;
            color: #333;
        }

        #chat-toggle-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 10px;
            background-color: #007bff;
            color: white;
            border-radius: 50%;
            font-size: 20px;
            cursor: pointer;
            z-index: 1100;
        }
    </style>
</head>
<body>

    <!-- Chatbot container -->
    <div id="chat-container">
        <div id="chat-header">AI Chatbot</div>
        <div id="chat-box"></div>
        <div id="input-container">
            <input type="text" id="user-input" placeholder="Ask me something..." />
            <button id="send-btn" onclick="sendMessage()">Send</button>
        </div>
    </div>

    <!-- Chat toggle button -->
    <button id="chat-toggle-btn" onclick="toggleChat()">💬</button>

    <script>
        const chatBox = document.getElementById("chat-box");
        const userInput = document.getElementById("user-input");

        // Toggle the visibility of the chatbot
        function toggleChat() {
            const chatContainer = document.getElementById("chat-container");
            chatContainer.style.display = chatContainer.style.display === "none" ? "block" : "none";
        }

        // Function to send a message
        function sendMessage() {
            const userMessage = userInput.value.trim();
            if (userMessage) {
                displayMessage(userMessage, "user");
                userInput.value = ""; // Clear the input field
                simulateBotResponse(userMessage);
            }
        }

        // Function to display the message in the chat box
        function displayMessage(message, sender) {
            const messageDiv = document.createElement("div");
            messageDiv.classList.add("message", sender === "user" ? "user-message" : "bot-message");
            messageDiv.textContent = message;
            chatBox.appendChild(messageDiv);
            chatBox.scrollTop = chatBox.scrollHeight; // Scroll to the latest message
        }

        // Simulate a bot response based on user input
        function simulateBotResponse(userMessage) {
            let botResponse = "";

            // Simulate chatbot responses (can be replaced with actual API calls)
            if (userMessage.toLowerCase().includes("book")) {
                botResponse = "I can assist you with booking. Please provide your details.";
            } else if (userMessage.toLowerCase().includes("route")) {
                botResponse = "Sure! I can help with route information. Which destination are you looking for?";
            } else if (userMessage.toLowerCase().includes("schedule")) {
                botResponse = "Let me check the schedule for you. When are you planning to travel?";
            } else {
                botResponse = "I'm sorry, I didn't quite understand that. Could you please clarify?";
            }

            // Display the bot's response after a brief delay
            setTimeout(() => {
                displayMessage(botResponse, "bot");
            }, 1000);
        }
    </script>

</body>
</html>

PROJECT : 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bus Ticket Booking</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bus Ticket Booking</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#book-ticket">Book Ticket</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <h2>Welcome to EasyBus</h2>
        <p>Your journey starts here! Book your bus tickets with ease.</p>
    </section>

    <!-- Book Ticket Section -->
    <section id="book-ticket">
        <h2>Book Your Bus Ticket</h2>
        <form id="booking-form">
            <label for="from">From:</label>
            <input type="text" id="from" name="from" placeholder="Enter departure city" required>

            <label for="to">To:</label>
            <input type="text" id="to" name="to" placeholder="Enter destination city" required>

            <label for="date">Date of Travel:</label>
            <input type="date" id="date" name="date" required>

            <label for="passengers">Number of Passengers:</label>
            <input type="number" id="passengers" name="passengers" min="1" required>

            <button type="submit">Search Buses</button>
        </form>
    </section>

    <!-- Available Buses Section -->
    <section id="available-buses">
        <h2>Available Buses</h2>
        <div class="bus-list">
            <!-- Bus list items will be dynamically inserted here (e.g., with JavaScript) -->
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out to us!</p>
        <p>Email: support@easybus.com</p>
        <p>Phone: 1-800-EASYBUS</p>
    </section>

    <footer>
        <p>&copy; 2025 EasyBus. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

        
