# Delicious Restaurant Website  
This is my final project using **HTML**, **SCSS**, and **Bootstrap**.  
The website is a restaurant template with many sections like Home, About, Menu, Specials, Events, Chefs and Gallery.

---

## 📁 Project Structure

his project is organized into clear folders to make the code easy to manage and understand:

Root Folder

Contains the main files of the project:

index.html → The main page of the website

package.json → Dependencies and project information

README.md → Project documentation

Public Folder

This folder contains all the assets used in the website:

1. css/

app.css → The compiled CSS file from SCSS

app.css.map → Map file for debugging SCSS

2. images/

All images used in the project:

Product images

Thumbnails

Icons (menu, close, cart, plus, minus…)

Logo and avatar

Design previews (desktop & mobile)

3. Pages/

A folder for extra HTML pages (currently empty).

4. videos/

Contains video files for the project (if used).

Src Folder

This folder contains the source code for styles:

1. Sass/

The main styling folder:

app.sass → The main file that imports all modules

_allModules.sass → Connects all SCSS module files

modules/ → Small SCSS files for each section

Inside modules → landing_page/

_header.sass → Styles for the navigation bar and header

⭐ Summary

Public/ holds everything the browser uses (CSS, images, videos).

Src/Sass/ holds the original styling files before compilation.

index.html connects everything and builds the full page.


Variables & Colors Used

This project uses custom SCSS variables to manage colors and maintain a consistent design. I defined primary, secondary, background, and text colors to make the UI easy to customize and style. These variables help keep the code clean, reusable, and scalable across all components

How to Run

Install dependencies:

npm i bootsrap
npm i bootsrap-icons

Compile SCSS:

sass --watch Src/Scss/app.scss Public/css/app.css



