Original by Brackeys : https://www.youtube.com/watch?v=CE9VOZivb3I

MAUNAL :

0. Create an empty named "levelLoader". We'll work in it.

1. Create a canvas.

2. Scale with screen size.

3. Create an image, re-size it to the width of the canvas and set its color (black).

4. Add a Canvas Group to your canvas.
This allows us to change the alpha of an entire group.

5. Create a new animator on your Canvas "crossfadeEnd".

6. Turn on the recorder mode, go to 1:00 and set the Alpha value in the component Canvas Group to 0.

7. Copy the animator keys. (to paste in other anim)

8. Create a new anim "crossfadeStart", and paste the keys.  Then, revert them (the keys of 0:00 to goes to 1:00, and 1:00 to 0:00).

9. In the animator, make a transition crossfadeEnd --) crossfadeStart with a new parameter "start" (bool).

10. Disable exit time of transitions and set transition duration to 0.

11. Add a script to your levelLoader (at the top of the inspector, the scene's name) named "levelLoader".

12. Copy&Paste the code in the github repo.

13. Prefab the levelLoader.

14. Done, enjoy !