
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Links with Descriptions</title>
    <style>
        .container-wrapper {
            display: flex;
            width: 100%;
            justify-content: space-between;
            align-items: center;
        }
        .container {
           display: flex;
            flex-direction: column;
            align-items: center;
            flex: 1;
            margin: 1px;
            padding: 10px;
        }  .container:not(:last-child) {
            border-right: 1px solid #ccc;
        }
        .description {
            margin-top: 10px;
            font-size: 16px;
            text-align: center;
        }
        .avatar{
              display: block;
                max-width:230px;
                max-height:155px;
                width: auto;
                height: auto;
        }
    </style>
</head>

<div>

<h1 style = "text-align: center"> About me </h1>

Hi, my name is Franciszek Łuczak and I am a second-year student at Breda University of Applied Sciences in the Creative Media and Game Technology program in a game programming major. I am mostly interested in Game AI and gameplay programming.
</div>

<div>
<br/>
<h1 style = "text-align: center"> Projects Completed </h1>

<h1 style = "text-align: center">Games</h1>

 <div class="container-wrapper">
        <div class="container">
            <a href="https://store.steampowered.com/app/2658510/Animal_Shelter_2/" target="_blank">
                <img src="Images/animal 2.png" alt="Placeholder Image" class="avatar"/>
            </a>
            <div class="description">
                <h2>Animal Shelter Simulator 2</h2>
                                <i class="fa-brands fa-unity" style = "font-size: 32px"></i>
                                <br/>
                A game I developed while working for Games Incubator. The game was created in unity and C#. My main responsibilities were: maintaining existing gameplay/AI features, as well as creating tools that allowed other people from the team to work more efficiently on level design and adding content to the game.
            </div>
        </div>
        <div class="container">
            <a href="https://store.steampowered.com/app/1239320/Animal_Shelter/" target="_blank">
                <img src="Images/Animal 1.png" alt="Placeholder Image" class="avatar"/>
            </a>
            <div class="description">
                <h2>Animal Shelter Simulator</h2>
                            <i class="fa-brands fa-unity" style = "font-size: 32px"></i>
                                <br/>
                A game I developed while working for Games Incubator. The game was created in unity and C#. My main responsibilities were mainly working on AI functionalities, as well as maintaining gameplay features of the game. After the release I was responsible for live-ops of the game, mainly fixing reported bugs, as well as working on additional content and features post-release.
            </div>
        </div>
        <div class="container">
            <a href="https://vittoriobellinello.itch.io/team-moth" target="_blank">
                <img src="Images/Smash balls.png" alt="Placeholder Image" class="avatar"/>
            </a>
            <div class="description">
                <h2>Smash Balls</h2>
                <svg xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 24 24"><path fill="currentColor" d="M12 0a12 12 0 1 0 12 12A12 12 0 0 0 12 0m0 23.52A11.52 11.52 0 1 1 23.52 12A11.52 11.52 0 0 1 12 23.52m7.13-9.791c-.206.997-1.126 3.557-4.06 4.942l-1.179-1.325l-1.988 2a7.34 7.34 0 0 1-5.804-2.978a3 3 0 0 0 .65.123c.326.006.678-.114.678-.66v-5.394a.89.89 0 0 0-1.116-.89c-.92.212-1.656 2.509-1.656 2.509a7.3 7.3 0 0 1 2.528-5.597a7.4 7.4 0 0 1 3.73-1.721c-1.006.573-1.57 1.507-1.57 2.29c0 1.262.76 1.109.984.923v7.28a1.2 1.2 0 0 0 .148.256a1.08 1.08 0 0 0 .88.445c.76 0 1.747-.868 1.747-.868V9.172c0-.6-.452-1.324-.905-1.572c0 0 .838-.149 1.484.346a6 6 0 0 1 .387-.425c1.508-1.48 2.929-1.902 4.112-2.112c0 0-2.151 1.69-2.151 3.96c0 1.687.043 5.801.043 5.801c.799.771 1.986-.342 3.059-1.441Z"/></svg>
                <br/>
                A team project I got to work on during 1st year of my studies. Smash Balls is a fun 2-4 player couch versus game with unique controls. In this project I took on the role of an Unreal Engine programmer, I worked on 3Cs implementations with emphasis on player states and their controls as well as player interactions.
            </div>
        </div>
    </div>

<br/>
<br/>
 <div class="container-wrapper">
        <div class="container">
            <a href="https://www.example.com" target="_blank">
                <img src="https://via.placeholder.com/150" alt="Placeholder Image" />
            </a>
            <div class="description">
                <h2>Owlet</h2>
                <i class="icon-cplusplus"></i> 
                This is a description of the image and the link it leads to.
            </div>
        </div>
</div>

<h1 style = "text-align: center">Tools</h1>

 <div class="container-wrapper">
        <div class="container">
            <a href="https://www.example.com" target="_blank">
                <img src="https://via.placeholder.com/150" alt="Placeholder Image" />
            </a>
            <div class="description">
                <h2>pepi engine</h2>
                This engine was created for a project at Breda University Of Applied Sciences,it was created to facilitate development of RTS games. The tools I was responsible for were: AI editor for Finite State Machines and Behavior Trees, Animation Controllers, as well as grid-based navigation. I was also responsible for the CI/CD and QA pipelines of the project using github actions.
            </div>
        </div>
        <div class="container">
            <a href="https://github.com/FLuczak/Franco-engine" target="_blank">
                <img src="https://via.placeholder.com/150" alt="Placeholder Image" />
            </a>
            <div class="description">
                <h2>Franco engine</h2>
                A passion project created in my free time. The engine is quite universal, yet its main benchmark and target game genre is bullet hell, top-down roguelikes. For this project I created: Navmesh navigation, AI structures with visual editor, performant physics system, Entity and Component Serialization, Asset explorer.
            </div>
        </div>
    </div>


</div>
