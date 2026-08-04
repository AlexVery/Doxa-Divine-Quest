# Doxa-Divine-Quest

This page is meant to showcase the different aspects of the game, which can be found [here](https://github.com/AlexVery#:~:text=Link%20to%20the%20game%3A%20https%3A//averik.itch.io/doxa%2Ddivine%2Dquest). The goal is to highlight the differences between the two versions of the game (the one I used for my thesis and the further improved one that got published on [itch.io](https://itch.io/). Some of them include the addition of sound effects, adding backgrounds and making the actions animated (button clicks, selection etc.).  

*Doxa:Divine Quest* is divided into three mini games:
- a labyrinth (offered both in 2D and 3D)
- levels inspired by some of the most iconic battles of the ancient Greek world
- some tales of the ancient Greek mythology

I got ispiration from [Doom using Python](https://www.youtube.com/watch?v=ECqUrT7IdqQ) to create the 3D version. Some changes needed to be made to fit the logic of my game, because each map is procedurally generated and the wall sizes are not always the same, they depend on the difficulty chosen by the player. After research I also decided to incorporate the images and sounds used in tha game into the code. The data was encypted once and put into two seperate files: one for the images and one for the sounds. They get decrypted once the game executes. This ensures that the game can be shipped as an executable alone, no extra files/folders needed and there is no danger of players accidentally deleting a file vital for the execution of the game. The executable can also be moved to any folder and still work, without needing to move other folders as well, it is independent.

<div align="center">

  The main menu screen can be seen in *Figure 1*.
  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/b7c2e526-6ea7-4b0a-8fb8-4529ea8899a9" />
  </p>

  **Figure 1**: Game main menu screen

</div>

I managed to translate the game into tha languages I know and then thanks to the help from close friends i managed to translate the game into the different languages seen in *Figure 2*.
<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/fe4bcc94-62c0-434b-84a5-45a4cfedc2e3" />
  </p>

  **Figure 2**: Languages provided by the game

</div>

<div align="center">

  The different game modes are displayed and shortly described as seen in *Figure 3*.

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/ff2b3b4a-1c68-41b2-906b-79d0fed8c36f" />
  </p>

  **Figure 3**: Game modes

</div>

When users click on *Normal(2D)* the screen seen in *Figure 4* appears, explaining the game structure and the different difficulty levels provided in the game.

<div align="center">  
  
  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/c7ae91cb-629b-4615-8a41-1f95ba3b52fb" />
  </p>

  **Figure 4**: 2D Labyrinth Mode

</div>

<div align="center">
  
  A graphical UI acting as a tutorial is run when the users open any mode (2D or 3D) for the first time (*Figure 5*).
  
  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/74a03181-eb06-48e3-9ab6-402594c25f60" />
  </p>

  **Figure 5**: Tutorial

</div>

Players can use the "Z" keyboard key to zoom-in/-out of the game. This comes handy especially in the normal and hard difficulty where the mazes get larger and the visibility gets worse. This happend because the maze is drawn like this: 
- take the width of the window
- get the wall size (changeable by the player)
- divide the width of the screen with the wall size
If the wall size is too small, it is displayed tiny, but with this addition the problem is counter (something mentioned in the first version of the game).

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/522cdb55-fa18-455c-a0e4-d6a0aa16d87c" />
  </p>

  **Figure 6**: Zoomed-in Mode

</div>

<div align="center">
  
  Players can press "Enter" to hide the UI box displaying info about the zoom values on x and y axis (*Figure 7*).
  
  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/ac1919d4-7bdd-4f7e-bd41-1d665b92e7f3" />
  </p>

  **Figure 7**: Hide bottom-left UI box for better visibility

</div>

<div align="center">

  The controls are shown by clicking "C" on the keyboard (*Figure 8*).

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/91b979e0-d0aa-41dd-bbf9-98abdc9bc541" />
  </p>

  **Figure 8**: Controls list

</div>

<div align="center">

  There are messages that help the player understand the game state and actions that are (un)available (*Figure 9* and Thesis pg. 36 *Figure 23*). 

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/9efdb20d-8d34-4f50-ba65-90dfd70b134b" />
  </p>

  **Figure 9**: Open chest message

</div>

There is an in-game shop where players can buy equipment (sword, shield, healing potions etc.). To buy them players need to complete levels, because according to the level's difficulty there are coin rewards. The coins are reset to 0 each time the mode changes (2D 🔄 3D). One improvement from the first version is that the message for the shop's tutorial is more easily visible and the button's appearance and function is visibly improved. Now the button when the mouse hovers over it, changes color and when clicked appears animated (like many modern UIs).

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/a06d900d-2d5f-4494-8a6c-aedbddcfea11" />
  </p>

  **Figure 10**: Shop UI

</div>

<div align="center">

  To clarify the exact use of an item, each one comes with a short but precise description (*Figure 11*).

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/1e1ad8e3-02a7-437e-9cd6-c49235d4d223" />
  </p>

  **Figure 11**: Info for selected item

</div>

<div align="center">

  There is also an inventory where players can keep track of the items they currently own or use an item (for example a healing potion).

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/c9164437-7fa8-4272-b0d8-3d3baa66b1e6" />
  </p>

  **Figure 12**: Inventory

</div>

Players can pause the game by pressing "P" on their keyboard. The pause screen is seen in *Figure 13*. It includes two extra buttons (except *Resume*): *Settings* which includes two subpages seen in *Figure 14* and *Figure 15* (one for the "Basics" and the other for the "Texture" settings). 

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/91a55ac9-d9c1-480a-9028-c3311243b67f" />
  </p>

  **Figure 13**: Pause game screen

</div>

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/cb641632-6be6-4336-8b09-3680ccc94357" />
  </p>

  **Figure 14**: Basics settings

</div>

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/a924e5b2-91f1-488a-affd-01f98f204c4c" />
  </p>

  **Figure 15**: Texture settings

</div>

In labyrinth mode the goal is to reach the exit after collecting all 3 keys. The keys can be found in the chests, which don't require unlocking. In the 2D mode players must move from the top right of the maze to the bottom left. In 3D mode there is an arrow indicating the direction players must follow to find the nearest chest and then the exit, along with a text specifying the distance between the main character and the chest/exit. 
In labyrinth mode there are 3 difficulty levels:
- Easy: just a normal and relatively small labyrinth
- Normal: flying monsters spawn for each chest the players open (doesn't happen in 3D), while the maze is larger
- Hard: the maze is significantly larger and there is a time limit within players must get to the exit (5 minutes - *Figure 16*) 

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/8922faff-7c75-4c45-85d2-654ec4f79032" />
  </p>

  **Figure 16**: Hard mode includes a clock

</div>

*Figure 17* - *Figure 19* showcase the 3D labyrinth mode. As seen in my Thesis on pg. 36 (*Figure 22*, *Figure 23*) the walls where not pixel art and felt disconnected from the overall design of the game. Along with the appearance there was another issue: the size of the image was large, because the the image was very sharp. Python is not a language that such issues can go unnoticed and therefore I needed to optimise my logic, so I instead created other images using [pixilart](https://www.pixilart.com/). I also added graphics settings (low, normal, high), so the 3D version works flawlessly on more PCs.

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/2313cb2d-8b8a-431b-8ac4-8f1ce3ab8791" />
  </p>

  **Figure 17**: 3D Labyrinth Mode

</div>

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/abd731fb-bbcf-4742-8865-3e74c82d9f29" />
  </p>

  **Figure 18**: 3D Labyrinth Mode - Hide UI

</div>

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/63f8f46f-dc5a-4ca2-a53e-103a04b6187f" />
  </p>

  **Figure 19**: 3D Mode - Textures are changeable here as well

</div>

There is also a dedicated page for the credits/license of the game assets used. Each is displayed along its creator, the license under it's used and a link to the creator's page or the asset within the site I downloaded it from, for example [freesound](https://freesound.org/).

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/bf80a47e-d3dc-44ba-8546-9ef72da84246" />
  </p>

  **Figure 20**: Credits/License page

</div>

Another display of the UI's improvement is the *Settings* page accessed from the main menu (*Figure 21*) and in my Thesis on pg. 56 (*Figure 48*). In the first version there were settings that got completely removed (player's color - since the player now is an animated character). No sound settings were present, because it was added in the second version and the background was blank. 

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/2b426ebc-c89f-4035-8ae2-c5705761598b" />
  </p>

  **Figure 21**: Settings (accessed from main menu screen)

</div>

The levels based on history and mythology try to balance the educational value and enjoyability of the game. In the start and during the level there are texts to explain the context and help players understand the setting (*Figure 22*). After enjoying the beatiful game named [Pentiment](https://www.playstation.com/en-gr/games/pentiment/) which features gorgeous game design and clever use of book animations, I thought I could incorporate a dictionary like book where players could seek important terms. These include significant historical figures, settings or deities. The searchable tearms are unterlined (*Figure 22*) and when clicked upon trigger a search on the dict-like book (*Figure 23*). 

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/7756d23e-4ab8-42e9-89d6-74676cbf252c" />
  </p>

  **Figure 22**: Historical info given before the level starts

</div>

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/39e08a2b-94d9-44c2-a61e-d76c9e089ab4" />
  </p>

  **Figure 23**: Each unterlined word leads to a dictionary search

</div>

All battles come with an explanation of the tactic the players must follow to win (to ensure historical accuracy). I tried to stay as close as I could to how the real-life battles happened, without damaging the user experience.

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/fe76f550-8cfa-4aa5-9cda-b4ec4f451202" />
  </p>

  **Figure 24**: Battle levels come with a plan explanation

</div>

This is how the *Marathon* level of the *History* levels is. The costumes and armors of the soldiers were colored according to what I found out after researching on the topic. For further reading on the topic please read my Thesis from pg. 57 - 59 (Section 5. 2. 10).   

<div align="center">

  <p align="center">
    <img width="625" height="385" alt="Image" src="https://github.com/user-attachments/assets/156aa482-aa72-4812-8c9f-4dceafdba7aa" />
  </p>

  **Figure 25**: Battle level (Marathon)

</div>

If the game seems like fun, please feel free to download and rate the game!  
Honest ratings and criticism is what helped me improve my game further.
