
<a name="paths"></a>
## 资源

<a name="about-us-api_resource"></a>
### About-us-api
关于我们


<a name="getcontentusingpost"></a>
#### 关于我们内容
```
POST /aboutUs/getContent
```


##### 说明
关于我们内容


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/aboutUs/getContent
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="ad-api_resource"></a>
### Ad-api
地址相关


<a name="findadsusingpost"></a>
#### ads
```
POST /adApi/ads
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**type**  <br>*可选*|type|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/adApi/ads
```


###### 请求 query
```
json :
{
  "type" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="address-api_resource"></a>
### Address-api
地址相关


<a name="addorupdateaddressusingpost"></a>
#### 修改或者添加收货地址
```
POST /AddresApi/addOrUpdateMailAddress
```


##### 说明
修改或者添加收货地址


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**areaId**  <br>*可选*|areaId|integer (int64)|
|**Query**|**cityId**  <br>*可选*|cityId|integer (int64)|
|**Query**|**detailAddress**  <br>*可选*|detailAddress|string|
|**Query**|**id**  <br>*可选*|id|integer (int64)|
|**Query**|**phone**  <br>*可选*|phone|string|
|**Query**|**provinceId**  <br>*可选*|provinceId|integer (int64)|
|**Query**|**receiveName**  <br>*可选*|receiveName|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/AddresApi/addOrUpdateMailAddress
```


###### 请求 query
```
json :
{
  "areaId" : 0,
  "cityId" : 0,
  "detailAddress" : "string",
  "id" : 0,
  "phone" : "string",
  "provinceId" : 0,
  "receiveName" : "string",
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getmailaddressusingpost"></a>
#### 获取收货地址
```
POST /AddresApi/getMailAddress
```


##### 说明
获取收货地址


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/AddresApi/getMailAddress
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="area-api_resource"></a>
### Area-api
地区相关


<a name="findareabycityidusingpost"></a>
#### findAreaByCityId
```
POST /area/findAreaByCityId
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/findAreaByCityId
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findareabyidusingpost"></a>
#### findAreaById
```
POST /area/findAreaById
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/findAreaById
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findcitybyidusingpost"></a>
#### findCityById
```
POST /area/findCityById
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/findCityById
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findcitysbyproviceidusingpost"></a>
#### findCitysByProviceId
```
POST /area/findCitysByProviceId
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/findCitysByProviceId
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findordersusingpost"></a>
#### findOrders
```
POST /area/findOrders
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**schoolId**  <br>*可选*|schoolId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult«AppUserOrder»](#ddcbc4d95d389c473ed78795180271b6)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/findOrders
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "schoolId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ {
    "appUserAccount" : {
      "accumulatePoints" : 0,
      "goldCoins" : 0,
      "id" : 0
    },
    "changeNum" : 0,
    "createDate" : "string",
    "des" : "string",
    "id" : 0,
    "personalLearnBook" : {
      "appUserNumber" : 0,
      "boughtTime" : "string",
      "buy" : true,
      "currentLeftWords" : "string",
      "currentUnitFinished" : true,
      "currentUnitName" : "string",
      "currentWord" : 0,
      "currentWordNum" : 0,
      "currnetWordname" : "string",
      "extractPoints" : "string",
      "freeBoughtTime" : "string",
      "id" : 0,
      "isCurrentBook" : 0,
      "isFinished" : 0,
      "isPassed" : 0,
      "isPreTested" : 0,
      "lastTestTime" : "string",
      "learnAfterScore" : "string",
      "learnBeforeScore" : "string",
      "learnBook" : {
        "bookName" : "string",
        "createTime" : "string",
        "downLoadNum" : 0,
        "download" : 0,
        "grade" : "string",
        "id" : 0,
        "imgUrl" : "string",
        "price" : 0,
        "stage" : "string",
        "updateTime" : "string",
        "version" : "string",
        "wordsNum" : 0
      },
      "learnedWords" : "string",
      "preScore" : 0,
      "score" : 0,
      "teacherSuggest" : "string",
      "totalWordNum" : 0,
      "unitId" : 0,
      "unitWordProgress" : 0,
      "valiable" : true
    },
    "redeemCode" : {
      "activeTime" : "string",
      "codeMoney" : 0,
      "codeNum" : "string",
      "createTime" : "string",
      "des" : "string",
      "id" : 0,
      "school" : {
        "LAY_CHECKED" : true,
        "address" : "string",
        "agents" : {
          "address" : "string",
          "areaId" : 0,
          "birthDay" : "string",
          "cityId" : 0,
          "detailAddress" : "string",
          "email" : "string",
          "headerImgUrl" : "string",
          "id" : 0,
          "name" : "string",
          "phone" : "string",
          "provinceId" : 0,
          "registerDate" : "string",
          "sex" : 0,
          "user" : {
            "createTiem" : "string",
            "id" : 0,
            "loginName" : "string",
            "name" : "string",
            "passWord" : "string",
            "roles" : [ {
              "id" : 0,
              "permissionIds" : "string",
              "permissions" : [ {
                "LAY_CHECKED" : true,
                "dataPath" : "string",
                "hasChild" : 0,
                "icon" : "string",
                "id" : 0,
                "lay_CHECKED" : true,
                "menuId" : 0,
                "parentId" : 0,
                "permissonName" : "string",
                "powerList" : [ {
                  "LAY_CHECKED" : true,
                  "dataPath" : "string",
                  "hasChild" : 0,
                  "icon" : "string",
                  "id" : 0,
                  "lay_CHECKED" : true,
                  "menuId" : 0,
                  "parentId" : 0,
                  "permissonName" : "string",
                  "powerList" : [ "..." ],
                  "powerMenuName" : "string",
                  "powerName" : "string",
                  "powerUrl" : "string",
                  "roles" : [ {
                    "id" : 0,
                    "permissionIds" : "string",
                    "permissions" : [ "..." ],
                    "roleName" : "string"
                  } ]
                } ],
                "powerMenuName" : "string",
                "powerName" : "string",
                "powerUrl" : "string",
                "roles" : [ {
                  "id" : 0,
                  "permissionIds" : "string",
                  "permissions" : [ "..." ],
                  "roleName" : "string"
                } ]
              } ],
              "roleName" : "string"
            } ],
            "rolesIds" : "string"
          }
        },
        "areaId" : 0,
        "city" : "string",
        "cityId" : 0,
        "createTime" : "string",
        "detailAddress" : "string",
        "id" : 0,
        "lay_CHECKED" : true,
        "masterId" : 0,
        "mastername" : "string",
        "name" : "string",
        "phone" : "string",
        "province" : "string",
        "provinceId" : 0,
        "seven" : 0,
        "shcoolDes" : "string",
        "thirty" : 0,
        "uid" : "string",
        "userNumber" : 0
      },
      "state" : 0,
      "termOfvalidity" : 0,
      "timeOut" : true,
      "upLoadUser" : {
        "createTiem" : "string",
        "id" : 0,
        "loginName" : "string",
        "name" : "string",
        "passWord" : "string",
        "roles" : [ {
          "id" : 0,
          "permissionIds" : "string",
          "permissions" : [ "..." ],
          "roleName" : "string"
        } ],
        "rolesIds" : "string"
      },
      "user" : {
        "address" : "string",
        "appUserAccount" : {
          "accumulatePoints" : 0,
          "goldCoins" : 0,
          "id" : 0
        },
        "areaId" : 0,
        "benginStartTime" : "string",
        "birthDay" : "string",
        "booksCount" : 0,
        "cityId" : 0,
        "classInSchool" : {
          "LAY_CHECKED" : true,
          "addUser" : {
            "createTiem" : "string",
            "id" : 0,
            "loginName" : "string",
            "name" : "string",
            "passWord" : "string",
            "roles" : [ {
              "id" : 0,
              "permissionIds" : "string",
              "permissions" : [ "..." ],
              "roleName" : "string"
            } ],
            "rolesIds" : "string"
          },
          "classInfo" : "string",
          "createTime" : "string",
          "headMaster" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "name" : "string",
          "school" : {
            "LAY_CHECKED" : true,
            "address" : "string",
            "agents" : {
              "address" : "string",
              "areaId" : 0,
              "birthDay" : "string",
              "cityId" : 0,
              "detailAddress" : "string",
              "email" : "string",
              "headerImgUrl" : "string",
              "id" : 0,
              "name" : "string",
              "phone" : "string",
              "provinceId" : 0,
              "registerDate" : "string",
              "sex" : 0,
              "user" : {
                "createTiem" : "string",
                "id" : 0,
                "loginName" : "string",
                "name" : "string",
                "passWord" : "string",
                "roles" : [ {
                  "id" : 0,
                  "permissionIds" : "string",
                  "permissions" : [ "..." ],
                  "roleName" : "string"
                } ],
                "rolesIds" : "string"
              }
            },
            "areaId" : 0,
            "city" : "string",
            "cityId" : 0,
            "createTime" : "string",
            "detailAddress" : "string",
            "id" : 0,
            "lay_CHECKED" : true,
            "masterId" : 0,
            "mastername" : "string",
            "name" : "string",
            "phone" : "string",
            "province" : "string",
            "provinceId" : 0,
            "seven" : 0,
            "shcoolDes" : "string",
            "thirty" : 0,
            "uid" : "string",
            "userNumber" : 0
          },
          "studentNum" : 0,
          "withInSevenNUm" : 0,
          "withInTwoNum" : 0
        },
        "classInSchoolId" : 0,
        "hasCompeltedInfo" : true,
        "id" : 0,
        "imgUrl" : "string",
        "isBatchCreate" : 0,
        "lastSignTime" : "string",
        "learnBookWords" : "string",
        "learnTime" : 0,
        "level" : "string",
        "name" : "string",
        "newWordNum" : 0,
        "number1" : "string",
        "number2" : "string",
        "pass64" : "string",
        "password" : "string",
        "phoneForInfo" : "string",
        "phoneNum" : "string",
        "provinceId" : 0,
        "punchCardsDays" : 0,
        "qqNickName" : "string",
        "qqNumber" : "string",
        "qqOpenId" : "string",
        "realNameForInfo" : "string",
        "registerDate" : "string",
        "schoolId" : "string",
        "schoolName" : "string",
        "sex" : 0,
        "sign" : "string",
        "standardDay" : 0,
        "teacher" : "string",
        "thirdImgUrl" : "string",
        "thirdNickName" : "string",
        "todayStudyTime" : "string",
        "totalNewOnlineTime" : "string",
        "totalNewVolidTime" : "string",
        "totalStudyTime" : "string",
        "uid" : "string",
        "wechatNickName" : "string",
        "wechatNum" : "string",
        "wechatOpenId" : "string",
        "weiboNickName" : "string",
        "weiboNumber" : "string",
        "weiboOpenId" : "string",
        "wordNum" : 0,
        "wordsNumReview" : 0
      }
    },
    "relatedId" : 0,
    "title" : "string",
    "type" : 0
  } ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findprovincesusingpost"></a>
