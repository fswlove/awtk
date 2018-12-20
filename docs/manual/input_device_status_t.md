## input\_device\_status\_t
### 概述
 输入设备状态管理器。本类仅供窗口管理器内部使用。
### 函数
<p id="input_device_status_t_methods">

| 函数名称 | 说明 | 
| -------- | ------------ | 
| <a href="#input_device_status_t_input_device_status_init">input\_device\_status\_init</a> |  初始化输入设备状态管理器。
| <a href="#input_device_status_t_input_device_status_on_input_event">input\_device\_status\_on\_input\_event</a> |  对输入事件进行处理，然后分发给widget。
### 属性
<p id="input_device_status_t_properties">

| 名属性称 | 类型 | 说明 | 
| -------- | ----- | ------------ | 
### 事件
<p id="input_device_status_t_events">

| 事件名称 | 类型  | 说明 | 
| -------- | ----- | ------- | 
#### input\_device\_status\_init 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | input\_device\_status\_t* | 返回输入设备状态管理器对象。 |
| ids | input\_device\_status\_t* | 输入设备状态管理器对象。 |
<p id="input_device_status_t_input_device_status_init"> 初始化输入设备状态管理器。



#### input\_device\_status\_on\_input\_event 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| ids | input\_device\_status\_t* | 输入设备状态管理器对象。 |
| widget | widget\_t* | 窗口管理器对象。 |
| e | event\_t* | 事件对象。 |
<p id="input_device_status_t_input_device_status_on_input_event"> 对输入事件进行处理，然后分发给widget。


