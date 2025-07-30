# Joker - A Hyprland Theme

*"Why so serious? Introduce a little anarchy to your desktop."*

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0d42213-e02b-4caf-a4fa-5218c1570cdd"
       alt="Joker Theme Preview 1"
       style="border-radius: 12px; border: 1px solid #ccc; width: 500px; margin: 10px; box-shadow: 0 4px 14px rgba(0,0,0,0.1);" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2dc56281-ea9c-4382-ac04-1a122607191d"
       alt="Joker Theme Preview 3"
       style="border-radius: 12px; border: 1px solid #ccc; width: 500px; margin: 10px; box-shadow: 0 4px 14px rgba(0,0,0,0.1);" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/117a0a73-5bb2-4336-87dd-a3568ce653db"
       alt="Joker Theme Preview 2"
       style="border-radius: 12px; border: 1px solid #ccc; width: 500px; margin: 10px; box-shadow: 0 4px 14px rgba(0,0,0,0.1);" />
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/ac3efc63-a998-47e1-86a9-26639caa34c5"
       alt="Joker Theme Preview 4"
       style="border-radius: 12px; border: 1px solid #ccc; width: 500px; margin: 10px; box-shadow: 0 4px 14px rgba(0,0,0,0.1);" />
</p>


### Description

This theme plunges your desktop into the chaotic and fractured mind of the Clown Prince of Crime. Inspired by the gritty, anarchic aesthetic of the Joker from the iconic 2008 film and the dark, melancholic atmosphere of the 2019 masterpiece, this theme is for those who find beauty in chaos.

The color palette is a carefully crafted descent into madness: deep, unsettling purples and vibrant, toxic greens clash with blood-red highlights, all set against a dark, Gotham-inspired background. It’s designed to be immersive, stylish, and just a little bit insane.

### Features

-   **Hyprland:** Custom borders with red/black gradients, increased blur, and shadows.
-   **Kitty Terminal:** A dark theme with Joker's signature colors.
-   **Rofi Launcher:** A sleek, centered launcher that asks the only question that matters: "Why so serious?"
-   **Waybar:** A stylish bar with a subtle gradient and sharp, readable modules.
-   **Kvantum:** Ensures your Qt applications (like Dolphin) don't escape the madness.
-   **Custom Font:** Includes the "Gothic Joker" font for the complete experience.
-   **Wallpapers:** A curated collection of high-quality Joker wallpapers.

### Installation

1.  **Clone the Repository**
    Clone this repository to your local machine.
    ```bash
    git clone [https://github.com/YOUR_USERNAME/hyde-joker-theme.git](https://github.com/YOUR_USERNAME/hyde-joker-theme.git)
    ```

2.  **Copy Theme Folder**
    Copy the `Joker` folder into your Hyprland themes directory.
    ```bash
    cp -r Joker ~/.config/hypr/themes/
    ```
    *(Create the `themes` directory if it doesn't exist.)*

3.  **Activate the Theme**
    Add the following line to the end of your `~/.config/hypr/hyprland.conf`:
    ```
    source = ~/.config/hypr/themes/Joker/hypr.theme
    ```

4.  **Activate Other Components**
    -   **Kitty:** Add `include ./themes/Joker.conf` to your `kitty.conf` after copying `Joker/kitty.theme` to `~/.config/kitty/themes/Joker.conf`.
    -   **Waybar:** Add `@import "themes/Joker.css";` to the top of your `style.css` after copying `Joker/waybar.theme` to `~/.config/waybar/themes/Joker.css`.
    -   **Rofi:** Copy `Joker/rofi.theme` to `~/.config/rofi/themes/Joker.rasi` and select it in your Rofi config.
    -   **Kvantum:** Copy the `Joker` folder from `Joker/kvantum` into `~/.config/Kvantum/`. Then, open Kvantum Manager and select "Joker" from the theme list.

5.  **Install Font**
    Copy the font from the `Joker/fonts` directory to `~/.local/share/fonts/` and run `fc-cache -fv` in your terminal.

### Credits

-   **Theme created by:** Ali Asghar Fathikhah
-   **Built for the HyDE Project.**

---
