# Personal Blog Website – Lars Burkhardt

Info: I didn't use CSS imports because of the downsides regarding loading time and additional requests, also I used SASS to develop this website.

For the Media Queries I used a mixin, the source: <https://gist.github.com/gpessia/0e1a81c3b75e47ee148e929f0cd7f03c> (also mentioned in `mixins.scss`)

For the naming of class selectors I tried to follow the BEM Syntax.

## File structure
📦udacity-personal-blog-website   
 ┣ 📂css  
 ┃ ┣ 📜styles.css  
 ┃ ┗ 📜styles.css.map  
 ┣ 📂fonts    
 ┃ ┣ 📜pt-sans-v12-latin-700.woff  
 ┃ ┣ 📜pt-sans-v12-latin-700.woff2  
 ┃ ┣ 📜pt-sans-v12-latin-700italic.woff  
 ┃ ┣ 📜pt-sans-v12-latin-700italic.woff2  
 ┃ ┣ 📜pt-sans-v12-latin-italic.woff  
 ┃ ┣ 📜pt-sans-v12-latin-italic.woff2  
 ┃ ┣ 📜pt-sans-v12-latin-regular.woff  
 ┃ ┣ 📜pt-sans-v12-latin-regular.woff2  
 ┃ ┣ 📜pt-serif-v12-latin-700.woff  
 ┃ ┣ 📜pt-serif-v12-latin-700.woff2  
 ┃ ┣ 📜pt-serif-v12-latin-700italic.woff  
 ┃ ┗ 📜pt-serif-v12-latin-700italic.woff2  
 ┣ 📂images  
 ┃ ┣ 📂icons  
 ┃ ┃ ┣ 📜facebook.svg  
 ┃ ┃ ┣ 📜github.svg  
 ┃ ┃ ┣ 📜linkedin.svg  
 ┃ ┃ ┗ 📜twitter.svg  
 ┃ ┣ 📜larsburkhardt.jpg  
 ┃ ┗ 📜the-lucky-neko-uePn9YCTCY0-unsplash.jpg  
 ┣ 📂scss  
 ┃ ┣ 📂components  
 ┃ ┃ ┣ 📜_blockquote.scss  
 ┃ ┃ ┣ 📜_buttons.scss  
 ┃ ┃ ┣ 📜_forms.scss  
 ┃ ┃ ┣ 📜_post-navigation.scss  
 ┃ ┃ ┗ 📜_sidebar.scss  
 ┃ ┣ 📂settings  
 ┃ ┃ ┣ 📜_helpers.scss  
 ┃ ┃ ┣ 📜_mixins.scss  
 ┃ ┃ ┗ 📜_variables.scss  
 ┃ ┣ 📂typography  
 ┃ ┃ ┣ 📜_font-face.scss  
 ┃ ┃ ┗ 📜_typo.scss  
 ┃ ┣ 📜_body.scss  
 ┃ ┣ 📜_content-all.scss  
 ┃ ┣ 📜_content-blogpage.scss  
 ┃ ┣ 📜_content-homepage.scss  
 ┃ ┣ 📜_footer.scss  
 ┃ ┗ 📜_header.scss  
 ┃ ┣ 📜styles.scss  
 ┣ 📜blog-page.html  
 ┣ 📜index.html  
 ┣ 📜prepros.config  
 ┗ 📜README.md  
## Tools used

- Webfonts: [Google Webfonts Helper](https://google-webfonts-helper.herokuapp.com/fonts)
- SASS Compiling: [prepros.io](https://prepros.io)
- Responsive headings with clamp(): <https://fluid-typography.netlify.app/>

## Where did I use Flexbox?

- Header
- Navigation bar
- Newsletter form
- Post navigation (Blog page)

## Where did I use CSS Grid?
- Body (to make sure the footer sticks to the bottom)
- Layout of the page (main area and sidebar)
- Card Grid (Homepage)
- Author info (Blog page)