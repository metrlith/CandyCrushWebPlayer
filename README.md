# Candy Crush Web Player

![Candy Crush Web Player Banner](<assets/Candy Crush Web Player Banner.png>)

Welcome to the **Candy Crush Web Player**! This player works with the [Candy Crush Level Editor](https://github.com/tp-duolingo/CandyCrushLevelEditor) to allow you to play your custom Candy Crush levels directly in your browser. It is a simple web application built using HTML, CSS, and JavaScript, designed to be easy to use and customize.

## Features

- **Play Custom Levels**: Load and play custom Candy Crush levels created using the Candy Crush Level Editor.
- **Seamless Integration**: Easily import level data from the editor.
- **User-Friendly Interface**: Simple and intuitive design for a smooth gaming experience.

## Requirements

To play the game, you will need a Flash-enabled browser. We recommend using **WaterFox Classic**, but any browser that supports Flash will work.

## Setup Instructions

Follow these steps to set up your environment:

1. **Download WaterFox and Flash**  
   Visit [this MediaFire mirror](https://www.mediafire.com/folder/y4nh28s0yuy0o/WaterFox_%26_Flash_Installers) to download the WaterFox and Flash installers.

2. **Install WaterFox**  
   - Run the WaterFox installer.  
   - During installation, choose **not to import anything** if you don't plan on using it as your main browser.

3. **Install Flash**  
   - Run the Flash installer.  
   - Disable automatic updates to prevent Flash from self-destructing.

4. **Enable Flash in WaterFox**  
   - Open WaterFox and type `about:config` in the address bar.  
   - Search for `plugin.state.flash` and set its value to `2` to enable Flash.  
   - (Optional) Set `plugin.state.flash` to `1` to disable Flash later.

## Usage

Once your environment is set up, follow these steps to create and play custom levels:

1. **Create a Level**  
   - Go to the [Candy Crush Level Editor](https://github.com/tp-duolingo/CandyCrushLevelEditor).  
   - Customize your level by setting the board size, number of moves, candy types, obstacles, and special candies.

2. **Export Level Data**  
   - Use the **Export Level** option to save your level data as a JSON string.  
   - Save the JSON string locally for future use, as levels are not saved in the editor.

3. **Import Level Data**  
   - Use the **Import Level** option to load a previously saved JSON string into the editor.  
   - This allows you to edit or replay your custom level.

4. **Play Your Level**  
   - Use the **Play Level** option to open the Candy Crush Web Player in a new tab and load your level data.

## Notes

- Ensure Flash is enabled in your browser before attempting to play.  
- For security reasons, avoid enabling Flash on untrusted websites.  
- The Candy Crush Web Player does not save levels; always export your level data if you want to reuse it.

Enjoy creating and playing your custom Candy Crush levels!

## Contact

For any questions or feedback, please reach out to the developer:

- **GitHub**: [tp-duolingo](https://github.com/tp-duolingo)
- **Discord Server**: [Candy Crush Level Editor](https://discord.gg/2Zq9tszNBn)
