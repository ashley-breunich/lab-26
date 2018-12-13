![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

# Lab 26
Create a counter application using React. Hai helped me with changing the button to a link. And then I helped Kevin and Hollie with that render function. 

## Author: Ashley Breunich

### Links and Resources
* [Warm Up](https://repl.it/@ashbreu/destructuring-and-spread)
* [Lab 26 Code](https://codesandbox.io/s/61z77944nk)
* [Front End URL](https://61z77944nk.codesandbox.io/)

### Modules

### `app.js`
#### Exported Values and Methods

##### `Class Counter`

###### `constructor(props)`
Declares the state

###### `handleDown(e)`
Modifies the state (decreases this.state.counter by 1)

###### `handleUp(e)`
Modifies the state (increases this.state.counter by 1)

###### `render() -> div`
Returns state.counter, resulting handleUp() link, and resulting handleDown() link

##### `Class App`

###### `render() -> React.Fragment`
Returns Header, Counter, Footer

### `index.js`
#### Exported Values and Methods

##### `Class Main`

###### `render() -> Component`
Returns App

### `header.js`
#### Exported Values and Methods

##### `Class Header`

###### `render() -> Header`
Returns Header

### `footer.js`
#### Exported Values and Methods

##### `Class Footer`

###### `render() -> Footer`
Returns Footer

#### UML
[Link to UML](assets/lab-26-uml.jpg)
I worked with Hai and Hollie on the UML drawing. 