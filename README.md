# soundcloud-repertoire
Rehearsal web app built in React and interfaced with Soundcloud

## Vision
*soundcloud-repertoire* will record the musician's performance, and the musician will be able to play it back and determine whether it was better or worse than their previous best performance of that particular piece.  If the user deems it worse, this performance will be discarded.  If the user deems it equal to or better, the user will be able to rate their own performance and overwrite their previous best.  

This performance will be stored on Soundcloud along with the user's personal rating and other metadata that includes (but is not necessarily limited to) performance frequency and timestamps.  *soundcloud-repertoire* will use this metadata to determine a *decay rate* which we will calculate using principles of spaced reptition (the less frequently a piece gets overwritten, the higher the decay rate).  In other words, whenever a performance gets overwritten, the rating will start at the user's *specified* rating and will decrease over time in accordance with the calculated decay rate.

With this simple system, the musician will be able to maintain a complete list of their repertoire along with their very best personal recordings.  Therefore, this app will not only keep the musician informed of what they need to practice, but will also provide an invaluable catalog of their music and, perhaps even more importantly, it will keep the musician aware of what they *actually know*.  I believe that most musicians who have played for any significant amount of time can probably only recall a small portion of all the pieces they've learned, and this app could potentially rectify that if the musician stays disciplined about using it.
