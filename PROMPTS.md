make a footer section with form Including Footer Section

Logo on the left
Social media links with icons on the right
A horizontal divider
Copyright message below the divider



OUTPUT
<!-- Here's a modern, responsive HTML5 + CSS3 footer that includes:

✅ Logo on the left
✅ Social media icons on the right (Font Awesome)
✅ Contact form
✅ Horizontal divider
✅ Copyright section
✅ Dark premium design
✅ Fully responsive (mobile-friendly)
HTML
<!-- Font Awesome -->
<!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">

<footer class="footer">
    <div class="footer-container"> -->

        <!-- Contact Form -->
        <div class="footer-form">
            <h2>Stay Connected</h2>
            <p>Subscribe for conference updates and announcements.</p>

            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Email Address" required>
                <textarea placeholder="Your Message"></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>

        <!-- Bottom Footer -->
        <div class="footer-bottom">

            <div class="footer-logo">
                <h2>TechConf</h2>
            </div>

            <div class="footer-social">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-x-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
            </div>

        </div>

        <hr>

        <div class="copyright">
            <p>&copy; 2026 TechConf. All Rights Reserved.</p>
        </div>

    </div>
</footer>
CSS
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

.footer{
    background:#0B0F19;
    color:#fff;
    padding:80px 20px 30px;
}

.footer-container{
    max-width:1200px;
    margin:auto;
}

/* Form */

.footer-form{
    max-width:700px;
    margin:0 auto 70px;
    text-align:center;
}

.footer-form h2{
    font-size:2rem;
    margin-bottom:10px;
}

.footer-form p{
    color:#b5b5b5;
    margin-bottom:30px;
}

.footer-form form{
    display:flex;
    flex-direction:column;
    gap:18px;
}

.footer-form input,
.footer-form textarea{
    width:100%;
    padding:16px;
    border:none;
    border-radius:10px;
    background:#151b28;
    color:#fff;
    outline:none;
    font-size:16px;
}

.footer-form textarea{
    height:140px;
    resize:none;
}

.footer-form input:focus,
.footer-form textarea:focus{
    border:1px solid #4F46E5;
}

.footer-form button{
    width:220px;
    margin:auto;
    padding:16px;
    border:none;
    border-radius:10px;
    background:#4F46E5;
    color:#fff;
    font-size:16px;
    cursor:pointer;
    transition:.3s;
}

.footer-form button:hover{
    background:#675dff;
}

/* Bottom */

.footer-bottom{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:20px;
    margin-bottom:30px;
}

.footer-logo h2{
    font-size:2rem;
}

.footer-social{
    display:flex;
    gap:18px;
}

.footer-social a{
    width:45px;
    height:45px;
    display:flex;
    align-items:center;
    justify-content:center;
    border-radius:50%;
    background:#151b28;
    color:#fff;
    text-decoration:none;
    font-size:18px;
    transition:.3s;
}

.footer-social a:hover{
    background:#4F46E5;
    transform:translateY(-4px);
}

hr{
    border:none;
    border-top:1px solid rgba(255,255,255,.15);
    margin:30px 0;
}

.copyright{
    text-align:center;
    color:#9ca3af;
    font-size:15px;
}

/* Responsive */

@media(max-width:768px){

    .footer-bottom{
        flex-direction:column;
        text-align:center;
    }

    .footer-social{
        justify-content:center;
        flex-wrap:wrap;
    }

    .footer-form button{
        width:100%;
    }
}
Optional premium additions

To make it look even more "conference website" quality, you can also add:

✨ Glassmorphism form (backdrop-filter: blur(15px))
🌈 Gradient button with glow effect
🎯 Animated social icon hover
📍 Newsletter + Contact form in two columns
🗺️ Address, phone, and email section
📄 Quick links (Home, Speakers, Schedule, Tickets)
⬆️ Back-to-top floating button
💫 Subtle background gradient or animated particles

These additions can make the footer feel like a polished, production-ready section rather than a basic one. -->