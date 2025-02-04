# davidlacerda

Using NPM:

# Install dependencies
$ npm install

# Listen to changes in CSS Preprocessor files ( SASS files )
$ npm run compile:scss
Once you run npm run compile:scss, then open the index.html inside your favorite browser or using the live server extension.


Step 1 - STYLES
Make sure you have started the SASS to CSS compilation by running

$ npm run compile:scss
Change the color theme of the website.

Go to sass/abstracts/_variables.scss and change the value of this sass variable called $themeClrPrimary to your preferred HEX color.

// Default value
$themeClrPrimary: #0062b9;


Step 2 - Homepage
Go to /index.html and fill your information, there are 6 sections:

Header of Homepage
On .header__logo-img, Add your own Image, Better if the background of the image is transparent so the background can match the theme color. To remove the background of your image, you can visit remove.bg where you can upload your image and it will remove the background of it.
On .header__logo-sub, Add your own Name.