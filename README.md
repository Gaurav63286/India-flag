<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Indian Flag</title>
    <style>
        .flag {
            width: 400px; /* Adjust the width as needed */
            height: 200px; /* Adjust the height as needed */
            border: 1px solid #000;
        }

        .saffron {
            background-color: #e87810;
            height: 33.33%;
            width: 100%;
        }

        .white {
            background-color: #FFFFFF;
            height: 33.33%;
            width: 100%;
            position: relative;
        }

        .green {
            background-color: #138808;
            height: 33.33%;
            width: 100%;
        }

        .ashoka-chakra {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 50px; /* Diameter of the Ashoka Chakra */
            height: 50px;
            border-radius: 50%;
            border: 2.8px solid #000080;
            box-sizing: border-box;
        }

        .ashoka-chakra::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 44px; /* Inner diameter of the Chakra */
            height: 44px;
            border-radius: 50%;
            border: 1px solid #000080;
        }

        .ashoka-chakra::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 2px; /* Diameter of the spokes */
            height: 44px;
            background-color: #000080;
        }

        .ashoka-chakra .spoke {
            position: absolute;
            top: 25%;
            left: 50%;
            width: 2px;
            height: 22px;
            background-color: #000080;
            transform-origin: center bottom;
        }

        /* Create 24 spokes */
        .ashoka-chakra .spoke:nth-child(1)  { transform: translate(-50%, -50%) rotate(0deg); }
        .ashoka-chakra .spoke:nth-child(2)  { transform: translate(-50%, -50%) rotate(15deg); }
        .ashoka-chakra .spoke:nth-child(3)  { transform: translate(-50%, -50%) rotate(30deg); }
        .ashoka-chakra .spoke:nth-child(4)  { transform: translate(-50%, -50%) rotate(45deg); }
        .ashoka-chakra .spoke:nth-child(5)  { transform: translate(-50%, -50%) rotate(60deg); }
        .ashoka-chakra .spoke:nth-child(6)  { transform: translate(-50%, -50%) rotate(75deg); }
        .ashoka-chakra .spoke:nth-child(7)  { transform: translate(-50%, -50%) rotate(90deg); }
        .ashoka-chakra .spoke:nth-child(8)  { transform: translate(-50%, -50%) rotate(105deg); }
        .ashoka-chakra .spoke:nth-child(9)  { transform: translate(-50%, -50%) rotate(120deg); }
        .ashoka-chakra .spoke:nth-child(10) { transform: translate(-50%, -50%) rotate(135deg); }
        .ashoka-chakra .spoke:nth-child(11) { transform: translate(-50%, -50%) rotate(150deg); }
        .ashoka-chakra .spoke:nth-child(12) { transform: translate(-50%, -50%) rotate(165deg); }
        .ashoka-chakra .spoke:nth-child(13) { transform: translate(-50%, -50%) rotate(180deg); }
        .ashoka-chakra .spoke:nth-child(14) { transform: translate(-50%, -50%) rotate(195deg); }
        .ashoka-chakra .spoke:nth-child(15) { transform: translate(-50%, -50%) rotate(210deg); }
        .ashoka-chakra .spoke:nth-child(16) { transform: translate(-50%, -50%) rotate(225deg); }
        .ashoka-chakra .spoke:nth-child(17) { transform: translate(-50%, -50%) rotate(240deg); }
        .ashoka-chakra .spoke:nth-child(18) { transform: translate(-50%, -50%) rotate(255deg); }
        .ashoka-chakra .spoke:nth-child(19) { transform: translate(-50%, -50%) rotate(270deg); }
        .ashoka-chakra .spoke:nth-child(20) { transform: translate(-50%, -50%) rotate(285deg); }
        .ashoka-chakra .spoke:nth-child(21) { transform: translate(-50%, -50%) rotate(300deg); }
        .ashoka-chakra .spoke:nth-child(22) { transform: translate(-50%, -50%) rotate(315deg); }
        .ashoka-chakra .spoke:nth-child(23) { transform: translate(-50%, -50%) rotate(330deg); }
        .ashoka-chakra .spoke:nth-child(24) { transform: translate(-50%, -50%) rotate(345deg); }
    </style>
</head>
<body>
    <h1><big><i>HAPPY INDEPENDENCE DAY</i></big></h1>
    <div class="flag">
        <div class="saffron"></div>
        <div class="white">
            <div class="ashoka-chakra">
                <!-- Spokes of the Ashoka Chakra -->
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
                <div class="spoke"></div>
            </div>
        </div>
        <div class="green"></div>
    </div>
</body>
</html>
