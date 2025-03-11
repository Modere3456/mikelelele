<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suomen Sotahistoria</title>	
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        header {
            background: #0077cc;
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        section:hover {
            transform: scale(1.02);
        }
        h2 {
            color: #0077cc;
            font-family: serif;
            border-bottom: 2px solid #0077cc;
            padding-bottom: 5px;
            cursor: pointer;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            font-family: cursive;
            color: #555;
        }
        p {
            font-size: 18px;
            margin: 10px 0;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
            transition: transform 0.3s;
        }
        img:hover {
            transform: scale(1.05);
        }
        .additional-info {
            display: none;
            margin-top: 10px;
            font-size: 16px;
            color: #333;
        }
    </style>
    <script>
        function toggleInfo(id) {
            const info = document.getElementById(id);
            if (info.style.display === "none" || info.style.display === "") {
                info.style.display = "block";
            } else {
                info.style.display = "none";
            }
        }
    </script>
</head>
<body>

<header>
    <h1>Suomen Sotahistoria</h1>
</header>

<section>
    <h2 onclick="toggleInfo('sisallissota-info')">Suomen Sisällissota (1918)</h2>
    <p>Sisällissota on sisäinen konflikti, jossa maa jakautuu eri osiin, jotka taistelevat vallasta. Yksi tunnetuimmista esimerkeistä on Suomen sisällissota (1918), jossa punaisten (sosialistinen työväenluokka) ja valkoisten (porvarillinen osapuoli) välillä käytiin taistelu vallasta Suomen itsenäistymisen jälkeen.</p>
    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.finna.fi%2FCover%2FShow%3Fid%3Dsatakunnanmuseo.368CE158-37D8-49A7-B05B-7D282D525CC1%26index%3D0%26size%3Dlarge%26source%3DSolr&f=1&nofb=1&ipt=4832f0f437cd9556213e4b7890107a385ed847072eaa6ec64766850e096b6758&ipo=images" alt="Sisällissota" width="200" height="300">
    <div id="sisallissota-info" class="additional-info">
        <p>Sota oli verinen ja jätti syvät arvet yhteiskuntaan. Sisällissodat voivat johtaa suuriin tuhoihin ja pitkäaikaisiin seurauksiin, ja niitä leimaa usein ideologinen ja poliittinen jakautuneisuus.</p>
    </div>
</section>

<section>
    <h2 onclick="toggleInfo('talvisota-info')">Talvisota (1939-1940)</h2>
    <p>Talvisota käytiin Suomen ja Neuvostoliiton välillä 30.11.1939–13.3.1940. Neuvostoliitto hyökkäsi Suomeen ilman sodanjulistusta, ja sen tavoitteena oli saada hallintaansa alueita, erityisesti Karjala.</p>
    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.petterimikkonen.fi%2Fcontent%2Fimages%2F2021%2F12%2Ftalvisota-lk.jpg&f=1&nofb=1&ipt=16916c96b300174fe758885ac8d17363e82b1b139cc8ef65fa7163579e5d6453&ipo=images" alt="Talvisota" width="200" height="300">
    <div id="talvisota-info" class="additional-info">
        <p>Suomen puolustus oli vahva, vaikka Neuvostoliiton armeija oli moninkertainen. Sota oli erittäin raskas, mutta Suomi onnistui puolustautumaan yli kahden kuukauden ajan. Vaikka Suomi ei voittanut sotaa, se sai säilytettyä itsenäisyytensä.</p>
    </div>
</section>

<section>
    <h2 onclick="toggleInfo('jatkosota-info')">Jatkosota (1941-1944)</h2>
    <p>Jatkosota käytiin Suomen ja Neuvostoliiton välillä 25. kesäkuuta 1941–19. syyskuuta 1944. Suomi liittoutui Saksan kanssa, mutta ei ollut virallisesti liittolainen. Sodan alussa Suomi valtasi talvisodassa menetetyt alueet ja eteni Syvärille ja Leningradin linjojen tuntumaan, mutta asemasotavaihe kesti yli kaksi vuotta. Kesällä 1944 Neuvostoliitto hyökkäsi ja mursi Suomen puolustuksen, mikä johti tulitaukoon. Välirauha 1944 vaati Saksan joukkojen poistamista Suomesta, mikä johti Lapin sotaan. Moskovan rauhassa Suomi menetti lisää alueita mutta säilytti itsenäisyytensä.</p>
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.sotahistoria.fi%2Fwp-content%2Fuploads%2F2022%2F09%2Fpoljarnik.jpg&f=1&nofb=1&ipt=8f3f92cf273ee93dc042ffcc2aebbc9b12e4e914fcfe50c61001947f3b8dd605&ipo=images" width="200" height="300">
</section>

