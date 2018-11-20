# Gocase - Digital Image Processing Challenge

First of all, thank you very much for accepting our challenge. Here at Gocase, we value the ability to deliver simple, elegant and functional code. When working with digital image processing, it's also important to have in mind that performance is an important aspect of the code. Our small challenge tries to identify if you have the abilities we value to join our Engineering Team.

## Background

Here at Gocase, most of our products are **customizable** with our clients' preferences. That's one of our main selling points and greatest differential. One important aspect related to this approach is to let our clients know what they're buying and let them know if it fits their expectations. To do that, we need to generate a **preview** of the product, including the desired customization.

If you look at our website, you can see that, for any of our customizable products, there's a near real-time preview of the product with the client's customization. That's useful to manage expectations and to let the clients know if that's what they're looking for.

![Website Customization](/website_customization.png)

## Problem Description

Your challenge is to create a simple **command-line application** that can receive a product's image and customize it. You can use **any language** you wish as long as solve the problem with a **good performance**.

### Input

Your application expects the following inputs:

- A product's image (in jpg).
- A font (in ttf).
- A font size.
- A name.
- Pixel coordinates (x, y).

Do the application interface for the inputs as you wish, it can work using **command-line arguments** or any other method. Don't forget to document how to use it.

### Expected Output

The output of the application must be a **new image file** that will use the product's image as the base image, with the given name plotted at the given position (x, y). The font used and the font size are passed as parameters to the application. Use your best judgment to decide your implementation and minor details.

### Example Files

To help you in your challenge, you can also find in this repository a few images of Gocase products and fonts that we also use.

## Additional Questions

After finishing to build your solution, take a good look in your creation and imagine you're going to expand it with some new features. Answer those questions with a small and concise paragraph:

1. Some Phone Cases may have cameras, buttons and other artifacts that can't be covered by the customization. What would you do to avoid that a customization would be plotted on top of one of those artifacts? A customization may be a name, but it can also be a picture or another complex element choosen by the client.

2. Some people have small names and it would be interesting to use a larger font size. But other people have large names and it would be interesting to use a smaller font size. What would you change to handle this situation?

3. Sometimes there's a problem with the generated preview. The colors seen by the client in his screen may be quiet diffent from the colors that come out of the printers. What would you do to handle the variation in colors between preview and printed product?

## How can I submit it?

Create a git repository with your solution and texts and give us the path to access it. It can be a public GitHub repository or something else if you prefer. If for some reason you didn't have enough time to complete all the requirements, add a brief description of how would you handle the missing features.

## What is under evaluation?

- Does the solution satisfy the requirements and it works correctly?
- How did you designed your solution? Is it organized?
- Is your code easy to understand?
