![SEO MASTER Logo](https://github.com/fekrh/SEOMASTER/blob/master/img/LOGO.png)

# <h1> Optimize WEB SITE SEO TOOLS
> Google Search Console. Google Search Console is a collection of services you can use to figure out how the search engine views your website. ...
* SEMrush
* BuzzStream. 
* Moz Pro. ...
* Linkody. ...
* Ontolo. ...
* HubSpot's Website Grader. ...
* Google AdWords Keyword Planner.

## <h2> Web Site Opimize Tools Google Sped 
 <b> Developing an SEO-friendly website. At a fundamental level, an SEO-friendly site is one that allows a search engine to explore and read pages across the site. Ensuring a search engine can easily crawl and understand your     

# <h1> GTmetrix Test Web Site Tools
GTmetrix is a free tool that analyzes your page's speed performance. Using PageSpeed and YSlow, GTmetrix generates scores for your pages and offers ...
# <h1> To-Do-List   	
* Make Site Responsive
    * make site responsive using bootstrap
    * support browser html5

* To-Do Main Work 
    * Navbar-Top 
    * Main Header
    * Carousel 
    * Content 
    * Footer
* List File complate 
    - [X] java script
    - [X] Css stylesheet
    - [X] html Pages
    - [X] Responsive Media query 
    - [ ] Testing Files
    - [ ] Google  PageSpeed Insights
    - [ ] GTmetrix | Website Speed and Performance Optimization

# <h1> Custom Style Load Dark Light 
```javascript
//load night mode style
function nightMode(){if(localStorage.getItem('stylesheet')){localStorage.clear();document.getElementById('night-css').setAttribute('href','');}else{localStorage.setItem('stylesheet','/css/night.css');document.getElementById('night-css').setAttribute('href',localStorage.getItem('stylesheet'));}}
document.getElementById('night-mode').addEventListener('click',nightMode)
if(document.getElementById('filter')){document.getElementById('filter').addEventListener('keyup',filterArticles)}
```
```stylesheet
    body{ background: #2d3544; font-family: 'lato' , 'sans-serif';}
a , h1 {color: #ff4444;}
li{list-style: none;}
.img-site{ width: 200px; height: 200px;} .img-p-m{margin-top: 40px;}
::selection{color:whitesmoke; background-color: #ff4444;}
.container{content: "";}
```

# [Requirements & Companents](#Requirements) 	
* [Nodejs](https://nodejs.org/)
* [Gulpjs](https://gulpjs.com/)
* [Sass](https://sass-lang.com/)
* [Browserify](http://browserify.org/)

# [install](#install)
    setup and install Workflow
    open Command Line Tools Mac OS X & past Line by line 
> npm install --save-dev gulp 

> npm install --save-dev sass

> npm install --save-dev Browserify

# <h1> Credits
* [Yasser Hamed](https://github.com/fekrh)
# <h1> License
The MIT License (MIT) - see [LICENSE.md](https://github.com/fatih/color/blob/master/LICENSE.md) for more details
