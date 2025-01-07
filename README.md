<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SG EVENTS</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="icon" type="image/x-icon" href="Media/favicon.ico">
</head>
<body>
    <header id="header">
        <div class="header-content">
            <img src="Media/logo2.png" alt="Company Logo" class="logo">
        </div>
    </header>
    
    <section id="hero" class="fade-in">
        <div class="slideshow-container">
            <div class="mySlides fade">
                <img src="Media/gallery1.JPG" style="width:100%">
            </div>
            <div class="mySlides fade">
                <img src="Media/gallery8.JPG" style="width:100%">
            </div>
            <div class="mySlides fade">
                <img src="Media/78.JPG" style="width:100%">
            </div>
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
        <div class="hero-overlay"></div> <!-- Add this line -->
        <div class="hero-content">
            <button id="buy-tickets-button" class="cta-button">Buy Tickets</button>
            <div class="next-event-info"></div>
        </div>
    </section>
    
    
    
    <section id="image-section" class="fade-in">
        <div class="content-container">
            <!-- Next Event Title -->
            <div class="next-event">Next Event</div>
    
            <!-- New Countdown Text -->
            <div class="flyer-container">
                <img src="Media/flyer44.JPG" alt="Event Flyer" class="flyer-image">
            </div>

            <div class="event-button-container">
                <a href="https://www.eventbrite.co.uk/e/sg-events-presents-la-premiere-tickets-1035219378027?utm_experiment=test_share_listing&aff=ebdsshios" class="event-button">Buy Tickets</a>
            </div>
    
            <!-- Timer Section -->
            <div class="timer" id="event-timer">
                <div>
                    <span id="days">00</span>
                    <p>Days</p>
                </div>
                <div>
                    <span id="hours">00</span>
                    <p>Hours</p>
                </div>
                <div>
                    <span id="minutes">00</span>
                    <p>Minutes</p>
                </div>
                <div>
                    <span id="seconds">00</span>
                    <p>Seconds</p>
                </div>
            </div>
    
            <!-- Button -->
            <div class="additional-images">
                <a href="https://www.facebook.com/shutdownglobalevents" target="_blank" rel="noopener noreferrer">
                    <img src="Media/facebook (1).png" alt="Facebook" class="event-image">
                </a>
                <a href="https://www.instagram.com/sgevents___/" target="_blank" rel="noopener noreferrer">
                    <img src="Media/insta (1).png" alt="Instagram" class="event-image">
                </a>
                <a href="https://www.tiktok.com/@sgevents__?lang=en" target="_blank" rel="noopener noreferrer">
                    <img src="Media/tiktok (1).png" alt="TikTok" class="event-image">
                </a>
            </div>
        </div>
    </section>
        </div>
    </section>
    
    
    
    <!-- Link to your JavaScript file -->
    <script src="countdown.js" defer></script>
    
    <div id="video-section">
        <h2>Watch Our Latest Event</h2>
        <div class="video-wrapper">
            <iframe 
                width="560" 
                height="315" 
                src="https://www.youtube.com/embed/7FiYgtfpKiQ?si=wGH7PPf_AGJrJhh6" 
                title="YouTube video player" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                referrerpolicy="strict-origin-when-cross-origin" 
                allowfullscreen>
            </iframe>
        </div>
    </div>
    
    

    <section id="gallery-section" class="fade-in">
        <h2>Gallery</h2>
        <div class="gallery-container">
            <img src="Media/gallery1.JPG" alt="Gallery Image 1" class="gallery-image">
            <img src="Media/gallery2.jpg" alt="Gallery Image 2" class="gallery-image">
            <img src="Media/gallery3.jpg" alt="Gallery Image 3" class="gallery-image">
            <img src="Media/Gallery4.jpg" alt="Gallery Image 4" class="gallery-image">
            <img src="Media/55.JPG" alt="Gallery Image 5" class="gallery-image">
            <img src="Media/gallery6.jpg" alt="Gallery Image 6" class="gallery-image">
            <img src="Media/gallery7.jpg" alt="Gallery Image 7" class="gallery-image">
            <img src="Media/gallery8.JPG" alt="Gallery Image 8" class="gallery-image">
            <img src="Media/galler9.JPG" alt="Gallery Image 9" class="gallery-image">
            <img src="Media/78.JPG" alt="Gallery Image 10" class="gallery-image">
            <img src="Media/galeery12.JPG" alt="Gallery Image 11" class="gallery-image">
            <img src="Media/gallery13.JPG" alt="Gallery Image 12" class="gallery-image">
        </div>
    </section>

    <section id="faq-section" class="fade-in">
        <h2>Frequently Asked Questions</h2>
        <div class="faq-item">
            <h3>Can I reserve a VIP Table in advance?</h3>
            <p>Yes, VIP Tables can be reserved in advance through our website or by contacting us via Instagram DMs. Booking a VIP Table guarantees entry for attendees and offers an elevated experience with dedicated service.</p>
        </div>
        <div class="faq-item">
            <h3>Are there any age restrictions?</h3>
            <p>All attendees must be 18 years or older and must present valid identification upon entry.</p>
        </div>
        <div class="faq-item">
            <h3>What music can I expect at SG events?</h3>
            <p>SG events feature some of the UK's biggest DJs who play the latest in hip-hop, trap, R&B, bashment, afrobeats, and amapiano. Our aim is to provide an exclusive and unforgettable music experience.</p>
        </div>
        <div class="faq-item">
            <h3>Can I buy tickets at the door?</h3>
            <p>Majority of our events are ticket-only to keep the exclusivity; however, we may put a certain amount of tickets at the door depending on the event. This will be stated on our event flyer.</p>
        </div>
        <div class="faq-item">
            <h3>How can I stay updated about upcoming SG events?</h3>
            <p>To stay in the loop about our upcoming events, follow us on our social media platforms.</p>
            <a href="https://www.instagram.com/sgevents___/" target="_blank" rel="noopener noreferrer">
                <img src="Media/insta (1).png" alt="Instagram" class="event-image">
            </a>
            <a href="https://www.tiktok.com/@sgevents__?lang=en" target="_blank" rel="noopener noreferrer">
                <img src="Media/tiktok (1).png" alt="TikTok" class="event-image">
            </a>
        </div>
    </section>

    <footer id="footer" class="fade-in">
        <p>© Copyright SG EVENTS Designed By <a href="https://www.instagram.com/dkwebworkss/" >DkWebWorks</a>   </p>
    </footer>   

    <script>
        // Countdown function
       
    // Countdown function
