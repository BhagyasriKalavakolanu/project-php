# project-php
0) { while($row = mysql_fetch_array($result)) { echo '  '; echo "
Name	:	$row[1]
Type	:	$row[2]
Address	:	$row[3]
Manager	:	$row[9]
Mobile	:	$row[13]
Email	:	$row[14]

 
"; } } else { echo "
"; echo "
No Results Found!
"; echo "
"; } mysql_close($con); ?> 
