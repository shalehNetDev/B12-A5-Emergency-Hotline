# B12-A5-Emergency-Hotline



1\. What is the difference between \*\*getElementById, getElementsByClassName, and querySelector / querySelectorAll\*\*?

Ans: we can grab html id's by getElementbyID, we can grab all the classes by getElementByClassName, we can grab the first element by querySelector inside a given css section, we can grab the all elements by querySelector inside a given css section



2\. How do you \*\*create and insert a new element into the DOM\*\*?

Ans: at first we create like this : let x = document.CreateElement('p');

&nbsp;				x.textContent='Very beautiful potol';

then grab the parent: let Parent = document.getElementById('parent);

then append it like : Parent.appendChild(x)





3\. What is \*\*Event Bubbling\*\* and how does it work?



Ans: event bubbling is finding the parent div from child div's

it works like : let parentDiv = callButton.closest('.card');

&nbsp;          	let findHeader = parentDiv.querySelector('.callingHeader').innerText;

&nbsp;          	let CallingNumber = parentDiv.querySelector('.callingNumber').innerText;

&nbsp;          	alert('Calling to...... ' + findHeader +" "+ "("+CallingNumber+")");

here I first found the parent div by a class, then find another class which is the child of this parentdiv and then manipulate it.



4\. What is \*\*Event Delegation\*\* in JavaScript? Why is it useful?

ans: I found it like when we write re usable code/function for completeing several task with onle block of code that is called event delegation. 
It is very usefull while there is lot of section perform similar kind of tasks then we can complete those by creating reusable codes. 



5\. What is the difference between \*\*preventDefault() and stopPropagation()\*\* methods?

Ans: preventDefault can manipulate browser's default behaviors

stopPropagation stops bubbling. if there is a button inside a div, normally browser hit the div at first and then trigger the button, but with stopPropagation 

only button can be triggerd without div. 



