FIRST OFFER
1. 6-12 months of experience (projects that people use)
2. core JS and React knowledge
3. interview experience
4. accurate resume and CV
   4.1 not mention knowledge level, as I don't outline it and may became a middle at the first attempt
5. work on mistakes after interviews

APPLICATION OF JS
1. multi page applications
2. single page applications
3. games
4. mobile apps
5. desktop apps
6. server applications 
7. command line applications
8. micro controllers

WHAT IS JS?
1. interpreted (not translated in other programming languages)
2. single thread (compiles only one function per time)
3. loosely typed (variables change its types depending on value)
4. multi paradigm (multiple styles of programming including object-oriented, functional, imperative and declarative)
5. cross platform (is compiled on both client and server sides)
6. automatic memory management (interpretator manages memory and cleans it up using garbage collector)

PAGE RENDERING
- rendering engine
masters html&css and renders them on the page. the mechanism has all the elements to render the page from html to screen pixels
- js engine
compiles js code and use compilation mechanisms to boost effectivity 

1. document receivement
browser send a request on server to get the page and server answers with html document
2. DOM (document object model) creation
is formed from the received html document. html elements form a tree that represents elements hierarchy in the code
3. CSSOM (css object model) creation 
browser sends a request on styles file that was found while creating DOM, creates CSSOM based on the file received and forms a similar tree
4. render tree 
a hybrid of DOM and CSSOM that only contains displayed elements and doesn't render the ones absent in either DOM or CSSOM with invisible elements like display: none; 