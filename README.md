# 测试Actions
# 测试项目
* `中青 youth.js youth.py Youth_AutoRead.js`
* `步步宝 bububao.js`
* `笑普 iboxpay.js`
* `芝嫲视频 zhima.js`
* `京东多合一签到 JD_DailyBonus.js`


# Secrets说明
### 【中青】
  * 签到分享转盘开箱打卡
      
 Actions  | yml   | Secrets  |  值  |  说明
 ---- | ----- | ------ | ----- | -----
 中青看点  | 中青看点签到.yml | YOUTH_HEADER | &uid=xxx&cookie=xxx&cookie_id=xxxx |  多账号换行 
 中青看点 | 中青看点签到.yml | YOUTH_ARTBODY | p=xxxxx | 多账号换行 
 中青看点 | 中青看点签到.yml | YOUTH_TIME | p=xxxxx | 多账号换行 
 中青-Python `Py版本` | 中青-Py.yml | YOUTH_HEADER_1 | 完整的请求头 如：{"Accept-Encoding"：xxx； } | 多账号换行
 中青-Python `Py版本` | 中青-Py.yml | YOUTH_ARTBODY_1 | p=xxxxx | 多账号换行 
 中青-Python `Py版本` | 中青-Py.yml | YOUTH_TIME_1 | p=xxxxx | 多账号换行 
  
 * 自动阅读观看
 
Actions  | yml   | Secrets  |  值  |  说明
 ---- | ----- | ------ | ----- | -----
中青看点-自动阅读A | 中青看点自动阅读A.yml | YOUTH_READ_1_50  | body：做多只能存50个 | 用&分隔 
中青看点-自动阅读A | 中青看点自动阅读A.yml | YOUTH_READ_51_100 | body：做多只能存50个 | 用&分隔 
中青看点-自动阅读A | 中青看点自动阅读A.yml | YOUTH_READ_101_150 | body：做多只能存50个 | 用&分隔 
中青看点-自动阅读A | 中青看点自动阅读A.yml | YOUTH_READ_151_200 | body：做多只能存50个 | 用&分隔 
中青看点-自动阅读A | 中青看点自动阅读A.yml | YOUTH_READ_201_250 | body：做多只能存50个 | 用&分隔 
中青看点-自动阅读A | 中青看点自动阅读A.yml | YOUTH_READ_251_300  | body：做多只能存50个 | 用&分隔 

### 【步步宝】
Actions  | yml   | Secrets  |  值  |  说明
 ---- | ----- | ------ | ----- | -----
步步宝 | 步步宝.yml | BBB_BUBUBAOTOKEN | token的值 | 多账号换行
步步宝 | 步步宝.yml | BBB_CASH | 可设置0 0.3 50 100 200 888    默认0关闭提现，设置888由上至下循环提现 | 多账号换行


### 【笑普】
Actions  | yml   | Secrets  |  值  |  说明
 ---- | ----- | ------ | ----- | -----
笑普 | 笑普.yml | XP_REFRESHTOKEN | token的值 | 多账号换行



### 【芝嫲视频】
Actions  | yml   | Secrets  |  值  |  说明
 ---- | ----- | ------ | ----- | -----
芝嫲视频 | 芝嫲视频.yml | ZM_ZHIMABODY | body 例：appversion=10&desarr=xxxx | 多账号换行


### 【京东多合一签到】
Actions  | yml   | Secrets  |  值  |  说明
 ---- | ----- | ------ | ----- | -----
京东-多合一签到 | 京东多合一签到.yml | KEY_1 | 京东cookie | 多账号自行修改yml，  目前可以写5个账号KEY_1、KEY_2、KEY_3、KEY_4、KEY_5


##### 致谢 脚本作者
  @ziye  
  @Sunert  
  @NobyDa  
  @Lxk0301
#### 更新 2021.2.25
#### By CurtinLV


