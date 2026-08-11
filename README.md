# Love.html
For my special person
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Our Little Love Story 💗</title>

<style>
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        font-family: "Georgia", serif;
        background: linear-gradient(135deg, #ffd6e7, #ffb6d5, #ffe4ef);
        min-height: 100vh;
        overflow: hidden;
        color: #7a2148;
    }

    .page {
        display: none;
        min-height: 100vh;
        width: 100%;
        padding: 40px 25px;
        justify-content: center;
        align-items: center;
        text-align: center;
        position: relative;
    }

    .page.active {
        display: flex;
        animation: fadeIn 0.8s ease;
    }

    .card {
        width: min(700px, 92%);
        padding: 45px 35px;
        border-radius: 30px;
        background: rgba(255,255,255,0.55);
        backdrop-filter: blur(10px);
        box-shadow: 0 15px 40px rgba(160, 45, 90, 0.18);
        border: 2px solid rgba(255,255,255,0.7);
        position: relative;
        z-index: 2;
    }

    h1 {
        font-size: clamp(38px, 8vw, 65px);
        margin-bottom: 25px;
        color: #c2185b;
    }

    h2 {
        font-size: clamp(30px, 6vw, 48px);
        margin-bottom: 25px;
        color: #c2185b;
    }

    p {
        font-size: clamp(18px, 3vw, 23px);
        line-height: 1.8;
        color: #71304c;
    }

    .heart {
        font-size: 45px;
        margin-bottom: 20px;
        animation: heartbeat 1.4s infinite;
    }

    .next-btn {
        margin-top: 35px;
        padding: 14px 35px;
        border: none;
        border-radius: 30px;
        background: #d81b60;
        color: white;
        font-size: 17px;
        cursor: pointer;
        box-shadow: 0 7px 18px rgba(216,27,96,0.3);
        transition: 0.3s;
    }

    .next-btn:hover {
        transform: scale(1.08);
        background: #ad1457;
    }

    .floating-heart {
        position: fixed;
        bottom: -50px;
        font-size: 25px;
        animation: floatUp linear infinite;
        opacity: 0.7;
        pointer-events: none;
    }

    @keyframes fadeIn {
        from {
            opacity: 0;
            transform: translateY(20px) scale(0.98);
        }
        to {
            opacity: 1;
            transform: translateY(0) scale(1);
        }
    }

    @keyframes heartbeat {
        0%, 100% {
            transform: scale(1);
        }
        50% {
            transform: scale(1.2);
        }
    }

    @keyframes floatUp {
        from {
            transform: translateY(0) rotate(0deg);
        }
        to {
            transform: translateY(-110vh) rotate(360deg);
        }
    }

    .small {
        margin-top: 15px;
        font-size: 16px;
        opacity: 0.8;
    }
</style>
</head>

<body>

<!-- PAGE 1 -->
<section class="page active">
    <div class="card">
        <div class="heart">💗</div>

        <h1>Hi Love,<br>Happy Birthday! 🎂</h1>

        <p>
            Today isn't just about celebrating another year of your life...
            it's about celebrating the beautiful person you are and how lucky
            I feel to have you as such a special part of my life.
        </p>

        <button class="next-btn" onclick="nextPage()">Next 💕</button>
    </div>
</section>


<!-- PAGE 2 -->
<section class="page">
    <div class="card">
        <div class="heart">💞</div>

        <h2>Our Story</h2>

        <p>
            Every beautiful story begins somewhere...
            and ours began in the most unexpected, simple way.
            Little did we know that one small moment would eventually
            turn into so many memories, conversations, laughs and feelings.
        </p>

        <button class="next-btn" onclick="nextPage()">Next 💕</button>
    </div>
</section>


<!-- PAGE 3 -->
<section class="page">
    <div class="card">
        <div class="heart">💓</div>

        <h2>How It All Began</h2>

        <p>
            It all began with me accepting a request.
            Then came our random conversations — talking about absolutely
            everything and nothing at the same time.
            Slowly, those random conversations became something I looked
            forward to every day.
            <br><br>
            Somewhere along the way, we stopped being just two people
            talking and became friends.
            And honestly, that friendship became one of the most beautiful
            beginnings to our story.
        </p>

        <button class="next-btn" onclick="nextPage()">Next 💕</button>
    </div>
</section>


<!-- PAGE 4 -->
<section class="page">
    <div class="card">
        <div class="heart">❤️</div>

        <h2>The Beginning of Us</h2>

        <p>
            We became best friends, and without even realizing it,
            we were creating something really special.
            <br><br>
            That was the beginning of our journey.
            Then I asked you to become my homeboy...
            and somehow, that little moment became the beginning
            of something even more beautiful.
            <br><br>
            Our friendship slowly turned into feelings,
            and our feelings became the beginning of our love story.
        </p>

        <button class="next-btn" onclick="nextPage()">Next 💕</button>
    </div>
</section>


<!-- PAGE 5 -->
<section class="page">
    <div class="card">
        <div class="heart">💖</div>

        <h2>My Favourite Memories</h2>

        <p>
            Then came the moment you proposed to me to be your girlfriend,
            and suddenly our little story became something I never wanted
            to stop writing.
            <br><br>
            Our video calls, our conversations, and the way you call me
            beautiful every single day — all those little things mean
            more to me than you probably realize.
            <br><br>
            Happy birthday, my love. 🎂💗
            The way you treat me and the care you show me is truly one
            of the sweetest things about you.
        </p>

        <button class="next-btn" onclick="nextPage()">Next 💕</button>
    </div>
</section>


<!-- PAGE 6 -->
<section class="page">
    <div class="card">
        <div class="heart">💘</div>

        <h2>Why I Love You</h2>

        <p>
            I love you for the man you are and for the man you are becoming.
            <br><br>
            I love the person behind all the little things,
            the person who makes me smile, makes ordinary moments special,
            and has become such an important part of my life.
            <br><br>
            I hope you always remember how special you are.
        </p>

        <button class="next-btn" onclick="nextPage()">Next 💕</button>
    </div>
</section>


<!-- PAGE 7 -->
<section class="page">
    <div class="card">
        <div class="heart">💗</div>

        <h2>Thank You, Love</h2>

        <p>
            Thank you for being with me.
            <br><br>
            Thank you for every conversation, every laugh,
            every memory and every little moment that became
            a part of our story.
            <br><br>
            Whatever the future brings, I'll always be grateful
            that our paths crossed and that our story began.
            <br><br>
            <strong>Happy Birthday, my love. 💕🎂</strong>
        </p>

        <p class="small">
            Here's to all the memories we've made and all the beautiful
            moments still waiting for us. ♡
        </p>

        <button class="next-btn" onclick="restart()">Read Again 💗</button>
    </div>
</section>


<script>

let currentPage = 0;
const pages = document.querySelectorAll(".page");

function nextPage() {
    pages[currentPage].classList.remove("active");

    currentPage++;

    if (currentPage >= pages.length) {
        currentPage = 0;
    }

    pages[currentPage].classList.add("active");
}

function restart() {
    pages[currentPage].classList.remove("active");
    currentPage = 0;
    pages[currentPage].classList.add("active");
}


/* Floating hearts */
function createHeart() {
    const heart = document.createElement("div");

    heart.classList.add("floating-heart");
    heart.innerHTML = ["♡", "♥", "💕", "💗", "💖"][Math.floor(Math.random() * 5)];

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (5 + Math.random() * 6) + "s";
    heart.style.fontSize = (18 + Math.random() * 25) + "px";

    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 11000);
}

setInterval(createHeart, 500);

</script>

</body>
</html>
