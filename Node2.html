<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SONGSANG CINEMA - Movie Booking</title>
    <style>
        :root {
            --primary-red: #e50914;
            --dark-bg: #000000;
            --card-bg: #1a1a1a;
            --text-white: #ffffff;
        }

        body { font-family: 'Segoe UI', Arial, sans-serif; background: var(--dark-bg); color: var(--text-white); margin: 0; padding-bottom: 50px; }
        
        /* Navigation */
        nav { background: #000; padding: 1rem; display: flex; justify-content: space-between; align-items: center; border-bottom: 3px solid var(--primary-red); position: sticky; top: 0; z-index: 100; }
        .logo { color: var(--primary-red); font-size: 1.5rem; font-weight: bold; text-transform: uppercase; letter-spacing: 2px; }
        
        .container { padding: 20px; max-width: 1000px; margin: auto; }
        .hidden { display: none; }
        
        /* Forms & Containers */
        .auth-form { background: var(--card-bg); padding: 30px; border-radius: 10px; border-top: 4px solid var(--primary-red); box-shadow: 0 4px 20px rgba(229, 9, 20, 0.2); }
        input, select { width: 100%; padding: 12px; margin: 10px 0; border-radius: 5px; border: 1px solid #333; background: #222; color: white; box-sizing: border-box; }
        
        /* Movie Selection */
        .movie-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 25px; margin-top: 20px; }
        .movie-card { border-radius: 12px; overflow: hidden; background: var(--card-bg); text-align: center; border: 1px solid #333; transition: 0.3s; }
        .movie-card:hover { transform: translateY(-8px); border-color: var(--primary-red); }
        .movie-card img { width: 100%; height: 320px; object-fit: cover; }
        .movie-card h3 { margin: 15px 10px; font-size: 1.1rem; height: 40px; overflow: hidden; }

        /* Seat Layout */
        .screen { background: linear-gradient(to bottom, #444, transparent); height: 12px; width: 80%; margin: 30px auto; border-radius: 50%; box-shadow: 0 5px 15px rgba(255,255,255,0.1); }
        .seat-grid { display: grid; grid-template-columns: repeat(6, 1fr); gap: 10px; max-width: 400px; margin: 20px auto; }
        .seat { background: #333; padding: 12px; text-align: center; cursor: pointer; border-radius: 6px; border: 1px solid #444; font-size: 0.8rem; }
        .seat.selected { background: var(--primary-red); color: #fff; font-weight: bold; border-color: #fff; }
        
        /* Buttons */
        button { background: var(--primary-red); color: white; border: none; padding: 12px 20px; font-weight: bold; cursor: pointer; border-radius: 5px; width: 100%; text-transform: uppercase; transition: 0.2s; }
        button:hover { background: #ff0f1a; transform: scale(1.02); }
        .btn-back { background: #333; width: auto; padding: 8px 15px; margin-bottom: 15px; font-size: 0.8rem; margin-right: 10px; }
        .btn-link { background: none; color: var(--primary-red); text-decoration: underline; width: auto; padding: 0; margin-top: 15px; text-transform: none; }
        .btn-logout { background: transparent; border: 1px solid var(--primary-red); color: var(--primary-red); width: auto; padding: 5px 15px; font-size: 0.8rem; }

        /* Ticket */
        .ticket { background: #fff; color: #000; padding: 25px; border-radius: 4px; text-align: center; border-left: 8px solid var(--primary-red); }
        .ticket h1 { color: var(--primary-red); margin: 0; }
        .qr-img { width: 150px; height: 150px; margin: 20px auto; border: 1px solid #ddd; padding: 5px; }
    </style>
</head>
<body>

<nav>
    <div class="logo">SONGSANG CINEMA</div>
    <div id="nav-user" class="hidden">
        <span id="user-display" style="margin-right:15px; font-size: 0.9rem;"></span>
        <button class="btn-logout" onclick="handleLogout()">Logout</button>
    </div>
</nav>

<div class="container">
    
    <div id="page-login" class="auth-form">
        <h2>Login</h2>
        <input type="email" id="login-email" placeholder="Email Address">
        <input type="password" id="login-pass" placeholder="Password">
        <button onclick="handleLogin()">Login</button>
        <p>Don't have an account? <button class="btn-link" onclick="showPage('page-register')">Register Now</button></p>
    </div>

    <div id="page-register" class="auth-form hidden">
        <button class="btn-back" onclick="showPage('page-login')">← Back to Login</button>
        <h2>Create Account</h2>
        <input type="text" id="reg-name" placeholder="Full Name">
        <input type="email" id="reg-email" placeholder="Email Address">
        <input type="password" id="reg-pass" placeholder="Password">
        <button onclick="handleRegister()">Sign Up</button>
    </div>

    <div id="page-movies" class="hidden">
        <h2 style="border-left: 4px solid var(--primary-red); padding-left: 15px;">NOW SHOWING</h2>
        <div class="movie-grid">
            <div class="movie-card">
                <img src="Panor.JPG" alt="Panor 2">
                <h3>Panor 2</h3>
                <p style="color:#888;">Horror | ฿199</p>
                <button onclick="selectMovie('Panor 2', 199)">Book Now</button>
            </div>
            <div class="movie-card">
                <img src="Teeyod.JPG" alt="Tee Yod 3">
                <h3>Tee Yod 3</h3>
                <p style="color:#888;">Horror | ฿199</p>
                <button onclick="selectMovie('Tee Yod 3', 199)">Book Now</button>
            </div>
            <div class="movie-card">
                <img src="Hor.JPG" alt="Hor Taew Tak">
                <h3>Hor Taew Tak</h3>
                <p style="color:#888;">Comedy | ฿199</p>
                <button onclick="selectMovie('Hor Taew Tak', 199)">Book Now</button>
            </div>
            <div class="movie-card">
                <img src="Ava.JPG" alt="Avatar 3">
                <h3>Avatar 3</h3>
                <p style="color:#888;">Sci-Fi | ฿199</p>
                <button onclick="selectMovie('Avatar 3', 199)">Book Now</button>
            </div>
            <div class="movie-card">
                <img src="Deeva.JPG" alt="Deeva Rawi">
                <h3>Deeva Rawi</h3>
                <p style="color:#888;">Comedy | ฿199</p>
                <button onclick="selectMovie('Deeva Rawi', 199)">Book Now</button>
            </div>
            <div class="movie-card">
                <img src="Zoo.WEBP" alt="Zootopia 2">
                <h3>Zootopia 2</h3>
                <p style="color:#888;">Family | ฿199</p>
                <button onclick="selectMovie('Zootopia 2', 199)">Book Now</button>
            </div>
        </div>
    </div>

    <div id="page-booking" class="hidden">
        <button class="btn-back" onclick="showPage('page-movies')">← Back to Movies</button>
        <h2 id="booking-title">Select Seats</h2>
        <div style="margin-bottom: 20px;">
            <label>Select Showtime: </label>
            <select id="showtime-select">
                <option>11:00 AM</option>
                <option>02:30 PM</option>
                <option>06:00 PM</option>
                <option>09:15 PM</option>
            </select>
        </div>

        <div class="screen"></div>
        <p style="text-align:center; font-size: 0.7rem; color:#666; letter-spacing: 5px;">SCREEN</p>

        <div class="seat-grid" id="seat-container"></div>

        <div style="background: #222; padding: 15px; border-radius: 8px; margin-top: 20px; text-align: center;">
            <p>Selected Seats: <span id="selected-seats-list" style="color:var(--primary-red)">-</span></p>
            <h3 style="margin:0;">Total Price: <span id="total-price" style="color:var(--primary-red)">0.00 ฿</span></h3>
        </div>
        <br>
        <button onclick="showPage('page-payment')">Proceed to Payment</button>
    </div>

    <div id="page-payment" class="hidden">
        <button class="btn-back" onclick="showPage('page-booking')">← Back to Seats</button>
        <h2>Payment Method</h2>
        <div class="auth-form">
            <p style="font-size: 1.2rem;">Amount to Pay: <strong id="pay-amount" style="color:var(--primary-red)">0.00 ฿</strong></p>
            <hr style="border:0.5px solid #333; margin: 20px 0;">
            <div style="text-align: left; margin: 20px 0;">
                <input type="radio" name="pay" id="cc" checked> <label for="cc">Credit / Debit Card</label><br><br>
                <input type="radio" name="pay" id="qr"> <label for="qr">PromptPay / Mobile Banking (QR Code)</label>
            </div>
            <button onclick="completePayment()">Confirm Payment</button>
        </div>
    </div>

    <div id="page-ticket" class="hidden">
        <div class="ticket">
            <h1>E-TICKET</h1>
            <p style="border-bottom: 1px dashed #ccc; padding-bottom: 10px; font-weight: bold;">SONGSANG CINEMA</p>
            <h2 id="ticket-movie-name" style="margin: 15px 0;">Movie Name</h2>
            <div style="display: flex; justify-content: space-around; background: #f9f9f9; padding: 10px; margin: 15px 0;">
                <div><small>TIME</small><br><strong id="ticket-time">00:00</strong></div>
                <div><small>SEATS</small><br><strong id="ticket-seats">-</strong></div>
                <div><small>TOTAL</small><br><strong id="ticket-final-price">0 ฿</strong></div>
            </div>
            <img id="qr-image" src="" alt="QR Code" class="qr-img">
            <p style="font-size: 0.75rem; color: #666;">Scan this QR at the entrance gate.</p>
        </div>
        <br>
        <button onclick="location.reload()">Back to Main Menu</button>
    </div>

</div>

<script>
    let selectedMovieName = "";
    let selectedSeats = [];
    let ticketPrice = 0;

    function showPage(pageId) {
        document.querySelectorAll('.container > div').forEach(div => div.classList.add('hidden'));
        document.getElementById(pageId).classList.remove('hidden');
        window.scrollTo(0,0);
    }

    // Authentication Logic
    function handleRegister() {
        const name = document.getElementById('reg-name').value;
        if(name) {
            alert("Registration Successful! Please login.");
            showPage('page-login');
        } else { alert("Please fill in all fields."); }
    }

    function handleLogin() {
        const email = document.getElementById('login-email').value;
        if(email) {
            document.getElementById('nav-user').classList.remove('hidden');
            document.getElementById('user-display').innerText = "Hello, " + email.split('@')[0];
            showPage('page-movies');
        } else { alert("Please enter your email."); }
    }

    function handleLogout() {
        if(confirm("Do you want to logout?")) {
            location.reload();
        }
    }

    // Movie & Seat Logic
    function selectMovie(name, price) {
        selectedMovieName = name;
        ticketPrice = price;
        document.getElementById('booking-title').innerText = "Booking: " + name;
        generateSeats();
        showPage('page-booking');
    }

    function generateSeats() {
        const container = document.getElementById('seat-container');
        container.innerHTML = "";
        selectedSeats = [];
        updateSeatUI();

        for(let i=1; i<=24; i++) {
            const seat = document.createElement('div');
            seat.classList.add('seat');
            seat.innerText = "A" + i;
            seat.onclick = function() {
                this.classList.toggle('selected');
                const seatNum = this.innerText;
                if(selectedSeats.includes(seatNum)) {
                    selectedSeats = selectedSeats.filter(s => s !== seatNum);
                } else {
                    selectedSeats.push(seatNum);
                }
                updateSeatUI();
            };
            container.appendChild(seat);
        }
    }

    function updateSeatUI() {
        document.getElementById('selected-seats-list').innerText = selectedSeats.length > 0 ? selectedSeats.join(', ') : "-";
        const total = (selectedSeats.length * ticketPrice).toFixed(2);
        document.getElementById('total-price').innerText = total + " ฿";
        document.getElementById('pay-amount').innerText = total + " ฿";
    }

    function completePayment() {
        if(selectedSeats.length === 0) {
            alert("Please select at least one seat.");
            return;
        }
        
        // Setup Ticket Info
        document.getElementById('ticket-movie-name').innerText = selectedMovieName;
        document.getElementById('ticket-time').innerText = document.getElementById('showtime-select').value;
        document.getElementById('ticket-seats').innerText = selectedSeats.join(', ');
        document.getElementById('ticket-final-price').innerText = document.getElementById('total-price').innerText;
        
        // Generate dynamic QR Code
        const qrData = `Movie:${selectedMovieName}|Seats:${selectedSeats.join(',')}`;
        document.getElementById('qr-image').src = `https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=${encodeURIComponent(qrData)}`;
        
        showPage('page-ticket');
    }
</script>

</body>
</html>