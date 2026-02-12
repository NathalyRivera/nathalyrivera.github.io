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
        
        <div class="intro-text">
            <h2 class="section-heading">Peer-Reviewed Publications</h2>

            <ol class="pub-list">
                <li class="pub-item">
                    <p class="pub-title">Wood-Burning Restrictions and Air Pollution: The Case of Air Quality Warnings in Southern Chile</p>
                    <p class="pub-authors">with <a href="#" class="coauthor-link">Cristian Concha</a></p>
                    <p class="pub-journal">Accepted at <em>Environment and Development Economics</em>, 2025</p>
                    <div class="pub-links">
                        <a href="#">[Paper]</a>
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs1')">[Abstract]</a>
                        <span class="media-links">— Featured in: <a href="#">[Universidad de Chile]</a></span>
                    </div>
                    <div id="abs1" class="abstract-box">Texto del abstract...</div>
                </li>
                </ol>

            <h2 class="section-heading" style="margin-top: 50px;">Working Papers</h2>
            <ol class="pub-list">
                <li class="pub-item">
                    <p class="pub-title">Blasting Dust: The Pollution-Health Impact of Industrial Mining Developments</p>
                    <p class="pub-authors">with <a href="#" class="coauthor-link">Gustavo Ahumada</a>, <a href="#" class="coauthor-link">Lenin Balza</a> and <a href="#" class="coauthor-link">Nicolás Gomez</a></p>
                    <div class="pub-links">
                        <a href="javascript:void(0)" onclick="toggleAbstract('abs3')">[Abstract]</a>
                    </div>
                    <div id="abs3" class="abstract-box">Texto del abstract...</div>
                </li>
            </ol>
        </div>

        <img src="assets/img/nathaly_bw.JPG" alt="Nathaly M. Rivera" class="foto-perfil">    

    </section>

    <script>
        function toggleAbstract(id) {
            var x = document.getElementById(id);
            x.style.display = (x.style.display === "block") ? "none" : "block";
        }
    </script>
</body>
</html>