# JavaScript-Learning

##Useful Tools and Resources

- [JavaScripting](http://www.javascripting.com/) - The Database of JavaScript Libraries 
- [JS Recipes](http://sahatyalkabov.com/jsrecipes/) - JavaScript tutorials for backend and frontend development. 
- [Jade Syntax Documentation by Example](http://naltatis.github.io/jade-syntax-docs/#attributes) - Even better than official Jade docs. 
- [HTML to Jade converter](http://html2jade.aaron-powell.com/) - Extremely valuable when you need to quickly copy and paste HTML snippets from the web. 
- [JavascriptOO](http://www.javascriptoo.com/) - A directory of JavaScript libraries with examples, CDN links, statistics, and videos. 
- [Favicon Generator](http://realfavicongenerator.net/) - Generate favicons for PC, Android, iOS, Windows 8.

##Recommended Design Resources
- [Code Guide](http://codeguide.co/) - Standards for developing flexible, durable, and sustainable HTML and CSS. 
- [Bootsnipp](http://bootsnipp.com/) - Code snippets for Bootstrap. 
- [UIBox](http://www.uibox.in/) - Curated HTML, CSS, JS, UI components. 
- [Bootstrap Zero](https://www.bootstrapzero.com/) - Free Bootstrap templates themes. 
- [Google Bootstrap](http://todc.github.io/todc-bootstrap/) - Google-styled theme for Bootstrap. 
- [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/icons/) - It's already part of the Hackathon Starter, so use this page as a reference. 
- [Colors](http://clrs.cc/) - A nicer color palette for the web. 
- [Creative Button Styles](http://tympanus.net/Development/CreativeButtons/) - awesome button styles. 
- [Creative Link Effects](http://tympanus.net/Development/CreativeLinkEffects/) - Beautiful link effects in CSS. 
- [Medium Scroll Effect](http://codepen.io/andreasstorm/pen/pyjEh) - Fade in/out header background image as you scroll. 
- [GeoPattern](https://github.com/btmills/geopattern) - SVG background pattern generator. 
- [Trianglify](https://github.com/qrohlf/trianglify) - SVG low-poly background pattern generator. 

##Recommended Node.js Libraries
- [Nodemon](https://github.com/remy/nodemon) - Automatically restart Node.js server on code changes. 
- [geoip-lite](https://github.com/bluesmoon/node-geoip) - Geolocation coordinates from IP address. 
- [Filesize.js](http://filesizejs.com/) - Pretty file sizes, e.g. filesize(265318); // "265.32 kB". 
- [Numeral.js](http://numeraljs.com/) - Library for formatting and manipulating numbers. 
- [Node Inspector](https://github.com/node-inspector/node-inspector) - Node.js debugger based on Chrome Developer Tools. 
- [node-taglib](https://github.com/nikhilm/node-taglib) - Library for reading the meta-data of several popular audio formats. 
- [sharp](https://github.com/lovell/sharp) - Node.js module for resizing JPEG, PNG, WebP and TIFF images. 

##Recommended Client-side Libraries
- [Framework7](http://www.idangero.us/framework7/) - Full Featured HTML Framework For Building iOS7 Apps. 
- [InstantClick](http://instantclick.io/) - Makes your pages load instantly by pre-loading them on mouse hover. 
- [NProgress.js](https://github.com/rstacruz/nprogress) - Slim progress bars like on YouTube and Medium. 
- [Hover](https://github.com/IanLunn/Hover) - Awesome CSS3 animations on mouse hover. 
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/) - Responsive jQuery Lightbox Plugin. 
- [jQuery Raty](http://wbotelhos.com/raty/) - Star Rating Plugin. 
- [Headroom.js](http://wicky.nillia.ms/headroom.js/) - Hide your header until you need it. 
- [X-editable](http://vitalets.github.io/x-editable/) - Edit form elements inline. 
- [Offline.js](http://github.hubspot.com/offline/docs/welcome/) - Detect when user's internet connection goes offline. 
- [Alertify.js](http://fabien-d.github.io/alertify.js/) - Sweet looking alerts and browser dialogs. 
- [selectize.js](http://brianreavis.github.io/selectize.js/) - Styleable select elements and input tags. 
- [drop.js](http://github.hubspot.com/drop/docs/welcome/) - Powerful Javascript and CSS library for creating dropdowns and other floating displays. 
- [scrollReveal.js](https://github.com/jlmakes/scrollReveal.js) - Declarative on-scroll reveal animations. 

##Pro Tips
- When installing an NPM package, add a --save flag, and it will be automatically added to package.json as well. For example, npm install --save moment. 
- Use async.parallel() when you need to run multiple asynchronous tasks, and then render a page, but only when all tasks are completed. For example, you might want to scrape 3 different websites for some data and render the results in a template after all 3 websites have been scraped. 
- Need to find a specific object inside an Array? Use _.find function from Lodash. For example, this is how you would retrieve a Twitter token from database: var token = _.find(req.user.tokens, { kind: 'twitter' });, where 1st parameter is an array, and a 2nd parameter is an object to search for. 


##Reference:
- https://github.com/sahat/hackathon-starter