#### findProvinces
```
POST /area/findProvinces
```


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/findProvinces
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getprovinceusingpost"></a>
#### getProvince
```
POST /area/getProvince
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/area/getProvince
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="book-api_resource"></a>
### Book-api
课本相关


<a name="agentssellsinfousingpost"></a>
#### agentsSellsInfo
```
POST /bookApi/agentsSellsInfo
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**classId**  <br>*可选*|classId|integer (int64)|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**schoolId**  <br>*可选*|schoolId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[LayPageResult«AppUserShowInfoBean»](#64208abcc996c5e1c6ddd01700043576)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/bookApi/agentsSellsInfo
```


###### 请求 query
```
json :
{
  "classId" : 0,
  "limit" : 0,
  "page" : 0,
  "schoolId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "code" : 0,
  "count" : 0,
  "data" : [ {
    "bookTestInfos" : [ {
      "bookId" : 0,
      "bookName" : "string",
      "isPre" : 0,
      "score" : 0,
      "testDate" : "string"
    } ],
    "books" : {
      "string" : "string"
    },
    "classId" : 0,
    "className" : "string",
    "countBooks" : 0,
    "currentBookName" : "string",
    "currentUnit" : "string",
    "currentWord" : "string",
    "currentWordName" : "string",
    "progress" : "string",
    "schoolId" : 0,
    "schoolName" : "string",
    "theLatesdScore" : 0,
    "unitTestInfos" : [ {
      "isPre" : 0,
      "score" : 0,
      "testtime" : "string",
      "unitName" : "string",
      "unitid" : 0
    } ],
    "userId" : 0,
    "userName" : "string"
  } ],
  "msg" : "string"
}
```


<a name="findallbookswihtuserusingpost"></a>
#### 获得课本列表
```
POST /bookApi/findAllBooksWihtUser
```


##### 说明
获得课本列表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**stage**  <br>*可选*|stage|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**Query**|**version**  <br>*可选*|version|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/bookApi/findAllBooksWihtUser
```


###### 请求 query
```
json :
{
  "stage" : "string",
  "userId" : 0,
  "version" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findunitsbybookidusingpost"></a>
#### 获得课本列表
```
POST /bookApi/findBookUnits
```


##### 说明
获得课本列表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/bookApi/findBookUnits
```


###### 请求 query
```
json :
{
  "bookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getallstageusingpost"></a>
#### 获得所有的阶段
```
POST /bookApi/getAllStage
```


##### 说明
获得所有的阶段


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/bookApi/getAllStage
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getversionsusingpost"></a>
#### 根据阶段获得版本
```
POST /bookApi/getVersions
```


##### 说明
根据阶段获得版本


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**stage**  <br>*可选*|stage|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/bookApi/getVersions
```


###### 请求 query
```
json :
{
  "stage" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="error-recovery-api_resource"></a>
### Error-recovery-api
纠错


<a name="errorrecoveryusingpost"></a>
#### 纠错
```
POST /ErrorRecoveryApi/errorRecovery
```


##### 说明
纠错


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**des**  <br>*可选*|des|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ErrorRecoveryApi/errorRecovery
```


###### 请求 query
```
json :
{
  "des" : "string",
  "userId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="errorrecoveryimgusingpost"></a>
#### 纠错图片上传
```
POST /ErrorRecoveryApi/errorRecoveryImg
```


##### 说明
纠错图片上传


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**FormData**|**img**  <br>*可选*|img|file|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `multipart/form-data`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ErrorRecoveryApi/errorRecoveryImg
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


###### 请求 formData
```
json :
"file"
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="geterrorusingpost"></a>
#### 获得纠错的集合
```
POST /ErrorRecoveryApi/getErrors
```


##### 说明
获得纠错的集合


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**resolved**  <br>*可选*|resolved|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult«ErrorRecovery»](#181331583bf47447985b7ae4b1619941)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ErrorRecoveryApi/getErrors
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "resolved" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ {
    "appUser" : {
      "address" : "string",
      "appUserAccount" : {
        "accumulatePoints" : 0,
        "goldCoins" : 0,
        "id" : 0
      },
      "areaId" : 0,
      "benginStartTime" : "string",
      "birthDay" : "string",
      "booksCount" : 0,
      "cityId" : 0,
      "classInSchool" : {
        "LAY_CHECKED" : true,
        "addUser" : {
          "createTiem" : "string",
          "id" : 0,
          "loginName" : "string",
          "name" : "string",
          "passWord" : "string",
          "roles" : [ {
            "id" : 0,
            "permissionIds" : "string",
            "permissions" : [ {
              "LAY_CHECKED" : true,
              "dataPath" : "string",
              "hasChild" : 0,
              "icon" : "string",
              "id" : 0,
              "lay_CHECKED" : true,
              "menuId" : 0,
              "parentId" : 0,
              "permissonName" : "string",
              "powerList" : [ {
                "LAY_CHECKED" : true,
                "dataPath" : "string",
                "hasChild" : 0,
                "icon" : "string",
                "id" : 0,
                "lay_CHECKED" : true,
                "menuId" : 0,
                "parentId" : 0,
                "permissonName" : "string",
                "powerList" : [ "..." ],
                "powerMenuName" : "string",
                "powerName" : "string",
                "powerUrl" : "string",
                "roles" : [ {
                  "id" : 0,
                  "permissionIds" : "string",
                  "permissions" : [ "..." ],
                  "roleName" : "string"
                } ]
              } ],
              "powerMenuName" : "string",
              "powerName" : "string",
              "powerUrl" : "string",
              "roles" : [ {
                "id" : 0,
                "permissionIds" : "string",
                "permissions" : [ "..." ],
                "roleName" : "string"
              } ]
            } ],
            "roleName" : "string"
          } ],
          "rolesIds" : "string"
        },
        "classInfo" : "string",
        "createTime" : "string",
        "headMaster" : "string",
        "id" : 0,
        "lay_CHECKED" : true,
        "name" : "string",
        "school" : {
          "LAY_CHECKED" : true,
          "address" : "string",
          "agents" : {
            "address" : "string",
            "areaId" : 0,
            "birthDay" : "string",
            "cityId" : 0,
            "detailAddress" : "string",
            "email" : "string",
            "headerImgUrl" : "string",
            "id" : 0,
            "name" : "string",
            "phone" : "string",
            "provinceId" : 0,
            "registerDate" : "string",
            "sex" : 0,
            "user" : {
              "createTiem" : "string",
              "id" : 0,
              "loginName" : "string",
              "name" : "string",
              "passWord" : "string",
              "roles" : [ {
                "id" : 0,
                "permissionIds" : "string",
                "permissions" : [ "..." ],
                "roleName" : "string"
              } ],
              "rolesIds" : "string"
            }
          },
          "areaId" : 0,
          "city" : "string",
          "cityId" : 0,
          "createTime" : "string",
          "detailAddress" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "masterId" : 0,
          "mastername" : "string",
          "name" : "string",
          "phone" : "string",
          "province" : "string",
          "provinceId" : 0,
          "seven" : 0,
          "shcoolDes" : "string",
          "thirty" : 0,
          "uid" : "string",
          "userNumber" : 0
        },
        "studentNum" : 0,
        "withInSevenNUm" : 0,
        "withInTwoNum" : 0
      },
      "classInSchoolId" : 0,
      "hasCompeltedInfo" : true,
      "id" : 0,
      "imgUrl" : "string",
      "isBatchCreate" : 0,
      "lastSignTime" : "string",
      "learnBookWords" : "string",
      "learnTime" : 0,
      "level" : "string",
      "name" : "string",
      "newWordNum" : 0,
      "number1" : "string",
      "number2" : "string",
      "pass64" : "string",
      "password" : "string",
      "phoneForInfo" : "string",
      "phoneNum" : "string",
      "provinceId" : 0,
      "punchCardsDays" : 0,
      "qqNickName" : "string",
      "qqNumber" : "string",
      "qqOpenId" : "string",
      "realNameForInfo" : "string",
      "registerDate" : "string",
      "schoolId" : "string",
      "schoolName" : "string",
      "sex" : 0,
      "sign" : "string",
      "standardDay" : 0,
      "teacher" : "string",
      "thirdImgUrl" : "string",
      "thirdNickName" : "string",
      "todayStudyTime" : "string",
      "totalNewOnlineTime" : "string",
      "totalNewVolidTime" : "string",
      "totalStudyTime" : "string",
      "uid" : "string",
      "wechatNickName" : "string",
      "wechatNum" : "string",
      "wechatOpenId" : "string",
      "weiboNickName" : "string",
      "weiboNumber" : "string",
      "weiboOpenId" : "string",
      "wordNum" : 0,
      "wordsNumReview" : 0
    },
    "bookWord" : {
      "aboutWords" : "string",
      "assistantNotation" : "string",
      "bookName" : "string",
      "englishExample1" : "string",
      "englishExample2" : "string",
      "exampleTranslation1" : "string",
      "exampleTranslation2" : "string",
      "id" : 0,
      "interpretation" : "string",
      "is_right" : true,
      "learnBook" : {
        "bookName" : "string",
        "createTime" : "string",
        "downLoadNum" : 0,
        "download" : 0,
        "grade" : "string",
        "id" : 0,
        "imgUrl" : "string",
        "price" : 0,
        "stage" : "string",
        "updateTime" : "string",
        "version" : "string",
        "wordsNum" : 0
      },
      "right" : true,
      "rootAffixes" : "string",
      "spare1" : "string",
      "spare2" : "string",
      "stage" : "string",
      "unit" : {
        "id" : 0,
        "learnBook" : {
          "bookName" : "string",
          "createTime" : "string",
          "downLoadNum" : 0,
          "download" : 0,
          "grade" : "string",
          "id" : 0,
          "imgUrl" : "string",
          "price" : 0,
          "stage" : "string",
          "updateTime" : "string",
          "version" : "string",
          "wordsNum" : 0
        },
        "name" : "string",
        "passTime" : "string",
        "testScore" : 0,
        "testTime" : "string",
        "unitTestStart" : "string",
        "unitTypeNumber1" : "string",
        "unitTypeNumber2" : "string",
        "unitTypeNumber4" : "string",
        "unitTypeNumber5" : "string",
        "unitTypeNumber6" : "string"
      },
      "unitName" : "string",
      "version" : "string",
      "word" : {
        "aboutWords" : "string",
        "americanPronunciation" : "string",
        "assistantNotation" : "string",
        "englishExample1" : "string",
        "englishExample2" : "string",
        "englishPronunciation" : "string",
        "exampleTranslation1" : "string",
        "exampleTranslation2" : "string",
        "id" : 0,
        "interpretation" : "string",
        "phonetic_symbol" : "string",
        "rootAffixes" : "string",
        "spare1" : "string",
        "spare2" : "string",
        "syllabification" : "string",
        "usaAudioUrl" : "string",
        "word" : "string",
        "wordAudioUrl" : "string"
      },
      "wordName" : "string"
    },
    "createTime" : "string",
    "des" : "string",
    "id" : 0,
    "imgUrl" : "string",
    "isResolved" : 0,
    "reply" : "string",
    "resolvedTime" : "string",
    "user" : {
      "createTiem" : "string",
      "id" : 0,
      "loginName" : "string",
      "name" : "string",
      "passWord" : "string",
      "roles" : [ {
        "id" : 0,
        "permissionIds" : "string",
        "permissions" : [ "..." ],
        "roleName" : "string"
      } ],
      "rolesIds" : "string"
    }
  } ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="excel-api_resource"></a>
### Excel-api
Excel Api


<a name="downloadusingpost"></a>
#### downLoad
```
POST /excel/downLoad
```


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|object|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/excel/downLoad
```


##### HTTP响应示例

###### 响应 200
```
json :
"object"
```


<a name="feed-back-api_resource"></a>
### Feed-back-api
反馈相关的API


<a name="addfeedbackusingpost"></a>
#### addFeedback
```
POST /feedback/addFeedBack
```


##### 说明
添加反馈


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**content**  <br>*可选*|content|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**FormData**|**file1**  <br>*可选*|file1|file|
|**FormData**|**file2**  <br>*可选*|file2|file|
|**FormData**|**file3**  <br>*可选*|file3|file|
|**FormData**|**file4**  <br>*可选*|file4|file|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `multipart/form-data`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/feedback/addFeedBack
```


###### 请求 query
```
json :
{
  "content" : "string",
  "userId" : 0
}
```


###### 请求 formData
```
json :
"file"
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findfeedbacksusingpost"></a>
#### 反馈列表
```
POST /feedback/feedBackList
```


##### 说明
反馈列表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult«FeedBack»](#e59783b7b397fc05ce23c7bd8fbd7408)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/feedback/feedBackList
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ {
    "answerContent" : "string",
    "answerTiem" : "string",
    "answerUser" : {
      "createTiem" : "string",
      "id" : 0,
      "loginName" : "string",
      "name" : "string",
      "passWord" : "string",
      "roles" : [ {
        "id" : 0,
        "permissionIds" : "string",
        "permissions" : [ {
          "LAY_CHECKED" : true,
          "dataPath" : "string",
          "hasChild" : 0,
          "icon" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "menuId" : 0,
          "parentId" : 0,
          "permissonName" : "string",
          "powerList" : [ {
            "LAY_CHECKED" : true,
            "dataPath" : "string",
            "hasChild" : 0,
            "icon" : "string",
            "id" : 0,
            "lay_CHECKED" : true,
            "menuId" : 0,
            "parentId" : 0,
            "permissonName" : "string",
            "powerList" : [ "..." ],
            "powerMenuName" : "string",
            "powerName" : "string",
            "powerUrl" : "string",
            "roles" : [ {
              "id" : 0,
              "permissionIds" : "string",
              "permissions" : [ "..." ],
              "roleName" : "string"
            } ]
          } ],
          "powerMenuName" : "string",
          "powerName" : "string",
          "powerUrl" : "string",
          "roles" : [ {
            "id" : 0,
            "permissionIds" : "string",
            "permissions" : [ "..." ],
            "roleName" : "string"
          } ]
        } ],
        "roleName" : "string"
      } ],
      "rolesIds" : "string"
    },
    "askTime" : "string",
    "askUser" : {
      "address" : "string",
      "appUserAccount" : {
        "accumulatePoints" : 0,
        "goldCoins" : 0,
        "id" : 0
      },
      "areaId" : 0,
      "benginStartTime" : "string",
      "birthDay" : "string",
      "booksCount" : 0,
      "cityId" : 0,
      "classInSchool" : {
        "LAY_CHECKED" : true,
        "addUser" : {
          "createTiem" : "string",
          "id" : 0,
          "loginName" : "string",
          "name" : "string",
          "passWord" : "string",
          "roles" : [ {
            "id" : 0,
            "permissionIds" : "string",
            "permissions" : [ "..." ],
            "roleName" : "string"
          } ],
          "rolesIds" : "string"
        },
        "classInfo" : "string",
        "createTime" : "string",
        "headMaster" : "string",
        "id" : 0,
        "lay_CHECKED" : true,
        "name" : "string",
        "school" : {
          "LAY_CHECKED" : true,
          "address" : "string",
          "agents" : {
            "address" : "string",
            "areaId" : 0,
            "birthDay" : "string",
            "cityId" : 0,
            "detailAddress" : "string",
            "email" : "string",
            "headerImgUrl" : "string",
            "id" : 0,
            "name" : "string",
            "phone" : "string",
            "provinceId" : 0,
            "registerDate" : "string",
            "sex" : 0,
            "user" : {
              "createTiem" : "string",
              "id" : 0,
              "loginName" : "string",
              "name" : "string",
              "passWord" : "string",
              "roles" : [ {
                "id" : 0,
                "permissionIds" : "string",
                "permissions" : [ "..." ],
                "roleName" : "string"
              } ],
              "rolesIds" : "string"
            }
          },
          "areaId" : 0,
          "city" : "string",
          "cityId" : 0,
          "createTime" : "string",
          "detailAddress" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "masterId" : 0,
          "mastername" : "string",
          "name" : "string",
          "phone" : "string",
          "province" : "string",
          "provinceId" : 0,
          "seven" : 0,
          "shcoolDes" : "string",
          "thirty" : 0,
          "uid" : "string",
          "userNumber" : 0
        },
        "studentNum" : 0,
        "withInSevenNUm" : 0,
        "withInTwoNum" : 0
      },
      "classInSchoolId" : 0,
      "hasCompeltedInfo" : true,
      "id" : 0,
      "imgUrl" : "string",
      "isBatchCreate" : 0,
      "lastSignTime" : "string",
      "learnBookWords" : "string",
      "learnTime" : 0,
      "level" : "string",
      "name" : "string",
      "newWordNum" : 0,
      "number1" : "string",
      "number2" : "string",
      "pass64" : "string",
      "password" : "string",
      "phoneForInfo" : "string",
      "phoneNum" : "string",
      "provinceId" : 0,
      "punchCardsDays" : 0,
      "qqNickName" : "string",
      "qqNumber" : "string",
      "qqOpenId" : "string",
      "realNameForInfo" : "string",
      "registerDate" : "string",
      "schoolId" : "string",
      "schoolName" : "string",
      "sex" : 0,
      "sign" : "string",
      "standardDay" : 0,
      "teacher" : "string",
      "thirdImgUrl" : "string",
      "thirdNickName" : "string",
      "todayStudyTime" : "string",
      "totalNewOnlineTime" : "string",
      "totalNewVolidTime" : "string",
      "totalStudyTime" : "string",
      "uid" : "string",
      "wechatNickName" : "string",
      "wechatNum" : "string",
      "wechatOpenId" : "string",
      "weiboNickName" : "string",
      "weiboNumber" : "string",
      "weiboOpenId" : "string",
      "wordNum" : 0,
      "wordsNumReview" : 0
    },
    "content" : "string",
    "id" : 0,
    "ifSolve" : 0,
    "imageInDbForCacheList" : [ {
      "createDate" : "string",
      "id" : 0,
      "imgName" : "string",
      "imgUrl" : "string",
      "size" : 0
    } ]
  } ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findfeedbackdetailusingpost"></a>
#### 反馈详情
```
POST /feedback/feedDetail
```


##### 说明
反馈详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/feedback/feedDetail
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="good-teaches-api_resource"></a>
### Good-teaches-api
Good Teaches Api


<a name="countusingpost"></a>
#### count
```
POST /goodTeaches/count
```


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/goodTeaches/count
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getgoodteachesusingpost"></a>
#### getGoodTeaches
```
POST /goodTeaches/data_list
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult«GoodTeaches»](#5bd4ad597fc3b695376bfa5c1379c739)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/goodTeaches/data_list
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ {
    "id" : 0,
    "imgUrl" : "string",
    "isBought" : 0,
    "score" : 0.0,
    "teacherDes" : "string",
    "teacherName" : "string",
    "title" : "string",
    "url" : "string",
    "wathNum" : 0
  } ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="help-api_resource"></a>
### Help-api
帮助相关


<a name="findhelpdetailusingpost"></a>
#### 获得帮助详情
```
POST /help/getHelpDetail
```


##### 说明
获得帮助详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**id**  <br>*可选*|id|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/help/getHelpDetail
```


###### 请求 query
```
json :
{
  "id" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="gethelplistusingpost"></a>
#### 获得帮助列表
```
POST /help/getHelpList
```


##### 说明
获得帮助列表


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/help/getHelpList
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="integral-api_resource"></a>
### Integral-api
积分相关


<a name="getintegraldesusingpost"></a>
#### 积分的来源和使用说明
```
POST /Integral/getIntegralDes
```


##### 说明
积分的来源和使用说明


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/Integral/getIntegralDes
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalintegraldetailusingpost"></a>
#### 获得个人积分明细
```
POST /Integral/getPersonalIntegralDetail
```


##### 说明
获得个人积分明细


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult](#pageapiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/Integral/getPersonalIntegralDetail
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "limit" : 0,
  "page" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ "object" ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getuserintegralusingpost"></a>
#### 获得用户积分
```
POST /Integral/getUserIntegral
```


##### 说明
获得用户积分


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/Integral/getUserIntegral
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="level-api_resource"></a>
### Level-api
级别相关


<a name="getleveldesusingpost"></a>
#### 获取级别
```
POST /Level/getLevelDes
```


##### 说明
获取级别


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/Level/getLevelDes
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="message-api_resource"></a>
### Message-api
message相关


<a name="deletemessageusingpost"></a>
#### 删除消息
```
POST /messageApi/deleteMessage
```


##### 说明
删除消息


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**messageId**  <br>*可选*|messageId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/deleteMessage
```


###### 请求 query
```
json :
{
  "messageId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getclassmessagenotreadedusingpost"></a>
#### 获得班级消息未读
```
POST /messageApi/getClassMessageNotReaded
```


##### 说明
获得班级消息未读


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult](#pageapiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getClassMessageNotReaded
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ "object" ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getclassmessagereadedusingpost"></a>
#### 获得班级消息已读
```
POST /messageApi/getClassMessageReaded
```


##### 说明
获得班级消息已读


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult](#pageapiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getClassMessageReaded
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ "object" ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getmessagedetailusingpost"></a>
#### 获得消息详情
```
POST /messageApi/getMessageDetail
```


##### 说明
获得消息详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**messageId**  <br>*可选*|messageId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getMessageDetail
```


###### 请求 query
```
json :
{
  "messageId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getsysmessagecountusingpost"></a>
#### 获得系统消息的未读数量
```
POST /messageApi/getSysMessageCount
```


##### 说明
获得系统消息的未读数量


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getSysMessageCount
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getsysmessagenotreadedusingpost"></a>
#### 获得系统未读消息
```
POST /messageApi/getSysMessageNotReaded
```


##### 说明
获得系统未读消息


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult](#pageapiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getSysMessageNotReaded
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ "object" ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getsysmessagereadedusingpost"></a>
#### 获得系统已读消息
```
POST /messageApi/getSysMessageReaded
```


##### 说明
获得系统已读消息


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult](#pageapiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getSysMessageReaded
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ "object" ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getmesssgesusingpost"></a>
#### 获得消息列表
```
POST /messageApi/getUserMessage
```


##### 说明
获得消息列表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**isRead**  <br>*可选*|isRead|integer (int32)|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult«MessageRead»](#5c0d4c33855dfb66d81aad86b9bfe6bd)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getUserMessage
```


###### 请求 query
```
json :
{
  "isRead" : 0,
  "limit" : 0,
  "page" : 0,
  "type" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ {
    "appUser" : {
      "address" : "string",
      "appUserAccount" : {
        "accumulatePoints" : 0,
        "goldCoins" : 0,
        "id" : 0
      },
      "areaId" : 0,
      "benginStartTime" : "string",
      "birthDay" : "string",
      "booksCount" : 0,
      "cityId" : 0,
      "classInSchool" : {
        "LAY_CHECKED" : true,
        "addUser" : {
          "createTiem" : "string",
          "id" : 0,
          "loginName" : "string",
          "name" : "string",
          "passWord" : "string",
          "roles" : [ {
            "id" : 0,
            "permissionIds" : "string",
            "permissions" : [ {
              "LAY_CHECKED" : true,
              "dataPath" : "string",
              "hasChild" : 0,
              "icon" : "string",
              "id" : 0,
              "lay_CHECKED" : true,
              "menuId" : 0,
              "parentId" : 0,
              "permissonName" : "string",
              "powerList" : [ {
                "LAY_CHECKED" : true,
                "dataPath" : "string",
                "hasChild" : 0,
                "icon" : "string",
                "id" : 0,
                "lay_CHECKED" : true,
                "menuId" : 0,
                "parentId" : 0,
                "permissonName" : "string",
                "powerList" : [ "..." ],
                "powerMenuName" : "string",
                "powerName" : "string",
                "powerUrl" : "string",
                "roles" : [ {
                  "id" : 0,
                  "permissionIds" : "string",
                  "permissions" : [ "..." ],
                  "roleName" : "string"
                } ]
              } ],
              "powerMenuName" : "string",
              "powerName" : "string",
              "powerUrl" : "string",
              "roles" : [ {
                "id" : 0,
                "permissionIds" : "string",
                "permissions" : [ "..." ],
                "roleName" : "string"
              } ]
            } ],
            "roleName" : "string"
          } ],
          "rolesIds" : "string"
        },
        "classInfo" : "string",
        "createTime" : "string",
        "headMaster" : "string",
        "id" : 0,
        "lay_CHECKED" : true,
        "name" : "string",
        "school" : {
          "LAY_CHECKED" : true,
          "address" : "string",
          "agents" : {
            "address" : "string",
            "areaId" : 0,
            "birthDay" : "string",
            "cityId" : 0,
            "detailAddress" : "string",
            "email" : "string",
            "headerImgUrl" : "string",
            "id" : 0,
            "name" : "string",
            "phone" : "string",
            "provinceId" : 0,
            "registerDate" : "string",
            "sex" : 0,
            "user" : {
              "createTiem" : "string",
              "id" : 0,
              "loginName" : "string",
              "name" : "string",
              "passWord" : "string",
              "roles" : [ {
                "id" : 0,
                "permissionIds" : "string",
                "permissions" : [ "..." ],
                "roleName" : "string"
              } ],
              "rolesIds" : "string"
            }
          },
          "areaId" : 0,
          "city" : "string",
          "cityId" : 0,
          "createTime" : "string",
          "detailAddress" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "masterId" : 0,
          "mastername" : "string",
          "name" : "string",
          "phone" : "string",
          "province" : "string",
          "provinceId" : 0,
          "seven" : 0,
          "shcoolDes" : "string",
          "thirty" : 0,
          "uid" : "string",
          "userNumber" : 0
        },
        "studentNum" : 0,
        "withInSevenNUm" : 0,
        "withInTwoNum" : 0
      },
      "classInSchoolId" : 0,
      "hasCompeltedInfo" : true,
      "id" : 0,
      "imgUrl" : "string",
      "isBatchCreate" : 0,
      "lastSignTime" : "string",
      "learnBookWords" : "string",
      "learnTime" : 0,
      "level" : "string",
      "name" : "string",
      "newWordNum" : 0,
      "number1" : "string",
      "number2" : "string",
      "pass64" : "string",
      "password" : "string",
      "phoneForInfo" : "string",
      "phoneNum" : "string",
      "provinceId" : 0,
      "punchCardsDays" : 0,
      "qqNickName" : "string",
      "qqNumber" : "string",
      "qqOpenId" : "string",
      "realNameForInfo" : "string",
      "registerDate" : "string",
      "schoolId" : "string",
      "schoolName" : "string",
      "sex" : 0,
      "sign" : "string",
      "standardDay" : 0,
      "teacher" : "string",
      "thirdImgUrl" : "string",
      "thirdNickName" : "string",
      "todayStudyTime" : "string",
      "totalNewOnlineTime" : "string",
      "totalNewVolidTime" : "string",
      "totalStudyTime" : "string",
      "uid" : "string",
      "wechatNickName" : "string",
      "wechatNum" : "string",
      "wechatOpenId" : "string",
      "weiboNickName" : "string",
      "weiboNumber" : "string",
      "weiboOpenId" : "string",
      "wordNum" : 0,
      "wordsNumReview" : 0
    },
    "id" : 0,
    "message" : {
      "classInSchool" : {
        "LAY_CHECKED" : true,
        "addUser" : {
          "createTiem" : "string",
          "id" : 0,
          "loginName" : "string",
          "name" : "string",
          "passWord" : "string",
          "roles" : [ {
            "id" : 0,
            "permissionIds" : "string",
            "permissions" : [ "..." ],
            "roleName" : "string"
          } ],
          "rolesIds" : "string"
        },
        "classInfo" : "string",
        "createTime" : "string",
        "headMaster" : "string",
        "id" : 0,
        "lay_CHECKED" : true,
        "name" : "string",
        "school" : {
          "LAY_CHECKED" : true,
          "address" : "string",
          "agents" : {
            "address" : "string",
            "areaId" : 0,
            "birthDay" : "string",
            "cityId" : 0,
            "detailAddress" : "string",
            "email" : "string",
            "headerImgUrl" : "string",
            "id" : 0,
            "name" : "string",
            "phone" : "string",
            "provinceId" : 0,
            "registerDate" : "string",
            "sex" : 0,
            "user" : {
              "createTiem" : "string",
              "id" : 0,
              "loginName" : "string",
              "name" : "string",
              "passWord" : "string",
              "roles" : [ {
                "id" : 0,
                "permissionIds" : "string",
                "permissions" : [ "..." ],
                "roleName" : "string"
              } ],
              "rolesIds" : "string"
            }
          },
          "areaId" : 0,
          "city" : "string",
          "cityId" : 0,
          "createTime" : "string",
          "detailAddress" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "masterId" : 0,
          "mastername" : "string",
          "name" : "string",
          "phone" : "string",
          "province" : "string",
          "provinceId" : 0,
          "seven" : 0,
          "shcoolDes" : "string",
          "thirty" : 0,
          "uid" : "string",
          "userNumber" : 0
        },
        "studentNum" : 0,
        "withInSevenNUm" : 0,
        "withInTwoNum" : 0
      },
      "createDate" : "string",
      "id" : 0,
      "msgContent" : "string",
      "msgType" : 0,
      "pushState" : 0,
      "relatedId" : 0,
      "sendUser" : {
        "createTiem" : "string",
        "id" : 0,
        "loginName" : "string",
        "name" : "string",
        "passWord" : "string",
        "roles" : [ {
          "id" : 0,
          "permissionIds" : "string",
          "permissions" : [ "..." ],
          "roleName" : "string"
        } ],
        "rolesIds" : "string"
      },
      "title" : "string",
      "url" : "string"
    },
    "state" : 0
  } ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getclassmessagecountusingpost"></a>
#### 获得班级信息的未读数量
```
POST /messageApi/getclassMessageCount
```


##### 说明
获得班级信息的未读数量


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/getclassMessageCount
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getclassmessagenotreadedusingpost_1"></a>
#### 设置消息为已读
```
POST /messageApi/setMessageReaded
```


##### 说明
设置消息为已读


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**messageId**  <br>*可选*|messageId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/messageApi/setMessageReaded
```


###### 请求 query
```
json :
{
  "messageId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="new-review-record-api_resource"></a>
### New-review-record-api
统计新学复习的单词数量


<a name="getreviewrecordnumusingpost"></a>
#### 获得更新复习新学
```
POST /NewReviewRecordApi/getReviewRecordNum
```


##### 说明
获得更新复习新学  
 yyyy-MM-dd HH:mm:ss


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/NewReviewRecordApi/getReviewRecordNum
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "date" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getreviewnumusingpost"></a>
#### 获得统计的新学和复习的个数
```
POST /NewReviewRecordApi/getReviewRecordNums
```


##### 说明
获得统计的新学和复习的个数  
 yyyy-MM-dd HH:mm:ss


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**endTime**  <br>*可选*|endTime|string|
|**Query**|**startTime**  <br>*可选*|startTime|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/NewReviewRecordApi/getReviewRecordNums
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "endTime" : "string",
  "startTime" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="uploadnewreviewrecordusingpost"></a>
#### 更新复习新学
```
POST /NewReviewRecordApi/uploadNewReviewRecord
```


##### 说明
更新复习新学  
 yyyy-MM-dd HH:mm:ss


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**newIds**  <br>*可选*|newIds|string|
|**Query**|**reviewIds**  <br>*可选*|reviewIds|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/NewReviewRecordApi/uploadNewReviewRecord
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "date" : "string",
  "newIds" : "string",
  "reviewIds" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="new-words-api_resource"></a>
### New-words-api
生词本


<a name="addnewwordusingpost"></a>
#### 添加生词
```
POST /newWordsApi/addNewWord
```


##### 说明
添加生词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/addNewWord
```


###### 请求 query
```
json :
{
  "userId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="deleteusingpost"></a>
#### 删除
```
POST /newWordsApi/delete
```


##### 说明
删除


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**newWordId**  <br>*可选*|newWordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/delete
```


###### 请求 query
```
json :
{
  "newWordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="deletenewwordusingpost"></a>
#### 根据用户id删除生词库单词
```
POST /newWordsApi/deleteNewWord
```


##### 说明
根据用户id删除生词库单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookWordId**  <br>*可选*|bookWordId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/deleteNewWord
```


###### 请求 query
```
json :
{
  "bookWordId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findnewwordsusingpost"></a>
#### 获得生词表
```
POST /newWordsApi/findNewWords
```


##### 说明
获得生词表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/findNewWords
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getnewwordnumusingpost"></a>
#### 获得当前的生词个数
```
POST /newWordsApi/getNewWordNum
```


##### 说明
获得当前的生词个数


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/getNewWordNum
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getnewwordshistoryusingpost"></a>
#### 获得生词表的历史
```
POST /newWordsApi/getNewWordsHistory
```


##### 说明
获得生词表的历史


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult](#pageapiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/getNewWordsHistory
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ "object" ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="isaddtowordsusingpost"></a>
#### 单词是否加入生词库
```
POST /newWordsApi/isAddToWords
```


##### 说明
单词是否加入生词库


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookWordId**  <br>*可选*|bookWordId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/isAddToWords
```


###### 请求 query
```
json :
{
  "bookWordId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="setnowtohistoryusingpost"></a>
#### 设置当前的单词为巩固的单词
```
POST /newWordsApi/setNowToHistory
```


##### 说明
设置当前的单词为巩固的单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**newWordId**  <br>*可选*|newWordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/newWordsApi/setNowToHistory
```


###### 请求 query
```
json :
{
  "newWordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="one-word-api_resource"></a>
### One-word-api
名言相关


<a name="getonewordusingpost"></a>
#### 获得当天的名言
```
POST /getOneWord
```


##### 说明
获得当天的名言


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/getOneWord
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getsharecontentusingpost"></a>
#### 获得分享的内容
```
POST /getShareContent
```


##### 说明
获得分享的内容


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/getShareContent
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="sharecallbackusingpost"></a>
#### 分享成功进行调用
```
POST /shareCallback
```


##### 说明
分享成功进行调用


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/shareCallback
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="order-api_resource"></a>
### Order-api
订单相关


<a name="getorderlistusingpost"></a>
#### 获得订单列表
```
POST /orderApi/getOrderList
```


##### 说明
获得订单列表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**limit**  <br>*可选*|limit|integer (int32)|
|**Query**|**page**  <br>*可选*|page|integer (int32)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[PageApiResult«AppUserOrder»](#ddcbc4d95d389c473ed78795180271b6)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/orderApi/getOrderList
```


###### 请求 query
```
json :
{
  "limit" : 0,
  "page" : 0,
  "type" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "allCount" : 0,
  "currentPage" : 0,
  "datas" : [ {
    "appUserAccount" : {
      "accumulatePoints" : 0,
      "goldCoins" : 0,
      "id" : 0
    },
    "changeNum" : 0,
    "createDate" : "string",
    "des" : "string",
    "id" : 0,
    "personalLearnBook" : {
      "appUserNumber" : 0,
      "boughtTime" : "string",
      "buy" : true,
      "currentLeftWords" : "string",
      "currentUnitFinished" : true,
      "currentUnitName" : "string",
      "currentWord" : 0,
      "currentWordNum" : 0,
      "currnetWordname" : "string",
      "extractPoints" : "string",
      "freeBoughtTime" : "string",
      "id" : 0,
      "isCurrentBook" : 0,
      "isFinished" : 0,
      "isPassed" : 0,
      "isPreTested" : 0,
      "lastTestTime" : "string",
      "learnAfterScore" : "string",
      "learnBeforeScore" : "string",
      "learnBook" : {
        "bookName" : "string",
        "createTime" : "string",
        "downLoadNum" : 0,
        "download" : 0,
        "grade" : "string",
        "id" : 0,
        "imgUrl" : "string",
        "price" : 0,
        "stage" : "string",
        "updateTime" : "string",
        "version" : "string",
        "wordsNum" : 0
      },
      "learnedWords" : "string",
      "preScore" : 0,
      "score" : 0,
      "teacherSuggest" : "string",
      "totalWordNum" : 0,
      "unitId" : 0,
      "unitWordProgress" : 0,
      "valiable" : true
    },
    "redeemCode" : {
      "activeTime" : "string",
      "codeMoney" : 0,
      "codeNum" : "string",
      "createTime" : "string",
      "des" : "string",
      "id" : 0,
      "school" : {
        "LAY_CHECKED" : true,
        "address" : "string",
        "agents" : {
          "address" : "string",
          "areaId" : 0,
          "birthDay" : "string",
          "cityId" : 0,
          "detailAddress" : "string",
          "email" : "string",
          "headerImgUrl" : "string",
          "id" : 0,
          "name" : "string",
          "phone" : "string",
          "provinceId" : 0,
          "registerDate" : "string",
          "sex" : 0,
          "user" : {
            "createTiem" : "string",
            "id" : 0,
            "loginName" : "string",
            "name" : "string",
            "passWord" : "string",
            "roles" : [ {
              "id" : 0,
              "permissionIds" : "string",
              "permissions" : [ {
                "LAY_CHECKED" : true,
                "dataPath" : "string",
                "hasChild" : 0,
                "icon" : "string",
                "id" : 0,
                "lay_CHECKED" : true,
                "menuId" : 0,
                "parentId" : 0,
                "permissonName" : "string",
                "powerList" : [ {
                  "LAY_CHECKED" : true,
                  "dataPath" : "string",
                  "hasChild" : 0,
                  "icon" : "string",
                  "id" : 0,
                  "lay_CHECKED" : true,
                  "menuId" : 0,
                  "parentId" : 0,
                  "permissonName" : "string",
                  "powerList" : [ "..." ],
                  "powerMenuName" : "string",
                  "powerName" : "string",
                  "powerUrl" : "string",
                  "roles" : [ {
                    "id" : 0,
                    "permissionIds" : "string",
                    "permissions" : [ "..." ],
                    "roleName" : "string"
                  } ]
                } ],
                "powerMenuName" : "string",
                "powerName" : "string",
                "powerUrl" : "string",
                "roles" : [ {
                  "id" : 0,
                  "permissionIds" : "string",
                  "permissions" : [ "..." ],
                  "roleName" : "string"
                } ]
              } ],
              "roleName" : "string"
            } ],
            "rolesIds" : "string"
          }
        },
        "areaId" : 0,
        "city" : "string",
        "cityId" : 0,
        "createTime" : "string",
        "detailAddress" : "string",
        "id" : 0,
        "lay_CHECKED" : true,
        "masterId" : 0,
        "mastername" : "string",
        "name" : "string",
        "phone" : "string",
        "province" : "string",
        "provinceId" : 0,
        "seven" : 0,
        "shcoolDes" : "string",
        "thirty" : 0,
        "uid" : "string",
        "userNumber" : 0
      },
      "state" : 0,
      "termOfvalidity" : 0,
      "timeOut" : true,
      "upLoadUser" : {
        "createTiem" : "string",
        "id" : 0,
        "loginName" : "string",
        "name" : "string",
        "passWord" : "string",
        "roles" : [ {
          "id" : 0,
          "permissionIds" : "string",
          "permissions" : [ "..." ],
          "roleName" : "string"
        } ],
        "rolesIds" : "string"
      },
      "user" : {
        "address" : "string",
        "appUserAccount" : {
          "accumulatePoints" : 0,
          "goldCoins" : 0,
          "id" : 0
        },
        "areaId" : 0,
        "benginStartTime" : "string",
        "birthDay" : "string",
        "booksCount" : 0,
        "cityId" : 0,
        "classInSchool" : {
          "LAY_CHECKED" : true,
          "addUser" : {
            "createTiem" : "string",
            "id" : 0,
            "loginName" : "string",
            "name" : "string",
            "passWord" : "string",
            "roles" : [ {
              "id" : 0,
              "permissionIds" : "string",
              "permissions" : [ "..." ],
              "roleName" : "string"
            } ],
            "rolesIds" : "string"
          },
          "classInfo" : "string",
          "createTime" : "string",
          "headMaster" : "string",
          "id" : 0,
          "lay_CHECKED" : true,
          "name" : "string",
          "school" : {
            "LAY_CHECKED" : true,
            "address" : "string",
            "agents" : {
              "address" : "string",
              "areaId" : 0,
              "birthDay" : "string",
              "cityId" : 0,
              "detailAddress" : "string",
              "email" : "string",
              "headerImgUrl" : "string",
              "id" : 0,
              "name" : "string",
              "phone" : "string",
              "provinceId" : 0,
              "registerDate" : "string",
              "sex" : 0,
              "user" : {
                "createTiem" : "string",
                "id" : 0,
                "loginName" : "string",
                "name" : "string",
                "passWord" : "string",
                "roles" : [ {
                  "id" : 0,
                  "permissionIds" : "string",
                  "permissions" : [ "..." ],
                  "roleName" : "string"
                } ],
                "rolesIds" : "string"
              }
            },
            "areaId" : 0,
            "city" : "string",
            "cityId" : 0,
            "createTime" : "string",
            "detailAddress" : "string",
            "id" : 0,
            "lay_CHECKED" : true,
            "masterId" : 0,
            "mastername" : "string",
            "name" : "string",
            "phone" : "string",
            "province" : "string",
            "provinceId" : 0,
            "seven" : 0,
            "shcoolDes" : "string",
            "thirty" : 0,
            "uid" : "string",
            "userNumber" : 0
          },
          "studentNum" : 0,
          "withInSevenNUm" : 0,
          "withInTwoNum" : 0
        },
        "classInSchoolId" : 0,
        "hasCompeltedInfo" : true,
        "id" : 0,
        "imgUrl" : "string",
        "isBatchCreate" : 0,
        "lastSignTime" : "string",
        "learnBookWords" : "string",
        "learnTime" : 0,
        "level" : "string",
        "name" : "string",
        "newWordNum" : 0,
        "number1" : "string",
        "number2" : "string",
        "pass64" : "string",
        "password" : "string",
        "phoneForInfo" : "string",
        "phoneNum" : "string",
        "provinceId" : 0,
        "punchCardsDays" : 0,
        "qqNickName" : "string",
        "qqNumber" : "string",
        "qqOpenId" : "string",
        "realNameForInfo" : "string",
        "registerDate" : "string",
        "schoolId" : "string",
        "schoolName" : "string",
        "sex" : 0,
        "sign" : "string",
        "standardDay" : 0,
        "teacher" : "string",
        "thirdImgUrl" : "string",
        "thirdNickName" : "string",
        "todayStudyTime" : "string",
        "totalNewOnlineTime" : "string",
        "totalNewVolidTime" : "string",
        "totalStudyTime" : "string",
        "uid" : "string",
        "wechatNickName" : "string",
        "wechatNum" : "string",
        "wechatOpenId" : "string",
        "weiboNickName" : "string",
        "weiboNumber" : "string",
        "weiboOpenId" : "string",
        "wordNum" : 0,
        "wordsNumReview" : 0
      }
    },
    "relatedId" : 0,
    "title" : "string",
    "type" : 0
  } ],
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="personal-book-api_resource"></a>
### Personal-book-api
个人课本


<a name="addcurrentwordusingpost"></a>
#### 认知当前单词
```
POST /PersonalBookApi/addCurrentWord
```

Caution : 
operation.deprecated


##### 说明
认知当前单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**pesonalLearnBookId**  <br>*可选*|pesonalLearnBookId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/addCurrentWord
```


###### 请求 query
```
json :
{
  "pesonalLearnBookId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="buybookallusingpost"></a>
#### 直接购买图书--无需进行体验
```
POST /PersonalBookApi/buyBookAll
```


##### 说明
直接购买图书


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/buyBookAll
```


###### 请求 query
```
json :
{
  "bookId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="boughtusingpost"></a>
#### 购买图书
```
POST /PersonalBookApi/buyPersonalBook
```


##### 说明
购买图书


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/buyPersonalBook
```


###### 请求 query
```
json :
{
  "bookId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="datasyncusingpost"></a>
#### dataSync
```
POST /PersonalBookApi/dataSync
```


##### 说明
同步文件


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[FileSystemResource](#filesystemresource)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/dataSync
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "description" : "string",
  "file" : "file",
  "filename" : "string",
  "inputStream" : { },
  "open" : true,
  "outputStream" : { },
  "path" : "string",
  "readable" : true,
  "uri" : {
    "absolute" : true,
    "authority" : "string",
    "fragment" : "string",
    "host" : "string",
    "opaque" : true,
    "path" : "string",
    "port" : 0,
    "query" : "string",
    "rawAuthority" : "string",
    "rawFragment" : "string",
    "rawPath" : "string",
    "rawQuery" : "string",
    "rawSchemeSpecificPart" : "string",
    "rawUserInfo" : "string",
    "scheme" : "string",
    "schemeSpecificPart" : "string",
    "userInfo" : "string"
  },
  "url" : {
    "authority" : "string",
    "content" : "object",
    "defaultPort" : 0,
    "file" : "string",
    "host" : "string",
    "path" : "string",
    "port" : 0,
    "protocol" : "string",
    "query" : "string",
    "ref" : "string",
    "userInfo" : "string"
  },
  "writable" : true
}
```


<a name="datasyncusingget"></a>
#### dataSync
```
GET /PersonalBookApi/dataSync
```


##### 说明
同步文件


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[FileSystemResource](#filesystemresource)|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/dataSync
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "description" : "string",
  "file" : "file",
  "filename" : "string",
  "inputStream" : { },
  "open" : true,
  "outputStream" : { },
  "path" : "string",
  "readable" : true,
  "uri" : {
    "absolute" : true,
    "authority" : "string",
    "fragment" : "string",
    "host" : "string",
    "opaque" : true,
    "path" : "string",
    "port" : 0,
    "query" : "string",
    "rawAuthority" : "string",
    "rawFragment" : "string",
    "rawPath" : "string",
    "rawQuery" : "string",
    "rawSchemeSpecificPart" : "string",
    "rawUserInfo" : "string",
    "scheme" : "string",
    "schemeSpecificPart" : "string",
    "userInfo" : "string"
  },
  "url" : {
    "authority" : "string",
    "content" : "object",
    "defaultPort" : 0,
    "file" : "string",
    "host" : "string",
    "path" : "string",
    "port" : 0,
    "protocol" : "string",
    "query" : "string",
    "ref" : "string",
    "userInfo" : "string"
  },
  "writable" : true
}
```


<a name="downloadwordsfileusingpost"></a>
#### downLoadBookWordsFile
```
POST /PersonalBookApi/downLoadBookWordsFile
```


##### 说明
打包下载文件


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[FileSystemResource](#filesystemresource)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/downLoadBookWordsFile
```


###### 请求 query
```
json :
{
  "bookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "description" : "string",
  "file" : "file",
  "filename" : "string",
  "inputStream" : { },
  "open" : true,
  "outputStream" : { },
  "path" : "string",
  "readable" : true,
  "uri" : {
    "absolute" : true,
    "authority" : "string",
    "fragment" : "string",
    "host" : "string",
    "opaque" : true,
    "path" : "string",
    "port" : 0,
    "query" : "string",
    "rawAuthority" : "string",
    "rawFragment" : "string",
    "rawPath" : "string",
    "rawQuery" : "string",
    "rawSchemeSpecificPart" : "string",
    "rawUserInfo" : "string",
    "scheme" : "string",
    "schemeSpecificPart" : "string",
    "userInfo" : "string"
  },
  "url" : {
    "authority" : "string",
    "content" : "object",
    "defaultPort" : 0,
    "file" : "string",
    "host" : "string",
    "path" : "string",
    "port" : 0,
    "protocol" : "string",
    "query" : "string",
    "ref" : "string",
    "userInfo" : "string"
  },
  "writable" : true
}
```


<a name="downloadwordsfileusingget"></a>
#### downLoadBookWordsFile
```
GET /PersonalBookApi/downLoadBookWordsFile
```


##### 说明
打包下载文件


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[FileSystemResource](#filesystemresource)|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/downLoadBookWordsFile
```


###### 请求 query
```
json :
{
  "bookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "description" : "string",
  "file" : "file",
  "filename" : "string",
  "inputStream" : { },
  "open" : true,
  "outputStream" : { },
  "path" : "string",
  "readable" : true,
  "uri" : {
    "absolute" : true,
    "authority" : "string",
    "fragment" : "string",
    "host" : "string",
    "opaque" : true,
    "path" : "string",
    "port" : 0,
    "query" : "string",
    "rawAuthority" : "string",
    "rawFragment" : "string",
    "rawPath" : "string",
    "rawQuery" : "string",
    "rawSchemeSpecificPart" : "string",
    "rawUserInfo" : "string",
    "scheme" : "string",
    "schemeSpecificPart" : "string",
    "userInfo" : "string"
  },
  "url" : {
    "authority" : "string",
    "content" : "object",
    "defaultPort" : 0,
    "file" : "string",
    "host" : "string",
    "path" : "string",
    "port" : 0,
    "protocol" : "string",
    "query" : "string",
    "ref" : "string",
    "userInfo" : "string"
  },
  "writable" : true
}
```


<a name="getbookpriceusingpost"></a>
#### 获得图书的价格
```
POST /PersonalBookApi/getBookPrice
```


##### 说明
获得图书的价格


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/getBookPrice
```


###### 请求 query
```
json :
{
  "bookId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalallbooksusingpost"></a>
#### 获得个人所有的课本
```
POST /PersonalBookApi/personalAllBooks
```


##### 说明
获得个人所有的课本


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/personalAllBooks
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="personalbookswithoutcurrentusingpost"></a>
#### 获得个人除当前的所有课本
```
POST /PersonalBookApi/personalBooksWithOutCurrent
```


##### 说明
获得个人除当前的所有课本


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/personalBooksWithOutCurrent
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="personalcurrentbookusingpost"></a>
#### 获得个人当前课本
```
POST /PersonalBookApi/personalCurrentBook
```


##### 说明
获得个人当前课本


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/personalCurrentBook
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findpersnalunitsusingpost"></a>
#### 获得个人的unit
```
POST /PersonalBookApi/personalUnits
```


##### 说明
获得个人的unit


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**personalBookId**  <br>*可选*|personalBookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/personalUnits
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "bookId" : 0,
  "personalBookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="setcurrentbookusingpost"></a>
#### 设置为当前的课本
```
POST /PersonalBookApi/setCurrentLearnBooks
```


##### 说明
设置为当前的课本


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**personalLeanrBookId**  <br>*可选*|personalLeanrBookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PersonalBookApi/setCurrentLearnBooks
```


###### 请求 query
```
json :
{
  "personalLeanrBookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="personal-test-api_resource"></a>
### Personal-test-api
个人测试相关


<a name="addbooktestusingpost"></a>
#### addBookTest
```
POST /personalBoolTestApi/addBookTest
```


##### 说明
保存用户的的课本测试


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**errorIds**  <br>*可选*|errorIds|string|
|**Query**|**ids**  <br>*可选*|ids|string|
|**Query**|**isPassed**  <br>*可选*|isPassed|integer (int32)|
|**Query**|**isPreLearnTest**  <br>*可选*|isPreLearnTest|integer (int32)|
|**Query**|**personalLearnBooId**  <br>*可选*|personalLearnBooId|integer (int64)|
|**Query**|**rightWordsNum**  <br>*可选*|rightWordsNum|integer (int64)|
|**Query**|**score**  <br>*可选*|score|integer (int32)|
|**Query**|**testDate**  <br>*可选*|testDate|string|
|**Query**|**testRecords**  <br>*可选*|testRecords|string|
|**Query**|**testTime**  <br>*可选*|testTime|integer (int64)|
|**Query**|**testWordsNum**  <br>*可选*|testWordsNum|integer (int64)|
|**Query**|**totalTestTime**  <br>*可选*|totalTestTime|integer (int64)|
|**Query**|**totalWordsNum**  <br>*可选*|totalWordsNum|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/addBookTest
```


###### 请求 query
```
json :
{
  "errorIds" : "string",
  "ids" : "string",
  "isPassed" : 0,
  "isPreLearnTest" : 0,
  "personalLearnBooId" : 0,
  "rightWordsNum" : 0,
  "score" : 0,
  "testDate" : "string",
  "testRecords" : "string",
  "testTime" : 0,
  "testWordsNum" : 0,
  "totalTestTime" : 0,
  "totalWordsNum" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="addreviewtestusingpost"></a>
#### 复习模块--上传测试结果
```
POST /personalBoolTestApi/addReviewTest
```


##### 说明
上传测试结果


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**errorIds**  <br>*可选*|errorIds|string|
|**Query**|**rightIds**  <br>*可选*|rightIds|string|
|**Query**|**state**  <br>*可选*|state|string|
|**Query**|**testUseTime**  <br>*可选*|testUseTime|integer (int64)|
|**Query**|**totalTestTime**  <br>*可选*|totalTestTime|integer (int64)|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/addReviewTest
```


###### 请求 query
```
json :
{
  "errorIds" : "string",
  "rightIds" : "string",
  "state" : "string",
  "testUseTime" : 0,
  "totalTestTime" : 0,
  "unitId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="addunittestusingpost"></a>
#### addUnitTest
```
POST /personalBoolTestApi/addUnitTest
```


##### 说明
保存单元测试的结果--isPassed 2 notPassed  1


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**errorIds**  <br>*可选*|errorIds|string|
|**Query**|**ids**  <br>*可选*|ids|string|
|**Query**|**isPassed**  <br>*可选*|isPassed|integer (int32)|
|**Query**|**personalUnitID**  <br>*可选*|personalUnitID|integer (int64)|
|**Query**|**rightWordsNum**  <br>*可选*|rightWordsNum|integer (int64)|
|**Query**|**score**  <br>*可选*|score|integer (int32)|
|**Query**|**testDate**  <br>*可选*|testDate|string|
|**Query**|**testRecords**  <br>*可选*|testRecords|string|
|**Query**|**testTime**  <br>*可选*|testTime|integer (int64)|
|**Query**|**testWordsNum**  <br>*可选*|testWordsNum|integer (int64)|
|**Query**|**totalTestTime**  <br>*可选*|totalTestTime|integer (int64)|
|**Query**|**totalWordsNum**  <br>*可选*|totalWordsNum|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/addUnitTest
```


###### 请求 query
```
json :
{
  "errorIds" : "string",
  "ids" : "string",
  "isPassed" : 0,
  "personalUnitID" : 0,
  "rightWordsNum" : 0,
  "score" : 0,
  "testDate" : "string",
  "testRecords" : "string",
  "testTime" : 0,
  "testWordsNum" : 0,
  "totalTestTime" : 0,
  "totalWordsNum" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findreviewtestusingpost"></a>
#### 复习模块--查询测试结果
```
POST /personalBoolTestApi/findReviewTest
```


##### 说明
复习模块--查询测试结果


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/findReviewTest
```


###### 请求 query
```
json :
{
  "unitId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findtestdetailusingpost"></a>
#### 获得个人课本的测试记录详情---每个测试题的详情
```
POST /personalBoolTestApi/findTestDetail
```


##### 说明
获得个人课本的测试记录详情--每个测试题的详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookTestId**  <br>*可选*|bookTestId|integer (int64)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|
|**Query**|**unitTestId**  <br>*可选*|unitTestId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/findTestDetail
```


###### 请求 query
```
json :
{
  "bookTestId" : 0,
  "type" : 0,
  "unitTestId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="findtestrulesusingpost"></a>
#### 获取测试规则说明
```
POST /personalBoolTestApi/findTestRules
```


##### 说明
获取测试规则说明


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/findTestRules
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getbooktestwordsusingpost"></a>
#### 获得课本测试的题目详情(单词列表)
```
POST /personalBoolTestApi/getBookTestWords
```


##### 说明
获得课本测试的题目详情(单词列表)


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**isWrongOnly**  <br>*可选*|isWrongOnly|integer (int32)|
|**Query**|**testId**  <br>*可选*|testId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getBookTestWords
```


###### 请求 query
```
json :
{
  "isWrongOnly" : 0,
  "testId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalbooktestsusingpost"></a>
#### 获得个人的课本测试
```
POST /personalBoolTestApi/getPersonalBookTests
```


##### 说明
获得个人的课本测试


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getPersonalBookTests
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalunittestsusingpost"></a>
#### 获得个人单元的测试
```
POST /personalBoolTestApi/getPersonalUnitTests
```


##### 说明
获得个人单元的测试


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**personalLearnBookId**  <br>*可选*|personalLearnBookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getPersonalUnitTests
```


###### 请求 query
```
json :
{
  "personalLearnBookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpeusingpost"></a>
#### 获得个人单元的测试记录-日期
```
POST /personalBoolTestApi/getPersonalUnitTestsRecords
```


##### 说明
获得个人单元的测试记录-日期


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**personalUnitId**  <br>*可选*|personalUnitId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getPersonalUnitTestsRecords
```


###### 请求 query
```
json :
{
  "personalUnitId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalbooktestrecordsusingpost"></a>
#### 获得个人课本的测试记录--日期
```
POST /personalBoolTestApi/getPersonalbookTestRecords
```


##### 说明
获得个人课本的测试记录-日期


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**personalLeanrBookId**  <br>*可选*|personalLeanrBookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getPersonalbookTestRecords
```


###### 请求 query
```
json :
{
  "personalLeanrBookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getunittestdetailsusingpost"></a>
#### 复习模块--个人单元测试情况
```
POST /personalBoolTestApi/getUnitTestDetails
```


##### 说明
复习模块，个人单元测试情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getUnitTestDetails
```


###### 请求 query
```
json :
{
  "bookId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getunittestwordsusingpost"></a>
#### 获得单元测试的题目详情(单词列表)
```
POST /personalBoolTestApi/getUnitTestWords
```


##### 说明
获得单元测试的题目详情(单词列表)


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**isWrongOnly**  <br>*可选*|isWrongOnly|integer (int32)|
|**Query**|**testId**  <br>*可选*|testId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/getUnitTestWords
```


###### 请求 query
```
json :
{
  "isWrongOnly" : 0,
  "testId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="istodaytestbookusingpost"></a>
#### 今天是否测试过了课本
```
POST /personalBoolTestApi/isTodayTestBook
```


##### 说明
今天是否测试过了课本--0未测试   -1已测试


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**personalBookId**  <br>*可选*|personalBookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/isTodayTestBook
```


###### 请求 query
```
json :
{
  "personalBookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="istodaytestunitusingpost"></a>
#### 今天是否测试过了单元
```
POST /personalBoolTestApi/isTodayTestUnit
```


##### 说明
今天是否测试过了单元--0未测试   -1已测试


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/personalBoolTestApi/isTodayTestUnit
```


###### 请求 query
```
json :
{
  "unitId" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="punch-card-api_resource"></a>
### Punch-card-api
打卡相关的api


<a name="getcontinuedusingpost"></a>
#### 获得连续的几天
```
POST /PunchCardApi/getContinued
```


##### 说明
获得连续的几天-【0，0，0，0，0，0，1，0】


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PunchCardApi/getContinued
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpunchcardsdetailusingpost"></a>
#### 获得打卡界面的详情
```
POST /PunchCardApi/getPunchCardsDetail
```


##### 说明
获得打卡界面的详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PunchCardApi/getPunchCardsDetail
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="punchcardusingpost"></a>
#### 打卡
```
POST /PunchCardApi/punchCard
```


##### 说明
打卡


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PunchCardApi/punchCard
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="punchcarddaysusingpost"></a>
#### 获得总的打卡天数-累计打卡
```
POST /PunchCardApi/punchCardDays
```


##### 说明
获得总的打卡天数--返回数字


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/PunchCardApi/punchCardDays
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="ranking-api_resource"></a>
### Ranking-api
排名相关的api


<a name="getonepersonalrankingusingpost"></a>
#### 获得个人的各种排名
```
POST /getOnePersonalRanking
```


##### 说明
获得个人的各种排名


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/getOnePersonalRanking
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "date" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getrankingallusingpost"></a>
#### 获得排名的情况
```
POST /getRankingAll
```


##### 说明
获得排名的情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**provinceId**  <br>*可选*|provinceId|integer (int64)|
|**Query**|**schoolId**  <br>*可选*|schoolId|string|
|**Query**|**topNum**  <br>*可选*|topNum|integer (int32)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/getRankingAll
```


###### 请求 query
```
json :
{
  "date" : "string",
  "provinceId" : 0,
  "schoolId" : "string",
  "topNum" : 0,
  "type" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getrankinginfousingpost"></a>
#### 获得排名的情况
```
POST /getRankingInfo
```


##### 说明
获得排名的情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**topNum**  <br>*可选*|topNum|integer (int32)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/getRankingInfo
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "date" : "string",
  "topNum" : 0,
  "type" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="recharge-api_resource"></a>
### Recharge-api
充值相关


<a name="rechargeusingpost"></a>
#### recharge
```
POST /RechargeApi/recharge
```


##### 说明
充值


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**code**  <br>*可选*|code|string|
|**Query**|**schoolUID**  <br>*可选*|schoolUID|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/RechargeApi/recharge
```


###### 请求 query
```
json :
{
  "code" : "string",
  "schoolUID" : "string",
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="reviews-api_resource"></a>
### Reviews-api
复习相关的api


<a name="findunitsreviewsusingpost"></a>
#### 获得reviews的记录
```
POST /ReviewsApi/findUnitsReviews
```


##### 说明
获得reviews的记录


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ReviewsApi/findUnitsReviews
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "bookId" : 0,
  "type" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getstudytimeusingpost"></a>
#### 获得用户学习时长
```
POST /ReviewsApi/getStudyTime
```


##### 说明
获得用户学习时长


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ReviewsApi/getStudyTime
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getoneusingpost"></a>
#### 获得reviews的记录
```
POST /ReviewsApi/getone
```


##### 说明
获得一个复习的详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserid**  <br>*可选*|appUserid|integer (int64)|
|**Query**|**bookid**  <br>*可选*|bookid|integer (int64)|
|**Query**|**type**  <br>*可选*|type|integer (int32)|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ReviewsApi/getone
```


###### 请求 query
```
json :
{
  "appUserid" : 0,
  "bookid" : 0,
  "type" : 0,
  "unitId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="updatereviewrecordusingpost"></a>
#### 更新review的记录
```
POST /ReviewsApi/updateReviewRecord
```


##### 说明
更新review的记录


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**times**  <br>*可选*|times|string|
|**Query**|**type**  <br>*可选*|type|integer (int32)|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/ReviewsApi/updateReviewRecord
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "bookId" : 0,
  "date" : "string",
  "times" : "string",
  "type" : 0,
  "unitId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="school-api_resource"></a>
### School-api
学校相关


<a name="getschoolsusingpost"></a>
#### schoollist
```
POST /school/schoolList
```


##### 说明
获得学校列表


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/school/schoolList
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="sync-user-learn-info-api_resource"></a>
### Sync-user-learn-info-api
同步个人学习的情况


<a name="getsyncuserlearninfusingpost"></a>
#### getSyncUserLearnInf
```
POST /syncUserLearnInfoApi/getSyncInfo
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/syncUserLearnInfoApi/getSyncInfo
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="synclogininfousingpost"></a>
#### syncLoginInfo
```
POST /syncUserLearnInfoApi/syncLoginInfo
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/syncUserLearnInfoApi/syncLoginInfo
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="syncpersonallearninfousingpost"></a>
#### syncPersonalLearnInfo
```
POST /syncUserLearnInfoApi/syncPersonalLearnInfo
```


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**info**  <br>*可选*|info|string|
|**Query**|**states**  <br>*可选*|states|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/syncUserLearnInfoApi/syncPersonalLearnInfo
```


###### 请求 query
```
json :
{
  "info" : "string",
  "states" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="user-api_resource"></a>
### User-api
用户相关


<a name="bindphonenumusingpost"></a>
#### 绑定手机号
```
POST /appUser/bindPhoneNum
```


##### 说明
绑定手机号


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**codeNum**  <br>*可选*|codeNum|string|
|**Query**|**pass**  <br>*可选*|pass|string|
|**Query**|**phone**  <br>*可选*|phone|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/bindPhoneNum
```


###### 请求 query
```
json :
{
  "codeNum" : "string",
  "pass" : "string",
  "phone" : "string",
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="bindschoolidusingpost"></a>
#### 绑定学校ID
```
POST /appUser/bindSchoolId
```


##### 说明
绑定学校ID


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**schoolId**  <br>*可选*|schoolId|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/bindSchoolId
```


###### 请求 query
```
json :
{
  "schoolId" : "string",
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="bindthirdnumusingpost"></a>
#### 绑定第三方账号
```
POST /appUser/bindThirdNum
```


##### 说明
绑定第三方账号


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**loginType**  <br>*可选*|loginType|integer (int32)|
|**Query**|**openId**  <br>*可选*|openId|string|
|**Query**|**thirdNum**  <br>*可选*|thirdNum|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/bindThirdNum
```


###### 请求 query
```
json :
{
  "loginType" : 0,
  "openId" : "string",
  "thirdNum" : "string",
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="forgetpassusingpost"></a>
#### 忘记密码
```
POST /appUser/forgePass
```


##### 说明
忘记密码


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**code**  <br>*可选*|code|string|
|**Query**|**pass**  <br>*可选*|pass|string|
|**Query**|**phone**  <br>*可选*|phone|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/forgePass
```


###### 请求 query
```
json :
{
  "code" : "string",
  "pass" : "string",
  "phone" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getallcodesusingpost"></a>
#### getAllCodes
```
POST /appUser/getAllCodes
```


##### 说明
获得所有的验证码


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**key**  <br>*可选*|key|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getAllCodes
```


###### 请求 query
```
json :
{
  "key" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="learntimeusingpost"></a>
#### 用户的学习时长
```
POST /appUser/getLearnTime
```


##### 说明
用户在线时长


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getLearnTime
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getleveldesusingpost_1"></a>
#### 获得积分等级说明
```
POST /appUser/getLevelDes
```


##### 说明
获得积分等级说明


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getLevelDes
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getleveldetailusingpost"></a>
#### 获得等级的详细情况
```
POST /appUser/getLevelDetail
```


##### 说明
获得等级的详细情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getLevelDetail
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="onlinetimeusingpost"></a>
#### 用户在线时长
```
POST /appUser/getOnlineTime
```


##### 说明
用户在线时长


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getOnlineTime
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalmealsusingpost"></a>
#### 获得个人的奖牌
```
POST /appUser/getPersonalMeals
```


##### 说明
获得个人的奖牌


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getPersonalMeals
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonalmealsausingpost"></a>
#### 强制的获取奖牌
```
POST /appUser/getPersonalMealsA
```


##### 说明
强制的获取奖牌


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getPersonalMealsA
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getsystemconfigusingpost"></a>
#### 获得系统配置
```
POST /appUser/getSystemConfig
```


##### 说明
获得系统配置


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getSystemConfig
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getaccountdetailusingpost"></a>
#### 获得个人账户信息
```
POST /appUser/getUserAccountDetail
```


##### 说明
获得个人账户信息


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getUserAccountDetail
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getuserdetailusingpost"></a>
#### 获得个人详情
```
POST /appUser/getUserDetail
```


##### 说明
获得个人详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/getUserDetail
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="loginusingpost"></a>
#### login
```
POST /appUser/login
```


##### 说明
登录


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**password**  <br>*可选*|password|string|
|**Query**|**phone**  <br>*可选*|phone|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/login
```


###### 请求 query
```
json :
{
  "password" : "string",
  "phone" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="registusingpost"></a>
#### 注册
```
POST /appUser/regist
```


##### 说明
注册


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**pass**  <br>*可选*|pass|string|
|**Query**|**phone**  <br>*可选*|phone|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/regist
```


###### 请求 query
```
json :
{
  "pass" : "string",
  "phone" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="sendcodeusingpost"></a>
#### 发送验证码
```
POST /appUser/sendCode
```


##### 说明
发送验证码


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**phone**  <br>*可选*|phone|string|
|**Query**|**type**  <br>*可选*|type|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/sendCode
```


###### 请求 query
```
json :
{
  "phone" : "string",
  "type" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="setpassusingpost"></a>
#### 设置密码
```
POST /appUser/setPass
```


##### 说明
设置密码


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**pass**  <br>*可选*|pass|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/setPass
```


###### 请求 query
```
json :
{
  "pass" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="thirdloginusingpost"></a>
#### 第三方登录
```
POST /appUser/thirdLogin
```


##### 说明
第三方登录  登录的类型 1:微信2:微博3：QQ


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**headerImgUrl**  <br>*可选*|headerImgUrl|string|
|**Query**|**loginType**  <br>*可选*|loginType|integer (int32)|
|**Query**|**nickName**  <br>*可选*|nickName|string|
|**Query**|**openId**  <br>*可选*|openId|string|
|**Query**|**thirdNum**  <br>*可选*|thirdNum|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/thirdLogin
```


###### 请求 query
```
json :
{
  "headerImgUrl" : "string",
  "loginType" : 0,
  "nickName" : "string",
  "openId" : "string",
  "thirdNum" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="unbindthirdnumusingpost"></a>
#### 解绑第三方账号
```
POST /appUser/unBindThirdNum
```


##### 说明
解绑第三方账号


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**type**  <br>*可选*|type|integer (int32)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/unBindThirdNum
```


###### 请求 query
```
json :
{
  "type" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="updateuserinfousingpost"></a>
#### 完善用户的信息
```
POST /appUser/updateUserInfo
```


##### 说明
完善用户信息


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**areaId**  <br>*可选*|areaId|integer (int64)|
|**Query**|**birthDay**  <br>*可选*|birthDay|string|
|**Query**|**cityId**  <br>*可选*|cityId|integer (int64)|
|**Query**|**classInSchoolId**  <br>*可选*|classInSchoolId|integer (int64)|
|**Query**|**id**  <br>*可选*|id|integer (int64)|
|**Query**|**name**  <br>*可选*|name|string|
|**Query**|**provinceId**  <br>*可选*|provinceId|integer (int64)|
|**Query**|**sex**  <br>*可选*|sex|integer (int32)|
|**Query**|**sign**  <br>*可选*|sign|string|
|**FormData**|**headerFile**  <br>*可选*|headerFile|file|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `multipart/form-data`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/updateUserInfo
```


###### 请求 query
```
json :
{
  "areaId" : 0,
  "birthDay" : "string",
  "cityId" : 0,
  "classInSchoolId" : 0,
  "id" : 0,
  "name" : "string",
  "provinceId" : 0,
  "sex" : 0,
  "sign" : "string"
}
```


###### 请求 formData
```
json :
"file"
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="uploaduserimagusingpost"></a>
#### 上传用户头像
```
POST /appUser/uploadUserImag
```


##### 说明
上传用户头像


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**FormData**|**img**  <br>*可选*|img|file|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `multipart/form-data`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/uploadUserImag
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


###### 请求 formData
```
json :
"file"
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="verifycodeusingpost"></a>
#### 校验验证码
```
POST /appUser/verifyCode
```


##### 说明
校验验证码


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**code**  <br>*可选*|code|string|
|**Query**|**phone**  <br>*可选*|phone|string|
|**Query**|**type**  <br>*可选*|type|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/appUser/verifyCode
```


###### 请求 query
```
json :
{
  "code" : "string",
  "phone" : "string",
  "type" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="word-count-api_resource"></a>
### Word-count-api
数据统计-发现


<a name="getunitcountusingpost"></a>
#### wordCount
```
POST /wordCount/getLearnTimeCount
```


##### 说明
数据统计-发现


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/wordCount/getLearnTimeCount
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getnewandreviewsinfosusingpost"></a>
#### newAndReviewsInfos
```
POST /wordCount/newAndReviewsInfos
```


##### 说明
新学和复习的统计


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/wordCount/newAndReviewsInfos
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="word-favorite-api_resource"></a>
### Word-favorite-api
单词收藏相关的Api


<a name="addwordfavorusingpost"></a>
#### 单词收藏
```
POST /wordFavor/addWordFavor
```


##### 说明
收藏单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/wordFavor/addWordFavor
```


###### 请求 query
```
json :
{
  "userId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="delwordfavorusingpost"></a>
#### 移除收藏的单词
```
POST /wordFavor/delWordFavor
```


##### 说明
移除用户收藏的单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/wordFavor/delWordFavor
```


###### 请求 query
```
json :
{
  "userId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getwordfavorusingpost"></a>
#### 查询收藏的单词
```
POST /wordFavor/getWordFavor
```


##### 说明
查询用户收藏的单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/wordFavor/getWordFavor
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="isfavusingpost"></a>
#### 单词是否收藏
```
POST /wordFavor/isFav
```


##### 说明
单词是否收藏


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/wordFavor/isFav
```


###### 请求 query
```
json :
{
  "userId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="word-learn-api_resource"></a>
### Word-learn-api
单词学习相关的Api


<a name="addlearnwordusingpost"></a>
#### 添加学习的单词
```
POST /userwordLearn/addLearnWord
```


##### 说明
添加学习的单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**isSuccess**  <br>*可选*|isSuccess|integer (int32)|
|**Query**|**state**  <br>*可选*|state|integer (int32)|
|**Query**|**time**  <br>*可选*|time|integer (int32)|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|
|**Query**|**wordId**  <br>*可选*|wordId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/addLearnWord
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "date" : "string",
  "isSuccess" : 0,
  "state" : 0,
  "time" : 0,
  "unitId" : 0,
  "wordId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="addlearnwordusingpost_1"></a>
#### 批量添加学习的单词
```
POST /userwordLearn/batchAddlearnWord
```


##### 说明
批量添加学习的单词


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**isSuccesses**  <br>*可选*|isSuccesses|string|
|**Query**|**states**  <br>*可选*|states|string|
|**Query**|**times**  <br>*可选*|times|string|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|
|**Query**|**words**  <br>*可选*|words|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/batchAddlearnWord
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "date" : "string",
  "isSuccesses" : "string",
  "states" : "string",
  "times" : "string",
  "unitId" : 0,
  "words" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getcertainlearningstateusingpost"></a>
#### 获取某人的学习状态
```
POST /userwordLearn/getCertainLearningState
```


##### 说明
获取某人的学习状态


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|string|
|**Query**|**unitId**  <br>*可选*|unitId|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/getCertainLearningState
```


###### 请求 query
```
json :
{
  "appUserId" : "string",
  "unitId" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getlearntimeusingpost"></a>
#### 获得个人有效的学习时间
```
POST /userwordLearn/getLearnTime
```


##### 说明
获得个人有效的学习时间；；yyyy-MM-dd hh:mm:ss


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**date**  <br>*可选*|date|string|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/getLearnTime
```


###### 请求 query
```
json :
{
  "date" : "string",
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getmustreviewlistusingpost"></a>
#### 获得需要强制复习的单元列表
```
POST /userwordLearn/getMustReviewList
```


##### 说明
获得需要强制复习的单元列表


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/getMustReviewList
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getallbookunitidsusingpost"></a>
#### 获得课本的学习情况
```
POST /userwordLearn/getPersonalLearnDetail
```


##### 说明
获得课本的学习情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/getPersonalLearnDetail
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "bookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonallearndetailallusingpost"></a>
#### 获得个人学习的详情---所有
```
POST /userwordLearn/getPersonalLearnDetailAll
```


##### 说明
获得个人学习的详情


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/getPersonalLearnDetailAll
```


###### 请求 query
```
json :
{
  "appUserId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="getpersonallearninfousingpost"></a>
#### 获得个人每天学习情况
```
POST /userwordLearn/getPersonalLearnInfo
```


##### 说明
获得个人每天学习情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/getPersonalLearnInfo
```


###### 请求 query
```
json :
{
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="setcurrentbookusingpost_1"></a>
#### 保存当前的bookId
```
POST /userwordLearn/setCurrentBook
```


##### 说明
保存当前的bookId


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/setCurrentBook
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "bookId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="updatepersoanllearndetailusingpost"></a>
#### 更新课本的学习情况
```
POST /userwordLearn/updatePersoanlLearnDetail
```


##### 说明
获得课本的学习情况


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**allUnitIds**  <br>*可选*|allUnitIds|string|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**currentUnitId**  <br>*可选*|currentUnitId|integer (int64)|
|**Query**|**isFinished**  <br>*可选*|isFinished|integer (int32)|
|**Query**|**leftUnitIDs**  <br>*可选*|leftUnitIDs|string|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/updatePersoanlLearnDetail
```


###### 请求 query
```
json :
{
  "allUnitIds" : "string",
  "appUserId" : 0,
  "bookId" : 0,
  "currentUnitId" : 0,
  "isFinished" : 0,
  "leftUnitIDs" : "string"
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="updatepersonallearnunitstateusingpost"></a>
#### 更新学习的unit
```
POST /userwordLearn/updatePersonalLearnUnitState
```


##### 说明
更新学习的unit/state:0失败1成功2开始学习 
 isLasteUnit:0不是1是 
wordNum 当前单元的单词个数


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**appUserId**  <br>*可选*|appUserId|integer (int64)|
|**Query**|**bookId**  <br>*可选*|bookId|integer (int64)|
|**Query**|**isLastUnit**  <br>*可选*|isLastUnit|integer (int32)|
|**Query**|**lastWordIds**  <br>*可选*|lastWordIds|string|
|**Query**|**leftWords**  <br>*可选*|leftWords|string|
|**Query**|**nextLearnStage**  <br>*可选*|nextLearnStage|integer (int32)|
|**Query**|**stageIds**  <br>*可选*|stageIds|string|
|**Query**|**state**  <br>*可选*|state|integer (int32)|
|**Query**|**unitId**  <br>*可选*|unitId|integer (int64)|
|**Query**|**wordNum**  <br>*可选*|wordNum|integer (int32)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/updatePersonalLearnUnitState
```


###### 请求 query
```
json :
{
  "appUserId" : 0,
  "bookId" : 0,
  "isLastUnit" : 0,
  "lastWordIds" : "string",
  "leftWords" : "string",
  "nextLearnStage" : 0,
  "stageIds" : "string",
  "state" : 0,
  "unitId" : 0,
  "wordNum" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```


<a name="uploadlearntimeusingpost"></a>
#### 上传个人有效的学习时间
```
POST /userwordLearn/uploadLearnTime
```


##### 说明
上传个人有效的学习时间


##### 参数

|类型|名称|说明|类型|
|---|---|---|---|
|**Query**|**time**  <br>*可选*|time|integer (int64)|
|**Query**|**userId**  <br>*可选*|userId|integer (int64)|


##### 响应

|HTTP代码|说明|类型|
|---|---|---|
|**200**|OK|[ApiResult](#apiresult)|
|**201**|Created|无内容|
|**401**|Unauthorized|无内容|
|**403**|Forbidden|无内容|
|**404**|Not Found|无内容|


##### 消耗

* `application/json`


##### 生成

* `*/*`


##### HTTP请求示例

###### 请求 path
```
/userwordLearn/uploadLearnTime
```


###### 请求 query
```
json :
{
  "time" : 0,
  "userId" : 0
}
```


##### HTTP响应示例

###### 响应 200
```
json :
{
  "data" : "object",
  "msg" : "string",
  "msgCode" : 0
}
```



