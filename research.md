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
        <h3 class="section-title">PEER-REVIEWED PUBLICATIONS</h3>

        <ol class="publications-list">
            <li>
                <div class="paper-header">
                    <span class="paper-title">Wood-Burning Restrictions and Air Pollution: The Case of Air Quality Warnings in Southern Chile</span>
                    <span class="paper-authors">(with Cristian Concha)</span>
                    <div class="inline-links">
                        <a href="#" class="link-view">[View]</a>
                        <button class="btn-abstract-link" onclick="toggleAbstract('abs1')">[Abstract]</button>
                    </div>
                </div>
                <div class="paper-details">
                    Accepted at <em>Environment and Development Economics</em>, 2025.
                </div>
                <div id="abs1" class="abstract-content">
                    This paper examines the impact of wood-burning restrictions on air quality in Southern Chile. Using a regression discontinuity design, we evaluate how air quality warnings influence household behavior and local pollution levels...
                </div>
            </li>

            <li>
                <div class="paper-header">
                    <span class="paper-title">Air Pollution in the Global South: An Overview of its Sources and Impacts</span>
                    <span class="paper-authors">(with Sandra Aguilar-Gomez)</span>
                    <div class="inline-links">
                        <a href="#" class="link-view">[View]</a>
                        <button class="btn-abstract-link" onclick="toggleAbstract('abs2')">[Abstract]</button>
                    </div>
                </div>
                <div class="paper-details">
                    <em>Oxford Research Encyclopedia of Economics and Finance</em>, 2025.
                </div>
                <div id="abs2" class="abstract-content">
                    This overview provides a comprehensive analysis of the unique challenges regarding air pollution in developing nations. We synthesize recent evidence on the sources of pollution and the disproportionate health impacts...
                </div>
            </li>
        </ol>
    </section>

    <script>
        function toggleAbstract(id) {
            var content = document.getElementById(id);
            content.style.display = (content.style.display === "block") ? "none" : "block";
        }
    </script>
</body>
</html>