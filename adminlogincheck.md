# project-php
0) { $row=mysql_fetch_array($result); $_SESSION[name]=$row[0]; $_SESSION[check]=1; echo "
YOU HAVE BEEN SUCCESSFULLY LOGGED IN
"; echo "
CONTINUE TO THE SITE
"; } else { echo "
INVALID USERNAME/PASSWORD
"; echo "
TRY AGAIN!!
"; session_stop(); } echo "
"; mysql_close($con); ?> 