// Countdown function
function updateCountdown() {
    const targetDate = new Date('November 2, 2024 00:00:00'); // Updated to November 2, 2024
    const now = new Date();
    const timeDifference = targetDate - now;

    if (timeDifference <= 0) {
        document.getElementById('days').textContent = '00';
        document.getElementById('hours').textContent = '00';
        document.getElementById('minutes').textContent = '00';
        document.getElementById('seconds').textContent = '00';
        clearInterval(timerInterval);
        return;
    }

    const days = Math.floor(timeDifference / (1000 * 60 * 60 * 24));
    const hours = Math.floor((timeDifference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((timeDifference % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((timeDifference % (1000 * 60)) / 1000);

    document.getElementById('days').textContent = days.toString().padStart(2, '0');
    document.getElementById('hours').textContent = hours.toString().padStart(2, '0');
    document.getElementById('minutes').textContent = minutes.toString().padStart(2, '0');
    document.getElementById('seconds').textContent = seconds.toString().padStart(2, '0');
}

const timerInterval = setInterval(updateCountdown, 1000);
updateCountdown();



        // Redirect to Eventbrite event page
        document.getElementById('buy-tickets-button').addEventListener('click', () => {
            window.open('https://www.eventbrite.com/e/943731485277', '_blank'); // Replace with your actual Eventbrite event URL
        });

        document.getElementById('buy-now-button').addEventListener('click', () => {
            window.open('https://www.eventbrite.com/e/943731485277', '_blank'); // Replace with your actual Eventbrite event URL
        });

        // Intersection Observer for fade-in effect
        const fadeInElements = document.querySelectorAll('.fade-in');
        const observerOptions = {
            root: null,
            threshold: 0.1
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in-visible');
                    observer.unobserve(entry.target);
                }
            });
        }, observerOptions);

        fadeInElements.forEach(element => observer.observe(element));
    </script>
    <script>
        let slideIndex = 0;
        showSlides();
        
        function showSlides() {
            let i;
            let slides = document.getElementsByClassName("mySlides");
            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";  
            }
            slideIndex++;
            if (slideIndex > slides.length) {slideIndex = 1}    
            slides[slideIndex-1].style.display = "block";  
            setTimeout(showSlides, 5000); // Change image every 5 seconds
        }
        
        function plusSlides(n) {
            slideIndex += n;
            if (slideIndex < 1) {slideIndex = slides.length}
            if (slideIndex > slides.length) {slideIndex = 1}
            showSlides();
        }
        </script>
        
