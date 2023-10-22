# Auto Website, Grid, and Carousel
## What I learned/Practiced
I learned how to use a page wrapper and the different ways you can use it to structure your website. I worked with headings, footers, and an image carousel as well. 

### Page Wrapper/Containers
I worked with using a page wrapper for this website. I put all my content (text, pictures, and the image carousel) inside a ```div``` given the ```id="container"```. I then used CSS and selected the ```.container``` to write the CSS for. On the first page, I used multiple divs that would act as different containers to create the grid-like structure, though they all follow the same structure.   
Each container holds both an image and text that both take up 50% or 1 fraction of the webpage. I used the ```1 fr``` value for mine because it was less finicky and was easier for me to work with. I also set up the ```display; grid``` in the CSS by using the different ```div ``` and the ```id``` given to each. The left side got ```div class=left```, while the right got ```div class=right```. This was then used  to create ```grid-template-areas:```
                                                        ```'left''right';```
This was then changed depending on the content shown within the left and the right to better be able to select the different content in CSS to be able to customize each one, as well as create different divs to create the grid in. 

### Header and Footers
I learned that you can select the entire web page in CSS by using the ```*``` selector. You can then use this to set the full width to 100%. This will help fix any problem occurring if the background of the header does not reach each end of the web page completely.
I also learned adding the respective ```top; 0``` or ```bottom; 0``` are is the best way to make the header and footer stay at their respective locations.

### Image Carousel
I also wanted to use an Image Carousel. It was very complicated and frustrating to create one myself, so I modeled mine off of a code pen. I simplified the code a bit by finding some code that I didn't necessarily need, and it also was a little confusing to me. [Link to Code Pen here](https://codepen.io/keefyboooo/pen/waJYMm)

[Vist Site Here](https://giaviolini.github.io/Auto-Website-Grid-and-Carousel/)
