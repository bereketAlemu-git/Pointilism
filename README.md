# Pointilism
## Image Pixel Manipulation with Pygame

This Python script uses Pygame to load an image and manipulate its pixels by drawing circles of varying colors based on the RGB values of each pixel. Each color channel (red, green, blue) determines the number of circles drawn in that color at each pixel location, scaled up by a factor of 5. 

### Usage

1. **Prerequisites**: Ensure you have Python and Pygame installed.
   
2. **Setup**:
   - Save your source image file in the same directory as this script.
   - Run the script with the image filename as a command line argument.

3. **Functionality**:
   - Loads the source image and calculates its dimensions.
   - Scales up the display window accordingly (multiplying by 5).
   - Iterates through each pixel of the image.
   - Draws circles based on the intensity of red, green, and blue at each pixel location.
   - Updates the Pygame display to show the manipulated image.

4. **Closing the Application**:
   - The application window remains open until you close it manually.
   - Close the window to terminate the script.

### Example

For example, if your image file is named `example_image.png`, you would run the script as follows:

```bash
python script_name.py example_image.png

This is from the course 1405 at carleton University
