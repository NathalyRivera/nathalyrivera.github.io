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

    <section class="intro">
        <img src="assets/img/nathaly_bw.JPG" alt="Nathaly M. Rivera" class="foto-perfil">    
        
        <div class="intro-text">
            
            <h2 class="section-heading">Peer-Reviewed Publications</h2>
            <ol class="pub-list">
                <li class="pub-item">
                    <p class="pub-title">Wood-Burning Restrictions and Air Pollution: The Case of Air Quality Warnings in Southern Chile</p>
                    <p class="pub-authors">with <a href="https://sites.google.com/view/cristianconcha" target="_blank" class="coauthor-link">Cristian Concha</a></p>
                    <p class="pub-journal">Accepted at <em>Environment and Development Economics</em>, 2025</p>
                    <div class="pub-links">
                        <a href="https://www.cambridge.org/core/journals/environment-and-development-economics/article/abs/woodburning-restrictions-and-air-pollution-the-case-of-air-quality-warnings-in-southern-chile/D5E8D3E03698146778DDF32786DA3FC7?utm_campaign=shareaholic&utm_medium=copy_link&utm_source=bookmark" target="_blank">[View]</a>
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs1')">[Abstract]</a>
                        <span class="media-links">— Featured in: <a href="https://uchile.cl/noticias/230506/u-de-chile-evalua-plan-anticontaminacion-en-los-angeles-y-sus-limites" target="_blank">[Universidad de Chile]</a> <a href="#">[La Tribuna]</a></span>
                    </div>
                    <div id="abs1" class="abstract-box">
                        Despite the substantial evidence linking particulate matter exposure to adverse health outcomes, a large portion of the global population, particularly in low-income countries, continues to rely on highly polluting fuels, such as wood, for cooking and heating. This study evaluates the immediate effects of wood-burning restrictions, which are triggered by air quality warnings, on levels of fine (PM2.5) and coarse (PM10) particulate matter in southern Chile. Using a difference-in-differences design that incorporates pre-policy data, we provide plausible causal estimates indicating that wood-burning restrictions lead to significant reductions in hourly PM10 and PM2.5 concentrations during the most severe air quality warning. Additional analyses, including a regression discontinuity design, further support these findings. While our analysis suggests that wood-burning restrictions are effective, they may not be sufficient to reduce air pollution concentrations to levels that are considered safe for public health.
                    </div>
                </li>

                <li class="pub-item">
                    <p class="pub-title">Air Pollution in the Global South: An Overview of its Sources and Impacts</p>
                    <p class="pub-authors">with <a href="https://www.sandraaguilargomez.com/" target="_blank" class="coauthor-link">Sandra Aguilar-Gomez</a></p>
                    <p class="pub-journal"><em>Oxford Research Encyclopedia of Economics and Finance</em>, 2025</p>
                    <div class="pub-links">
                        <a href="https://doi.org/10.1093/acrefore/9780190625979.013.911" target="_blank">[View]</a>
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs2')">[Abstract]</a>
                    </div>
                    <div id="abs2" class="abstract-box">
                  The literature on the impacts of air pollution on both health and non-health outcomes in the Global South is examined, focusing on the growing body of causal evidence, and on the several pollution sources that are particularly relevant in the Global South, including indoor air pollution, particulate emissions from wildfires, and agricultural burning. The evidence consistently shows that, across different contexts, air pollution has severe health consequences, including high rates of respiratory and cardiovascular diseases, as well as premature mortality. Indoor air pollution, in particular, poses a significant burden, especially in rural areas. In addition to health impacts, air pollution also has non-health consequences, such as reduced productivity, impaired cognitive performance, pollution-induced migration, and associated economic impacts. The review highlights the growing body of scientific research documenting these impacts. Yet, notable regional disparities still remain.                    </div>
                </li>
            </ol>

            <h2 class="section-heading" style="margin-top: 50px;">Working Papers</h2>
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