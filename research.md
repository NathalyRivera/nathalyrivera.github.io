<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research - Nathaly M. Rivera</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+3:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="assets/style.css">
</head>
<body>

    <nav class="main-nav">
        <a href="index.html">HOME</a>
        <a href="research.html">RESEARCH</a>
        <a href="teaching.html">TEACHING</a>
        <a href="officehours.html">OFFICE HOURS</a> 
    </nav>

    <section class="research-container">
        <h2 class="section-heading">Peer-Reviewed Publications</h2>

        <div class="pub-item">
            <p class="pub-title">Wood-Burning Restrictions and Air Pollution: The Case of Air Quality Warnings in Southern Chile</p>
            <p class="pub-authors">with Cristian Concha</p>
            <p class="pub-journal">Accepted at <em>Environment and Development Economics</em>, 2025</p>
            <div class="pub-links">
                <a href="#">[Paper]</a>
                <a href="javascript:void(0)" onclick="toggleAbstract('abs1')">[Abstract]</a>
            </div>
            <div id="abs1" class="abstract-box">
                This paper examines the impact of wood-burning restrictions on air quality in Southern Chile. Using a regression discontinuity design, we evaluate how air quality warnings influence household behavior and local pollution levels...
            </div>
        </div>

        <div class="pub-item">
            <p class="pub-title">Air Pollution in the Global South: An Overview of its Sources and Impacts</p>
            <p class="pub-authors">with Sandra Aguilar-Gomez</p>
            <p class="pub-journal"><em>Oxford Research Encyclopedia of Economics and Finance</em>, 2025</p>
            <div class="pub-links">
                <a href="#">[Paper]</a>
                <a href="javascript:void(0)" onclick="toggleAbstract('abs2')">[Abstract]</a>
            </div>
            <div id="abs2" class="abstract-box">
                This overview provides a comprehensive analysis of the unique challenges regarding air pollution in developing nations. We synthesize recent evidence on the sources of pollution and the disproportionate health and economic impacts...
            </div>
        </div>
    </section>

    <script>
        function toggleAbstract(id) {
            var x = document.getElementById(id);
            if (x.style.display === "block") {
                x.style.display = "none";
            } else {
                x.style.display = "block";
            }
        }
    </script>
</body>
</html>