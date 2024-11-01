## Features

- **Window Management**: Initializes an SDL window with a defined resolution of 1600x700 pixels.
- **Rendering Functions**:
  - `window_color()`: Sets the background color of the window.
  - `rect()`: Draws customizable rectangles with specified position, size, color, and fill options.
- **Text Rendering**: Loads and renders text using `SDL2_ttf`, allowing dynamic text display in the application.
- **Image Loading**: Uses `SDL2_image` to load and render images, supporting a wide range of image formats.
- **Audio Playback**: Integrates `SDL2_mixer` for audio playback, with support for various audio formats, such as WAV and MP3.
- **File Management**: Includes file handling to support saving/loading data, configuration settings, or game states.
- **Timing and Randomness**: Uses time-based functions, potentially to handle animations, create random events, or add gameplay variation.

## Project Structure

The main functions available in this project include:

- **window_color(SDL_Renderer*, int R, int G, int B)**: Sets the background color using RGB values.
- **rect(SDL_Renderer*, int x, int y, int w, int h, int R, int G, int B, int fill_boolean)**: Draws a rectangle at (x, y) with width `w`, height `h`, color (R, G, B), and whether it should be filled or not (`fill_boolean`).
- **load_texture(std::string path)**: Loads an image from a specified path and returns it as an SDL texture.
- **play_audio(std::string path)**: Plays an audio file from a specified path.
- **display_text(SDL_Renderer*, std::string text, int x, int y)**: Renders text to the screen at a specified position.

## Project Extensions

For developers interested in building upon this project, consider the following potential extensions:

- **Animation Support**: Implement smooth animations using SDL's timing functions.
- **Event Handling**: Add keyboard or mouse event handling for interactive features.
- **Game Logic**: Expand into a simple game by adding logic for player movement, scoring, or winning conditions.
- **Save & Load Features**: Utilize file management to save configurations or game progress.


## Screenshots

Here are some visuals demonstrating the project’s features:
![Screen1](https://github.com/user-attachments/assets/dc585ae5-fcc5-4d7c-9792-f8f6467868fc)

![Screen2](https://github.com/user-attachments/assets/ead9997c-72d7-465c-9b72-178c73cb0770)

![Screen3](https://github.com/user-attachments/assets/32571ea7-dc02-4afc-a487-1d89fca56ec8)

![Screen4](https://github.com/user-attachments/assets/0b57b73b-5519-43bc-8faf-87303b2f75b4)
