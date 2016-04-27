**Insnergy Check New (Schedule)**
-----


|Interface|[Schedule] Do|
|:--------|:-----------------|
|{<br>'expected_update_period_in_days' => "10",<br>'device_id' => "RS06000D6F0003BBA08C\|01"，<br>'unit' => "500"<br>}| 將介面`device_id`裡的值藉由符號`|`拆開為兩個值，將此兩個值<br>透過API查詢本月的總用電量，並將總用電量乘上介面`unit`裡的值，最後<br>將`插座編號`、`插座位置`、`月份`、`本月總電量`、`本月總費用`往下送|

|Created Event|
|:---------------------:|
|![the origin of the name](https://github.com/A20229/autorun_user_manual/blob/master/images/insnergy_check_new.png)|

