# questions-placeholder
For hosting the questions and the answers.


1. Your top 3 projects?

A) Video backend integration for the Mstar platform. Gstreamer-based plugin. This allowed the video playback on the device - in the webapplication to take place. It must have behaved correctly - under starting/stopping/seeking the video stream - which also the MSE tests written in Javascript helped to reveal.

B) Jenkins and other relevant infrastructure support for the compilation of the code / automatic integration tests of the code that processed television viewership data.

C) Web camera integration on the MTK android device with the code processing the speakers from the video feed provided by the vendor. Included not only a work with embedded device, but also analysis of 3D data/OpenGL/QT presentation of them.

2. Why did you choose them?

Ad A) Interesting combination of both Javascript (V8) engine in chromium working together with the embedded device. Backend was mostly written in C-style though...

Ad B) Something new for me that allowed myself to get more practice with Docker/docker registries/Jenkins/bash/python/little bit of AWS/databases.

Ad C) Lot of scientific-like problems + usage of more modern C++. Allowed me to practice Android/embedded devices better + get in touch for the first time with running the inference using neural networks on the embedded device.

3. What was the gratifying part for you in them?

Ad. A) That I could make the video to work on the embedded device that was hard to work with in the first place. Also had a chance to do a little bit of assembly code. It kind of interacted nicely with modern web browser engine.

Ad. B) I helped the team to learn the SVN->git migration and prepared their code for the CI/CD + integration tests - besides ordinary, everyday work with their code.

Ad. C) Making the logic of the analyzing speakers data better - plus creating my own gstreamer plugings that affected the streaming processing. Making it to run on android platform + doing 3D positional data analysis was also pretty nice.
