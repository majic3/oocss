## To Do

* Split module skins   
* remove unnecessary directories and files  

## Filestructure Coventions

_Example:_  

\-mod/ {plugin-root}  
+-mod.css {essential CSS}  
+-mod_debug.css {CSS for debugging} 
+-mod_doc.html {Examples and Explanation}  
+-mod_skins.css {all skins that only require pure css, others via @import}  
+-\ skins/ {skins that need more than pure CSS}  
  +-\ photo/ {skin-root}  
    +-photo_skin.css  
    +-img/  
  +-\ flow/ {skin-root}  
    +-flow_skin.css  
    +-img/  

## Ideas for this fork

* Add navigation systems
* Find a process for Producing Selected & Combined Plugins from OOCSS - with semantic output
* Be able to mix n match parts of other frameworks


## Todo for this fork

* Revising navigation system - now looking at Hovecana by Apmyp. My for is at github.com/majic3/hovecana
* completely revise the use of sitemap
* Looking at many by Vladimir Carrer
