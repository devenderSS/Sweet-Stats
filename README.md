
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

In this framework there are horizonttal bar graphs are of three types:

1. Single Valued.
2. Double Valued.
3. Triple Valued.

With each three different sizes:

1. Large
2. Medium
3. Small.

All the graphs are available in five different colors:

1. Pink
2. Blue
3. Black
4. Orange
5. Red

To change these attributes you have to change the class name of main parent div.

Each div inside main graph div represents single entity or element of graph.

Some important points:

1. Data-value( data-one data-two and data-three in double or triple valued graphs ) are percentages which also represents width of bar.
2. You can change the color of graph by changing classes. ex- pink in eamples below.

Here are some examples.

#Horizontal bar graph single-value
Add the following codes to create a horizontal bar graph.There are three sizes - small, medium, large.

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


       
       
