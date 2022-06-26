# react-simple-todo-app
This app is developed to learn the basics of portals and ref's  in react

# React portals
Portals needs two things:
1) You need a place you want to port the component to.
2) Let that component know it should have portal to that place.
To mark that place we got to index.html file, add a div with id.

# useRef
They allow us get access to other DOM elements n work with them.

How do refs work?<br/>
With refs we can set up connection b/w a HTML element which is being rendered in the end & our other Javascript code.<br/>

What does useRef return & what value it takes?<br/>
It takes default value you wanna initialize it to, it returns value which allows us to work with that ref later.

If you just eant to read a value refs are probably better than state.
