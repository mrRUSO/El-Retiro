<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Retiro - Antioquia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-image: url('https://www.laprensaoriente.info/wp-content/uploads/2023/01/Imagen-de-WhatsApp-2023-01-05-a-las-10.33.16.jpg'); /* Imagen de fondo de la iglesia */
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
        }
        header {
            background-color: rgba(46, 139, 87, 0.9);
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(34, 49, 63, 0.9);
            padding: 10px 0;
        }
        nav button {
            background-color: #556B2F;
            color: white;
            border: none;
            padding: 10px 15px;
            margin: 0 5px;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
        }
        nav button:hover {
            background-color: #6B8E23;
        }
        section {
            display: none;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            margin: 10px auto;
            width: 90%;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        section.active {
            display: block;
        }
        h2 {
            color: #2E8B57;
            margin-top: 0;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin: 10px 0;
        }
    </style>
    <script>
        function showSection(sectionId) {
            document.querySelectorAll("section").forEach(section => {
                section.classList.remove("active");
            });
            document.getElementById(sectionId).classList.add("active");
        }
    </script>
</head>
<body>

    <header>
        <h1>Bienvenidos a El Retiro, Antioquia</h1>
        <p>Explora la historia, cultura, y naturaleza de este encantador municipio antioqueño.</p>
    </header>

    <nav>
        <button onclick="showSection('historia')">Historia</button>
        <button onclick="showSection('comida')">Comida</button>
        <button onclick="showSection('gentilicio')">Gentilicio</button>
        <button onclick="showSection('rios')">Ríos y Quebradas</button>
        <button onclick="showSection('puntos')">Puntos Turísticos</button>
        <button onclick="showSection('personajes')">Personajes Importantes</button>
    </nav>

    <!-- Sección Historia -->
    <section id="historia">
        <h2>Historia</h2>
        <img src="https://propiedades.com.co/wp-content/uploads/2021/10/1.-Capilla-de-San-Jos%C3%A9-2.jpg" alt="Arquitectura colonial en El Retiro">
        <p>El Retiro, fundado en 1790, tiene una rica historia que incluye su papel en la independencia de Antioquia y su desarrollo como centro de comercio de madera y muebles. La historia de El Retiro está marcada por la ebanistería, una actividad que lo posicionó como referente en la industria de muebles de alta calidad. En el siglo XIX, el municipio se consolidó como punto estratégico para comerciantes y arrieros que cruzaban la región.</p>
        <p>Con el paso del tiempo, el desarrollo agrícola y la ganadería se integraron en su economía. Actualmente, El Retiro conserva su encanto colonial, con casas de fachadas coloridas y calles empedradas, atrayendo a visitantes interesados en la historia y la cultura de Antioquia.</p>
    </section>

    <!-- Sección Comida -->
    <section id="comida">
        <h2>Comida</h2>
        <img src="https://mojo.generalmills.com/api/public/content/geavWbc7i0eptb2tGb-CyA_gmi_hi_res_jpeg.jpeg?v=5f30c0a4&t=16e3ce250f244648bef28c5949fb99ff" alt="Comida típica de El Retiro">
        <p>La gastronomía de El Retiro es una fusión de sabores tradicionales antioqueños. La bandeja paisa, el sancocho antioqueño, y el asado al carbón son platos infaltables. Aquí, los productos frescos de las montañas y las recetas locales reflejan la cultura retireña.</p>
        <p>Entre sus delicias, destacan las arepas de chócolo, buñuelos, pandebonos, y empanadas, todos acompañados de café de fincas locales. La calidad del café en El Retiro es reconocida, y el municipio se ha convertido en un destino popular para los amantes del café, quienes disfrutan de diversas preparaciones en las cafeterías locales.</p>
    </section>

    <!-- Sección Gentilicio -->
    <section id="gentilicio">
        <h2>Gentilicio</h2>
        <img src="https://colombiamaspositiva.com/wp-content/uploads/2017/09/GOR9392-1.jpg" alt="Gente de El Retiro">
        <p>Los habitantes de El Retiro se conocen como <strong>guarceños</strong>. Son personas trabajadoras, hospitalarias y dedicadas a preservar sus tradiciones culturales y naturales. Las fiestas y eventos locales reflejan su espíritu comunitario y su orgullo por las raíces antioqueñas. Además, los retireños destacan por su habilidad en la ebanistería y la agricultura, herencia de generaciones anteriores que sigue vigente.</p>
    </section>

    <!-- Sección Ríos y Quebradas -->
    <section id="rios">
        <h2>Ríos y Quebradas</h2>
        <img src="data:image/jpeg;base64,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" alt="Río Pantanillo">
        <p>El Retiro cuenta con importantes recursos hídricos, entre ellos el <strong>río Pantanillo</strong> y la <strong>quebrada La Fe</strong>. Estos cuerpos de agua son esenciales para la biodiversidad de la región y también brindan espacios recreativos para locales y turistas.</p>
        <p>La quebrada La Fe, que abastece de agua potable a la región, es popular para el senderismo y los picnics. Las autoridades locales han implementado proyectos para preservar estos recursos naturales y promover el ecoturismo en la zona, fomentando el respeto y cuidado del medio ambiente.</p>
    </section>

    <!-- Sección Puntos Turísticos -->
    <section id="puntos">
        <h2>Puntos Turísticos</h2>
        <img src="https://turismo.encolombia.com/wp-content/uploads/2024/07/Represa-La-Fe-768x405.jpg" alt="Embalse La Fe">
        <ul>
            <li><strong>Embalse La Fe:</strong> Espacio natural perfecto para actividades acuáticas y observación de aves, rodeado de montañas.</li>
            <li><strong>Parque Principal:</strong> En el centro de El Retiro, rodeado de arquitectura colonial, es ideal para experimentar la vida local.</li>
            <li><strong>Casa Museo La Madera:</strong> Un museo que relata la historia de la ebanistería en El Retiro, con muestras de muebles tradicionales.</li>
            <li><strong>Sendero Ecológico La Ceja:</strong> Ruta de senderismo para disfrutar de vistas panorámicas y la rica biodiversidad de la región.</li>
        </ul>
    </section>

    <!-- Sección Personajes Importantes -->
    <section id="personajes">
        <h2>Personajes Importantes</h2>
        <img src="https://radionacional-v3.s3.amazonaws.com/s3fs-public/styles/portadas_relaciona_4_3/public/node/article/field_image/JAVIERA.jpeg?h=23a2addc&itok=NnU8_CUy" alt="Personajes importantes de El Retiro">
        <p>El Retiro ha sido hogar de figuras destacadas que contribuyeron a su desarrollo. <strong>José María Ceballos</strong> es recordado por su labor en la promoción de la cultura y el comercio. <strong>Manuel Uribe Ángel</strong>, empresario en la industria maderera, ayudó a posicionar a El Retiro como un referente en la fabricación de muebles de alta calidad.</p>
        <p>Estos personajes son parte de la historia viva de El Retiro, y sus legados continúan influyendo en la cultura y economía del municipio.</p>
    </section>

</body>
</html>
