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
        <h1 class="teaching-title">Research</h1>
        <p style="margin-bottom: 40px; color: #64748b;">Peer-Reviewed Publications</p>

        <div class="paper-item">
            <span class="paper-year">2025</span>
            <div class="paper-info">
                <h4 class="paper-title">Wood-Burning Restrictions and Air Pollution: The Case of Air Quality Warnings in Southern Chile</h4>
                <p class="paper-authors">with Cristian Concha</p>
                <p class="paper-journal">Accepted at <em>Environment and Development Economics</em></p>
                
                <div class="paper-links">
                    <a href="#" class="btn-research">View Paper</a>
                    <button class="btn-abstract" onclick="toggleAbstract('abs1')">Show Abstract</button>
                </div>

                <div id="abs1" class="abstract-content">
                    This paper examines the impact of wood-burning restrictions on air quality in Southern Chile. Using a regression discontinuity design, we evaluate how air quality warnings influence household behavior and local pollution levels... [Puedes completar aquí con el texto oficial].
                </div>
            </div>
        </div>

        <div class="paper-item">
            <span class="paper-year">2025</span>
            <div class="paper-info">
                <h4 class="paper-title">Air Pollution in the Global South: An Overview of its Sources and Impacts</h4>
                <p class="paper-authors">with Sandra Aguilar-Gomez</p>
                <p class="paper-journal"><em>Oxford Research Encyclopedia of Economics and Finance</em></p>
                
                <div class="paper-links">
                    <a href="#" class="btn-research">View Paper</a>
                    <button class="btn-abstract" onclick="toggleAbstract('abs2')">Show Abstract</button>
                </div>

                <div id="abs2" class="abstract-content">
                    This overview provides a comprehensive analysis of the unique challenges regarding air pollution in developing nations. We synthesize recent evidence on the sources of pollution and the disproportionate health and economic impacts... [Puedes completar aquí].
                </div>
            </div>
        </div>
    </section>

    <script>
        function toggleAbstract(id) {
            var content = document.getElementById(id);
            if (content.style.display === "block") {
                content.style.display = "none";
            } else {
                content.style.display = "block";
            }
        }
    </script>

</body>
</html>