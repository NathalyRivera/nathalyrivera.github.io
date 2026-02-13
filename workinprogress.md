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
           <h2 class="section-heading" style="margin-top: 50px;">Selected Work in Progress</h2>
            <ol class="pub-list">
                <li class="pub-item">
                    <p class="pub-title">Blasting Dust: The Pollution-Health Impact of Industrial Mining Developments</p>
                    <p class="pub-authors">with <a href="https://gahumada.weebly.com" class="coauthor-link">Gustavo Ahumada</a>, <a href="https://scholar.google.com/citations?hl=en&user=1K-_JF0AAAAJ&view_op=list_works" class="coauthor-link">Lenin Balza</a> and <a href="https://scholar.google.com/citations?user=1xjpsMgAAAAJ&hl=en" class="coauthor-link">Nicolás Gomez</a></p>
                    <div class="pub-links">
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs-w1')">[Abstract]</a>
                    </div>
                    <div id="abs-w1" class="abstract-box">
                    We study the pollution-health channel of the large-scale industrial mining developments leveraging exogenous variation in the geographical expansion of mineral leases in Chile over time and the distance to these installations. Using a battery of estimations in double differences and novel measures of expansion, we find a large negative impact of these developments on satellite-derived criteria air pollution concentrations within 50 km of these facilities, particularly SO$_2$. Later on, we link this increased pollution with the health outcomes of nearby communities. These results have important implications for the debate on the local welfare impact of mining developments
                    </div>
                </li>

                <li class="pub-item">
                    <p class="pub-title">Droughts, Dirty Energy, and Health</p>
                    <p class="pub-authors">with <a href="https://hernandezcortes.github.io/#publications" class="coauthor-link">Danae Hernandez-Cortes</a>, <a href="https://sophie-mathes.com" class="coauthor-link">Sophie Mathes</a>, and <a href="https://www.econ.ucsb.edu/people/students/ricardo-jose-ramos-fontes" class="coauthor-link">Ricardo Ramos Fontes</a></p>
                    <div class="pub-links">
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs-w2')">[Abstract]</a>
                    </div>
                    <div id="abs-w2" class="abstract-box">
                    Water availability threatened by climate change challenges the reliability of hydropower-based electricity generation systems. This paper evaluates the environmental and health impacts of ramped-up fossil fuel generation in response to periods of droughts in Brazil. For identification, we use exogenous variation in the standardized precipitation evapotranspiration index that relies on monthly precipitation and evapotranspiration to signal drought intensity and duration. We first document the ramping up of thermal combustion in periods of below-normal precipitations and its impacts on local air quality near thermal power plants. We use these estimates to quantify the impact of changes in air quality on hospitalizations. The results are expected to demonstrate an important link between climate change-induced water scarcity, fossil fuels, and health.
                    </div>
                </li>
  
            <li class="pub-item">
                <p class="pub-title">Renewable Energies, Fossil Fuel Displacement and Academic Performance in Environmental Justice Communities</p>
                <p class="pub-authors">Nathaly M. Rivera</p>
                <p class="pub-journal">Winner of CAF Grant 2022-2023</p>
            </li>

            <li class="pub-item">
                <p class="pub-title">Environmental Enforcement in the Aftermath of Major Environmental Disasters</p>
                <p class="pub-authors">with <a href="https://scholar.google.com/citations?hl=en&user=1K-_JF0AAAAJ&view_op=list_works" class="coauthor-link">Lenin Balza</a> and <a href="https://scholar.google.com/citations?user=1xjpsMgAAAAJ&hl=en" class="coauthor-link">Nicolás Gomez</a></p>
            </li>

            <li class="pub-item">
                <p class="pub-title">The Economics of Green Technology Adoption in Latin America</p>
                <p class="pub-authors">with <a href="https://scholar.google.com/citations?hl=en&user=1K-_JF0AAAAJ&view_op=list_works" class="coauthor-link">Lenin Balza</a>, <a href="https://www.hernandbejarano.com" class="coauthor-link">Hernán Bejarano</a>, and <a href="https://scholar.google.com/citations?user=1xjpsMgAAAAJ&hl=en" class="coauthor-link">Nicolás Gomez</a></p>
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