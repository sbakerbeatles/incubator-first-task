# Incubator First Task
Welcome to the Incubator! The most common problem candidates encounter when completing their first task is rushing through each of the steps. Please read [“The Definition of Completed”](https://exerceo.org/news-completed.php).  Slow down, read all of the instructions and seek to understand before starting.  We strongly suggest slowing down and really reading each line and evaluating the success or failure of those lines before proceeding onward. Did we mention slow down and read…. If you have questions, don't hesitate to reach out to a mentor ... after re-reading the document.

## Set up
For this task we recommend using [codesandbox.io](https://codesandbox.io). If you've never used Codesandbox before, it's a great tool for developing, protoyping and testing new technologies in the browser; in the same vein as Jsfiddle or Codepen if you've used those before.

1. Navigate to the [Codesandbox template](https://codesandbox.io/s/interclypseinc-incubator-first-task-060i9) for this project

2. Sign in to the Codesandbox to save your changes (NOTE: If you do not have / or want to make a Github or Google account please get in contact with your mentor).

3. `Fork` the project and **bookmark the page**.

You should be ready to go! Codesandbox has a slight learning curve but if you ever feel like you need to start from scratch just create a new `fork` of the original [template](https://codesandbox.io/s/interclypseinc-incubator-first-task-060i9).

## Your Assignment
First make sure you understand what you are being asked to complete. By the end of this assignment you should have created a new success story page and add a link to your story to the front page of the website.

### Read everything below before starting and ask questions before you start if you do not understand the outcome:

* Choose an image from [Pixabay](https://www.pixabay.com) for your success story that represents you. We recommend downloading the 1920x1280 size. Follow the Image Manipulation instructions to generate the two properly sized images. We recommend using [gimp](https://www.gimp.org/). (hint: scale, then canvas size).
  * First Image
    * Naming Convention is illus-[your name].jpg (note: your image will follow the same naming conventions as the other images already in the repo; just don’t replace an existing image if your name already exists please add the first character of your last name to differentiate it)
    * Size is 720px wide by 300px height
    * Location: this image appears at the top of your individual success story page.
  * Second Image
    * Naming Convention is [your name].jpg
    * Size is 228px wide by 170px height
    * Location: this image will appear on the home page that contains a list of success stories.
  * Upload these images to the `/assets` directory in your Codesandbox project.
* Add your success story to the full list of success stories. Note leave the very top story (Justin’s Success Story), and add the new story to the top left of the existing list of stories (no other story should be removed or replaced from this page). Use your second image from above for this location. See the production page as an example: https://exerceo.org/.
* Add your full success story
  * Naming Convention: success-story-[first name].html
  * Image: Use your first image from above for this location.
  * Content: write a simple paragraph of what you envision your success upon completing the working groups and incubator. Please do not spend more than 15 minutes on this part of the task.
# Typical Gotchas (Ensure you test before submitting)
* All special HTML characters must be fixed, for example the quote in the write-up should be `&quot` (See https://en.wikipedia.org/wiki/Character_encodings_in_HTML section on XML Character references)
* When creating the images be sure not to scale the image out of proportion. AKA don’t make the person look fatter or skinnier… This is fixed by scaling the image first only using one axis and then changing the canvas size to adjust the other size without changing the look of the image. The second most common problem candidates encounter is in reference to image manipulation. [Here](docs/ImageManipulation.pdf) is a link to a document to help educate you in regards to image manipulation, we highly recommend that you read our document on Image Manipulation.

# Upon Completion
When you are finished email the mentor who assigned you the task with a link to your codesandbox.