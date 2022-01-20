# Introduction to VUE

To open this project, you can access this github webpage:

https://ull-esit-dmsi-1920.github.io/vue-fundamentals-alu0101227610/

## TODOS for the Shopping list app

Follow these steps:

- [x] Write initial HTML with a shopping-list div
- [x] Load and Instanciate Vue add data and Vue template syntax to interpolate
- [x] Add an input an synchronize it with the interpolated text to see it
- [x] Explore the app in the console
- [x] Discuss the syntax of JS inside moustaches
- [x] Learn to read the errors in the console
- [x] Add items to data and show them using v-for
- [x] Add input a variable to store the newItem
- [x] Connect the input with the newItem and check the binding
- [x] Use Vue Devtools. Configure it to work with file://
- [x] Add v-on: Start by simulating in the console what we are going to do
- [x] Add button to add the new item when clicked
- [x] Add v-on:keyup.enter to the input element
- [x] Shorthands for v-on 
- [x] Use a method `saveItem` to factorice
- [x] Reset the input when finished the insertion
- [x] Check the method using the debugger
- [x] v-if and v-else
- [x] Add states: default and edition 

### Next Steps: Add State to your App

- [x] Add a `state` variable to the app `data` to represent the states of the app. 
- [x] Move the `input` and `button` *Save Item* elements to a `div` with class `add-item-form` so that these styles apply
- [x] Show the `div` with class `add-item-form` only if the state is `edition`
- [x] To the div with class `header` add a button `Add Item` that will make the app transit from the `default` state to the `edition` state 
- [x] Show the  `add button` only if the state is `default` 
- [x] To the div with class `header` add a button `Cancel Adding Item` with the class `btn-cancel` that will make the app transit from the `edition` state to the `default` state 
- [x] Show the  `Cancel Adding Item` button only if the state is `edition`
- [x] Add the `changeState` method that reflect the transitions between both states 

## v-bind steps

- [x] Using the dev tools, check that when we click the `save item` with the `input` empty we are adding new empty strings to the `items` list
- [x] Disable the button `save item` when the `input` is empty by binding the `disabled` attribute of the button

## Dynamic classes with v-bind

- [ ] Change the list of items from a list of Strings to a list of Objects with `label` and `purchased` attributes. Update the `saveItem` method and the template accordingly
- [ ] Make use of the class `.strikeout` in the css file:
  to style the purchased items. See the [Vue.js Guide section on Class and Style Bindings](https://vuejs.org/v2/guide/class-and-style.html)
  - [ ]  Use first the *object syntax* `v-bind:class="{myclass: expression}"` and 
  - [ ]  later the *array syntax* `v-bind:class=[exp1, exp2]`

