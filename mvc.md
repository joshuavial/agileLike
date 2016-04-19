Listener
- can know about the dom to listen to events
- can not do anything
- calls controller methods with params pulled from dom/events

Controller
- can not do anything
- delegates work to models to do work (logic/apis)
- renders views to change the dom

Model
- calls apis
- does logic
- maintains state

View
- doesn't do any work
- updates the dom
- adds listeners to the dom

