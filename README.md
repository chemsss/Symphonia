# Symphonia
Intuitive DataViz solution displaying graph oriented data using d3js

<br>

## Installation

The project being just a front-end HTML page using mainly [D3js](https://d3js.org/) and other Javascript libraries, there is no need to install anything.   
However, to be able to import data into the page, you need to host it on a server.
<br><br>
We recommend you using [Visual Studio Code](https://code.visualstudio.com/) and installing the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension. In one click the extension will launch a server (if not taken, on the port 5500) and you'll be able to see the index.html on your web browser using the address http://127.0.0.1:{Port used by Live Server}/index.html .
<br><br>
Alternatively, you can easily set up a server using NodeJS, installable with NPM. We recommend you looking it up if you don't want to use Visual Studio Code.

<br><br>

 ## Usage

When going on index.html, you will be welcomed with a blank page. You can use the footer to import the database of your choice to display the data.   
For now, our solution uses a JSON database that has a graph type format which has the root node and its children stored in it. You can use one of our 2 mock databases stored in the [db](https://github.com/chemsss/Symphonia/tree/main/db) file. These 2 examples are based on what files a person working in a hospital could have in his computer.

![image](https://user-images.githubusercontent.com/61418782/162484943-f0422a54-81f6-4529-a93f-706cd450975e.png)

<br><br>

## Functionnalities

* On the left side of the footer, you can choose in which view you want to display the data  
![image](https://user-images.githubusercontent.com/61418782/162486564-d172ba5b-7071-4caa-a4af-8db22c863851.png)
![image](https://user-images.githubusercontent.com/61418782/162486406-8155ce3b-e585-4551-b8bd-c80892dd9ce0.png)  
<br>  
  
* When putting your mouse on a node, it will highlight its path and display the node's data on the top left panel  
![image](https://user-images.githubusercontent.com/61418782/162487177-02bd5668-72d5-4a93-8148-e74303d67f0b.png)  

* The search bar contains all the node's names. Clicking on one of them will expand the tree if the corresponding node is collapsed and will higlight the node's path and display its information.  
![image](https://user-images.githubusercontent.com/61418782/162487762-ba1c678e-539c-441d-b4f0-a85db87ae2b2.png)
![image](https://user-images.githubusercontent.com/61418782/162487893-6a5b73f2-6668-43ee-9cf8-5ab61adb3c16.png)

* In the circles' view, hovering with the mouse on a circle will display its data on the top left corner and clicking on a circle will zoom on it and show its children  
![image](https://user-images.githubusercontent.com/61418782/162488582-10a20482-c808-40af-a786-c7baae1a4d99.png) 
