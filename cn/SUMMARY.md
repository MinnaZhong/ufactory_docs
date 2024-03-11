# Table of contents

* [Gcode](README.md)
  * [UFactory-Gcode](gcode/ufactory-gcode.md)
* [Modbus Tcp](modbustcp/README.md)
  * [UF\_ModbusTcp\_Manual](modbustcp/uf\_modbustcp\_manual.md)
* [firmware](firmware/README.md)
  * [report](firmware/report.md)
* [support\_articles](support\_articles/README.md)
  * [更换控制器或者控制器混用，应该如何设置？](support\_articles/what-should-i-do-if-i-swap-the-robot-control-box.md)
  * [如何使用第三方设备](support\_articles/ru-he-shi-yong-di-san-fang-she-bei.md)
  * [如何获取 xArm 机器人的关节电流/扭矩数据](support\_articles/ru-he-huo-qu-xarm-ji-qi-ren-de-guan-jie-dian-liu-niu-ju-shu-ju.md)
  * [为什么当我调整 Roll 和 Yaw 时机器人表现相同？](support\_articles/wei-shi-mo-dang-wo-tiao-zheng-roll-he-yaw-shi-ji-qi-ren-biao-xian-xiang-tong.md)
* [Studio  API](studio-api/README.md)
  * [Studio  API](studio-api/studio-api.md)
  * [Live Contorl API](studio-api/live-contorl-api/README.md)
    * [1.xarm\_move\_step](studio-api/live-contorl-api/1.xarm\_move\_step.md)
    * [2.xarm\_move\_step\_over](studio-api/live-contorl-api/2.xarm\_move\_step\_over.md)
    * [3.xarm\_move\_joint](studio-api/live-contorl-api/3.xarm\_move\_joint.md)
    * [4.switch\_mode\_lite6](studio-api/live-contorl-api/4.switch\_mode\_lite6.md)
    * [5.xarm\_urgent\_stop](studio-api/live-contorl-api/5.xarm\_urgent\_stop.md)
    * [6.xarm\_set\_simulation\_robot](studio-api/live-contorl-api/6.xarm\_set\_simulation\_robot.md)
    * [7.xarm\_set\_speed](studio-api/live-contorl-api/7.xarm\_set\_speed.md)
    * [8.xarm\_set\_lite6\_gripper](studio-api/live-contorl-api/8.xarm\_set\_lite6\_gripper.md)
    * [9.xarm\_switch\_mode](studio-api/live-contorl-api/9.xarm\_switch\_mode.md)
  * [Blockly](studio-api/blockly/README.md)
    * [1.xarm\_move\_arc\_line](studio-api/blockly/1.xarm\_move\_arc\_line.md)
    * [2.xarm\_move\_circle](studio-api/blockly/2.xarm\_move\_circle.md)
    * [3.xarm\_set\_blockly\_init](studio-api/blockly/3.xarm\_set\_blockly\_init.md)
    * [4.run\_blockly](studio-api/blockly/4.run\_blockly.md)
    * [5.get\_app\_xml\_data](studio-api/blockly/5.get\_app\_xml\_data.md)
    * [6.get\_app\_info](studio-api/blockly/6.get\_app\_info.md)
    * [7.app\_save\_info](studio-api/blockly/7.app\_save\_info.md)
    * [8.app\_create\_file](studio-api/blockly/8.app\_create\_file.md)
  * [Python IDE](studio-api/python-ide/README.md)
    * [1.ide\_list\_projects](studio-api/python-ide/1.ide\_list\_projects.md)
    * [2.ide\_get\_project](studio-api/python-ide/2.ide\_get\_project.md)
    * [3.ide\_create\_project](studio-api/python-ide/3.ide\_create\_project.md)
    * [4.ide\_delete\_project](studio-api/python-ide/4.ide\_delete\_project.md)
    * [5.ide\_rename\_project](studio-api/python-ide/5.ide\_rename\_project.md)
    * [6.ide\_save\_project](studio-api/python-ide/6.ide\_save\_project.md)
    * [7.ide\_create\_file](studio-api/python-ide/7.ide\_create\_file.md)
    * [8.ide\_to\_python\_allow](studio-api/python-ide/8.ide\_to\_python\_allow.md)
    * [9.ide\_blockly\_to\_python](studio-api/python-ide/9.ide\_blockly\_to\_python.md)
    * [10.ide\_write\_file](studio-api/python-ide/10.ide\_write\_file.md)
    * [11.ide\_get\_file](studio-api/python-ide/11.ide\_get\_file.md)
    * [12.ide\_delete\_file](studio-api/python-ide/12.ide\_delete\_file.md)
    * [13.ide\_rename\_file](studio-api/python-ide/13.ide\_rename\_file.md)
    * [14.ide\_create\_folder](studio-api/python-ide/14.ide\_create\_folder.md)
    * [15.ide\_delete\_folder](studio-api/python-ide/15.ide\_delete\_folder.md)
    * [16.ide\_rename\_folder](studio-api/python-ide/16.ide\_rename\_folder.md)
    * [17.run\_python\_program](studio-api/python-ide/17.run\_python\_program.md)
    * [18.stop\_python\_program](studio-api/python-ide/18.stop\_python\_program.md)
  * [settings](studio-api/settings/README.md)
    * [1.xarm\_set\_effector\_modbus\_rtu\_cmd](studio-api/settings/1.xarm\_set\_effector\_modbus\_rtu\_cmd.md)
    * [2.xarm\_set\_cgpio\_digital](studio-api/settings/2.xarm\_set\_cgpio\_digital.md)
    * [3.xarm\_set\_cgpio\_analog](studio-api/settings/3.xarm\_set\_cgpio\_analog.md)
    * [4.xarm\_set\_gpio\_digital](studio-api/settings/4.xarm\_set\_gpio\_digital.md)
    * [5.xarm\_set\_motion\_config](studio-api/settings/5.xarm\_set\_motion\_config.md)
    * [6.xarm\_set\_suction\_cup](studio-api/settings/6.xarm\_set\_suction\_cup.md)
    * [7.get\_tcp\_offset\_load\_config](studio-api/settings/7.get\_tcp\_offset\_load\_config.md)
    * [8.set\_tcp\_load\_offset\_configs](studio-api/settings/8.set\_tcp\_load\_offset\_configs.md)
    * [9.remove\_tcp\_load\_offset\_configs](studio-api/settings/9.remove\_tcp\_load\_offset\_configs.md)
    * [10.associate\_tcp\_offset\_load](studio-api/settings/10.associate\_tcp\_offset\_load.md)
    * [11.xarm\_start\_identification](studio-api/settings/11.xarm\_start\_identification.md)
    * [12.xarm\_stop\_identification](studio-api/settings/12.xarm\_stop\_identification.md)
    * [13.xarm\_get\_reduced\_states](studio-api/settings/13.xarm\_get\_reduced\_states.md)
    * [14.xarm\_get\_approx\_motion](studio-api/settings/14.xarm\_get\_approx\_motion.md)
    * [15.xarm\_config\_gpio\_reset\_when\_stop](studio-api/settings/15.xarm\_config\_gpio\_reset\_when\_stop.md)
    * [16.xarm\_set\_collision\_rebound](studio-api/settings/16.xarm\_set\_collision\_rebound.md)
    * [17.xarm\_set\_self\_collision\_detection](studio-api/settings/17.xarm\_set\_self\_collision\_detection.md)
    * [18.xarm\_set\_jerk](studio-api/settings/18.xarm\_set\_jerk.md)
    * [19.xarm\_get\_joint\_pi](studio-api/settings/19.xarm\_get\_joint\_pi.md)
    * [20.xarm\_factory\_reset](studio-api/settings/20.xarm\_factory\_reset.md)
    * [21.xarm\_start\_report\_gpio\_digital](studio-api/settings/21.xarm\_start\_report\_gpio\_digital.md)
    * [22.xarm\_stop\_report\_gpio\_digital](studio-api/settings/22.xarm\_stop\_report\_gpio\_digital.md)
    * [23.get\_gpio\_config](studio-api/settings/23.get\_gpio\_config.md)
    * [24.set\_gpio\_config](studio-api/settings/24.set\_gpio\_config.md)
    * [25.xarm\_set\_stop\_loop](studio-api/settings/25.xarm\_set\_stop\_loop.md)
    * [26.xarm\_set\_modbus\_baud\_rate](studio-api/settings/26.xarm\_set\_modbus\_baud\_rate.md)
    * [27.xarm\_get\_end\_io\_info](studio-api/settings/27.xarm\_get\_end\_io\_info.md)
    * [28.xarm\_set\_user\_config](studio-api/settings/28.xarm\_set\_user\_config.md)
    * [29.xarm\_save\_config](studio-api/settings/29.xarm\_save\_config.md)
    * [30.xarm\_get\_ft\_sensor\_mode](studio-api/settings/30.xarm\_get\_ft\_sensor\_mode.md)
    * [31.xarm\_get\_ft\_sensor\_info](studio-api/settings/31.xarm\_get\_ft\_sensor\_info.md)
    * [32.get\_world\_offset\_config](studio-api/settings/32.get\_world\_offset\_config.md)
    * [33.set\_world\_offset\_configs](studio-api/settings/33.set\_world\_offset\_configs.md)
    * [34.xarm\_set\_mount\_direction](studio-api/settings/34.xarm\_set\_mount\_direction.md)
    * [35.xarm\_set\_reduced\_max\_joint\_speed](studio-api/settings/35.xarm\_set\_reduced\_max\_joint\_speed.md)
    * [36.xarm\_set\_reduced\_max\_tcp\_speed](studio-api/settings/36.xarm\_set\_reduced\_max\_tcp\_speed.md)
    * [37.xarm\_set\_reduced\_joint\_range](studio-api/settings/37.xarm\_set\_reduced\_joint\_range.md)
    * [38.xarm\_set\_reduced\_mode](studio-api/settings/38.xarm\_set\_reduced\_mode.md)
    * [39.xarm\_set\_reduced\_tcp\_boundary](studio-api/settings/39.xarm\_set\_reduced\_tcp\_boundary.md)
    * [40.xarm\_set\_fense\_mode](studio-api/settings/40.xarm\_set\_fense\_mode.md)
  * [General](studio-api/general/README.md)
    * [1.xarm\_clear\_error\_warn](studio-api/general/1.xarm\_clear\_error\_warn.md)
    * [加载导入机械臂参数文件](studio-api/general/jia-zai-dao-ru-ji-xie-bi-can-shu-wen-jian.md)
  * [API Code](studio-api/api-code/README.md)
    * [API Code](studio-api/api-code/api-code.md)