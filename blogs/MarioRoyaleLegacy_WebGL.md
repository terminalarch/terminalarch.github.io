# Mario Royale Legacy - WebGL Support
<div id="post-date">January 23rd, 2025</div>

Mario Royale Legacy is getting a cool new renderer made from the ground up with WebGL!<br><br>
Why is this important? The HTML 2D canvas uses the CPU more than the GPU, effectively causing a bottleneck with how much performance we can get out of the game.<br><br>
For a while I had been trying to optimize the game loop code, however the main problem had really just been the renderer.<br><br>
Here's a comparison of the level `Mountain Leap` on both renderers. The first part shows the old renderer, and the second part is the new WebGL renderer. We still haven't added culling to the WebGL renderer, and this is how well it's performing!<br>
<video width="100%;" controls>
  <source src="videos/webgl.mp4" type="video/mp4">
</video>
The renderer is still work in progress, and will most likely come in version 7.0, however we also tend to release V7 features on the skintester branch of our game ([here](https://marioroyale.com/skintester)), which already has the unlocked framerate. We will likely push our new renderer to the skintester when we deem it ready, and then ultimately in the major update!