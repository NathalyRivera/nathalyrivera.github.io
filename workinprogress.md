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
        <a href="research.html">PUBLICATIONS</a>
        <a href="workinprogress.html">WORK IN PROGRESS</a>        
        <a href="teaching.html">TEACHING</a>
        <a href="officehours.html">OFFICE HOURS</a> 
    </nav>

    <section class="intro">
        <img src="assets/img/nathaly_bw.JPG" alt="Nathaly M. Rivera" class="foto-perfil">    
        
        <div class="intro-text">
           <h2 class="section-heading" style="margin-top: 50px;">Work in Progress</h2>
            <ol class="pub-list">
                <li class="pub-item">
                    <p class="pub-title">Blasting Dust: The Pollution-Health Impact of Industrial Mining Developments</p>
                    <p class="pub-authors">with <a href="#" class="coauthor-link">Gustavo Ahumada</a>, <a href="#" class="coauthor-link">Lenin Balza</a> and <a href="#" class="coauthor-link">Nicolás Gomez</a></p>
                    <div class="pub-links">
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs-w1')">[Abstract]</a>
                    </div>
                    <div id="abs-w1" class="abstract-box">
                        We study the pollution-health impact of industrial mining developments, specifically focusing on the effects of blasting dust...
                    </div>
                </li>

                <li class="pub-item">
                    <p class="pub-title">Droughts, Dirty Energy, and Health</p>
                    <p class="pub-authors">with <a href="#" class="coauthor-link">Danae Hernandez-Cortes</a>, <a href="#" class="coauthor-link">Sophie Mathes</a>, and <a href="#" class="coauthor-link">Ricardo Ramos Fontes</a></p>
                    <div class="pub-links">
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs-w2')">[Abstract]</a>
                    </div>
                    <div id="abs-w2" class="abstract-box">
                        This paper investigates how water scarcity affecting hydroelectric generation leads to an increase in fossil fuel-based electricity production, impacting local air quality and infant health in Chile...
                    </div>
                </li>
            </ol>
        </div> </section>

    <footer class="site-footer">
        <p>&copy; 2026 Nathaly M. Rivera. All rights reserved.</p>
    </footer>

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