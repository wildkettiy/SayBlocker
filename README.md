<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    </head>
<body>
<div class="container">
    <h1>SayBlocker v2.3.1</h1>
    <p>Ein spezialisiertes Addon für WotLK (3.3.5), das den <code>/sagen</code>-Chat in Dalaran filtert, um Spam zu reduzieren, während wichtige Interaktionen erlaubt bleiben.</p>
    <center>
        <img src="https://kittyranger.hopto.org/addons/sb231.png" alt="SayBlocker Interface Vorschau">
    </center>
    <h2>1. Kernfunktionen</h2>
    <ul class="feature-list">
        <li><span class="highlight">Automatischer Dalaran-Filter:</span> Das Addon erkennt, wenn du Dalaran betrittst und aktiviert den Schutz automatisch.</li>
        <li><span class="highlight">Sprechblasen-Blocker:</span> Optional werden auch die grafischen Sprechblasen über den Charakteren ausgeblendet.</li>
        <li><span class="highlight">Manueller Override:</span> Über den Minimap-Button kann der Chat jederzeit für eine festgelegte Dauer (Standard: 60 Sek.) geöffnet werden.</li>
    </ul>
    <h2>2. Whitelist-Systeme</h2>
    <p>SayBlocker nutzt ein zweistufiges Vertrauenssystem, damit du nie Nachrichten von wichtigen Personen verpasst:</p>
    <h3>A. Automatisches Vertrauen</h3>
    <p>In den Einstellungen kannst du festlegen, dass folgende Gruppen den Filter immer umgehen:</p>
    <ul class="feature-list">
        <li>Deine <strong>Freunde</strong> (Friendlist)</li>
        <li>Deine <strong>Gildenmitglieder</strong></li>
        <li>Mitglieder deiner aktuellen <strong>Gruppe oder deines Raids</strong></li>
    </ul>
    <h3>B. Manuelle Whitelist</h3>
    <p>Rechts im Menü kannst du gezielt Namen hinzufügen. Diese Spieler werden niemals blockiert. 
    Um einen Spieler zu entfernen, klicke einfach auf seinen Namen in der Liste (der Name färbt sich beim Drüberfahren <span class="warning">rot</span>).</p>
    <h2>3. Emote-Trigger</h2>
    <p>Du kannst den Chat temporär freischalten, indem du ein Emote ausführst (z.B. <code>/hi</code>, <code>/wave</code> oder <code>/jubeln</code>). Dies signalisiert dem Addon, dass du gerade aktiv am Chat-Geschehen teilnehmen möchtest.</p>
    <h2>4. Bedienung</h2>
    <table style="width:100%; border-collapse: collapse;">
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #444;"><strong>Befehl:</strong></td>
            <td style="padding: 10px; border-bottom: 1px solid #444;"><code>/sbl</code> oder <code>/sayblocker</code></td>
        </tr>
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #444;"><strong>Linksklick (Icon):</strong></td>
            <td style="padding: 10px; border-bottom: 1px solid #444;">Chat manuell öffnen / schließen (Timer)</td>
        </tr>
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #444;"><strong>Rechtsklick (Icon):</strong></td>
            <td style="padding: 10px; border-bottom: 1px solid #444;">Einstellungsmenü öffnen</td>
        </tr>
    </table>
    <h2>5. Status-Anzeige</h2>
    <p>Das Infofenster am Minimap-Button zeigt dir jederzeit den aktuellen Status:</p>
    <ul class="feature-list">
        <li><span class="warning">Rot:</span> Filter ist in Dalaran aktiv.</li>
        <li><span class="highlight">Grün:</span> Chat ist offen (Timer läuft) oder du bist außerhalb Dalarans.</li>
        <li><span style="color: #f1c40f;">Gelb:</span> Addon ist global deaktiviert.</li>
    </ul>
</div>
<div class="footer">
    SayBlocker v2.3.1 | Erstellt für ein sauberes Dalaran-Erlebnis.
</div>
</body>
</html>
