<img src="components/title.svg" width="100%" height="97"/>

<br />

<img src="components/subtitle.svg" width="100%" height="26"/>

<br />

***

<br />

<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/dheereshagrwal/colored-icons@1.7.5/src/app/ci.min.css"
/>

<div style="display:flex;height:fit-content;width:100%;">
    <div style="height:100%;padding:0px 10px 0px 0px;width:70%">
        <h2 style="margin:0px;margin-bottom:10px;border:0px">
            About me
        </h2>
        <ul style="height:100%;display:flex;flex-direction:column;justify-content: space-around;gap: 30px;font-size:15px">
        <li>
            💼 <strong>Backend Developer</strong> & <strong>Infrastructure Manager</strong> at <a href="https://www.rizaasset.com/">Riza Asset Management</a>
        </li>
        <li>
            📈 Gave weekly <strong>workshops about Unity</strong> and created a <strong>VR, AR and MR academic team</strong> (<a href="https://github.com/MetaversoMaua">Metaverso Mauá</a>)
        </li>
        <li>
            ❤️ I love using <strong>Unity Engine</strong>, and building fun <strong>games, experiences and demonstrations</strong>
        </li>
        <li>
            💬 <strong>Ask me</strong> about anything <a href="https://github.com/FernandoPFH/FernandoPFH/issues/">here</a>
        </li>
        </ul>
    </div>
    <div style="display: inline-flex;flex-direction:column;height: 260px;padding: 0px 0px 10px 0px">
        <img style="width: 100%;" src="https://avatars.githubusercontent.com/u/51247535?v=4">
        <div style="display:flex;justify-content:space-around;width:100%;margin:5px;">
            <a title="LinkedIn" href="https://www.linkedin.com/in/fernando-padilha-farah/"><i class="ci ci-linkedin ci-2x"></i></a>
            <a title="YouTube" href="https://www.youtube.com/@farahcode"><i class="ci ci-youtube ci-2x"></i></a>
            <a title="Email" href="mailto: fernandofarah1@hotmail.com"><i class="ci ci-gmail ci-2x"></i></a>
        </div>
    </div>
</div>

<br />

***

<br />

<h2 style="margin:0px;margin-bottom: 5px;border:0px;">
    Skills
</h2

<img src="components/skills.svg" width="100%" height="110"/>

<br />

***

<br />

<h2 style="margin:0px;margin-bottom: 5px;border:0px;">
    Repositories
</h2>

<h3 style="margin:0px;margin-bottom: 5px;border:0px;">
    Games
</h3>

<style>
    :root {
        --games_repositories: 3;
        --demos_repositories: 4;
        --mics_repositories: 2;

        --repository_width: 250px;
        --repository_gap: 10px;
    }

    .repositories_list {
        display: flex;
        white-space: nowrap;
        overflow: hidden;
        gap: var(--repository_gap);
    }

    .repositories_list:hover > .repository {
        animation-play-state: paused;
    }

    #games_repositories_list > * {
        animation-name: games_repositories_move;
        animation-delay: 0.5s;
    }

    #demos_repositories_list > * {
        animation-name: demos_repositories_move;
        animation-delay: 1s;
    }

    #mics_repositories_list > * {
        animation-name: mics_repositories_move;
        animation-delay: 1.5s;
    }

    .repository {
        position: relative;
        display: inline-flex;
        flex-direction: column;
        padding:10px;
        background-color:#3ec156;
        width: var(--repository_width);
        min-width: var(--repository_width);
        border-radius: 10px;
        color:black;

        animation-duration: 3s;
        animation-direction: alternate;
        animation-iteration-count: infinite;
        
        transition: background-color 0.2s ease-in-out;
        transition: color 0.2s ease-in-out;
    }

    .repository:hover {
        text-decoration: none;
        color: white;
        background-color:purple;
    }

    .repository img {
        height:100%;
    }

    .repository p {
        width:100%;
        text-align:center;
        margin:0px;
    }

    @keyframes games_repositories_move {
        0%, 10% {
            left: 0px;
        }

        90%, 100% {
            left: clamp(calc(infinity * -1px), calc((100vw - (var(--repository_width) * var(--games_repositories) + var(--repository_gap) * (var(--games_repositories) - 1)))*var(--games_repositories)), 0px);
        }
    }

    @keyframes demos_repositories_move {
        0%, 10% {
            left: 0px;
        }

        90%, 100% {
            left: clamp(calc(infinity * -1px), calc((100vw - (var(--repository_width) * var(--demos_repositories) + var(--repository_gap) * (var(--demos_repositories) - 1)))*var(--demos_repositories)), 0px);
        }
    }

    @keyframes mics_repositories_move {
        0%, 10% {
            left: 0px;
        }

        90%, 100% {
            left: clamp(calc(infinity * -1px), calc((100vw - (var(--repository_width) * var(--mics_repositories) + var(--repository_gap) * (var(--mics_repositories) - 1)))*var(--mics_repositories)), 0px);
        }
    }
