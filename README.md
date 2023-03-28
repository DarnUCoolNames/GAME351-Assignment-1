# Game351-Assignment-1
School of Information, University of Arizona 
March 27, 2023

Group Members: 
Teresa Tran
Hannah Klecan
Samantha Jackson
Ian Roach

Required Features:

In this deliverable, the team implements all the required features including the camera following Jammo feature, realistic terrain, trees/foliage, and the Baron's Castle. Some choice features were added including a small village with a graveyard. 

(1: Follow Camera) The camera following Jammo hovers behind the android from a 3rd person perspective. The key bindings to move the android are unchanged from the provided source material and are WASD or arrow keys. When moving around the developed world map, the camera follows Jammo and does not change orientation relative to Jammo. 

(2: Realistic Terrain) In order to create a more realistic terrain, several grass, stone, and dirt textures were added to the project. Additionally, a mountain range surrounds the players' initial position to create a valley where the other game items were implemented. Several paths composed of dirt and stone textures were also added to the main area of the game. 

(3: Trees & Foliage): In the scene, the team added 5 different tree prefabs, as well as a bush prefab. After adding these prefabs to the scene, the team then grouped them together by creating a parent GameObject called "Forest". This parent GameObject acts as a container for all of the tree and foliage prefabs, making it easy to manage and manipulate them as a group.

(4: Baron’s Castle): For the Baron’s Castle there is an outer wall, an inner castle structure, and staircases within the structure leading to a secondary level. All the components of the Baron’s Castle are grouped together within the “Castle” GameObject. In order to improve the aesthetics of the castle, a stone wall texture was added to the project. 

(5: Choice Feature: Village): For our choice feature in this assignment, the team added a medieval-style village to the world where Jammo spawns. Within the village, there are paths, trees, logs, and a small graveyard with a house/church attached to it. The graveyard is also surrounded by a fence to distinguish the location. 

Installation Procedure:
1) Create a blank 3D project in Unity Hub.
2) Allow Unity editor to initialize the project.
3) Add the probuilder package to your project.
3) Save your blank 3D project and exit Unity.
4) Navigate to project directory in file system.
5) Drop the "Assets" folder into this directory.
6) Open and reload the Unity project you created.
7) In the project navigator, go to the assets directory and find the "Scenes" folder.
8) Click on the "Planet959 Scene" to load it.
7) Go to Unity->File->Build Settings and verify that the "Planet959 Scene" is "Scenes in Build" list.
8) If the scene is not in the build list, click "Add Open Scenes". The scene should appear checked. 

Rendering Pipeline: None (Render Pipeline Assist)

Assets Added to Assignment1:
(1)https://assetstore.unity.com/packages/2d/textures-materials/wood/hand-painted-bark-textures-23055
(2)https://assetstore.unity.com/packages/2d/textures-materials/floors/stylized-terrain-texture-153469
(3)https://assetstore.unity.com/packages/2d/textures-materials/glass/stylized-grass-texture-153153
(4)https://assetstore.unity.com/packages/2d/textures-materials/floors/hand-painted-stone-texture-73949
(5)https://assetstore.unity.com/packages/3d/stonewalls-normal-maps-64841
(6)https://assetstore.unity.com/packages/3d/environments/fantasy/spooky-graveyard-pack-156860
(7)https://assetstore.unity.com/packages/2d/textures-materials/floors/free-pack-woden-planks-214610


Credits:
Sample code by Leonard D. Brown, University of Arizona.
This program was developed for educational purposes.

Freeware media assets were used from the following sources:
(1) http://millionthvector.blogspot.com/
(2) https://assetstore.unity.com/
(3) https://www.gameartguppy.com/
(4) https://www.videvo.net/royalty-free-sound-effects/
(5) https://freesound.org/search/


