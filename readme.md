check out http://www.oakvillelandscaping.com
or https://todd-demone.github.io/oakville-landscaping-latest/index.html

I. OVERVIEW OF BUILD PROCESS
1. compile Sass (src/dummy.scss) to CSS (dist/dummy.css)
2. handle browser's vendor prefixes (dist/dummy.css)
3. minify the CSS (dist/dummy.css) to (dist/dummy.min.css)

II. COMMAND LINE
mkdir ~/sites/npmbuild && cd ~/sites/npmbuild 
npm init -y
npm i -D autoprefixer clean-css-cli node-sass postcss-cli
npm i bootstrap jquery popper.js

III. DEPENDENCIES
1. node-sass
2. autoprefixer
3. postcss-cli
4. clean-css-cli
5. bootstrap
6. jquery
7. popper.js

IV. DIRECTORY STRUCTURE
npmbuild/
	dist/
		css/
			dummy.css
			dummy.min.css
		images/
		index.html
	node_modules/
	src/
		dummy.scss
package.json
readme.md

V. BUILD COMMAND
npm run build (no watch)