---
title: My New Post
date: 2016-11-28 11:05:54
tags:
---

    
    **简要描述：** 

    - 店粉列表--新接口

    **请求URL：** 
    - ` http://xx.com//MerchantApp/ShopMember/listNewData `
      
      **请求方式：**
      - POST 

      **参数：** 

      |参数名|必选|类型|缺省值|说明|
      |:----    |:---|:----- |:-----|-----   |
      |p |是  |intval | 1     | 页码 |
      |orderfield |是  |string |  lasttime    | 排序字段：lasttime：到店时间，nums:到店次数,fee:消费金额   |
      |ordertype     |是  |string | desc     | 排序方式：desc：倒叙，asc：正序  |
      |search     |否  |string |      | 搜索内容   |
      |flag     |否  |string |      | 查询方法：1：本周到店，2：今日到店，3：今日新增，4：消费金额Top，5：消费次数Top，6:回头客,7：待激活,8：活跃,0：全部店粉(默认)   |
      |shop_id     |否  |string |      | 门店id   |
      |version     |是  |string |      | App版本号   |

       **返回示例**

       ```
       This is data
       ```
