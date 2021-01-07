### Practice Questions Answers

1. RGBA value is tuple of four integers (each ranging from 0 to 255) , which correspond to the amount of red, green, blue and alpha in the color.

2. To get the RGBA value of 'CornflowerBlue' from Pillow module we use
   ``` bash
   from PIL import ImageColor
   ImageColor.getcolor('CornflowerBlue','RGBA')
   ```

3. box tuple is a tuple of four integer coordinates that represent a rectangular region in an image. The four integers are, in order, as follows:
   ``` bash
   Left - The x-coordinate of the leftmost edge of the box.
   Top - The y-coordinate of the top edge of the box
   Right - The x-coordinate of one pixel to the right of the rightmost edge of the box.
   Botton - The y-coordinate of one pixel lower than the bottom edge of the box.
   ```

4. Image.open('Zophie.png') function will return an Image object for an image file named zophie.png

5. To find out the width and height of an Image object's image we can use ImageObj.size

6. To get Image object for 100x100 image, excluding the lower-left quarter of it we can use ImageObj.crop((0,50,50,50)).

7. To save Image object after making changes as an image file we can use ImageObj.save('file.png')

8. ImageDraw module contains Pillow's shape-drawing code.

9. ImageDraw objects have drawing methods. We pass the Image object to the ImageDraw.Draw() function to receive an ImageDraw object.
