
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Links with Descriptions</title>
    <style>
        .wrapper{
            width:90%;
        }
        ul, ol { padding:0; margin: 0 ;text-align:center;}
        li{
            text-align:center;
        }
        .container-wrapper {
        display: flex;
        width: 100%;
        height: 100%;
        justify-content: start;
        align-content:center;
        align-items: flex-start; /* Align items from the top */
        }
        .container {
            display: flex;
            flex-direction: column;
            flex: 1;
            margin: 1px;
            padding: 5px;
            align-items: center;
            align-content: center;
            align-content:center;
            text-align:center;
            justify-content: flex-start; /* Align 
            content at the top */
            align-self: stretch;
        }
        .container:not(:last-child) {
            border-right: 1px solid #ccc;
        }
        .description {
            margin: 0 !important;
            padding: 0 !important;
            font-size: 16px;
            text-align: center;
            top: 0;
        }
        .avatar
        {
                max-width:230px;
                max-height:155px;
        }
         .social-links {
            display: flex;
            gap: 20px;
        }
        .social-links a {
            text-decoration: none;
            color: #333;
            font-size: 48px;
        }
        .social-links a:hover {
            color: #0077b5; /* LinkedIn color */
        }
        .social-links a.github:hover {
            color: #A020F0;
        }
        .social-links a.itch:hover {
            color: #fa5c5c;
        }
        .pretty-button {
    background: linear-gradient(135deg, #4a90e2, #357ABD); /* Toned-down blue gradient */
    border: none;
    border-radius: 25px; /* Rounded edges */
    color: white; /* White text */
    padding: 12px 24px; /* Comfortable padding */
    font-size: 16px; /* Readable font size */
    font-weight: bold;
    cursor: pointer; /* Pointer cursor on hover */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Soft shadow for depth */
    transition: all 0.3s ease; /* Smooth transitions */
}
.pretty-button:hover {
    background: linear-gradient(135deg, #357ABD, #4a90e2); /* Slightly reversed gradient on hover */
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2); /* Slightly deeper shadow */
    transform: translateY(-2px); /* Slight lift on hover */
}
.pretty-button:active {
    background: linear-gradient(135deg, #326da8, #2d6a9f); /* Darker blues for active state */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); /* Smaller shadow on click */
    transform: translateY(1px); /* Button press effect */
}
/* Media query for smaller screens (e.g., tablets and phones) */
@media (max-width: 768px) {
    .container-wrapper {
        flex-direction: column; /* Stack containers vertically */
    }
    .container{
        border-bottom: 1px solid #ccc; /* Add bottom border for separation */
    }
    .container:not(:last-child) {
        border-right: none; /* Remove the right border */
    }
}
    </style>
        <link src="http://maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

</head>

<div style = "height: 100%;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction:column;
            align-content:center;
            text-align:center;">

<h1 style = "text-align: center;"> About me </h1>
<p style= "text-align:center;">

I am a game programmer, as well as a student at Breda University Of Applied Sciences on Creative Media and Game Technologies programme. My main skillset revolves around AI and gameplay programming, yet I have extensive experience with tool development as well. I am proficient in C++ and C# and created multiple game projects (including commercial releases) in both Unity and Unreal Engine, I also have experience with working on custom engines and using them to make games. 
Currently interested in C++ game programming roles, especially focused on AI/Gameplay programming, as well as positions in Unity projects.
</p>

 <div class="social-links" style = "height = 64px;">
        <!-- Itch.io -->
        <a href="https://kenarf.itch.io" class="itch" target="_blank">
            <i class="fab fa-itch-io"></i>
        </a>
        <!-- GitHub -->
        <a href="https://github.com/FLuczak" class="github" target="_blank">
            <i class="fab fa-github"></i>
        </a>
        <!-- LinkedIn -->
        <a href="https://www.linkedin.com/in/franciszek-łuczak-02b9a8207/" class="linkedin" target="_blank">
            <i class="fab fa-linkedin"></i>
        </a>
</div>

</div>

<div>
<br/>
<h1 style = "text-align: center"> Projects Completed </h1>

<h1 style = "text-align: center">Games</h1>

 <div class="container-wrapper">
    <!-- Container 1 -->
    <div class="container">
        <a href="https://buas.itch.io/owlet" target="_blank">
            <img class="avatar" src="Images/owlet.png" alt="Placeholder Image" />
        </a>
        <div class="description">
            <h2>Owlet</h2>
            <br />
            <img src="Images/cpp.svg" alt="C++" style="width:32px" />
            <br />
            March 2024 - June 2024
            <br/>
            RTS game / Custom engine (C++) / AI and tools programmer
            <br /><br />
            Responsibilities:
            <ul>
                <li>Creating an AI framework with tools (visual scripting) for the designers to use.</li>
                <li>Writing gameplay functionality and AI mechanics based on the design team's input.</li>
                <li>Maintenance and development of the engine's core features (ECS, serialization, in-editor tools).</li>
                <li>Maintenance of the project's CI/CD pipelines and QA pipeline.</li>
                <li>Management of the programming team, communication with the producer, and distributing tasks within the programming team.</li>
                <br/>
                <button class = "pretty-button"> Details</button>
            </ul>
            <br/>
        </div>
    </div>
    <hr/>
    <!-- Container 2 -->
    <div class="container">
        <a href="https://store.steampowered.com/app/2658510/Animal_Shelter_2/" target="_blank">
            <img src="Images/Animal2.png" class="avatar" alt="Placeholder Image" />
        </a>
        <div class="description">
            <h2>Animal Shelter Simulator 2</h2>
            <img src="Images/unity.png" alt="Unity" style="width:32px" />
            <br />
            March 2024 - Current
            <br />
            Simulation game / Unity Engine / Gameplay and tools programmer
            <br /><br />
            Responsibilities:
            <ul>
                <li>Designing the game's architecture in the initial development stage.</li>
                <li>Implementing gameplay mechanics based on the design team's documents.</li>
                <li>Maintenance of the codebase and bug fixing.</li>
                <li>Tools programming for the Level Design, QA, and Design teams to facilitate their workflows.</li>
                <li>Maintaining documentation of the codebase.</li>
                <br>
                <br>                
                <br>        
                <button class= "pretty-button"> Details</button>
            </ul>
        </div>
    </div>
</div>

<br/>
<br/>
<div class="container-wrapper">
    <!-- Container 1 -->
    <div class="container">
        <a href="https://vittoriobellinello.itch.io/team-moth" target="_blank">
            <img src="Images/Smash balls.png" alt="Placeholder Image" class="avatar" />
        </a>
        <div class="description">
            <h2>Smash Balls</h2>
            <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 24 24">
                <path fill="currentColor"
                    d="M12 0a12 12 0 1 0 12 12A12 12 0 0 0 12 0m0 23.52A11.52 11.52 0 1 1 23.52 12A11.52 11.52 0 0 1 12 23.52m7.13-9.791c-.206.997-1.126 3.557-4.06 4.942l-1.179-1.325l-1.988 2a7.34 7.34 0 0 1-5.804-2.978a3 3 0 0 0 .65.123c.326.006.678-.114.678-.66v-5.394a.89.89 0 0 0-1.116-.89c-.92.212-1.656 2.509-1.656 2.509a7.3 7.3 0 0 1 2.528-5.597a7.4 7.4 0 0 1 3.73-1.721c-1.006.573-1.57 1.507-1.57 2.29c0 1.262.76 1.109.984.923v7.28a1.2 1.2 0 0 0 .148.256a1.08 1.08 0 0 0 .88.445c.76 0 1.747-.868 1.747-.868V9.172c0-.6-.452-1.324-.905-1.572c0 0 .838-.149 1.484.346a6 6 0 0 1 .387-.425c1.508-1.48 2.929-1.902 4.112-2.112c0 0-2.151 1.69-2.151 3.96c0 1.687.043 5.801.043 5.801c.799.771 1.986-.342 3.059-1.441Z"/>
            </svg>
            <br />
            April 2023-June 2023
            <br/>
            Arcade co-op game / Unreal Engine (C++ and Blueprints) / Gameplay programmer
            <br /><br />
            Responsibilities:
            <ul>
                <li>Design of game's architecture in the early stages of development</li>
                <li>Implementation and maintenance of gameplay mechanics based on the design team's input</li>
                <li>Implementation of gameplay features in C++ that technical designers and other programmers could use in blueprints for rapid prototyping</li>
                <br>
                <br>
            </ul>
        </div>
        <button class= "pretty-button"> Details</button>
    </div>
    <!-- Container 2 -->
    <div class="container">
        <a href="https://store.steampowered.com/app/1239320/Animal_Shelter/" target="_blank">
            <img src="Images/Animal 1.png" alt="Placeholder Image" class="avatar" />
        </a>
        <div class="description">
            <h2>Animal Shelter Simulator</h2>
            <img src="Images/unity.png" alt="Unity" style="width:32px" />
            <br />
            March 2022 - March 2023
            <br />
            Simulation game / Unity Engine / AI and gameplay programmer
            <br /><br />
            Responsibilities:
            <ul>
                <li>Rebuilding the core AI system of the game and implementing custom tools for the design team to use</li>
                <li>Implementing gameplay mechanics and AI functionalities based on the design team's input</li>
                <li>Maintenance of the codebase and bug fixing</li>
                <li>Implementing a tool for the QA team for easier testing</li>
                <li>Maintenance of the QA pipeline including live automatic bug reporting and logging</li>
            </ul>
        </div>
        <button class= "pretty-button"> Details</button>
    </div>
</div>

<div class="container-wrapper">
    <!-- Container 1 -->
    <div class="container">
        <a href="https://play.google.com/store/apps/details?id=com.FroccoGames.FallDude&hl=pl&gl=US" target="_blank">
            <img class="avatar" src="Images/Fall dude.png" alt="Placeholder Image" />
        </a>
        <div class="description">
            <h2>Fall dude</h2>
            <br />
            <img src="Images/unity.png" alt="C++" style="width:32px" />
            <br />
            September 2022 - November 2022
            <br/>
            Arcade mobile game / Unity engine 
            <br /><br />
            Responsibilities:
            <ul>
               <li>Designing the game and its architecture</li>
                <li>Adding gameplay mechanics</li>
                <li>Integrating Google APIs to the project (admob, google play games, firebase) </li>
                <br/>
                <button class = "pretty-button"> Details</button>
            </ul>
            <br/>
        </div>
    </div>
    <div class="container">
        <a href="https://play.google.com/store/apps/details?id=com.froccoGames.BallProject&hl=pl&gl=US" target="_blank">
            <img class="avatar" src="Images/Boing boing ball.png" alt="Placeholder Image" />
        </a>
        <div class="description">
            <h2>Boing boing ball</h2>
            <br />
            <img src="Images/unity.png" alt="C++" style="width:32px" />
            <br />
            January 2022 - April 2022
            <br/>
            Arcade mobile game / Unity engine 
            <br /><br />
            Responsibilities:
            <ul>
             <li>Designing the game and its architecture</li>
                <li>Adding gameplay mechanics</li>
                <li>Integrating Google APIs to the project (admob, google play games, firebase) </li>
                <br/>
                <button class = "pretty-button"> Details</button>
            </ul>
            <br/>
        </div>
    </div>
</div>

<hr/>
<h1 style = "text-align: center">Tools</h1>
<div class="container-wrapper">
    <!-- Container 1: Pepi Engine -->
    <div class="container">
        <a href="https://www.example.com" target="_blank">
            <img src="Images/pepi_engine_logo_small.png" alt="Pepi Engine Logo" class="avatar" />
        </a>
        <div class="description">
            <h2>Pepi Engine</h2>
            <img src="Images/cpp.svg" alt="C++" style="width:32px;" />
            <br />
            This engine was created for a project at Breda University of Applied Sciences to facilitate the development of RTS games. My responsibilities included:
            <ul>
                <li>AI editor for Finite State Machines and Behavior Trees.</li>
                <li>Animation Controllers and grid-based navigation.</li>
                <li>CI/CD and QA pipelines using GitHub Actions.</li>
            </ul>
        </div>
    </div>
    <!-- Container 2: Franco Engine -->
    <div class="container">
        <a href="https://github.com/FLuczak/Franco-engine" target="_blank">
            <img src="Images/Franco.png" alt="Franco Engine Logo" class="avatar" />
        </a>
        <div class="description">
            <h2>Franco Engine</h2>
            <img src="Images/cpp.svg" alt="C++" style="width:32px;" />
            <br />
            A passion project created in my free time. This engine is universal but optimized for bullet hell and top-down roguelikes. Key features I developed include:
            <ul>
                <li>Navmesh navigation.</li>
                <li>AI structures with a visual editor.</li>
                <li>Performant physics system.</li>
                <li>Entity and component serialization.</li>
                <li>Asset explorer.</li>
            </ul>
        </div>
    </div>
    <!-- Container 3: Visual Debug Console -->
    <div class="container">
        <a href="https://gitlab.com/darthkornik/visual-debug-console" target="_blank">
            <img src="Images/visualDebuggingConsole.png" alt="Visual Debug Console Logo" class="avatar" />
        </a>
        <div class="description">
            <h2>Visual Debug Console</h2>
            <img src="Images/unity.png" alt="Unity" style="width:32px;" />
            <br />
            An open-source project I co-created while working at a games incubator. This tool is widely used across multiple game projects for QA processes and playtesting. Its key features include:
            <ul>
                <li>Replacing the classic debug console with a user-friendly interface.</li>
                <li>Programmatic buttons bound to in-game functions.</li>
                <li>Live variable previews for enhanced debugging.</li>
            </ul>
        </div>
    </div>
</div>
</div>
