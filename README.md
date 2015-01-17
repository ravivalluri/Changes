![National LGBTQ Task Force Logo](http://www.thetaskforce.org/wp-content/themes/lgbtq/assets/images/logotype.png)

**Coding at Creating Change - Beginner Level**

## Project Set-Up

Create a new folder for your project.

We need a program to edit text. Download [Sublime](http://www.sublimetext.com/) and open it. There are many text editors available; this is just one that we like.

Create a new folder inside your folder and name it css.

[Bootstrap](http://getbootstrap.com/) is a framework that makes it easier to style your basic webpage. Go to the [Bootstrap website](http://getbootstrap.com/), click download, and then click download Bootstrap. Save it in your downloads folder.

Open the newly downloaded zip file. Open the dist folder, then the css folder. Then copy the bootstrap.css file into your css folder.

Open your project folder in Sublime by right clicking it and selecting open with. In Sublime, you should see your project folder and your css folder.

Using Sublime, create a new file in your project folder by right clicking on the project folder and selecting new file. Name it index.html

Do that again in Sublime to create a new file in your css folder called styles.css

##

Now let's work on your index.html file. Open it in Sublime by clicking it in the sidebar.

First, we have to let your web browser know that this is an HTML file. HTML stands for Hyper Text Markup Language. Let's use an analogy of building a house. The HTML is the structure of the house - the wood, drywall, and the floorplans.

You're about to write your first bit of code! Write

```html
<!DOCTYPE html>
<html lang="en">
</html>
```

Your browser will know that everything between the 2nd and the 3rd line is written in HTML. The `lang="en"` bit tells the browser that the website will be in English, so that if it has built-in translation functionality, it knows what language the website is in. So we're going to write all the rest of our code within what we call the opening `<html>` tag and the closing `</html>` tag.

Now we need to let the browser know where to find supporting files that it will need to properly load the page. We call that section the head.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
  </head>
</html>
```

We'll be adding those within the head. Note that the head tags are indented. We do that to keep the code organized and readable. That way, you can always see what section you're in, and make sure you've closed each section. It's kind of like outline format.

Now let's tell the browser about our supporting files. They're both stylesheets that will help us style this index.html file and can be found in the css folder within our project folder.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="css/styles.css">
  </head>
</html>
```
## Installation

Add it to your Gemfile:

```ruby
gem 'simple_form'
```

Run the following command to install it:

```console
bundle install
```