</style>

<div class="repositories_list" id="games_repositories_list">
    <a class="repository" href="https://github.com/FernandoPFH/MemoryPuzzle-Game-Unity">
        <img src="https://raw.githubusercontent.com/FernandoPFH/MemoryPuzzle-Game-Unity/ca1d03ce09da7405d86eb04967a5d641ed972bd7/Imagens/MenuInicial.PNG">
        <p>
            <strong>MemoryPuzzle - Unity</strong>
        </p>
    </a>
    <a class="repository" href="https://github.com/FernandoPFH/Dodger-Game-Unity">
        <img src="https://raw.githubusercontent.com/FernandoPFH/Dodger-Game-Unity/main/Imagens/MenuInicial.PNG">
        <p>
            <strong>Dodger - Unity</strong>
        </p>
    </a>
    <a class="repository" href="https://github.com/FernandoPFH/FarahZero-Game-Unity">
        <img src="https://raw.githubusercontent.com/FernandoPFH/FarahZero-Game-Unity/main/Imagens/MenuInicial.PNG">
        <p>
            <strong>FarahZero - Unity</strong>
        </p>
    </a>
</div>

</br>

<h3 style="margin:0px;margin-bottom: 5px;border:0px;">
    Demos
</h3>

<div class="repositories_list" id="demos_repositories_list">
    <a class="repository" href="https://github.com/FernandoPFH/BezierCurves-OnlineDemo-P5js">
        <img src="https://raw.githubusercontent.com/FernandoPFH/BezierCurves-OnlineDemo-P5js/main/Imagems/Captura_CurvaBezier.PNG">
        <p>
            <strong>BezierCurves - P5.js</strong>
        </p>
    </a>
    <a class="repository" href="https://github.com/FernandoPFH/Graph-OnlineDemo-P5js">
        <img src="https://raw.githubusercontent.com/FernandoPFH/Graph-OnlineDemo-P5js/master/Imagens/Grafo_Capturar.PNG">
        <p>
            <strong>Graphs - P5.js</strong>
        </p>
    </a>
    <a class="repository" href="https://github.com/FernandoPFH/Metaballs-OnlineDemo-P5js">
        <img src="https://raw.githubusercontent.com/FernandoPFH/Metaballs-OnlineDemo-P5js/master/Imagens/Metaballs_Capturar.PNG">
        <p>
            <strong>Metaballs - P5.js</strong>
        </p>
    </a>
    <a class="repository" href="https://github.com/FernandoPFH/SortingAlgorithms-OnlineComparator-P5js">
        <img src="https://raw.githubusercontent.com/FernandoPFH/SortingAlgorithms-OnlineComparator-P5js/master/Imagens/Captura_AlgoritmosDeCompara%C3%A7%C3%A3o.PNG">
        <p>
            <strong>Sorting Algorithms - P5.js</strong>
        </p>
    </a>
</div>

</br>

<h3 style="margin:0px;margin-bottom: 5px;border:0px;">
    Mics
</h3>

<div class="repositories_list" id="mics_repositories_list">
    <a class="repository" href="https://github.com/FernandoPFH/dotfiles">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fernandopfh&layout=compact&theme=buefy&hide_border=true">
        <p>
            <strong>Dotfiles</strong>
        </p>
    </a>
    <a class="repository" href="https://github.com/FernandoPFH/Portfolio-Online-Unity">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fernandopfh&layout=compact&theme=buefy&hide_border=true">
        <p>
            <strong>Portfolio - Unity</strong>
        </p>
    </a>
</div>

<br />

***

<br />

<h2 style="margin:0px;margin-bottom: 5px;border:0px;">
    Metrics
</h2>

<a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=fernandopfh&show_icons=true&include_all_commits=true&theme=buefy&hide_border=true" alt="Anurag's github stats" /></a>  <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fernandopfh&layout=compact&theme=buefy&hide_border=true" /></a>