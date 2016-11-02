
# Sweet-Stats
A simple and beautiful graph framework for your web-pages.

#Get-Started
Include jquery.js, sweet-stats.js and sweet-stats.css to you html.

>

    <head>
      <script src="/path/sweet-stats.js"></script>
      <script src="/path/jquery.js"></script>
      <link rel="stylesheet" href="/path/sweet-stats.css"/>
    </head>


#Horizontal bar graph single-value
---> Add the following codes to create a horizontal bar graph.There are three sizes - small, medium, large.
>
    //small          
    <div class="horizontal-bar-small pink" data-title="progress">
         <div class="horizontal-bar-element" data-name="India" data-value="40"></div>
         <div class="horizontal-bar-element" data-name="Pakistan" data-value="20"></div>
         <div class="horizontal-bar-element" data-name="Iran" data-value="29"></div>
         <div class="horizontal-bar-element" data-name="Saudi Arabia" data-value="4"></div>
    </div>
    //medium
    <div class="horizontal-bar-medium pink" data-title="health" >
        <div class="horizontal-bar-element" data-name="India" data-value="40"></div>
        <div class="horizontal-bar-element" data-name="Pakistan" data-value="40"></div>
        <div class="horizontal-bar-element" data-name="Iran" data-value="29"></div>
        <div class="horizontal-bar-element" data-name="Saudi Arabia" data-value="4" ></div>
    </div>
     //large
    <div class="horizontal-bar-large pink" data-title="Education">
        <div class="horizontal-bar-element" data-name="India" data-value="40"></div>
        <div class="horizontal-bar-element" data-name="Pakistan" data-value="40"></div>
        <div class="horizontal-bar-element" data-name="Iran" data-value="29"></div>
        <div class="horizontal-bar-element" data-name="Saudi Arabia" data-value="4"></div>
    </div> 
#Horizontal bar graph double-value
>
    //small         
    <div class="horizontal-double-small pink" data-title="health" data-legend-one="medical" data-teo="natural">
       <div class="horizontal-double-element" data-name="India" data-one="40" data-two="100"></div>
       <div class="horizontal-double-element" data-name="Pakistan" data-one="40" data-two="10"></div>
       <div class="horizontal-double-element" data-name="Iran" data-one="29" data-two="35"></div>
       <div class="horizontal-double-element" data-name="Iraq" data-one="4" data-two="86"></div>
    </div>
    //medium
    <div class="horizontal-double-medium pink" data-title="health" data-legend-one="medical" data-teo="natural">
       <div class="horizontal-double-element" data-name="India" data-one="40" data-two="100"></div>
       <div class="horizontal-double-element" data-name="Pakistan" data-one="40" data-two="10"></div>
       <div class="horizontal-double-element" data-name="Iran" data-one="29" data-two="35"></div>
       <div class="horizontal-double-element" data-name="Iraq" data-one="4" data-two="86"></div>
    </div>
    //large
    <div class="horizontal-double-large pink" data-title="health" data-legend-one="medical" data-teo="natural">
       <div class="horizontal-double-element" data-name="India" data-one="40" data-two="100"></div>
       <div class="horizontal-double-element" data-name="Pakistan" data-one="40" data-two="10"></div>
       <div class="horizontal-double-element" data-name="Iran" data-one="29" data-two="35"></div>
       <div class="horizontal-double-element" data-name="Iraq" data-one="4" data-two="86"></div>
    </div>
#Horizontal bar graph triple-value
>

    //small
    <div class="horizontal-triple-small pink" data-title="health" data-legend-one="medical" data-legend-two="natural" data-legend-three="chemical">
        <div class="horizontal-triple-element" data-name="India" data-one="40" data-two="100" data-three="20"></div>
        <div class="horizontal-triple-element" data-name="Pakistan" data-one="40" data-two="10" data-three="20"></div>
        <div class="horizontal-triple-element" data-name="Iran" data-one="29" data-two="35" data-three="20"></div>
        <div class="horizontal-triple-element" data-name="Iraq" data-one="4" data-two="86" data-three="20"></div>
    </div>
    //medium
    <div class="horizontal-triple-medium pink" data-title="health" data-legend-one="medical" data-legend-two="natural" data-legend-three="chemical">
        <div class="horizontal-triple-element" data-name="India" data-one="40" data-two="100" data-three="40"></div>
        <div class="horizontal-triple-element" data-name="Pakistan" data-one="40" data-two="10" data-three="40"></div>
        <div class="horizontal-triple-element" data-name="Iran" data-one="29" data-two="35" data-three="40"></div>
        <div class="horizontal-triple-element" data-name="Saudi Arabia" data-one="4" data-two="86" data-three="40"></div>
    </div>
    //large
    <div class="horizontal-triple-large pink" data-title="health" data-legend-one="medical" data-legend-two="natural" data-legend-three="chemical">
        <div class="horizontal-triple-element" data-name="India" data-one="40" data-two="100" data-three="40"></div>
        <div class="horizontal-triple-element" data-name="Pakistan" data-one="40" data-two="10" data-three="40"></div>
        <div class="horizontal-triple-element" data-name="Iran" data-one="29" data-two="35" data-three="40"></div>
        <div class="horizontal-triple-element" data-name="Saudi Arabia" data-one="4" data-two="86" data-three="40"></div>
    </div>
#Important Notes
1. All data-values are in percentages
2. You can use a wrapper div to allign graph on your page

       
       
