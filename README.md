<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Menú Desplegable</title>
    <style>
        .dropdown { position: relative; display: inline-block; }
        .dropdown-content { display: none; position: absolute; background-color: #f9f9f9; min-width: 160px; }
        .dropdown:hover .dropdown-content { display: block; }
    </style>
</head>
<body>

<div class="dropdown">
    <button onclick="toggleDropdown()">Menú</button>
    <div id="myDropdown" class="dropdown-content">
        <a href="#">Opción 1</a>
        <a href="#">Opción 2</a>
    </div>
</div>

<script>
    function toggleDropdown() {
        document.getElementById("myDropdown").classList.toggle("show");
    }
</script>

</body>
</html>
