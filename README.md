# sectexas.github.io
This is the repository for the Student Engineering Council's website. In this README, you will find information on the project structure and how to make any edits you need on the website. 

# Requirements for Installation
You will need the following items in order to run the code on your local machine which is just fancy terminology for saying "your computer".

## Text Editor
You will need to use a text editor in order to edit the code. Download one of your choice. My top 3 recommendations would probably be [VS Code](https://code.visualstudio.com/), [Atom](https://atom.io/), and [Sublime Text](https://www.sublimetext.com/). VS Code and Atom are heavier applications whereas Sublime Text is a little more lightweight. *Note that Sublime Text is a paid-for application, but has a free trial period which can be used forever*. This isn't going to be a comprehensive overview on text editors though, so feel free to find your own and read reviews on them. Some other notable editors include: [Notepad++](https://notepad-plus-plus.org/), [Brackets](http://brackets.io/), and [Vim](https://www.vim.org/) (*Linux and Mac only*).

## Sass
[Sass](https://sass-lang.com/) is a CSS precompiler. Instead of using plain-old CSS to style your websites, Sass can be used to extend CSS to offer greater functionality like variables and other fancy stuff. To install, you can follow [Sass's page to Install Sass](https://sass-lang.com/install). Their directions aren't very clear, so feel free to follow the following directions to install the standalone version of Sass. *Note that these directions may vary depending on your operating system. The following directions are for Windows.*
1. Visit the [Dart Sass Github Page](https://github.com/sass/dart-sass/releases/tag/1.13.0) and download the files for your operating system.
2. Unzip the folder and store it somewhere it will not be deleted.
3. Inside the main folder, there should be another folder called `dart-sass`. Add this folder to your PATH. See [this](https://katiek2.github.io/path-doc/) for help.
4. Once the folder has been successfully added to your PATH, you can use Sass.

# Installation
1. Ensure you have a text editor and Sass on your computer. See [Requirements for Installation](#Requirements-for-Installation) for more information.
2. Open the project in your text editor.
3. Using your terminal, go into the directory of your project and type `sass --watch ./styles/:./styles`. This will watch the `styles` folder for any changes to the Sass files, and compile them into a CSS file that will also be located in the `styles` folder.
4. To see the website locally, you will need to run a local web server. Your text editor may have packages or extensions to automatically do this for you. 
4. Now, you should be able to edit HTML or SCSS files and view the changes

# Project Structure
The project contains several files and folders.

<pre>
sectexas.github.io/
├── assets/
│   ├── images/
│   ├── logos/
├── scripts/ 
└── styles/
    └── bootstrap-scss/
</pre>
sectexas.github.io is the main folder that contains the entire project. All of the HTML files are located in this directory. All of the folders are contained within this directory:
* [assets](.\assets). This folder contains 2 subfolders: 
    * The [images](.\assets\images) folder contains all photographs used throughout the website. 
    * The [logos](.\assets\logos) folder contains all of the logos used throughout the website in SVG format.
* [scripts](.\scripts). This folder contains all of the Javascript files used for this project.
* [styles](.\styles). This folder contains all of the SCSS (Sass) and CSS files used for this project.
    * The [bootstrap-scss](.\styles\bootstrap-scss) folder contains all of the source scss files from Bootstrap.



