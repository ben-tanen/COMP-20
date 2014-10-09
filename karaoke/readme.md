### Lab #5: Karakoke

#### By Ben Tanen

This lab involves annotating a HTML5 video using Javascript and media events.

In this case, a JS function was called whenever the video time changed (using `addEventListner()`) that checked if it should update the contents of the annotation. The contents was determined using two arrays, an array of when the lyrics should appear and an array of the lyrics themselves.

Currently, the project works in all the ways it is suppose to (lyrics appear when they should). It also shows an entire stanza until clearing it when a new stanza starts. The page also works to annotate if you scrub forward through the video. However, if the user were to pause the video at some point and rewind, the annotation would be out-of-sync. This problem could potentially be solved with a very long if-statement, but I thought the array structure was more efficient.

All of the code was written by Ben Tanen (minor references to Mozilla documentation). Overall, the lab took approximately 30-min.
