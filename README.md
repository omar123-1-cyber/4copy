## Welcome To ( সহজ সরল সিম্পল ) Assignment - 4 




## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementByid is only for id...when we need to call single line that time we use getElementById....
getElementclassName is for simmilar name...when we need to call simillar class that time we use getElementById.
querySelector is for sinle line like id but not same...when we need to call single line that time we use querySelector.
querySelectorAll is for multiple line ...when we need to call multiple line that time we use querySelectorAll.


### 2. How do you create and insert a new element into the DOM?
 1 document.createElement('tagname') 
2  .innerText বা .innerHTML 
3  parentElement.appendChild(newElement) 
example...
let newDiv = document.createElement('div'); // 
newDiv.innerText = "Hello World";           
document.body.appendChild(newDiv);          

### 3. What is Event Bubbling? And how does it work?
Event Bubbling holo emon ekta process, jekhane ekta child element-e kono event (jemon: click) ghotle, shei event-ti tar parent element-guloteo oporer dike choriye pore.


Eta kivabe kaj kore?
Start (Target): Jokhon tumi kono button-e click koro, tokhon prothome oi button-ti click hoy (eti holo event-er shuru).

Bubbling (Oporer dike otha): Button-ti jekhane ache (dhore nao ekta div-er bhitor), tokhon oi click event-ti automatically oi div-er kache chole jabe.

Hierarchy: Div-er pore jodi aro boro kono parent thake, event-ti sheikhaneo jabe. Ervabe ekdom document porjonto bheshe uthbe.

### 4. What is Event Delegation in JavaScript? Why is it useful?
Event Delegation holo emon ekta technique, jekhane tumi protita child element-e alada kore event listener na bosiye, tader common parent element-e matro ekta event listener bosao.

odaharon hisebe niche liktechi..

document.querySelector('ul').addEventListener('click', function(event) {
  
    if (event.target.tagName === 'LI') {
        console.log("List item clicked: " + event.target.innerText);
    }
});

### 5. What is the difference between preventDefault() and stopPropagation() methods?
. preventDefault()
Kaj: Browser-er "default" behaviour bondho kore.

Example: Ekta link-e click korle browser automatic oi page-e niye jay. preventDefault() dile oi link-e jabe na. Form submit korle page reload hoy, eta bondho korteo lage.

2. stopPropagation()
Kaj: Event-er "bubbling" (uporer dike chora-no) bondho kore.

Example: Ekta button click korle jeno tar parent div-er click event trigger na hoy, shudhu button-er kaj-i hoy—eijonno eta use kora hoy.

---


**Technology Stack:**
- HTML
- CSS (Vanilla/Tailwind/DaisyUI)
- JavaScript (Vanilla)


--- 

## What to submit: 

1. GitHub Repository Link: 
2. Live Site Link: 
