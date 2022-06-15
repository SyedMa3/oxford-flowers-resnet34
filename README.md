# oxford-flowers-resnet30

Using a pretrained ResNet 34 and train on the Oxford Flowers dataset. Used image transforms.

I used batch size as 8 after trial and error.

**Transformations used:**

*    RandomResizedCrop(224)
*    RandomHorizontalFlip()

**Val Accuracy:**

* lr = 0.01 &rarr; Accuracy = 0.92
* lr = 0.05 &rarr; Accuracy = 0.84

**Test Accuracy:**

* lr = 0.01 &rarr; Accuracy = 0.88
* lr = 0.05 &rarr; Accuracy = 0.80
