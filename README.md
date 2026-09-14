# zakii-betting-app
ZAKII KE Sports Betting App
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ZAKII KE SPORTS</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    font-family:Arial,sans-serif;
    background:#f3f5f7;
    color:#222;
}

header{
    background:#087f23;
    color:white;
    padding:18px;
    text-align:center;
}

header h1{
    font-size:25px;
}

header p{
    margin-top:5px;
    font-size:13px;
}

nav{
    background:white;
    display:flex;
    justify-content:space-around;
    padding:13px 5px;
    box-shadow:0 2px 5px #ccc;
}

nav button{
    border:0;
    background:none;
    font-weight:bold;
    color:#555;
}

.container{
    padding:12px;
    max-width:600px;
    margin:auto;
}

.section-title{
    margin:15px 0 10px;
    font-size:19px;
}

.match{
    background:white;
    border-radius:10px;
    margin-bottom:12px;
    padding:15px;
    box-shadow:0 2px 5px #ddd;
}

.league{
    font-size:12px;
    color:#777;
    margin-bottom:10px;
}

.teams{
    font-size:17px;
    font-weight:bold;
    margin-bottom:12px;
}

.odds{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:7px;
}

.odds button{
    background:#eef1f3;
    border:1px solid #ddd;
    padding:10px 5px;
    border-radius:6px;
    font-weight:bold;
}

.odds button:hover{
    background:#087f23;
    color:white;
}

.betslip{
    background:white;
    border-radius:10px;
    padding:15px;
    margin-top:15px;
    box-shadow:0 2px 5px #ddd;
}

.betslip h2{
    margin-bottom:12px;
}

.bet{
    background:#f1f3f4;
    padding:10px;
    border-radius:6px;
    margin-bottom:7px;
}

input{
    width:100%;
    padding:12px;
    margin-top:10px;
    border:1px solid #ccc;
    border-radius:6px;
    font-size:16px;
}

.place{
    width:100%;
    padding:13px;
    margin-top:12px;
    background:#087f23;
    color:white;
    border:0;
    border-radius:7px;
    font-size:17px;
    font-weight:bold;
}

footer{
    text-align:center;
    padding:25px;
    color:#777;
    font-size:12px;
}
</style>
</head>

<body>

<header>
    <h1>⚽ ZAKII KE SPORTS</h1>
    <p>Sports Predictions & Virtual Bet Slip</p>
</header>

<nav>
    <button>🏠 Home</button>
    <button>⚽ Matches</button>
    <button>🎟️ Bet Slip</button>
    <button>👤 Account</button>
</nav>

<div class="container">

<h2 class="section-title">🔥 Today's Matches</h2>

<div class="match">
    <div class="league">Premier League</div>

    <div class="teams">
        Arsenal vs Chelsea
    </div>

    <div class="odds">
        <button onclick="addBet('Arsenal',1.80)">
            Arsenal<br>1.80
        </button>

        <button onclick="addBet('Draw',3.20)">
            Draw<br>3.20
        </button>

        <button onclick="addBet('Chelsea',2.50)">
            Chelsea<br>2.50
        </button>
    </div>
</div>

<div class="match">
    <div class="league">Premier League</div>

    <div class="teams">
        Man United vs Liverpool
    </div>

    <div class="odds">
        <button onclick="addBet('Man United',2.10)">
            Man United<br>2.10
        </button>

        <button onclick="addBet('Draw',3.00)">
            Draw<br>3.00
        </button>

        <button onclick="addBet('Liverpool',1.90)">
            Liverpool<br>1.90
        </button>
    </div>
</div>

<div class="match">
   
