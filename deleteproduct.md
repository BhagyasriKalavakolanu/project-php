# project-php
0) { while($row = mysql_fetch_array($result)) { echo '  '; echo "

Name	:	$row[3]
Size	:	$row[2]
Price	:	$row[4]
Quantity	:	$row[5]
Description	:	$row[6]
  


"; } } else { echo "
"; echo "
No Results Found!
"; echo "
"; } mysql_close($con); ?> 
