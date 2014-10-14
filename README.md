####Openmosaic Readme(for the lack of a better name)

Openmosaic uses javascript and nodejs to split up a sketch (html5 canvas thing) into multiple canvases.


####Requirements :

1) Nodejs
2) socket.io node packet [use 'npm install socket.io']
3) A modern web browser that supports html5 (chrome, chromium or firefox)

####How to :

1) 'node server.js' runs the server.

2) Navigate to http://localhost:8000/index.html to see the main sketch. Underlying code is in app.js

3) Go to http://localhost:8000/slave1.html, slave2.html, slave3.html and slave4.html. Make sure each of the slaves are opened in a new window and they are resized to around 400x400 (or less). The slaves, when put together, forms our mosaic.

4) Move mouse over index.html and you will see lines appear on the slaves as well

5) open mosaic calculates the canvas positions of the slaves dynamically. There's a very basic tool to help you decide the order in which the slaves should be put together so that you can see the whole picture. Go to http://localhost:8000/packer_view.html. The page will be blank first. Open a slave in another tab and packer_view.html should show you the arrangement in the form of rectangles

6) Just want to know if this works? Check the screenshots directory
