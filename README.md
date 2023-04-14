__DEVELOPING A PICTIONARY-STYLE GAME WITH AWS DEEPLENS AND AWS ALEXA__

Just say, "Alexa, play Guess My Drawing with DeepLens," to begin playing. The game's rules are explained by Alexa, who also questions about the number of players. The order of turns is decided by the players.

Each player receives a common word from Alexa. By way of illustration, Alexa might remark, "Your object to draw is bowtie." It must be drawn on a whiteboard in 12 seconds without the use of any letters or words.

When the timer runs out, the player finishes drawing and requests that Alexa reveal the results. The item that you sketched is predicted by the ML model running on AWS DeepLens. Alexa awards 10 points if the object matches the question. No points are awarded if DeepLens does not properly guess the drawing or if the player takes more than 12 seconds to draw.

__ARCHITECTURE DIAGRAM__


![image](https://user-images.githubusercontent.com/87432987/232169983-cf09bca6-2775-4427-818e-fc22748cdbaa.png)
