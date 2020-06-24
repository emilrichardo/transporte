
# Bootstrap 4.4.1 Boilerplate - Basic

This is a Bootstrap 4.4.1 Boilerplate with Gulp 4+. Sass, browser-sync.

[Documentation](https://bootstrapstarter.com/bootstrap-templates/template-basic-bootstrap-html/)

![bootstrapstarter](src/img/screenshot.jpg)



How to
Download or clone the repository (git clone https://github.com/wowthemesnet/bootstrap-4-boilerplate.git). After that, from the root of your download/clone:

Install
npm install


If something goes wrong, delete the node_modules folder and run npm install again.

Now let’s make sure you also have Gulp installed globally:

$ npm install gulp -g


Start server
gulp serve


You should see a live browser at http://localhost:3000/.

Development
Override Bootstrap’s variables and create your custom styles

src/scss/style.scss

This will be automatically compiled to src/css/styles.css.

Add custom scripts

src/js/index.js

Partials

You can add partials in src/partials/.

Insert partial : <partial src="header.html"></partial>.

Examples are already added in this this project for header & footer.

Production
gulp
Cmd
If you want HTML, CSS minification & image optimization:

npm run prod
Cmd
Docs folder is the destination. You can now go docs/index.html and check the output.



windows conflicto de proxy

npm config set proxy null 
npm config set https-proxy null
npm config set registry http://registry.npmjs.org/