</body>
</html>/* General Styles */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: white;
    overflow-x: hidden;
}

/* Header Styles */
header {
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1000;
    padding: 10px 20px;
    display: flex;
    justify-content: center;
    background-color: rgba(0, 0, 0, 0.8);
    border-bottom: 1px solid rgba(255, 255, 255, 0.319);
    transition: background-color 0.3s ease, border-bottom 0.3s ease;
}
/* Flyer Image Styles */
.flyer-container {
    margin-top: 20px;
    text-align: center;
}

.flyer-image {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5); /* Add shadow for depth */
}

#header.scrolled {
    background-color: rgba(0, 0, 0, 1);
    border-bottom: 0.5px solid white;
}

.header-content {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
}

.logo {
    max-width: 150px;
    padding-right: 50px;
    align-self: center;
}

/* Hero Section Styles */
#hero {
    position: relative;
    height: 100vh;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
}

.hero-content h1 {
    font-size: 3em;
    font-weight: bold;
    color: white;
    text-transform: uppercase;
    line-height: 1.2;
    margin: 0;
    padding: 0;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
}

/* Video Section Styles */
#video-section {
    padding: 40px 20px;
    background-color: #333;
    color: #fff;
    text-align: center;
}

#video-section h2 {
    font-size: 2em;
    margin-bottom: 20px;
    color: #ffd700;
    font-family: 'Georgia';
}

.video-wrapper {
    max-width: 800px;
    margin: 0 auto;
}

video {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.video-container {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    overflow: hidden;
    z-index: -1;
    border: 5px solid white;
}

#background-video {
    width: 100%;
    height: 100%;
    object-fit: cover;
    position: absolute;
    top: 0;
    left: 0;
    filter: brightness(28%);
}

.video-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7);
}

/* Button Styles */
.cta-button, #buy-now-button {
    padding: 15px 30px;
    font-size: 1.3em;
    background: linear-gradient(135deg, #f7d700, #f5b300);
    border: none;
    border-radius: 12px;
    color: #333333;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.7);
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}

.cta-button:hover, #buy-now-button:hover {
    background: linear-gradient(135deg, #555, #777);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.8);
    transform: translateY(-2px);
}

.cta-button:active, #buy-now-button:active {
    background: linear-gradient(135deg, #444, #666);
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4);
    transform: translateY(0);
}

/* Image Section Styles */
#image-section {
    background-color: #1e1e1e;
    padding: 50px 20px;
    text-align: center;
    color: white;
}

/* Refined Next Event Styles */
.next-event {
    font-size: 2.5em;
    font-weight: bold;
    color: #ffd700;
    margin-bottom: 30px;
    text-transform: uppercase;
    letter-spacing: 1.5px;
}

