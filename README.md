!-- an html,css code where i designed a simple card --!
[card.html](https://github.com/user-attachments/files/23470885/card.html)
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .outerbox {
            height: 600px;
            width: 400px;
            border: 10px solid black;
            align-items: center;
            border-radius: 10px;
            background-color:antiquewhite;
        }

        .inner-box {
            height: 220px;
            width: 350px;
            border: 3px solid black;
            margin: 20px;
            border-radius: 15px;
        }

        .img {
            height: 220px;
            width: 350px;
            border-radius: 10px;

        }

        .buttons {
            display: flex;
            gap: 1px;
        }

        .categories,
        .about {
            height: 25px;
            width: 100px;
            border: 2px solid black;
            margin-left: 20px;
            border-radius: 10px;
            text-align: center;
            background: black;
            color: white;
            text-transform: uppercase;
            font-size: 15px;
            vertical-align: top;
        }

        .p {
            font-size: 20px;
            margin-left: 20px;
            margin-right: 20px;
            margin-top: 10px;
        }

        .readmore {
            height: 20px;
            width: 100px;
            border: 2px solid rgba(0, 0, 0, 0.274);
            color: white;
            border-radius: 10px;
            background-color: black;
            margin-left: 130px;
            margin-right: 50px;
            text-align: center;
        }

        .c {
            font-size: 25px;
            margin-left: 20px;
            text-decoration:underline;
        }
    </style>
</head>

<body>
    <div class="outerbox">
        <div class="inner-box">
            <img src="nat-geo.jpg" class="img"></img>
        </div>

        <div class="buttons">
            <div class="about">about</div>
            <div class="categories">categories</div>
        </div>
        <p class="c"><b>NAT-GEO</b></p>
        <p class="p">The National Geographic Society has been inspiring people to care about the planet since 1888. It
            is one of
            the largest nonprofit scientific and educational institutions in the world. Its interests include geography,
            archaeology and natural science, and the promotion of environmental and historical conservation.</p>
        <div class="readmore">READMORE</div>
    </div>
</body>

</html>
