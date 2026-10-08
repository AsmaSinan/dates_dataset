DATES AI KIDS DATASET / مجموعة صور تمور لتدريب نموذج ذكاء اصطناعي
===================================================================

Purpose / الهدف
----------------
A small beginner-friendly dataset prepared for a student workshop using Machine Learning for Kids (ML for Kids) and Scratch.
مجموعة صغيرة مناسبة للمبتدئين لتدريب نموذج تصنيف صور خلال ورشة الذكاء الاصطناعي.

Classes / الأصناف
------------------
- Ajwa / عجوة: 20 images
- Medjool / مجهول: 20 images
- Sukkari / سكري: 20 images
Total: 60 images

Why these three?
----------------
They provide relatively clear visual differences in color, shape, size, and texture, which makes a first image-classification activity easier for students. They are also relevant to students in Saudi Arabia.

Source
------
The images were selected from the public “Date Fruit Image Dataset in Controlled Environment” as mirrored in this GitHub repository:
https://github.com/AnasSohailZafar/Date-Fruit-Image-Classification-Using-Deep-Learning

The mirror organizes the images by date variety. Twenty images were sampled across each source class rather than simply taking adjacent images.

Label notes
-----------
- The source folder uses “Mejdool”; this package uses “Medjool”.
- The source folder uses “Sokari”; this package uses “Sukkari”.
- Ajwa retains the source spelling.

Important teaching limitation / ملاحظة تعليمية مهمة
-----------------------------------------------------
These images were captured in a controlled setup with a very similar light/white background and generally a single fruit per image. This is useful for a first successful classroom model, but it can also make the model rely partly on the photography setup rather than only the fruit itself.

لذلك لا يُفترض أن يعمل النموذج بنفس الدقة مباشرة على صور المزرعة أو صور الجوال ذات الخلفيات المختلفة.

Recommended workshop extension
------------------------------
During the farm visit, let students take 5–10 new phone photos of each available variety from different angles and backgrounds. Test the original model on those images, discuss why accuracy changes, then add some real-world images and retrain. This turns dataset bias and generalization into a hands-on learning activity.

Using with ML for Kids
----------------------
Create three image labels/classes in ML for Kids:
1. Ajwa
2. Medjool
3. Sukkari

Upload the images from the matching folder into each class, train the model, and then connect it to Scratch.

Validation
----------
- 20 images in each class
- 60 images total
- All files are readable JPG images
- No exact duplicate files were detected in the selected 60-image subset
- Classes are balanced

Rights / usage note
-------------------
The GitHub mirror README states an MIT license for the repository code, but it does not explicitly state a license for the dataset images themselves. Do not assume the code license automatically applies to the images. Check the original dataset/Kaggle terms before publishing or redistributing the images outside your educational workshop.

See dataset_sources.csv for the source URL of every image.
