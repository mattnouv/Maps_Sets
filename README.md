<p>
<h2>Maps and Sets Exercise</h2>
</p>
<p>
  Quick Question <b>#1</b> <i>What does the following code return?</i>
</p>

new Set([1,1,2,2,3,4])
<br>
<p>
  Quick Question <b>#2</b> <i>What does the following code return?</i>
</p>

[...new Set("referee")].join("")
<br>
<p>
  Quick Question <b>#3</b> <i>What does the following code return?</i>
</p>
<p>
let m = new Map();<br>
m.set([1,2,3], true);<br>
m.set([1,2,3], false);
<br>
<p>Write a function called <b>hasDuplicate</b> which accepts an array and returns true or false if that array contains a duplicate.</p>

hasDuplicate([1,3,2,1]) // true<br>
hasDuplicate([1,5,-1,4]) // false
<br>
<p>Write a function called <b>vowelCount</b> which accepts a string and returns a map where the keys are numbers and the values are the count of the vowels in the string.</p>

vowelCount('awesome') // Map { 'a' => 1, 'e' => 2, 'o' => 1 }<br>
vowelCount('Colt') // Map { 'o' => 1 }
