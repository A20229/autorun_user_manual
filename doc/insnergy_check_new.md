**Insnergy Check New (Schedule)**
-----


|Interface|[Schedule] Do|
|---|:-----------------:|
|{<br>'expected_update_period_in_days' => "10",<br>'device_id' => "RS06000D6F0003BBA08C\|01",<br>'unit' => "500"<br>}| 將介面`device_id`裡的值藉由符號`|`拆開為兩個值,將此兩個值透過API<br>查詢本月的總用電量,並將總用電量乘上介面`unit`裡的值 |

|If(true)|
|:-----------------:|
|![the origin of the name](https://github.com/A20229/autorun_user_manual/blob/master/images/insnergy_check_new.png)|

