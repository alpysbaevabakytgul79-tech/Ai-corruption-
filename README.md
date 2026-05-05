<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ақтау Тендер Бақылау</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f5f5f5;
}

/* HEADER */
header {
    background: linear-gradient(90deg, #1E88E5, #1565C0);
    color: white;
    padding: 60px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 36px;
}

header p {
    font-size: 18px;
}

/* BUTTON */
.btn {
    background: white;
    color: #1E88E5;
    padding: 10px 20px;
    border: none;
    margin-top: 15px;
    cursor: pointer;
    border-radius: 8px;
    font-weight: bold;
}

/* SECTION */
section {
    padding: 30px;
}

/* CARDS */
.cards {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 10px;
    flex: 1;
    min-width: 200px;
}

/* TABLE */
table {
    width: 100%;
    border-collapse: collapse;
    background: white;
}

th, td {
    padding: 12px;
    border: 1px solid #ddd;
    text-align: center;
}

th {
    background: #1E88E5;
    color: white;
}

/* STATUS */
.green { color: green; font-weight: bold; }
.red { color: red; font-weight: bold; }

/* FORM */
input, textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<!-- HERO -->
<header>
    <h1>Ақтау Тендер Бақылау</h1>
    <p>Ашықтық – әділдіктің негізі</p>
    <button class="btn">Тендерлерді қарау</button>
</header>

<!-- INFO -->
<section>
    <h2>Жоба туралы</h2>
    <p>
        Бұл платформа Ақтау қаласындағы мемлекеттік сатып алу жүйесін бақылауға арналған.
        Жасанды интеллект арқылы күмәнді тендерлер анықталады.
    </p>
</section>

<!-- CARDS -->
<section>
    <h2>Артықшылықтар</h2>
    <div class="cards">
        <div class="card">✔ Ашықтық</div>
        <div class="card">✔ Қоғамдық бақылау</div>
        <div class="card">✔ ЖИ талдау</div>
    </div>
</section>

<!-- TABLE -->
<section>
    <h2>Тендерлер тізімі</h2>

    <table>
        <tr>
            <th>№</th>
            <th>Тендер атауы</th>
            <th>Қатысушылар</th>
            <th>Жеңімпаз</th>
            <th>Баға</th>
            <th>Статус</th>
        </tr>

        <tr>
            <td>1</td>
            <td>Мектеп жиһазы</td>
            <td>3</td>
            <td>Company A</td>
            <td>12 500 000 ₸</td>
            <td class="green">Ашық</td>
        </tr>

        <tr>
            <td>2</td>
            <td>Жол жөндеу</td>
            <td>5</td>
            <td>Company B</td>
            <td>45 000 000 ₸</td>
            <td class="red">Күмәнді</td>
        </tr>

        <tr>
            <td>3</td>
            <td>IT жүйе енгізу</td>
            <td>2</td>
            <td>Company C</td>
            <td>18 200 000 ₸</td>
            <td class="green">Ашық</td>
        </tr>
    </table>
</section>

<!-- ANALYTICS -->
<section>
    <h2>ЖИ талдау</h2>
    <p>
        Кейбір тендерлерде бәсекелестік төмен және бір компанияның жиі жеңуі байқалады.
    </p>
</section>

<!-- FORM -->
<section>
    <h2>Шағым қалдыру</h2>

    <input type="text" placeholder="Аты-жөні">
    <input type="text" placeholder="Тендер атауы">
    <textarea placeholder="Пікіріңіз"></textarea>
    <button class="btn" style="background:#1E88E5;color:white;">Жіберу</button>
</section>

<!-- FOOTER -->
<footer>
    © 2026 Ақтау Тендер Бақылау | Жоба
</footer>

</body>
</html>