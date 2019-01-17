## 车证通
这是北京大学软件与微电子学院的车证管理系统，我们打算设计系统主要以微信小程序为主的移动端与web界面为主的客户端
 ##### 移动端主要功能
1、固定车辆车证办理，固定车辆申请人有以下三种情况：

-    教职工车辆
采集信息包括：职工号、姓名、部门、联系电话、车牌号码、车辆所有者姓名、备注（选填）
-	学生车辆
采集信息包括：学号、姓名、专业、联系电话、车牌号码、车辆所有者姓名、备注（选填）
-	服务商车辆	
采集信息包括：职工号、姓名、部门、专业、联系电话、车牌号码、车辆所有者姓名、备注（选填）

办理车证前，需要同意“申请人承诺条款”，方可办理车证。

车证办理必须上传行驶证、驾驶证照片，上传时可以考虑增加需要上传页面的示意图。

如果行驶证与驾驶人信息不一致需要上传（多个）其他附加证明材料。

以上车证有效期，默认三年。后台管理员可以单独修改某辆车的有效期。

也可以批量设置多辆车的有效期限。
	不同用户类型可以申请车证数量，后台可配置。
    
2、临时车辆入校预约
	用户分为学生用户和教职工用户申请。
    
预约人姓名、预约人学号/工号、预约人联系电话、部门；

驾驶人姓名，驾驶人联系方式、车牌号、入校原因、入校日期、时间、备注（选填）

车辆预约前，需要弹出“车辆预约说明信息”。

3、临时人员入校预约

用户分为学生用户和教职工用户申请。

预约人姓名、预约人学号/工号、预约人联系电话、部门；

来访人姓名，来访人联系方式、随行人数、入校原因、入校日期、时间、备注（选填）

人员预约前，需要弹出“人员预约说明信息”。


##### 后台管理系统
办理车证有承诺条款，后台可以编辑。

预约有预约说明，后台可以编辑。

预约成功后，有成功预约提醒。

预约成功后，有向门卫提醒的功能。门卫可以考虑有信息展示屏。

办理车证成功后，有提醒领取车证通知。

后台有打印车证办理申请表及承诺书的功能。

后台有统计功能，车辆、人员统计功能

后台有单独添加车证办理功能。

后台有单独添加车辆预约功能。

后台有单独添加人员预约功能。

后台有向用户发送消息通知的功能。



