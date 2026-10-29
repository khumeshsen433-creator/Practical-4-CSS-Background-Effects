# Practical-4-CSS-Background-Effects
<!DOCTYPE html>
<html>
<head>
    <title>Background Effects</title>

    <style>
        body {
            background-color: lightblue;
            font-family: Arial, sans-serif;
        }

        h1 {
            text-align: center;
        }

        .box {
            height: 300px;
            margin: 20px;
            padding: 20px;
            color: white;

            background-color: navy;
            background-image: url(
                "https://placehold.co/600x300/224466/ffffff"
            );
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
        }
    </style>
</head>
<body>

    <h1>CSS Background Demo</h1>

    <div class="box">
        <h2>Welcome to Our College</h2>
        <p>This section demonstrates background effects.</p>
    </div>

</body>
</html>