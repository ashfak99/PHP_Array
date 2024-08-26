<h1>PHP INDEXED ARRAY</h1>
In indexed arrays each item has an index number.<br><br>
By default, the first item has index 0, the second item has 1, etc.<br>
<code>$arr=array("Ashfak","Asrar","Alam");</code><br>
<code>var_dump($arr);</code>

<h3>Access Indexed Array</h3>
To Access an array item you can refer to the index number<br>
<code>$arr=array("Ashfak","Asrar","Alam");</code><br>
<code>echo $arr[0];</code>

<h3>Change Value</h3>
To change the value of an array item use the index number.<br>
<code>$arr=array("Ashfak","Asrar","Alam");</code><br>
<code>$arr[1]="Ali";</code><br>
<code>var_dump($arr);</code>

<h3>Loop Through an Indexed Array</h3>
To loop through and print all the values of an indexed array, you could as a foreach loop, like this<br>
<code>$arr=array("Ashfak","Asrar","Alam");</code><br>
<code>foreach($arr as $a){</code><br>
<code>echo "$a";</code><br>
<code>}</code>

<h3>Index Number</h3>
The Key of an indexed array is a number, by default the first item is 0 and the second item is 1.<br><br>
New items get the next index number , meaning one higher than the highest existing index.<br>
<code>$arr[0]="Ashfak";</code><br>
<code>$arr[1]="Alam";</code><br>
<code>$arr[2]="Ali";</code><br>
And if you use the <bold>array_push()</bold> function to add a new item, the new item will get the index 3.<br>
<code>array_push($arr,"Asrar");</code><br>
<code>var_dump($arr);</code><br><br>
But if you have an array with random index number like this:<br>
<code>$arr[5]="Ashfak";</code><br>
<code>$arr[8]="Alam";</code><br>
<code>$arr[18]="Ali";</code><br>
And if you use the <bold>array_push()</bold> function to add a new item:
<code>array_push($arr,"Asrar");</code><br>
<code>var_dump($arr);</code><br><br>
