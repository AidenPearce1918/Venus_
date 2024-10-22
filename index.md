<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Space-Themed AR</title>
    <!-- Import A-Frame -->
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <!-- Import AR.js -->
    <script src="https://cdn.rawgit.com/jeromeetienne/ar.js/1.7.2/aframe/build/aframe-ar.min.js"></script>
</head>
<body style="margin: 0; overflow: hidden;">
    <!-- AR scene -->
    <a-scene embedded arjs>
        <!-- AR content will go here -->
    </a-scene>
    <a-marker preset="Hiro_marker_ARjs">
        <a-entity gltf-model="models/solar_system_animation.glb"></a-entity>
    </a-marker>
</body>
</html>
