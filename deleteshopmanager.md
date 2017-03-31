# project-php
0) { while($row = mysql_fetch_assoc($result)) { //echo "manager found"; 
$mgr_id= $row["mgr_id"]; 
$qry= "delete from SHOP_MANAGER where manager_id = $mgr_id "; 
if(mysql_query($qry,$con)) echo "Shop deletion successful"; 
else echo "Error: Shop deletion failed"; 
} } else { echo "Error: The shop record could not be found";
} ?> 
