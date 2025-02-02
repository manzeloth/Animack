<div align="center">
 
 <a href="https://github.com/Torrex123/Animack/">
    <img src="src/img/Animack-Logo-400x80.png" alt="Animack - Anime & Manga tracker">
 </a>

 # Animack

 <h4>
   Keep track of your anime & manga shows.a
 </h4>

 [![GitHub](https://img.shields.io/badge/by-giusgo-green)](https://github.com/giusgo)
 [![GitHub](https://img.shields.io/badge/by-Torrex123-green)](https://github.com/Torrex123)
 [![Framework](https://img.shields.io/badge/framework-pywebview-blue)](https://pywebview.flowrl.com/)
 [![Python Version](https://img.shields.io/badge/python-%3E%3D3.10.4-blue)](https://www.python.org/downloads/release/python-3104/)
     
</div>

## Demo

[![Demo](demos/demo.gif)](https://github.com/Torrex123/Animack/)

## Overview

### What Animack does (functional requirements)

It will provide you with basic functionalities of an anime & manga app tracker. It will:

1. `Search` for a anime or manga given a specific or general title.
2. Give you the option to `add the show` to your list.
3. Give you the ability to `edit`/`track` your progress on a show manually in 'My List' section.
4. Give you the option to `rate` the selected show on a scale of 10.
5. And finally, your list is saved on a sigle file which you can `export` and save elsewhere or `import` another file.

### Class diagram

<div align="center">
  
<img src="Uml.png" alt="Animack UML" style="width: 80%;"/>
 
</div>

## Installation

### Source code

We highly recommend using <a href="https://pyinstaller.org/en/stable/index.html">pyinstaller</a> to make the executable for your system. Read their manual to know how to bundle a Python application and all its dependencies (see <a href="https://github.com/Torrex123/Animack/blob/main/requirements.txt">requirements.txt</a>).

<b>NOTE:</b> Make sure to add the <a href="https://github.com/Torrex123/Animack/tree/main/src">src</a> folder to the executable path in such a way it can read the files it needs to display.

### Pre-built binaries

#### Windows

Get the latest version of <a href="https://www.python.org/">Python</a>. After that, go to the <a href="https://github.com/Torrex123/Animack/releases">releases page</a> and download the latest version of the windows build package (`Animack_vx.xx_windows-build.zip`). Finally, unzip the folder and execute `Animack.exe`.

#### Linux

All the dependencies and bundled inside the application's folder, so just open a terminal and follow the instructions.

+ Download the file:
  + Arch-based distros:
  ```bash
  wget https://github.com/Torrex123/Animack/releases/download/v1.02/Animack_v1.02_arch-linux-build.tar.xz
  ```
  + Ubuntu-based distros:
  ```bash
  wget https://github.com/Torrex123/Animack/releases/download/v1.02/Animack_v1.02_ubuntu-linux-build.tar.gz
  ```

+ Decompress the downloaded file:
```bash
tar -xf 'file_name'
```

+ Change to the decompressed directory:
```bash
cd 'folder_name'
```

+ Change permissions to the executable file:
```bash
chmod +x Animack
```

+ Execute the file (in the same folder):
```bash
./Animack
```

## Getting started

### Searching

This is the most basic function of the app. You can search for any anime or manga.

<div align="center">
<img src="demos/search.png" style="width: 90%;"/>
</div><br/>

Use the search bar tool to look for some show in specific.

<div align="center">
<img src="demos/search-bar-tool.png" style="width: 90%;"/>
</div><br/>

If you click any of the results, you may be able to see more info about it and an option to add it to your list.

<div align="center">
<img src="demos/more-info.png" style="width: 90%;"/>
</div>

### Your list

Besides searching for shows and manga, you can add them to your list.

<div align="center">
<img src="demos/my-list.png" style="width: 90%;"/>
</div><br/>

You can track the progress of each individual show or give it a personal score.

<div align="center">
<img src="demos/list-element.png" style="width: 70%;"/>
</div><br/>

Also, you have a recommendation button which gives you some recommendations based on the shows you have on your list.

<div align="center">
<img src="demos/recommendations.png" style="width: 50%;"/>
</div>

### Configuration

Through this menu you can establish you preferences related to the content displayed in the application when searching. Also, you can import an existing list, export the current or delete it.

<div align="center">
<img src="demos/config.png" style="width: 90%;"/>
</div>
