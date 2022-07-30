## Task ((WSI) Medical image related)
Digital pathology has emerged with the digitization of patient tissue samples and in particular
the use of digital whole slide images (WSIs). Image analysis of WSIs (Whole Slide Images),
promises to play an important role in helping the pathologists by indicating potential disease
locations and by aiding their interpretation.

These images are very large therefore problem arises in analysing them as a whole. So
sometimes they are used as a whole or sometimes they are divided into tiles. However, they
cannot be analysed properly further if any pen marks are present on it. Also only the tissue
region in the slide is important. To analyse the fine details, various filters and masks are applied
on it.

Stain color from one laboratory differs from other. Even though they might be of same organ,
same tissue of two images might appear different. Segmentation is used in these images to
localize the object. However, due to very less variations in the images visually, it becomes
difficult to classify objects and localize them.
Data Provided

### Link to Data:
[In pdf]
Data is present in a folder called, assignment data.
Inside that folder first folder is whole slide images, in which two whole slides images are
present.
1. Normal lymph node with an extension of .svs.
2. Reactive lymph node with an extension of .svs.
These can be used for task 1, 2 and 3.
### These are the following tasks that one may need to complete with python. And deep
learning:

1. Break the Whole Slide Image into tiles or patches(must include more tissue content).
2. Perform image processing, such that resultant sample from two slides are visually same.3. Two Slides given are of different categories, one belong to normal lymph node, other
one is Reactive lymph node. They can be differentiated based on name given to slides.

Train an image classification model on these images and show model’s performance
using graphs, comparing true and predicted results.

## NLP Task
Link_to_website [In pdf], a website in which contains all the information about organs, tissue. This
knowledge is of extreme importance for pathologist.
Make a dictionary using Natural language processing from this website such that each organ
name should be the key, and contents present in the organs should be the vaule.
