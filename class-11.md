# Class 11 Reading Notes

## Video and Images

When sharing video and images were first getting started on the internet third party plug ins such as Flash were used which came with their own host of issues. Now a days we can simply use the built in video and audio elements in HTML.

With in the `<video>` element you use the src attribute in much the same way you would when you want to reference where an image lives in the `<image>` tag. the Controls attribute is what gives the user the ability to play and pause the video. Just incase the browser does not play the video, tiy can use fallback content which will display what you put inside as an alternative to the video.

### Short story about video and audio

Years ago flash was the only way to bridge between the website and audio video content, but everything changed when the hackers attacked. My brother and I found the new interface via HTML, and although it attributes seem small I believe they can save the world.

## The Grid

The grid in css is a little different from flex boxes like we talked about earlier. When you declare something a flex box you are referencing the things around and in it as you manipulate the boxes. When declaring a grid you are referencing the body and the pre positions inside that grid.
Some important things to remember when declareing grids is:

- `class="item"` Grid items are the children of the grid

- `container` Grid container is the element that the grid is applied to

- `line` Grid line refers to the boundry lines that make up the cells of the grid

## A Responsive Image

Images are important to the content of your page and making an image responsive will help ensure that your site is able to be experienced exactly the way you made it regardless of what is on the clients end. The `<srcset>` will be essentially a bank where you will store all the images you wish the browser to use in different defined scenarios. This is more useful than css because instead of loading the image then manipulating it you ensure the image you want is loaded instead of what you originally have loaded there. Use `<sizes>` to define the conditions you want the browser to look for when chosing the right image to display in the screen.