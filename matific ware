<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matific Ware</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            min-height: 100vh;
            overflow: hidden;
        }

        h1 {
            font-size: 3em;
            margin: 20px 0;
            text-align: center;
        }

        .title-blue {
            color: #00aaff;
        }

        p {
            font-size: 1.2em;
            margin-bottom: 40px;
            line-height: 1.5em;
            color: #bbbbbb;
            text-align: center;
        }

        .btn-green {
            background-color: #32CD32;
            color: #fff;
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }

        .btn-green:hover {
            background-color: #28a428;
        }

        /* Informações em caixas */
        .info-container {
            display: flex;
            gap: 20px;
            max-width: 1000px;
            width: 100%;
            justify-content: space-around;
            margin-top: 40px;
        }

        .info-box {
            background-color: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
            width: 30%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        .info-box img {
            width: 50px;
            height: 50px;
            margin-bottom: 15px;
        }

        .info-box h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .info-box p {
            font-size: 1em;
            color: #bbbbbb;
        }

        /* Estilo da neve */
        .snowflake {
            position: absolute;
            top: -10px;
            background-color: #ffffff;
            border-radius: 50%;
            opacity: 0.8;
            pointer-events: none;
            animation: fall linear infinite;
        }

        @keyframes fall {
            to {
                transform: translateY(100vh);
            }
        }
    </style>
</head>
<body>

    <h1>Matific <span class="title-blue">Ware</span></h1>
    <p>Aprimore sua experiência no Matific com este script poderoso que permite novas funcionalidades e otimizações. Fácil de usar e altamente eficiente.</p>
    <a href="link_do_script" class="btn-green">Baixar Script</a>

    <!-- Seção das Caixas de Informações -->
    <div class="info-container">
        <div class="info-box">
            <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="JavaScript Logo">
            <h3>Made using pure Javascript</h3>
            <p>Experience optimal performance and full control with pure JavaScript, no unnecessary dependencies, just speed and precision.</p>
        </div>
        <div class="info-box">
            <img src="https://cdn-icons-png.flaticon.com/512/545/545673.png" alt="Customization Icon">
            <h3>Customizable to Your Liking</h3>
            <p>Khanware allows for full customization of user profiles, including the option to upload a custom profile picture and select a personalized username or nickname.</p>
        </div>
        <div class="info-box">
            <img src="https://cdn-icons-png.flaticon.com/512/4067/4067434.png" alt="Update Icon">
            <h3>Always updated</h3>
            <p>Cheat Khanware is consistently updated to stay ahead, always exploring and utilizing the latest vulnerabilities and exploits discovered.</p>
        </div>
    </div>

    <!-- Script da Neve -->
    <script>
        function createSnowflake() {
            const snowflake = document.createElement('div');
            snowflake.classList.add('snowflake');

            const size = Math.random() * 10 + 5 + 'px';
            const position = Math.random() * 100 + 'vw';
            const duration = Math.random() * 5 + 3 + 's';

            snowflake.style.width = size;
            snowflake.style.height = size;
            snowflake.style.left = position;
            snowflake.style.animationDuration = duration;

            document.body.appendChild(snowflake);

            setTimeout(() => {
                snowflake.remove();
            }, parseInt(duration) * 1000);
        }

        setInterval(createSnowflake, 200);
    </script>

</body>
</html>
