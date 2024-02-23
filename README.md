code
// HTML
<button id="myButton" onclick="changeLabel()">Click me</button>

// JavaScript
function changeLabel() {
  var button = document.getElementById("myButton");
  button.innerHTML = "18 degrees";
}
