# Your first deployment

There is no better way to feel like a developer than by actually becoming one, which you do by shipping code. In this lab, you'll be altering the CSS and HTML of a [profile template](http://learn-co-curriculum.github.io/cssi-bootcamp-deploy-on-day-one/) and then deploying it to a brand new repository. Later today you'll learn how to create a new repository on github and push your changes up from your local machine.

Your assignment is to create a student profile for someone else in the CSSI Training program. By the end of this project, every student should have a profile for themselves that was created by someone else and every student should have created a profile for someone else.

We have already created a template, but you need to use your HTML and CSS skills to submit an updated version of the profile with your information. Here we go!

## Requirements

You'll need the following information about yourself:

* Name
* Blog Url (if you have one)
* Twitter URL
* LinkedIn URL
* Github URL
* Tagline
* Profile Picture (something normal, a headshot, of a good reusable size that can be easily cropped)
* Background Picture (like your cover picture from Twitter)
* Previous Work Experience
* Short Bio
* Education

## Structure

The structure of this project looks something like this:

```text
├── README.md 
├── css
│   ├── css style sheets
├── assets
|   |__ img
|   |   ├── lots of images
|   |__ fonts
|   |   ├── some fonts
├── index.html (The profile page)
```

### Files you will need to alter:
  * `index.html`
  * `css/styles.css`
  * `css/custom.css`

## Getting Started

Fork and clone this lab.

#### Add your images

The first thing you'll need to do is add your image assets.

  * Add two pictures to the `assets/img` folder (they can be jpg or png files):
    * A cover picture (named `student-name-cover.jpg` or `student-name-cover.png`)
    * A profile picture (name `student-name.jpg` or `student-name.png`)

#### Add your Profile page

  1. Double-check that you added your cover and profile photo to the `img` directory
  2. Open up `index.html` and modify it with your partners information (links, bio etc).
     * Adding the images is a bit tricky! Take a look at the `css/styles.css` or use inspect element for an idea of where those images come from.

#### Taking stock

Now that you have everything locally, let's take stock of what we have. Take a look at `index.html` in the browser. To do this: 

* If you're working on a Mac, you can just find the file locally using Finder and click to view the webpage in Chrome. 

You may need to cycle a few times until everything looks good. Once you're happy with it, you're ready to submit.

#### Extensions

Once you've had a chance to get your partner's profile page filled out with the correct content, take some time to start messing around with the CSS on the page - change colors, fonts, sizes, and event try some CSS animations. We've created the `custom.css` stylesheet for you to tinker around in. The sky is the limit!

#### Create a Github Repository (Part 2)!

(We'll do this together the first time)

  1. Create a new repository on GitHub
  2. Initialize a git repository for your project (git init)
  3. Add and commit all of your changes (git add ., git commit -m "message")
  4. Push your changes to your GitHub repository (git push)
  5. Create a gh-pages branch to publish your site!
