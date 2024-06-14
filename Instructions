
Steps on how to modify the game engine to make your own game below!

TO RUN YOUR OWN CODE YOU WILL NEED TO:

learn to use pony IDE, then:

Paste the source code into pony IDE's code editor, you can edit/make-changes there. https://lua.flaffipony.rocks/
With your code pasted in the PONY IDE editor, click on the blue minify button with the minfy tab open, there should be new minified code in the minifier tab, if the code is bigger than 4000 chars then use the white drop down to switch the level of minification. After the code is minified copy the code and paste it into the stormworks LUA block located within the microcontroller.

TO MODIFY THE 3D MODEL USED BY THE CODE YOU WILL NEED TO:


Learn how to XML edit and use pony IDE, then:

First open the OBJ PARESER that I made specifically for this game engine, you will need to paste the OBJ parser code into PONY IDE.
Since there is a size limit on property texts (4096 when XML edited) you will need to find a small 3D model with a low triangle count.
Once you have your desired low-poly model you will need to convert it to OBJ format, once that is complete open the obj file as text and copy the entire file to your clip-board with CTRL+A then CTRL+C.
Then open the OBJ parser in pony IDE, select the large string and paste your OBJ onto the existing OBJ. After that is complete then you will need to press the blue start button at the top left corner of the PONY IDE webpage.
The script will compile your OBJ Model into a format that can be used by the-game engine. If the console is not open, open it. With the console open, verify that your verticies and faces both say good.
Go into the microcontroller in stormworks and make a copy of the sample_t and sample_v property texts, rename them with your 3D model's name, like Benis_V and Benis_T.. or whatever you want to call it.
After that is completed you will need to XML edit the microcontroller that our game engine runs on. With your favorite text editor open, find the property text that you created by doing CTRL+F and searching for the name that you named the property text. Find the sample text of the property text and copy the text from the OBJ parser. So you copy: "t/faces" text and paste into the Sample_Tinput text box, and for "v/verticies" copy the text from OBJ parser and place it into "Sample_Vinput". After that you will need to go into the code and initialise your model, like this: Benis = {{text2Num("Benis_V")},{text2Num("Benis_T")}} After that you will need to make the game engine draw the model by using the following: projectModel(Benis, {0, 0, 0}, {100, 100, 100}). If the game bluescreens after you complete this make sure the model you are using uses only triangles, some game engine support drawing quads, quads are 4 points instead of 3. Once you have completed that and it works now Great job! Im proud of you! If it didint work.. im very sorry, feel free to modify the OBJ parser to work with your model. if you feel like giving up then.. Go take a long walk and think about what would be the most positivly impactful thing you could do in this current moment to benifit your quality of life.
