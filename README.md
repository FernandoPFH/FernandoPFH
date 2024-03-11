<style>    
    @font-face {
        font-family: "Anton";
        src: url(fonts/Anton/Anton-Regular.ttf);
    }

    .title {
        height: 95px;
        background-color: #3ec156;
        display: flex;
        align-items: center;
        justify-content: center;

        margin: 0px 30px;

        border-radius: 16px;
        border: 1px solid white;
    }

    .title p {
        align: center;
        text-align: center;
        color: black;
        font-size:26px;
        margin: 0px;

        font-family: Anton;
        font-weight: 400;
    }

    .subtitle {
        display:flex;
        gap:10px;

        justify-content:center;
    }

    .subtitle div {
        background-color: purple;
        color: white;

        padding: 2px 10px;

        border-radius: 16px;
    }

    .subtitle p {
        margin: 0px;
    }



    .rainbow_text > * {
        position: relative;
        animation: rainbow_auto 1.5s 2;
    }

    #letter1 {animation-delay: 0.1s;}
    #letter2 {animation-delay: 0.2s;}
    #letter3 {animation-delay: 0.3s;}
    #letter4 {animation-delay: 0.4s;}
    #letter5 {animation-delay: 0.5s;}
    #letter6 {animation-delay: 0.6s;}
    #letter7 {animation-delay: 0.7s;}
    #letter8 {animation-delay: 0.8s;}
    #letter9 {animation-delay: 0.9s;}
    #letter10 {animation-delay: 1s;}
    #letter11 {animation-delay: 1.1s;}
    #letter12 {animation-delay: 1.2s;}
    #letter13 {animation-delay: 1.3s;}
    #letter14 {animation-delay: 1.4s;}
    #letter15 {animation-delay: 1.5s;}
    #letter16 {animation-delay: 1.6s;}
    #letter17 {animation-delay: 1.7s;}
    #letter18 {animation-delay: 1.8s;}
    #letter19 {animation-delay: 1.9s;}
    #letter20 {animation-delay: 2s;}

    .title:hover .rainbow_text > * {
        animation: rainbow_man 1.5s 2;
    }

    .title:hover #letter1 {animation-delay: 0.1s;}
    .title:hover #letter2 {animation-delay: 0.2s;}
    .title:hover #letter3 {animation-delay: 0.3s;}
    .title:hover #letter4 {animation-delay: 0.4s;}
    .title:hover #letter5 {animation-delay: 0.5s;}
    .title:hover #letter6 {animation-delay: 0.6s;}
    .title:hover #letter7 {animation-delay: 0.7s;}
    .title:hover #letter8 {animation-delay: 0.8s;}
    .title:hover #letter9 {animation-delay: 0.9s;}
    .title:hover #letter10 {animation-delay: 1s;}
    .title:hover #letter11 {animation-delay: 1.1s;}
    .title:hover #letter12 {animation-delay: 1.2s;}
    .title:hover #letter13 {animation-delay: 1.3s;}
    .title:hover #letter14 {animation-delay: 1.4s;}
    .title:hover #letter15 {animation-delay: 1.5s;}
    .title:hover #letter16 {animation-delay: 1.6s;}
    .title:hover #letter17 {animation-delay: 1.7s;}
    .title:hover #letter18 {animation-delay: 1.8s;}
    .title:hover #letter19 {animation-delay: 1.9s;}
    .title:hover #letter20 {animation-delay: 2s;}

    @keyframes rainbow_auto {
        0% {
            top: 0px;
        }

        25% {
            color: blue;
            top: -10px;
        }

        75% {
            color: red;
            top: 10px;
        }

        90%, 100% {
            top: 0px;
        }
    }

    @keyframes rainbow_man {
        0% {
            top: 0px;
        }

        25% {
            color: blue;
            top: -10px;
        }

        75% {
            color: red;
            top: 10px;
        }

        90%, 100% {
            top: 0px;
        }
    }
</style>

<div class="title">
    <strong>
        <p>
        👋 Hello, I'm <span class="rainbow_text"><span id="letter1">F</span><span id="letter2">e</span><span id="letter3">r</span><span id="letter4">n</span><span id="letter5">a</span><span id="letter6">n</span><span id="letter7">d</span><span id="letter8">o</span> <span id="letter9">P</span><span id="letter10">a</span><span id="letter11">d</span><span id="letter12">i</span><span id="letter13">l</span><span id="letter14">h</span><span id="letter15">a</span> <span id="letter16">F</span><span id="letter17">a</span><span id="letter18">r</span><span id="letter19">a</span><span id="letter20">h</span></span>
        </p>
    </strong>
</div>

<img style="width:100%;" align="center" src="components/title.svg" alt="Anurag's github stats" />

<br />

<div class="subtitle">
    <div>
        🎮 Game Developer
    </div>
    <div>
        ⚙ Backend Developer
    </div>
    <div>
        👨‍🎓 Teacher
    </div>
</div>

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
</h2>

<style>
    .grid-container {
        position: relative;
        display: flex;
        justify-content: center;
        gap: 5px;
    }

    .grid-container .grid-modal{
        position: absolute;
        top: 0px;
        width: 100%;
        height: 100%;
        background-color: rgba(62,193,86,0.7);

        display: flex;
        align-items: center;
        justify-content: center;
        
        font-size: 50px;
        color: black;
        cursor: default;
        -webkit-user-select: none; /* Safari */
        -ms-user-select: none; /* IE 10 and IE 11 */
        user-select: none; /* Standard syntax */

        opacity: 1;
        transition: opacity 0.1s ease-in-out;
    }

    .grid-container:hover > .grid-modal{
        opacity: 0;
        pointer-events: none;
    }

    .grid-item {
        position: relative;
        display: inline-flex;
        height: 110px;
        max-height: 110px;
        width: 66px;
        max-width: 66px;
        transition: transform 0.3s ease-in-out;
    }

    .grid-item img {
        height: 100px;
        max-height: 100px;
        z-index: 0;
    }

    .grid-level {
        position: absolute;
        bottom: 40px;
        width: 100%;
        z-index: -1;

        background-color: #3ec156;
        height: 30px;

        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-end;

        transition: bottom 0.2s ease-in-out;
    }

    .grid-item:hover > .grid-level {
        bottom: 13px;
    }

    .grid-level p {
        width: 95%;
        font-size: 9px;
        text-align: center;
        margin: 0px;
        color: black;
    }

    .grid-item:hover {
        transform: scale(1.7);
        z-index: 1;
    }
</style>

<div class="grid-container">
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Unity-Dark.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/UnrealEngine.svg">
        <div class="grid-level">
            <p><strong>Intermediate</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/CS.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/CPP.svg">
        <div class="grid-level">
            <p><strong>Intermediate</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Python-Dark.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Git.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Blender-Dark.svg">
        <div class="grid-level">
            <p><strong>Intermediate</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Linux-Dark.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/VSCode-Dark.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Docker.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/MySQL-Dark.svg">
        <div class="grid-level">
            <p><strong>Advanced</strong></p>
        </div>
    </div>
    <div class="grid-item">
        <img alt="Unity3D" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Bash-Dark.svg">
        <div class="grid-level">
            <p><strong>Intermediate</strong></p>
        </div>
    </div>
    <div class="grid-modal" id="skills-modal">
        <p>
        <strong>Hover here!</strong>
        </p>
    </div>
</div>

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