/* Content Container Styles */
.content-container {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    overflow: hidden;
}

/* Image Styles */
.image-left {
    width: 30%; /* Reduced width for smaller images */
    height: auto; /* Maintain aspect ratio */
    margin-right: 20px; /* Adjusted margin for better spacing */
}

/* Event Details Container */
#event-details {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    text-align: left;
    padding: 20px;
    width: 65%; /* Adjusted width to accommodate smaller image */
}

#event-details h4 {
    font-size: 1.2em;
    margin-bottom: 10px;
    color: #ffd700;
}

#event-details h1 {
    font-size: 2.5em;
    margin: 20px 0;
    color: #ffffff;
    line-height: 1.4;
    font-weight: 600;
    text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.4);
    letter-spacing: 0.5px;
    font-family: 'Georgia', serif;
    text-transform: capitalize;
}

/* Timer Styles */
.timer {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.5em;
    margin-top: 30px;
}

.timer div {
    margin: 0 10px;
}

.timer span {
    display: block;
    font-size: 2em;
    font-weight: bold;
    color: #ffd700;
}

.timer p {
    margin: 0;
}

/* FAQ Section Styles */
#faq-section {
    background-color: #1e1e1e;
    color: white;
    padding: 40px 20px;
    text-align: center;
    font-family: 'Georgia', serif;
}

#faq-section h2 {
    font-size: 2.5em;
    margin-bottom: 30px;
    color: #ffd700;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.faq-item {
    background-color: #1e1e1e;
    border-radius: 8px;
    padding: 20px;
    margin: 15px 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
    font-family: 'Georgia', serif;
}

.faq-item h3 {
    font-size: 1.5em;
    margin-bottom: 10px;
    color: #ffd700;
    text-transform: uppercase;
    font-family: 'Georgia', serif;
}

.faq-item p {
    font-size: 1.2em;
    margin: 0;
    line-height: 1.5;
    color: #ffffff;
    font-family: 'Georgia', serif;
}

.faq-item img {
    width: 50px; /* Smaller image size */
    height: 50px; /* Keep the height equal to the width */
    margin: 5px; /* Spacing around the images */
    object-fit: cover; /* Ensure images cover the area properly */
}

/* Gallery Section Styles */
#gallery-section {
    padding: 80px 20px;
    background-color: #1e1e1e;
    color: #fff;
    text-align: center;
    min-height: 1000px;
}

#gallery-section h2 {
    font-size: 3.5em;
    margin-bottom: 50px;
    color: #ffd700;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.gallery-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 30px;
    justify-content: center;
    max-width: 1200px;
    margin: 0 auto;
}

.gallery-image {
    width: 100%;
    height: 400px;
    object-fit: cover;
    border-radius: 12px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-image:hover {
    transform: scale(1.05);
    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.7);
}

/* Footer Styles */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}

footer a {
    color: #ffd700;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}

/* Additional Images Section Styles */
.additional-images {
    display: flex;
    justify-content: center;
    gap: 20px; /* Adjust spacing between images */
    padding: 20px;
}

.event-image {
    width: 40px; /* Smaller width for icons */
    height: 40px; /* Ensure height matches width */
    object-fit: cover; /* Ensure images cover the area properly */
    transition: transform 0.3s ease; /* Smooth hover effect */
}

.event-image:hover {
    transform: scale(1.1); /* Slightly enlarge the image on hover */
}

/* Media Queries */

/* Hide Video Section on Mobile */


/* Adjust Image Sizes and Layout for Mobile */
@media (max-width: 768px) {
    .content-container {
        flex-direction: column;
        align-items: center;
    }

    .image-left {
        width: 80%;
        margin-right: 0;
        margin-bottom: 20px;
    }

    #event-details {
        width: 90%;
    }

    .faq-item {
        width: 90%;
    }

    .gallery-image {
        height: 250px;
    }

    .event-image {
        width: 30px; /* Smaller width on medium screens */
        height: 30px; /* Ensure height matches width */
    }
}

