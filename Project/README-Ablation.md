# Ablation Study

* Short summary: Throughout the experiment, we have used the following models:
    * UNet - 10 epochs - 150 classes - 0.01236 score.
    * UNet - 50 epochs - 10 classes - 0.73861 score.
    * Attention UNet - 50 epochs - 10 classes - 1.00579 score.
    * Attention UNet - 125 epochs - 10 classes - 0.74429 score.
    * Attention UNet - 200 epochs - 10 classes - 0.5686 score.
    * DeepLabV3 - 50 epochs - 10 classes - 0.53589 score.
* Attention UNet link: https://www.kaggle.com/code/vladbaranceanu/notebookb109c339e7
* UNet link: https://www.kaggle.com/code/vlapin/notebookb109c339e7
* DeepLabV3 link: https://www.kaggle.com/code/raduapetrii/notebookb109c339e7
* Findings:
    * Attention UNet provides the best results. It also uses the least memory out of all the models tried.
    * In terms of changes that influence the results, the model used plays a primary role in it.
    * None of the architectures would achive good results if trained on CPU. 