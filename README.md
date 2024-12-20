<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHARMACIE DE GARDE</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* تثبيت زر الرجوع مع الشريط */
        .back-bar {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            height: 60px;
            background-color: #f8f9fa;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 0 20px;
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.2);
            z-index: 10;
        }

        .back-button {
            display: flex;
            align-items: center;
            font-size: 20px;
            color: #007bff;
            cursor: pointer;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .back-button:hover {
            color: #0056b3;
        }

        .back-button i {
            margin-right: 8px;
        }

        /* باقي تنسيقات الصفحة */
        body {
            background-color: #e9ecef;
            margin: 0;
            padding-top: 80px; /* لتجنب تغطية المحتوى بالشريط */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #343a40;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        .title {
            font-size: 26px;
            color: #006400; /* أخضر غامق */
            font-weight: bold;
            text-align: center;
            margin-bottom: 5px;
        }

        .title-underline {
            width: 50px;
            height: 4px;
            background-color: #006400; /* أخضر غامق */
            border-radius: 2px;
            margin-bottom: 20px;
        }

        .box {
            background-color: #ffffff;
            width: 90%;
            max-width: 400px;
            margin: 15px 0;
            padding: 20px;
            box-shadow: 0px 6px 18px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
            position: relative;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .box:hover {
            transform: translateY(-5px);
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.2);
        }

        .box-title {
            font-size: 20px;
            color: #006400; /* أخضر غامق */
            font-weight: bold;
            margin-bottom: 8px;
        }

        .box-title-underline {
            width: 30px;
            height: 2px;
            background-color: #006400; /* أخضر غامق */
            margin: 0 auto 10px auto;
            border-radius: 2px;
        }

        .info {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            color: #495057;
            font-size: 15px;
        }

        .info-item {
            display: flex;
            align-items: center;
            margin: 8px 0;
        }

        .info-item i {
            color: #007bff; /* أزرق */
            font-size: 18px;
            margin-right: 10px;
        }

        .info-item a {
            color: #007bff;
            text-decoration: none;
        }

        .info-item a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- شريط زر الرجوع الثابت -->
    <div class="back-bar">
        <a href="Grand_guelize.html" class="back-button">
            <i class="fas fa-arrow-left"></i> الرجوع
        </a>
    </div>

    <div class="container">
        <div class="title">PHARMACIE DE GARDE A GUELIZE</div>
        <div class="title-underline"></div>

        <!-- الخانات الخمس -->
        <div class="box">
            <div class="box-title">PHAR, ALKABIR</div>
            <div class="box-title-underline"></div>
            <div class="info">
                <div class="info-item"><i class="fas fa-phone-alt"></i> +2222222222</div>
                <div class="info-item"><i class="fas fa-map-marker-alt"></i> <a href="Grand_guelize.html">localisation</a></div>
                <div class="info-item"><i class="fas fa-flag"></i> Qartier : guelize</div>
            </div>
        </div>

        <div class="box">
            <div class="box-title">PHAR, ALFARABI</div>
            <div class="box-title-underline"></div>
            <div class="info">
                <div class="info-item"><i class="fas fa-phone-alt"></i> +2222222223</div>
                <div class="info-item"><i class="fas fa-map-marker-alt"></i> <a href="Grand_guelize.html">localisation</a></div>
                <div class="info-item"><i class="fas fa-flag"></i> Qartier : gueliz</div>
            </div>
        </div>

        <div class="box">
            <div class="box-title">PHAR, ELHANA</div>
            <div class="box-title-underline"></div>
            <div class="info">
                <div class="info-item"><i class="fas fa-phone-alt"></i> +2222222224</div>
                <div class="info-item"><i class="fas fa-map-marker-alt"></i> <a href="Grand_guelize.html">localisation</a></div>
                <div class="info-item"><i class="fas fa-flag"></i> Qartier : gueliz</div>
            </div>
        </div>

        <div class="box">
            <div class="box-title">PHAR, ALWAFA</div>
            <div class="box-title-underline"></div>
            <div class="info">
                <div class="info-item"><i class="fas fa-phone-alt"></i> +2222222225</div>
                <div class="info-item"><i class="fas fa-map-marker-alt"></i> <a href="Grand_guelize.html">localisation</a></div>
                <div class="info-item"><i class="fas fa-flag"></i> Qartier : gueliz hda albahria rn face snack anoir et 200m à la gare de train</div>
            </div>
        </div>

        <div class="box">
            <div class="box-title">PHAR, ANNOUR</div>
            <div class="box-title-underline"></div>
            <div class="info">
                <div class="info-item"><i class="fas fa-phone-alt"></i> +2222222226</div>
                <div class="info-item"><i class="fas fa-map-marker-alt"></i> <a href="Grand_guelize.html">localisation</a></div>
                <div class="info-item"><i class="fas fa-flag"></i> Qartier : gueliz</div>
            </div>
        </div>

    </div>

</body>
</html>
