# Output-the-Third-element-in-the-list-using-button-through-javascript
Output the Third element in the list using button through javascript
First create a list,

<ul>
     <li>Red</li>
     <li>Blue</li>
     <li>Green</li>
</ul>

now create a p tag where you want the output to display

<p id="showHere"></p>

now create a script,

<script>
function show(){
var x = document.getElementsByTagName("li");
document.getElementById("showHere").innerHTML = x[2].innerHTML;
}
</script>

now create a button to show the output and call the function show()

<button type="button" onclick="show()">Check Now</button>



//OUTPUT

Green

//

Thank you for reading the post. Have a great day!
