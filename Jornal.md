**Date: December 3, 2023.**

**Focus Summary:**
Today, I kicked off the development of my frontend website "happy_birthday" to celebrate Alexis's birthday. The initial focus is on setting up the HTML structure and applying general styles.

**Progress:**
- Created the HTML file with a title, meta description, and links to necessary stylesheets.
- Added a hero section with an image of Dr. Bubbles to set the festive mood.
- Included an introduction section with a catchy title and a description of Alexis's birthday party.
- Added a contact section with details about the event, including the date, time, and location.

**Obstacles:**
Making images flexible presented a challenge. I couldn't simply change the image width to a percentage in CSS because that would affect all images.
The first step was to make our "hero" or top image a discrete div with its own class, and then specify the percentage for that class.
Encountered challenges while implementing media queries to maintain image responsiveness across different screen sizes.
Understanding specificity in CSS rules, especially regarding the hierarchy of conflicting property values, required additional effort.

**Learned:**
Reinforced HTML and CSS skills, especially in structuring a webpage and applying basic styles.
- Adapting images to be flexible requires creating discrete divs with unique classes for individual images.
- Specifying percentages for specific image classes allows for better control over image responsiveness.
- Explored the concept of specificity in CSS, realizing that choices specified farther down the style sheet override those above them.
- Gained insights into using media queries to conditionally apply CSS rules based on screen size, allowing for responsive design.
- Experimented with size conditions in media queries, such as setting a maximum width of 630 pixels to trigger the application of a specific style sheet.
- Emphasized the importance of correctly ordering style sheets to ensure effective cascading and avoid unintended conflicts.

**Code Snippets:**
```html
<!-- HTML -->
<!DOCTYPE html>
<html>
  <head>
    <title>Happy Birthday Alexis!</title>
    <meta name="description" content="Happy Birthday Alexis!">
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/style.css">
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:300,700|Lobster' rel='stylesheet' type='text/css'>
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
  <body>
    <div class="container">
      <div class="hero">
        <img src="images/hero-image.png" alt="Dr.. Bubbles">
      </div>
      <!-- Intro and Contact sections not included for brevity -->
    </div><!--Container-->
  </body>
</html>

/* CSS */
body {
  background: #DDD;
  font-family: 'Open Sans', arial, sans-serif;
}

* {
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

/* Styles for h1 and h2 not included for brevity */

.container {
  width: 100%;
  margin: 100px auto;
  background: #FFF;
}

.hero img {
  width: 100%;
}
```

**Screenshots and Links:**
No screenshots or links at this stage.

**Goals and Milestones:**
- Successfully set up the basic structure and styling for the "happy_birthday" website.

**Challenges and Solutions:**
No significant challenges faced; the process was straightforward.

**New Technologies or Techniques:**
No new technologies or techniques incorporated at this point.

**Feedback and Iteration:**
Awaiting feedback in subsequent entries.

**Personal Reflection:**
Feeling accomplished with the initial setup. Excited to continue building and enhancing the website.
The journey into media queries and specificity was both challenging and enlightening.
It's fascinating how conditional CSS rules can transform the appearance of the website based on screen size.
Toggling between large and small views provided a valuable hands-on experience, ensuring that design elements appear appropriately at different sizes.

**Collaboration and Communication:**
Solo development at this stage, no collaboration involved.

**Future Plans:**
Next session's goal is to add more detailed content, enhance styling, and potentially introduce interactive elements.

