# eye_gaze


This study developed an eye-controlled virtual keyboard for differently-abled individuals, enabling text-based interactions through eye movements and blinks. Using TensorFlow and neural networks, the system accurately predicts eye states to operate the keyboard. The study successfully created an efficient solution for the target audience, highlighting the importance of accessible digital technologies and paving the way for future advancements



## REQUIREMENTS:

1.OpenCV (cv2).
2.math (hypot).
3.NumPy (numpy).
4.Dlib (dlib).
5.Pyglet (pyglet).

## flowchart:
![flow chart ](https://github.com/user-attachments/assets/b6b0a50c-ce12-47ad-99cc-eb5c2642d82e)

## EYE POINTS:
![landmarks_points](https://github.com/user-attachments/assets/6678eb7e-aec0-4e6f-8ebf-50c3b0bc54b3)

Left eye points: (36, 37, 38, 39, 40, 41)
Right eye points: (42, 43, 44, 45, 46, 47)


## Eyeblink detection
Eyeblink detection refers to identifying and quantifying the occurrence of blinks in a person's eye movements.

Blinking occurs when:-
Eyelids are closed
Eyeballs are no longer visible
The bottom and upper eyelashes connect

###Results of eye blink model 
![Blink Detection Model](https://github.com/user-attachments/assets/924e1b8c-4ef2-4a43-a1f9-9fea0fb5cba9)

## EyeGaze Detection
Eyegaze detection, also known as eye tracking, is a technology that enables the tracking and analysis of eye movements and gaze direction. Eyegaze detection systems typically use cameras and infrared sensors to capture eye movements, and sophisticated algorithms to analyze the data. The main goal of eyegaze detection is to determine where a person is looking, which can provide valuable insights into their visual attention and cognitive processes. It has various applications in different fields, including human-computer interaction, psychology, neuroscience, market research, and assistive technology.

###Results of eye Gaze model 
![Gaze Detection Model](https://github.com/user-attachments/assets/ab7a7f43-761c-415d-84ad-f0e91a1e2e4a)

## DATA SETS: 
Kaggle eyeblink dataset: https://www.kaggle.com/datasets/nikospetrellis/nitymed.
Eyeblink using CNN: https://github.com/kairess/eye_blink_detector.
Eye gaze data set kaggle: https://www.kaggle.com/datasets/4quant/eye-gaze. 
Gaze tracking library: https://github.com/antoinelame/GazeTracking.



