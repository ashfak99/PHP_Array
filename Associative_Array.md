# Associative Array
Associative arrays are arrays that use named keys that you assign to them.<br>
<code>$arr=array("Name"=>"Ashfak","City"=>"New Delhi","DOB"=>2005)</code><br>
<code>var_dump($arr);</code><br><br>

<h3>Access Associative Arrays</h3>
To access an array item you can refer to the key name.<br>
<code>$arr=array("Name"=>"Ashfak","Cit"=>"New Delhi","DOB"=>2005);</code><br>
<code>echo $arr["Name"];</code><br><br>

<h3>Change Value</h3>
To change the value of an array item use the key name.<br>
<code>$arr=array("Name"=>"Ashfak","City"=>"New Delhi","DOB"=>2005);</code><br>
<code>$arr["City"]="Mumbai";</code><br>
<code>var_dump($arr);</code><br><br>

<h3>Loop Through An Associative Array</h3>
To loop through and print all the values of an associative array, you could use a <bold>foreach loop</bold>,like this<br>
<code>$arr=array("Name"=>"Ashfak","City"=>"New Delhi","DOB"=>2005);</code><br>
<code>foreach($arr as $a=>$n){</code><br>
<code>echo "$a : $n"; </code><br>
<code>}</code>
