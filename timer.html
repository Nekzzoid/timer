<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PTC Timeslots Publishing</title>

<style>
    body {
        margin: 0;
        padding: 0;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background: linear-gradient(135deg, #00539C, #0081C9, #00A8E8); /* School colors */
        font-family: 'Arial', sans-serif;
        color: #fff;
        text-align: center;
    }

    .container {
        padding: 30px;
        background: rgba(0,0,0,0.3);
        border-radius: 15px;
        box-shadow: 0 8px 20px rgba(0,0,0,0.4);
    }

    h1 {
        font-size: 6vw;
        margin-bottom: 20px;
        font-weight: bold;
        text-transform: uppercase;
        color: #FFD700; /* Gold accent */
    }

    #countdown {
        font-size: 14vw;
        font-weight: bold;
        letter-spacing: 2px;
        color: #ffffff;
        text-shadow: 2px 2px 6px #000;
    }

    @media (min-width: 600px) {
        h1 { font-size: 32px; }
        #countdown { font-size: 70px; }
    }
</style>
</head>

<body>

<div class="container">
    <h1>PTC Timeslots Publishing</h1>
    <div id="countdown">Loading...</div>
</div>

<script>
let alarmPlayed = false;

// 🔔 Alarm
function playAlarm() {
    const audio = new Audio("https://actions.google.com/sounds/v1/alarms/alarm_clock.ogg");
    audio.play();
    if (navigator.vibrate) {
        navigator.vibrate([500, 300, 500]);
    }
}

// Format time
function formatTime(time) {
    return time < 10 ? "0" + time : time;
}

function updateCountdown() {
    const now = new Date();
    const target = new Date();

    target.setHours(15, 0, 0, 0); // 3:00 PM

    if (now > target) {
        target.setDate(target.getDate() + 1);
        alarmPlayed = false;
    }

    const diff = target - now;

    const hours = formatTime(Math.floor((diff / (1000 * 60 * 60)) % 24));
    const minutes = formatTime(Math.floor((diff / (1000 * 60)) % 60));
    const seconds = formatTime(Math.floor((diff / 1000) % 60));

    document.getElementById("countdown").innerHTML =
        `${hours}h ${minutes}m ${seconds}s`;

    if (diff <= 0 && !alarmPlayed) {
        document.getElementById("countdown").innerHTML = "PTC Timeslots Published!";
        playAlarm();
        alarmPlayed = true;
    }
}

// Auto start countdown
setInterval(updateCountdown, 1000);
updateCountdown();
</script>

</body>
</html>
