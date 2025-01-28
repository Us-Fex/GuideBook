<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Training Manual</title>
<link href="https://fonts.googleapis.com/css2?family=Monument+Extended&display=swap" rel="stylesheet">
    <style>
        /* Layout for the whole page */
        body {
            font-family: 'Monument Extended', Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .container {
            display: flex;
            width: 100%;
        }

        /* Left Sidebar */
        .sidebar {
            width: 20%;
            background-color: #f4f4f4;
            padding: 10px;
            position: fixed;
            height: 100vh;
            overflow-y: auto;
        }

        .sidebar ul {
            list-style-type: none;
            padding: 0;
        }

        .sidebar li {
            margin: 10px 0;
        }

        .sidebar a {
            text-decoration: none;
            color: #333;
            font-size: 16px;
        }

        .sidebar a:hover {
            color: #007bff;
        }

        .sidebar button {
            background: none;
            border: none;
            cursor: pointer;
            color: #007bff;
            padding: 0;
        }

        /* Right Content Section */
        .content {
            margin-left: 20%;
            padding-left: 20px;
            width: 80%;
        }
		


.content p,
h2,
.strong {
    margin-left: 10%; /* Indent for specific elements */
}

.content p {
    font-size: 14px; /* Already defined separately, keep it here */
}

ol, ul {
    padding-left: 20px; /* Add spacing for list items */
    margin: 0;
}

        section {
            margin-bottom: 30px;
        }

        section img {
            max-width: 100%;
            height: auto;
            display: block;
            margin-bottom: 0;
        }

        .floating-box {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 10%;
            font-size: 18px;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s;
        }

        .floating-box:hover {
            background-color: #0056b3;
        }

        p {
            font-size: 14px;
            margin-top: 5px;
            margin-bottom: 15px;
        }

        ol {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        /* Collapsible Sub-links */
        .sub-links {
            list-style-type: none;
            padding-left: 20px;
            display: none;
        }

        .sub-links li {
            margin: 5px 0;
        }

        /* Button to toggle sub-links */
        .toggle-btn {
            font-size: 18px;
            margin-left: 5px;
            cursor: pointer;
        }

        /* Circle Icon for Sub-links */
        .circle-icon {
            width: 7px;
            height: 7px;
            background-color: #007bff;
            border-radius: 50%;
            display: inline-block;
            margin-right: 5px;
        }
		
		.sub-links li a {
    font-size: 12px;  /* Smaller font size */
    font-style: italic;  /* Italicized text */
}
@media (max-width: 800px) {
    .sidebar a {
        font-size: 12px;  /* Smaller font size for mobile devices */
    }

    .sub-links li a {
        font-size: 10px;  /* Smaller font size for sub-links on mobile */
    }

    .sidebar {
        width: 30%;  /* 30% width for mobile */
    }

    .content {
        margin-left: 30%;  /* 30% margin for mobile */
        width: 70%;  /* 70% width for mobile */
    }
}
    </style>
</head>
<body>
    <div class="container">
        <!-- Left Sidebar -->
        <div class="sidebar">
            <ul>
				<li><a href="#top"><b>US-FEX GUIDE</b></a></li>
                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section1')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#invite1" onclick="toggleSubLinks('section1')">Invite A User [ Only this one is fully functional ]</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section1" class="sub-links">
                        <li><a href="#inv2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#inv3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
                <li>                    
					<button class="toggle-btn" onclick="toggleSubLinks('section2')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#carrier1" onclick="toggleSubLinks('section2')">Invite Carriers to the Platform</a> <!-- Invite - Fully typed is for title with button -->
                    <ul id="section2" class="sub-links">
                        <li><a href="#car2">Sub-link 4</a></li><!-- Inv - first few letters to img -->
                        <li><a href="#car3">Sub-link 5</a></li>
						<li><a href="#car4">Sub-link 5</a></li>
                    </ul>
                </li>
                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section3')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#Shipment1" onclick="toggleSubLinks('section3')">Broker Shipment</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section3" class="sub-links">
                        <li><a href="#ship2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#ship3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#ship4">Sub-link 3</a></li>
                    </ul>
                </li>
				                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section4')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#invite1">Broker Registration</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section4" class="sub-links">
                        <li><a href="#inv2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#inv3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
				                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section5')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#invite1">Invite Carriers to the Platform</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section5" class="sub-links">
                        <li><a href="#inv2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#inv3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
				                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section6')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#carrier12">Carrier Registration</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section6" class="sub-links">
                        <li><a href="#car2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#car3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
				                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section7')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#invite1">Brokers Creating Shipments (Bid & Contract Rates)</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section7" class="sub-links">
                        <li><a href="#inv2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#inv3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
				                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section8')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#invite1">Carrier Negotiates on a Shipment</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section8" class="sub-links">
                        <li><a href="#inv2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#inv3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
				                <li>
					<button class="toggle-btn" onclick="toggleSubLinks('section9')">
                    <span class="circle-icon"></span>
                    </button>
                    <a href="#invite1">Broker Negotiation on Shipment</a>   <!-- Invite - Fully typed is for title with button -->
                    <ul id="section9" class="sub-links">
                        <li><a href="#inv2">Open the application.</a></li> <!-- Inv - first few letters to img -->
                        <li><a href="#inv3">Log in using your “Username” and “Password”.</a></li>
                        <li><a href="#inv4">Navigate to the "Profile" section and select the "Invite User" option.</a></li>
						<li><a href="#inv4">Click the "Invite User" button.</a></li>
						<li><a href="#inv5">Fill in the required details on the form.</a></li>
						<li><a href="#inv5">Click the "Invite User" button to send the invitation.</a></li>
                    </ul>
                </li>
            </ul>
        </div>

        <!-- Right Content Section -->
        <div class="content">
            <section >
                <img id ="invite1" src="https://i.imgur.com/Zl7sNak.jpeg" alt="Image 1">
            </section>
				
            <section>
                <img id ="inv2" src="https://i.imgur.com/slz5VOL.jpeg" alt="Image 2"><br>
				<p>Open the application.</p>
            </section>
			
            <section>
                <img id="inv3" src="https://i.imgur.com/evNL2oJ.jpeg" alt="Image 3"><br>
				<p>Log in using your “<b>Username</b>” and “<b>Password</b>”.</p>
            </section>

            <section>
                <img id="inv4" src="https://i.imgur.com/29ix2MO.jpeg" alt="Image 4"><br>
                <p>Navigate to the "<b>Profile</b>" section and select the "<b>Invite User</b>" option.</p>
				<p>Click the "<b>Invite User</b>" button.</p>
            </section>

            <section >
                <img id="inv5" src="https://i.imgur.com/wu9g4LO.jpeg" alt="Image 5"><br>
				<p>Fill in the required details on the form.</p>
				<p>Click the <b>"Invite User"</b> button to send the invitation.</p>
            </section>
			
			<section>
                <img id ="carrier1" src="https://i.imgur.com/Zl7sNak.jpeg" alt="Image 1">
				<p>Open the application.</p>
            </section>
			
            <section>
                <img id ="inv2" src="https://i.imgur.com/slz5VOL.jpeg" alt="Image 2"><br>
				<p>Open the application.</p>
            </section>
			<section>
                <img id ="invite1" src="https://i.imgur.com/Zl7sNak.jpeg" alt="Image 1">
				<p>Open the application.</p>
            </section>
			
            <section id="section2">
                <img id ="inv2" src="https://i.imgur.com/slz5VOL.jpeg" alt="Image 2"><br>
				<p>Open the application.</p>
            </section>
			<section>
                <img id ="invite1" src="https://i.imgur.com/Zl7sNak.jpeg" alt="Image 1">
				<p>Open the application.</p>
            </section>
			
            <section>
                <img id ="inv2" src="https://i.imgur.com/slz5VOL.jpeg" alt="Image 2"><br>
				<p>Open the application.</p>
            </section>
			
			<section >
                <img id ="invite1" src="https://i.imgur.com/Zl7sNak.jpeg" alt="Image 1">
				<p>Open the application.</p>
            </section>
			
            <section>
                <img id ="inv2" src="https://i.imgur.com/slz5VOL.jpeg" alt="Image 2"><br>
				<p>Open the application.</p>
            </section>

            <section id="section2">
                <img id ="inv2" src="https://i.imgur.com/slz5VOL.jpeg" alt="Image 2"><br>
				<p>Open the application.</p>
            </section>
			
            <a href="#top" class="floating-box">↑ Top</a>
        </div>
    </div>

    <script>
        function toggleSubLinks(sectionId) {
            const subLinks = document.getElementById(sectionId);
            if (subLinks.style.display === "none" || subLinks.style.display === "") {
                subLinks.style.display = "block";
            } else {
                subLinks.style.display = "none";
            }
        }
    </script>
</body>
</html>
