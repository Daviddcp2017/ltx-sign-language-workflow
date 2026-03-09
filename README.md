Hi everyone,
I’ve been experimenting with LTX 2.3 inside ComfyUI and I modified the original workflow to try something similar to Kling Motion Control.
The idea of my workflow is the following:
• I use a reference image for the character identity
• I use a video of a friend performing sign language
• The system transfers the motion from the video to the character from the reference image
So the final generated video keeps the appearance of the reference image but follows the body and hand motion from the original video.
The results are interesting but not perfect yet.
Currently the sign language gestures are about 80% recognizable, but the hand shapes and finger positions are still not precise enough, which is a problem for sign language.
If anyone has ideas to improve:
• hand accuracy
• finger articulation
• motion fidelity
• LTX parameters
I would really appreciate feedback.
My goal is to eventually use this kind of workflow to generate accurate sign language animation, so improving gesture precision is very important.
Thanks!
