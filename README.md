# Guided-Grad-Cam

First, create needed data in load_data.py
run transform_fetaures()
run toCrossValidation(5)

Second, you need train network for each fold in model.py
run method train(fold) for each fold


In grad_cam.py you can

compute and save GradCam for each image, run
for K_FOLD in range(0, 5):
compute_saliency_for_imgs()

compute and save GradCam for each class with, run
for K_FOLD in range(0, 5):
compute_saliency_for_classes(colormap=True)
