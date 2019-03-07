#### css-meter or Loader (depends on how you want to use it)



css meter gauge optimized for js customization by @codefingers . 

 get more from https://www.cssscript.com/creating-fast-and-responsive-gauges-with-pure-css/


    so this is how it works :
    In the index.html, you'll see a stroke-offset on the path tag, embedded in 
    svg.viewBox

    that shows how far the line grows, 0 (keeps it complete), 630 (eats it completely), 
    1260 (takes it twice over). etc.

    in the css, .progress svg:nth-child(2) path controls the apperance of the bar
     especially the color.

     .progress>li controls the text in the loader the color especially.
