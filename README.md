# Birthday-wish
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 19th Birthday Poojaa! 🎉</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 99%, #fecfef 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
            max-width: 800px;
            width: 100%;
            padding: 30px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .header h1 {
            color: #e91e63;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .header p {
            color: #666;
            font-size: 1.1rem;
            margin-bottom: 25px;
        }

        /* Photo Gallery Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 15px;
            margin-bottom: 30px;
        }

        .gallery img {
            width: 100%;
            height: 120px;
            object-fit: cover;
            border-radius: 12px;
            border: 3px solid #ff80ab;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.08) rotate(2deg);
            box-shadow: 0 8px 20px rgba(233, 30, 99, 0.3);
        }

        /* Birthday Message Box */
        .message-box {
            background: #fff5f8;
            border-left: 5px solid #e91e63;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 25px;
            box-shadow: inset 0 2px 4px rgba(0,0,0,0.02);
        }

        .message-box p {
            color: #444;
            font-size: 1.15rem;
            line-height: 1.6;
            font-style: italic;
        }

        .sender {
            margin-top: 15px;
            font-weight: bold;
            color: #d81b60;
            font-size: 1.2rem;
            text-align: right;
            font-style: normal;
        }

        /* Footer Accent */
        .footer-heart {
            font-size: 1.5rem;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .header h1 {
                font-size: 1.8rem;
            }
            .gallery {
                grid-template-columns: repeat(3, 1fr);
            }
            .gallery img {
                height: 90px;
            }
        }
    </style>
</head>
<body>

    <div
