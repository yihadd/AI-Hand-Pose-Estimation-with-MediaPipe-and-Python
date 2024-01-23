# AI-Hand-Pose-Estimation-with-MediaPipe-and-Python
![hand pose](https://github.com/yihadd/AI-Hand-Pose-Estimation-with-MediaPipe-and-Python/assets/141911690/e89dec17-bd02-4955-bcf3-1f06f3b3bbc5)
### this project going to do is Hand pose Estimation using Mediapipe so you will be able to use webcam to be able to track all the joints within your hand in real time.


## what we are goning to do?
- installing[ Media Pipe](https://mediapipe.readthedocs.io/en/latest/solutions/hands.html).
- Detecting hand poses.
- Outputting image by[ OpenCV](https://opencv.org).

## 📥Installing Media Pipe
'''pip
![code1](https://github.com/yihadd/AI-Hand-Pose-Estimation-with-MediaPipe-and-Python/assets/141911690/b5e286af-7653-4c77-a83f-d55567be9cef)

## Mediapipe and OpenCV are going to be two core dependency
- Mediapipe >> computer solution >> you able to use hand pose tracking, body pose tracking, facial landmark  tracking etc.
- OpenCV >> open computer vision libraries it allow to work with a webcam amd imagies really well.

## next i will import those independency
![code2](https://github.com/yihadd/AI-Hand-Pose-Estimation-with-MediaPipe-and-Python/assets/141911690/7fa5f74b-12a5-489f-be69-080ff469a69d)

## this is a two media pipe component
![code3](https://github.com/yihadd/AI-Hand-Pose-Estimation-with-MediaPipe-and-Python/assets/141911690/908faed8-c67b-4774-88da-18f88e518817)
- first line >> utils(utilities) drawing utilities just make it easier for us to render all the different landmarks in our hand
- when you get the output from the media pipe >> what you're going to get is a series of landmarks, so there's going to be one landmark for each individual joint in your hand. 👇👇👇
![hand](https://github.com/yihadd/AI-Hand-Pose-Estimation-with-MediaPipe-and-Python/assets/141911690/1f47fd45-b826-40f9-9748-39c6f400a17f)
- landmarks >> each one of these dots, the red dots represent a landmarks so landmark is a joint
- so you can get really specificated on joint tracking for your model
  