@media (max-width: 480px) {
    .hero-content h1 {
        font-size: 2em;
    }

    #event-details h1 {
        font-size: 1.8em;
    }

    .timer {
        font-size: 1.2em;
    }

    .faq-item h3 {
        font-size: 1.2em;
    }

    .gallery-image {
        height: 200px;
    }

    .event-image {
        width: 25px; /* Even smaller width on small screens */
        height: 25px; /* Ensure height matches width */
    }
}
/* Updated Countdown Text Style */
.countdown-text {
    font-size: 1.5em;
    color: #ffd700;
    text-align: center;
    margin-bottom: 15px;
    font-family: 'Georgia', sans-serif;
}

.countdown-text p {
    margin: 10px 0;
    line-height: 1.6;
    font-size: 1.2em;
    color: #ffffff;
}
/* Image Section Styles */
#image-section {
    background-color: #1e1e1e;
    padding: 20px;
    color: white;
}

/* Next Event Styles */
.next-event {
    font-size: 2em;
    font-weight: 700;
    color: #ffd700;
    margin-bottom: 20px;
    text-align: center;
    text-transform: uppercase;
    font-family: 'Georgia', sans-serif;
}

/* Content Container in Column */
.content-container {
    display: flex;
    flex-direction: column;
    align-items: center; /* Align content to center */
    text-align: center; /* Center the text */
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
}

/* Timer Styles */
.timer {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.5em;
    margin: 20px 0;
}

.timer div {
    margin: 0 10px;
}

.timer span {
    display: block;
    font-size: 2em;
    font-weight: bold;
    color: #ffd700;
}

.timer p {
    margin: 0;
}

/* Social Media Icons */
.additional-images {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.event-image {
    width: 40px;
    height: 40px;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.event-image:hover {
    transform: scale(1.1);
}
/* Hero Section Styles */
#hero {
    position: relative;
    height: 100vh;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
}

/* Overlay Styles */
.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1; /* Place it above the background images but below content */
}

/* Adjust hero content z-index */
.hero-content {
    position: relative; /* Ensure content is above overlay */
    z-index: 2; /* Make sure it's above the overlay */
}

/* Adjust existing styles as necessary *//* Slideshow container */
.slideshow-container {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    overflow: hidden;
    z-index: -1;
    border: 5px solid white;
}

/* Fading animation */
.fade {
    animation-name: fade;
    animation-duration: 1.5s;
}

@keyframes fade {
    from { opacity: 0.4; }
    to { opacity: 1; }
}

/* Slideshow controls (Next/prev buttons) */
.prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    margin-top: -22px;
    padding: 16px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
    user-select: none;
}

.next {
    right: 0;
    border-radius: 3px 0 0 3px;
}

.prev:hover, .next:hover {
    background-color: rgba(0,0,0,0.8);
}

/* Image adjustments */
.mySlides img {
    width: 100%;
    height: 100vh;
    object-fit: cover;
}

.tiktok-container {
    display: flex;
    justify-content: center;
    gap: 20px;
  }/* Video Section Styles */
/* Video Section Styles */
#video-section {
    padding: 40px 20px;
    background-color: #333;
    color: #fff;
    text-align: center;
    border-radius: 12px; /* Rounded corners */
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5); /* Shadow for depth */
    margin: 20px auto; /* Center the section with margin */
    max-width: 900px; /* Limit the max width */
}

#video-section h2 {
    font-size: 2em;
    margin-bottom: 20px;
    color: #ffd700;
    font-family: 'Georgia';
    text-transform: uppercase;
    letter-spacing: 1px;
    text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.7); /* Subtle shadow for the title */
}

.video-wrapper {
    max-width: 100%; /* Use full width within max-width */
    margin: 0 auto; /* Center the video wrapper */
    position: relative;
    padding-top: 56.25%; /* 16:9 Aspect Ratio */
}

