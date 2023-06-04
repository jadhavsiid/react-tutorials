# react-tutorials
React JS Notes

Step-1: To create react app type: 'npx create-react-app (myreactapp)';

Step-2: then go into dir myreactapp by 'cd myreactapp'.

Step-3: Then type 'npm start'.


<b> Remember </b> : 1.) while writing JSX, in order to decalre any tag it is important to decalre it inside a parent ``` <div>, <article>, ``` <React.Fragment> or simply <> tag.
  
  
2.) The way we write 'class' inside a HTML Tag in order to declare it while writing CSS, incase of ReactJs we have to write 'className' as 'class' is an reserved keyword in ReactJs
  
  
3.) Every Tag needs to be closed in ReactJs JSX.
  
  
4.) While writing name of any function write initial of it as capital. Eg: Function


<b> How to remove boilerplate </b> :

1.) In SRC folder: 
- remove 'index.css' and 'app.text.js'
- remove 'app.css'
- remove 'reportWebVitals.js'
- remove 'logo.svg'
- remove 'setupTests.js'

2.) In Public folder: - remove 'logo192.png' and 'logo512.png'.

3.) Delete all the lines of code which comes by default in 'App.js' and use shortcut by writing <b> 'rafce' (react arrow function component with export). </b>

4.) Now go in <b> 'index.js' </b> and remove this line - <b> 'import './index.css'; </b>
and also remove <b> 'import reportWebVitals from './reportWebVitals'; </b>
You're good to go now !!
