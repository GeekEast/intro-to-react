- [Course](https://btholt.github.io/complete-intro-to-react-v5/)
### createElement
- pass single child
```javascript
React.createElement(
  "div", // element type
  {id:"something-important"}, // props to be passed in 
  React.createElement("h1", {}, "Adopt Me!") // child to be passed in
)
```
- pass multiple children
```javascript
React.createElement(
  "div", // element type
  {id:"something-important"}, // props to be passed in 
  [
    React.createElement("h1", {}, "Adopt Me!"),
    React.createElement("h1", {}, "Adopt Me!")
  ] // child[] to be passed in
)
```

#### Q & A
- Where did `not rendered` inside root go?
  - It will be `overwritten` once you render components inside root



