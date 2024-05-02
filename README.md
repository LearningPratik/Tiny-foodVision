# Tiny-foodVision
Observations:

* With Data augmentation, model performed well so applying data augmentation is useful.
* With less data deep learning model will overfit, even if the architecture/layers are less.
* With more data it performs well.
* Learning rate and optimizer are very important for model's better and stable performance.
* With high learning rate loss takes big steps and with low value the learning could become very slow
* For this data AdamW (provided by PyTorch) performed well with learning_rate = 0.001.
* More epochs and hidden units also contributed to model's good performance.

Confusion Matrix for the Tiny VGG architecture:

![image](https://github.com/LearningPratik/Tiny-foodVision/assets/139999671/fd0fc022-40d9-4a96-931a-6eb9a131556a)


Created web using Gradio and made some predictions
Average prediction speed is less than 3 seconds.
![image](https://github.com/LearningPratik/Tiny-foodVision/assets/139999671/caff96ba-2d86-442b-8048-89fa44c40438)
![image](https://github.com/LearningPratik/Tiny-foodVision/assets/139999671/4e8d45be-207b-41be-b531-dc08def2ca2c)
![image](https://github.com/LearningPratik/Tiny-foodVision/assets/139999671/ce977315-ad2b-40ac-bc26-61fc49c4106d)
