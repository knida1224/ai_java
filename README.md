# ai_java
Expanded Java aima program
Kyle Nida
Z 23410025
10/28/2018

AI Homework 5

In order to run this program, you need to open you IDE (Eclipse preferred).
With you IDE open, import the zip file AI_HW5 into the IDE. 

After importing the files, you can use them, open them, change them, run them, 
whatever you choose. To run my 15 puzzle program with A* search you must
navigate to the "aima.gui.swing.applications.search.games" folder. Open that
folder (ie. click the drop down arrow) where you will find a file called
"EightPuzzleApp.java". Right click on that file and find the option to 
"Run As", hover over this and navigate to the follow up option called
"1 Java Application". 

Now, the GUI should be open with the options available for searches and
so forth. Here you have the first choice from a set of available, hard-coded
initialized puzzle arrangements or a random arrangement. In the second box
you must click one of the 2 options at the bottom of the list called
"AStar Search(MisplacedTileHeuristic)" or "AStar Search(ManhattanDistance)".
Depending on the choice for initialization, you will see different things.
Three Moves, Medium, and Extreme will run the searches immediatly with
different outputs for each heuristic. However, choosing 'Random' will 
tell you whether or not that found arrangement is solvable or not. If the 
random state is indeed solvable, you simply click 'ok' and the program will
proceed to solve the 15 puzzle. If the random state is found to be unsolvable
the program will output a statement telling you so, which you will then 
click 'ok' then the 'clear' button at the top right of the program GUI. By 
clicking 'clear', a new random state will be found where you will, once again,
be told if that state is solvable or not. Continue until a solvable state
is found. 

By running the program, you will see in the dialog box which moves are being
held as well as a visualization by the blank spot in the 15 puzzle. After the 
program is complete, the path cost(total moves), nodes expanded(total nodes 
searched through), queue size(waiting for each node) and max queue size will
be displayed for an in-depth view of a working A* search with 2 different
heuristics. 

I enjoyed this project very much. It gave me a kickstart to learning Java 
as well as a new knowledge of user interface.
