# Wanez - Rainbow Files

*Filter/Highlighting Utility (Files) for Grim Dawn.*

---

Discord Server: https://discord.gg/y4WtATmMzr

Forum Thread: https://forums.crateentertainment.com/t/tool-rainbow-filter-item-highlighting/42765

---

[TOC]

# 1. What Is This?

A utility for the game Grim Dawn to add colors to item Nameplates on the ground and Tooltips.

# 2. Installation

## 2.1. Download

In the repo you will see a green button ```<> Code```, click on it to open the menu and search at the bottom for ```Download ZIP```. This will download a clone of the repo as ZIP containing a folder ```WanezRainbowFiles-main``` with all Localizations inside. You may also use  [this link to download the cloned repo ZIP](https://github.com/WareBare/WanezRainbowFiles/archive/refs/heads/main.zip).

## 2.2. Setup

<ol>
        <li>After downloading the files.</li>
        <li>Go to your Grim Dawn directory and either open or create (if it doesn't exist) the folder settings, extract/move the text_en for the English files or the text_xx for your Language into that settings folder. (<em><strong>Note:</strong></em> Root directory of the Zip is WanezRainbowFiles-main, I recommend to just open the Grim Dawn\settings folder and drag the text_en from the ZIP into the settings folder.)</li>
        <li>You should end up with 6 *.txt files inside <code>/Grim Dawn/settings/text_en/</code> These files are responsible for changing the colors of Items and Properties in the game. If you wish to play the game without color changes you simply delete those files.</li>
        <li>Start Grim Dawn. (or restart it if the game was running before, the new files need to be loaded in and this only occurs during startup)</li>
    </ol>
    <font color="#50AF50">When the files require an update you must do all these steps again.</font><br />
    You may use either the Grim Dawn install directory or the User Data directory in documents/my games, the choice is yours.<br /><br />
    <details>
    <summary><font color=#50AFAF>Game Directory</font></summary>
    <hr>
        Example Path taken from me: C:\Program Files (x86)\Steam\steamapps\common\Grim Dawn
    <pre>
    |-- Grim Dawn
    	|-- ArchiveTool.exe
    	|-- Grim Dawn.exe
    	|-- settings
    		|-- text_en
    			|-- tags_items.txt
    			|-- tags_ui.txt
    			|-- tagsgdx1_items.txt
    			|-- tagsgdx1_storyelements.txt
    			|-- tagsgdx2_endlessdungeon.txt
    			|-- tagsgdx2_items.txt
    </pre>
    <hr>
    </details>
    <details>
    <summary><font color="#50AFAF">User Data Directory</font></summary>
    <hr>
        Example Path taken from me: C:\Users\Ware\Documents\My Games\Grim Dawn
    <pre>
    |-- Grim Dawn
    	|-- save
    	|-- Screenshots
    	|-- Settings
    		|-- text_en
    			|-- tags_items.txt
    			|-- tags_ui.txt
    			|-- tagsgdx1_items.txt
    			|-- tagsgdx1_storyelements.txt
    			|-- tagsgdx2_endlessdungeon.txt
    			|-- tagsgdx2_items.txt
    </pre>
    <hr>
    </details>

## 3. Potential Problems

### 3.1. Files Are Not Working!

Some windows settings or Windows 11 seem to require the files to be inside the User Data directory, give that documents/my games a try.

### 3.2. Files Did Not Update Properly!

If you downloaded the newly updated files, but your game is not using them, you may have made a mistake updating those files on your computer. Go over all the steps in 2.2. again one by one and be sure you are in the correct folder. Another cause could be you used both possible directories at one point, if that is the case, delete the (outdated) files in the other directory.

