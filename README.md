# Incubator First Task
Welcome to the Incubator! The most common problem candidates encounter when completing their first task is rushing through each of the steps. Please read [“The Definition of Completed”](https://exerceo.org/news-completed.php).  Slow down, read all of the instructions and seek to understand before starting.  We strongly suggest slowing down and really reading each line and evaluating the success or failure of those lines before proceeding onward. Did we mention slow down and read…. If you don't hesitate to reach out to a mentor ... after re-reading the document.

## Your First Task Assignment
First make sure you understand what you are being asked to complete. At the end of this task you will have created (Read everything below before starting and ask questions before you start if you do not understand the outcome):

* Choose an image from [Pixabay](https://www.pixabay.com) for your success story that represents you. We recommend downloading the 1920x1208 size. Follow the Image Manipulation instructions to generate the two properly sized images. We recommend using [gimp](https://www.gimp.org/). (hint: scale, then canvas size)
  * First Image
    * Naming Convention is illus-[your name].jpg (note: your image will follow the same naming conventions as the other images already in the repo; just don’t replace an existing image if your name already exists please add the first character of your last name to differentiate it)
    * Size is 720px wide by 300px height
    * Location: this image appears at the top of your individual success story page.
  * Second Image
    * Naming Convention is [your name].jpg
    * Size is 228px wide by 170px height
    * Location: this image will appear on the home page that contains a list of success stories.
* Add your success story to the far left side on the home-page list of three success stories (remove the far right success story). The content for this is in an include found in public/includes/success.php See the production page as an example: https://exerceo.org/ Use your second image from above for this location.
* Add your success story to the full list of success stories. Note leave the very top story (Justin’s Success Story), and add the new story to the top left of the existing list of stories (nobody’s story should be removed or replaced from this page) Use your second image from above for this location.
* Add your full success story
  * Naming Convention: success-story-[first name].php
  * Image: Use your first image from above for this location.
  * Content: write a simple paragraph of what you envision your success upon completing the working groups and incubator. Please do not spend more than 15 minutes on this part of the task.
* Add your success story to the sitemap.xml in the public folder
* Add your success story to the site-map.php in the public folder

# Typical Gotchas (Ensure you test before submitting)
* All special HTML characters must be fixed, for example the quote in the write-up should be `&quot` (See https://en.wikipedia.org/wiki/Character_encodings_in_HTML section on XML Character references)
* When creating the images be sure not to scale the image out of proportion. AKA 	don’t make the person look fatter or skinnier… This is fixed by scaling the image first only using one axis and then changing the canvas size to adjust the other size without changing the look of the image. The second most common problem candidates encounter is in reference to image manipulation. [Here](docs/ImageManipulation.pdf) is a link to a document to help educate you in regards to image manipulation, we highly recommend that you read our document on Image Manipulation