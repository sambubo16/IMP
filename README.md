## IMP

**IMP** is a thing in Batch for printing images or GIFS, without using any .EXE

### Features

- **Simple Usage**: Just call ByteBat with the URL and desired window dimensions.
- **Customizable**: Easily adjust the browser window's position and size.
- **Lightweight**: Minimal resource usage, making it efficient and fast.

### Usage

To use IMP, simply run the following command:

```batch
call IMP URL_OF_IMAGE x y width height
```
URL: The web address you want to open.
x: The x-coordinate of the window’s position.
y: The y-coordinate of the window’s position.
width: The width of the browser window.
height: The height of the browser window.
Example
```
call ByteBat https://www.example.com 100 100 800 600
```
This command will open the specified URL in a browser window positioned at (100, 100) with a size of 800x600.
