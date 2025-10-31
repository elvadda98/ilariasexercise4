<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Tempi Condizionali Interattivi</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 40px;
    background-color: #f7f9fb;
    color: #333;
  }
  h1, h2 {
    color: #2c3e50;
  }
  .example {
    background: #ecf0f1;
    padding: 10px;
    border-radius: 8px;
    margin: 10px 0;
  }
  button {
    background-color: #3498db;
    color: white;
    border: none;
    border-radius: 6px;
    padding: 8px 12px;
    cursor: pointer;
  }
  button:hover {
    background-color: #2980b9;
  }
  .quiz {
    margin-top: 30px;
    background: #fff;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  .feedback {
    margin-top: 10px;
    font-weight: bold;
  }
</style>
</head>
<body>
<h1>Tempi Condizionali in Inglese</h1>
<p>Questa pagina spiega la differenza tra <strong>“would be”</strong> e <strong>“would have been”</strong> in inglese, con esempi e un piccolo quiz interattivo.</p>

<h2>1️⃣ The full fee <em>would be</em></h2>
<p><strong>Tempo / Struttura:</strong> Condizionale presente (Present Conditional)</p>
<p><strong>Forma:</strong> <code>would + verbo base</code></p>
<p><strong>Uso:</strong> Si usa per parlare di qualcosa che <em>potrebbe accadere nel presente o nel futuro</em> se una condizione fosse vera.</p>
<div class="example">
  <strong>Esempio:</strong> “The full fee <em>would be</em> €200 if you didn’t have a discount.”<br>
  → Significato: ipotizziamo una situazione attuale o futura non reale.
</div>

<h2>2️⃣ The full fee <em>would have been</em></h2>
<p><strong>Tempo / Struttura:</strong> Condizionale perfetto (Perfect Conditional o Past Conditional)</p>
<p><strong>Forma:</strong> <code>would have + participio passato</code></p>
<p><strong>Uso:</strong> Si usa per parlare di qualcosa che <em>sarebbe potuto accadere nel passato</em>, ma non è successo.</p>
<div class="example">
  <strong>Esempio:</strong> “The full fee <em>would have been</em> €200 if you hadn’t had a discount.”<br>
  → Significato: situazione passata ipotetica, diversa da quella reale.
</div>

<h2>3️⃣ Riassunto</h2>
<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse;">
  <tr style="background:#ecf0f1;">
    <th>Frase</th>
    <th>Nome del tempo</th>
    <th>Struttura</th>
    <th>Riferimento temporale</th>
    <th>Significato</th>
  </tr>
  <tr>
    <td><em>would be</em></td>
    <td>Condizionale presente</td>
    <td>would + verbo base</td>
    <td>Presente / Futuro</td>
    <td>Situazione ipotetica nel presente o nel futuro</td>
  </tr>
  <tr>
    <td><em>would have been</em></td>
    <td>Condizionale perfetto</td>
    <td>would have + participio passato</td>
    <td>Passato</td>
    <td>Situazione ipotetica nel passato</td>
  </tr>
</table>

<div class="quiz">
  <h2>Quiz Interattivo</h2>
  <p>Scegli la forma corretta per completare la frase:</p>
  <p><em>If you hadn’t missed the train, you ______ on time.</em></p>
  <button onclick="checkAnswer('would be')">would be</button>
  <button onclick="checkAnswer('would have been')">would have been</button>
  <div id="feedback" class="feedback"></div>
</div>

<script>
function checkAnswer(choice) {
  const feedback = document.getElementById('feedback');
  if (choice === 'would have been') {
    feedback.textContent = '✅ Corretto! Usiamo “would have been” perché parliamo di una situazione passata ipotetica.';
    feedback.style.color = 'green';
  } else {
    feedback.textContent = '❌ Non esatto. “Would be” si usa per il presente o futuro, non per il passato.';
    feedback.style.color = 'red';
  }
}
</script>
</body>
</html>
