<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QM-Kurs Industriemeister</title>

<style>
body{
 font-family:Arial,sans-serif;
 background:#f4f6f9;
 margin:0;
}

header{
 background:#005b96;
 color:white;
 text-align:center;
 padding:20px;
}

main{
 max-width:1000px;
 margin:auto;
 padding:20px;
}

.card{
 background:white;
 border-radius:10px;
 padding:20px;
 margin-bottom:20px;
 box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.quiz{
 background:#eef7ff;
 padding:15px;
 border-radius:8px;
 margin-top:15px;
}

button{
 background:#005b96;
 color:white;
 padding:10px 20px;
 border:none;
 border-radius:5px;
 cursor:pointer;
}

button:hover{
 background:#003f68;
}
</style>
</head>

<body>

<header>
<h1>Qualitätsmanagement</h1>
<p>Industriemeister Papier- und Kunststoffverarbeitung</p>
</header>

<main>

<div class="card">
<h2>Kapitel 1: Grundlagen des Qualitätsmanagements</h2>

<p>
Qualitätsmanagement umfasst alle Tätigkeiten zur Planung,
Lenkung, Sicherung und Verbesserung der Qualität.
</p>

<ul>
<li>Kundenzufriedenheit steigern</li>
<li>Fehler vermeiden</li>
<li>Kosten senken</li>
<li>Wettbewerbsvorteile schaffen</li>
</ul>
</div>

<div class="card">
<h2>Kapitel 2: Qualitätsbegriffe</h2>

<p>
Qualität ist der Grad, in dem Anforderungen erfüllt werden.
Die ISO 9000 definiert die wichtigsten Qualitätsbegriffe.
</p>

<ul>
<li>Qualitätsplanung</li>
<li>Qualitätslenkung</li>
<li>Qualitätssicherung</li>
<li>Qualitätsverbesserung</li>
</ul>
</div>

<div class="card">

<h2>Prüfungsblock 1</h2>

<div class="quiz">

<p><b>Frage 1:</b> Was beschreibt Qualität nach ISO 9000?</p>

<input type="radio" name="q1"> Teures Produkt<br>
<input type="radio" name="q1" id="q1r"> Erfüllung von Anforderungen<br>
<input type="radio" name="q1"> Hohe Produktionsmenge<br>

<hr>

<p><b>Frage 2:</b> Welche Bereiche gehören zum Qualitätsmanagement?</p>

<input type="radio" name="q2"> Qualitätsplanung<br>
<input type="radio" name="q2"> Qualitätssicherung<br>
<input type="radio" name="q2" id="q2r"> Alle genannten<br>

</div>
</div>

<div class="card">

<h2>Kapitel 3: ISO 9001</h2>

<p>
Die DIN EN ISO 9001 definiert Anforderungen
an ein Qualitätsmanagementsystem.
</p>

<ul>
<li>Kundenorientierung</li>
<li>Führung</li>
<li>Prozessorientierung</li>
<li>Verbesserung</li>
</ul>

</div>

<div class="card">

<h2>Kapitel 4: Prozessorientierung und PDCA</h2>

<p>
Unternehmen werden als Netzwerk von Prozessen betrachtet.
Ein Prozess wandelt Eingaben in Ergebnisse um.
</p>

<h3>PDCA-Zyklus</h3>

<ul>
<li>Plan</li>
<li>Do</li>
<li>Check</li>
<li>Act</li>
</ul>

</div>

<div class="card">

<h2>Prüfungsblock 2</h2>

<div class="quiz">

<p><b>Frage 3:</b> Wofür steht PDCA?</p>

<input type="radio" name="q3" id="q3r">
Plan - Do - Check - Act<br>

<input type="radio" name="q3">
Prepare - Design - Control - Audit<br>

<hr>

<p><b>Frage 4:</b> Was ist ein Prozess?</p>

<input type="radio" name="q4" id="q4r">
Abfolge zusammenhängender Tätigkeiten mit Input und Output<br>

<input type="radio" name="q4">
Organisationsstruktur<br>

</div>

<br>

<button onclick="alert('Version 1 erfolgreich geladen!')">
Kurs testen
</button>

</div>

</main>

</body>
</html>
