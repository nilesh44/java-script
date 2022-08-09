# Events are actions that take place in the browser that can be initiated by either the user or the browser itself. Below are a few examples of common events that can happen on a website:

   * The page finishes loading
   * The user clicks a button
   * The user hovers over a dropdown
   * The user submits a form
   * The user presses a key on their keyboard
   * An event is something that happens when user interact with the web page, such as when he clicked a link or button, entered text into an input box or textarea, made selection in a select box, pressed key on the keyboard, moved the mouse pointer, submits a form, etc. In some cases, the Browser itself can trigger the events, such as the page load and unload events.
* By coding JavaScript responses that execute upon an event, developers can display messages to users, validate data, react to a button click, and many other actions.
* When an event occur, you can use a JavaScript event handler (or an event listener) to detect them and perform specific task or set of tasks. By convention, the names for event handlers always begin with the word "on", so an event handler for the click event is called onclick, similarly an event handler for the load event is called onload, event handler for the blur event is called onblur, and so on
* In general, the events can be categorized into four main groups — mouse events, keyboard events, form events and document/window events.


# inline events:
![image](https://user-images.githubusercontent.com/44174633/183687952-1f3a505b-0940-46dd-bc7e-880193b2c82f.png)
![image](https://user-images.githubusercontent.com/44174633/183688038-c3fd6772-a26e-4bc6-b8aa-583e4c16651e.png)

* this is not best practice

# adding javascript function as a event handler
![image](https://user-images.githubusercontent.com/44174633/183688804-0559b348-ea4e-4b88-a8ff-19c942267c69.png)
![image](https://user-images.githubusercontent.com/44174633/183688855-faec622b-358e-47b6-b065-292cdfaee656.png)
![image](https://user-images.githubusercontent.com/44174633/183688913-7b2ca848-5516-44d2-8bfc-8e90d8cc666d.png)

* this is also not recemended to use.

# using eventListner to handle event with js function
![image](https://user-images.githubusercontent.com/44174633/183689443-40011b08-91ee-4285-a3e6-794d2e3565cf.png)
![image](https://user-images.githubusercontent.com/44174633/183690182-500c459b-f0b0-403d-8851-742d3339f4b6.png)
![image](https://user-images.githubusercontent.com/44174633/183690455-615bf229-7727-4894-8370-073a73c2df5a.png)
in console we can see the value object of event
![image](https://user-images.githubusercontent.com/44174633/183691135-7670920f-3a26-4ebc-8aad-e315f9d6fde5.png)
* in console we can see value of this keyword

# using arrow function to create event handler function for eventListner (this is recomended and best practise for event handling)
![image](https://user-images.githubusercontent.com/44174633/183696781-f0533c4d-9d62-41d1-b8ee-0bc79bb302aa.png)
![image](https://user-images.githubusercontent.com/44174633/183696919-27b48648-d245-475c-a1d5-bff4922fef6d.png)
* here we can see that the value of this is windows objec not html element details like when we use function

