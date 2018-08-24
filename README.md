# bootsass
Small Framework to build upon Bootstrap responsive utility classes using Sass

Purpose:
  To use Sass to create dynamic utility classes based on the classes already provided by Bootstrap. 
  
Dependancies: 
  Sass. 
  (Bootstrap is not required to use these classes)
  
Documentation:
(All xs classes DO NOT require {up/down})

  FLOAT
    
    pull-{xs/sm/md/lg}-{up/down}-{left/right}
    
  SPACING
  ($i => Any value from 0-100)
    
    margin:      m-{xs/sm/md/lg}-{up/down}-{l/r/t/b/x/y/a}-#{$i} 
    padding:     p-{xs/sm/md/lg}-{up/down}-{l/r/t/b/x/y/a}-#{$i} 
    
    width(%):    width-{xs/sm/md/lg}-{up/down}-#{$i}
    width(vw):   width-{xs/sm/md/lg}-{up/down}-v-#{$i}
    width(auto): width-{xs/sm/md/lg}-{up/down}-auto
    
    height(%):    height-{xs/sm/md/lg}-{up/down}-#{$i}
    height(vw):   height-{xs/sm/md/lg}-{up/down}-v-#{$i}
    height(auto): height-{xs/sm/md/lg}-{up/down}-auto
    
   VISIBILITY
    
    visible:   visible-{xs/sm/md/lg}-{up/down}
    invisible: invisible-{xs/sm/md/lg}-{up/down}
    
   POSITION: 
    
    position-{xs/sm/md/lg}-{up/down}-{static/relative/absolute/sticky/fixed}
    
   TEXT
    
    text-hide-{xs/sm/md/lg}-{up/down}
    
  NOTE:
  For reference on original classes and their uses, please see the Bootstrap Documentation
  https://getbootstrap.com/docs/4.1/utilities/borders/
    
   
