# FoxFlow - UserChrome Theme for Firefox

Sleek aesthetics of the Arc combined with URL bar an top

## Features:

- **Sleek Aesthetics:** Inspired by the clean look of the Arc browser.
- **Top-Placed URL Bar:** Quick and intuitive navigation for efficiency.
- **Streamlined Interface:** Hides unnecessary elements for a clutter-free experience.
- **Custom Icons:** Material Design Icons are included in this repository
- 
## Known Issues
1. **Inconsistent Styling:**
   - Description: The styling exhibits inconsistencies, particularly when using themes like Adwaita and TokyoNight.
   - Status: Unresolved
2. **URL Identity Border Setting:**
   - Description: The border setting for URL identity in the settings does not take effect.
   - Status: Unresolved
Feel free to start an issue or contribute to resolving these problems. Your input is valuable, and I'll work on addressing these in my free time. Contributions are welcome!

> [!CAUTION]
> It works only in dark theme
>

## Screenshots
Default           |  Themed
:-------------------------:|:-------------------------:
![](https://github.com/p1xlized/FoxFlow/blob/main/Screenshots/1.png )  |  ![](https://github.com/p1xlized/FoxFlow/blob/main/Screenshots/2.png)
![](https://github.com/p1xlized/FoxFlow/blob/main/Screenshots/FoxFlow.gif)  |  ![](https://github.com/p1xlized/FoxFlow/blob/main/Screenshots/gif2.gif)



## Installation Instructions
> [!IMPORTANT]
> I only tested it on my Linux machine, I cannot guarantee that it will work on Windows or MacOS
> 

### Step 1: Download FoxFlow

- Click on the "Code" button on the GitHub repository.
- Choose "Download ZIP" to get the theme files.

### Step 2: Extract the ZIP file

- Extract the downloaded ZIP file to a location on your computer.

### Step 3: Locate your Firefox Profile Folder

1. Open Firefox and type `about:support` into the address bar.
2. Look for "Profile Folder" in the Application Basics section.
3. Click on "Open Folder" to access your profile directory.

### Step 4: Create a 'chrome' folder

- Inside your profile folder, create a new folder named 'chrome' (if it doesn't already exist).

### Step 5: Copy FoxFlow files

- Copy the contents of the extracted 'FoxFlow' folder into the 'chrome' folder.

### Step 6: Enable Custom Themes

1. Open a new tab in Firefox.
2. Type `about:config` in the address bar and press Enter.
3. Promise to be careful if prompted.
4. Right-click anywhere in the preferences and choose "New" > "Boolean".
5. Enter `toolkit.legacyUserProfileCustomizations.stylesheets` as the preference name and set it to `true`.

### Step 7: Restart Firefox

- Close and reopen Firefox to apply the FoxFlow userChrome theme.

## Customization (Optional)

- If you want to customize colors, fonts, or other visual elements, you can do so by editing the userChrome.css file inside the 'chrome' folder.
