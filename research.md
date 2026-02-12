<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research - Nathaly M. Rivera</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+3:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
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
            <p class="pub-authors">with <a href="https://sites.google.com/view/cristianconcha" target="_blank" class="coauthor-link">Cristian Concha</a></p>
            <p class="pub-journal">Accepted at <em>Environment and Development Economics</em>, 2025</p>
            
            <div class="pub-links">
                <a href="#">[Paper]</a>
                <a href="javascript:void(0)" onclick="toggleAbstract('abs1')">[Abstract]</a>
                <span class="media-links">— Featured in: <a href="#">[Universidad de Chile]</a> <a href="#">[La Tribuna]</a></span>
            </div>
            
            <div id="abs1" class="abstract-box">
                This paper examines the impact of wood-burning restrictions on air quality in Southern Chile. Using a regression discontinuity design, we evaluate how air quality warnings influence household behavior and local pollution levels...
            </div>
        </div>

        <div class="pub-item">
            <p class="pub-title">Air Pollution in the Global South: An Overview of its Sources and Impacts</p>
            <p class="pub-authors">with <a href="https://www.sandraagulargomez.com/" target="_blank" class="coauthor-link">Sandra Aguilar-Gomez</a></p>
            <p class="pub-journal"><em>Oxford Research Encyclopedia of Economics and Finance</em>, 2025</p>
            
            <div class="pub-links">
                <a href="#">[Paper]</a>
                <a href="javascript:void(0)" onclick="toggleAbstract('abs2')">[Abstract]</a>
            </div>
            
            <div id="abs2" class="abstract-box">
                This overview provides a comprehensive analysis of the unique challenges regarding air pollution in developing nations. We synthesize recent evidence on the sources of pollution and the disproportionate health and economic impacts...
            </div>
        </div>

        <div class="pub-item">
            <p class="pub-title">The Health Benefits of Solar Power Generation: Evidence from Chile</p>
            <p class="pub-authors">with <a href="#" class="coauthor-link">Beia Spiller</a> and <a href="#" class="coauthor-link">J. Cristobal Ruiz-Tagle</a></p>
            <p class="pub-journal"><em>Journal of Environmental Economics and Management</em>, 2024</p>
            
            <div class="pub-links">
                <a href="#">[Paper]</a>
                <a href="javascript:void(0)" onclick="toggleAbstract('abs3')">[Abstract]</a>
                <span class="media-links">— Featured in: <a href="#">[EDF Blog Post]</a> <a href="#">[Foco Económico]</a> <a href="#">[La Tercera]</a></span>
            </div>
            
            <div id="abs3" class="abstract-box">
                We investigate the impact of large-scale solar entry into the Chilean electricity market on local air pollution and health outcomes...
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