.video-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%; /* Fill the wrapper */
    border-radius: 8px; /* Round the video corners */
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5); /* Shadow for the video */
}


@media (max-width: 768px) {
    #video-section {
        padding: 20px 10px; /* Adjust padding for smaller screens */
    }
    #video-section h2 {
        font-size: 1.5em; /* Smaller font size for headings */
    }
    .video-wrapper iframe {
        height: 300px; /* Smaller height for mobile */
    }
}
@media (max-width: 768px) {
    #hero {
        height: auto; /* Allow the hero section to adjust based on content */
        min-height: 60vh; /* Minimum height to keep some visual space */
    }

    .mySlides img {
        height: auto; /* Allow images to maintain their aspect ratio */
    }
}
.mySlides img {
    width: 100%;
    height: auto; /* Maintain aspect ratio */
    object-fit: cover; /* Adjust if necessary */
}
/* Style for Button Container */
.button-container {
    margin-top: 20px;
    display: flex;
    justify-content: center;
    width: 100%;
}

/* Ensure the button width matches the flyer image width */
#buy-now-button {
    width: 100%;
    max-width: 500px; /* Matches flyer image's max width */
    padding: 15px 0;
    font-size: 1.2em;
    background: linear-gradient(135deg, #f7d700, #f5b300);
    border: none;
    border-radius: 8px;
    color: #333333;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.7);
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: bold;
}

#buy-now-button:hover {
    background: linear-gradient(135deg, #555, #777);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.8);
    transform: translateY(-2px);
}

#buy-now-button:active {
    background: linear-gradient(135deg, #444, #666);
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4);
    transform: translateY(0);
}

/* Ensure flyer-container has a fixed max-width */
.flyer-container {
    max-width: 500px; /* Adjust as necessary */
    margin: 0 auto;
    text-align: center;
}
/* Button Styles */
.event-button {
    display: inline-block; /* Allow padding and margin */
    padding: 15px 30px;
    font-size: 1.5em; /* Adjust font size */
    background: linear-gradient(135deg, #f7d700, #f5b300); /* Gradient background */
    border: none; /* Remove default border */
    border-radius: 12px; /* Rounded corners */
    color: #333; /* Text color */
    text-decoration: none; /* Remove underline from links */
    cursor: pointer; /* Pointer cursor on hover */
    transition: all 0.3s ease; /* Smooth transition for hover effects */
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5); /* Subtle shadow */
    text-transform: uppercase; /* Uppercase text */
    letter-spacing: 1px; /* Letter spacing for readability */
    font-weight: bold; /* Bold text */
    margin-top: 20px; /* Margin for spacing */
}

/* Hover Effects */
.event-button:hover {
    background: linear-gradient(135deg, #f5b300, #f7d700); /* Reverse gradient on hover */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.8); /* Increased shadow on hover */
    transform: translateY(-2px); /* Slight lift effect */
}

/* Active Effects */
.event-button:active {
    background: linear-gradient(135deg, #f5b300, #f7d700); /* Keep hover effect */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4); /* Reduced shadow */
    transform: translateY(0); /* Reset lift effect */
}
@media (max-width: 768px) {
    .mySlides img {
        height: 70vh; /* Increase height to 70% of the viewport height */
        object-fit: cover; /* Ensure the image covers the space without distortion */
    }
}

@media (max-width: 480px) {
    .mySlides img {
        height: 80vh; /* Increase height to 80% of the viewport height for smaller screens */
        object-fit: cover; /* Keep the image from being distorted */
    }
}
@media (max-width: 768px) {
    #video-section {
        padding: 20px 10px; /* Adjust padding for smaller screens */
    }
    #video-section h2 {
        font-size: 1.5em; /* Smaller font size for headings */
    }
    .video-wrapper iframe {
        height: 250px; /* Smaller height for mobile */
    }
}
