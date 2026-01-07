# iledcanarias.com
Iluminación Led Con tecnología Digital 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ILEDCANARIAS - Tecnología LED Digital</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        html, body { height: 100%; width: 100%; overflow: hidden; background: #000; }
        .contenedor { display: flex; flex-direction: column; height: 100vh; }
        .video-superior { flex: 0.4; min-height: 0; }
        .video-inferior { flex: 0.6; min-height: 0; }
        iframe { width: 100%; height: 100%; border: none; display: block; }
    </style>
</head>
<body>
    <div class="contenedor">
        
        <!-- VIDEO SUPERIOR: LOGOTIPO (40%) -->
        <div class="video-superior">
            <iframe 
                src="https://www.youtube.com/embed/PoMZjT_Nywg?autoplay=1&mute=1&loop=1&controls=0&modestbranding=1&rel=0&playlist=PoMZjT_Nywg" 
                title="ILEDCANARIAS - Logotipo"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen>
            </iframe>
        </div>
        
        <!-- VIDEO INFERIOR: CORPORATIVO (60%) -->
        <div class="video-inferior">
            <iframe 
                src="https://www.youtube.com/embed/KJGOr5wnc_A?autoplay=1&mute=1&loop=1&controls=0&modestbranding=1&rel=0&playlist=KJGOr5wnc_A" 
                title="ILEDCANARIAS - Video Corporativo"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen>
            </iframe>
        </div>
        
    </div>
</body>
</html>
