
<a name="definitions"></a>
## 定义

<a name="agents"></a>
### Agents

|名称|说明|类型|
|---|---|---|
|**address**  <br>*可选*|**样例** : `"string"`|string|
|**areaId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**birthDay**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**cityId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**detailAddress**  <br>*可选*|**样例** : `"string"`|string|
|**email**  <br>*可选*|**样例** : `"string"`|string|
|**headerImgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**phone**  <br>*可选*|**样例** : `"string"`|string|
|**provinceId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**registerDate**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**sex**  <br>*可选*|**样例** : `0`|integer (int32)|
|**user**  <br>*可选*|**样例** : `"[user](#user)"`|[User](#user)|


<a name="apiresult"></a>
### ApiResult

|名称|说明|类型|
|---|---|---|
|**data**  <br>*可选*|**样例** : `"object"`|object|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="appuser"></a>
### AppUser

|名称|说明|类型|
|---|---|---|
|**address**  <br>*可选*|**样例** : `"string"`|string|
|**appUserAccount**  <br>*可选*|**样例** : `"[appuseraccount](#appuseraccount)"`|[AppUserAccount](#appuseraccount)|
|**areaId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**benginStartTime**  <br>*可选*|**样例** : `"string"`|string|
|**birthDay**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**booksCount**  <br>*可选*|**样例** : `0`|integer (int32)|
|**cityId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**classInSchool**  <br>*可选*|**样例** : `"[classinschool](#classinschool)"`|[ClassInSchool](#classinschool)|
|**classInSchoolId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**hasCompeltedInfo**  <br>*可选*|**样例** : `true`|boolean|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**imgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**isBatchCreate**  <br>*可选*|**样例** : `0`|integer (int32)|
|**lastSignTime**  <br>*可选*|**样例** : `"string"`|string|
|**learnBookWords**  <br>*可选*|**样例** : `"string"`|string|
|**learnTime**  <br>*可选*|**样例** : `0`|integer (int64)|
|**level**  <br>*可选*|**样例** : `"string"`|string|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**newWordNum**  <br>*可选*|**样例** : `0`|integer (int64)|
|**number1**  <br>*可选*|**样例** : `"string"`|string|
|**number2**  <br>*可选*|**样例** : `"string"`|string|
|**pass64**  <br>*可选*|**样例** : `"string"`|string|
|**password**  <br>*可选*|**样例** : `"string"`|string|
|**phoneForInfo**  <br>*可选*|**样例** : `"string"`|string|
|**phoneNum**  <br>*可选*|**样例** : `"string"`|string|
|**provinceId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**punchCardsDays**  <br>*可选*|**样例** : `0`|integer (int32)|
|**qqNickName**  <br>*可选*|**样例** : `"string"`|string|
|**qqNumber**  <br>*可选*|**样例** : `"string"`|string|
|**qqOpenId**  <br>*可选*|**样例** : `"string"`|string|
|**realNameForInfo**  <br>*可选*|**样例** : `"string"`|string|
|**registerDate**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**schoolId**  <br>*可选*|**样例** : `"string"`|string|
|**schoolName**  <br>*可选*|**样例** : `"string"`|string|
|**sex**  <br>*可选*|**样例** : `0`|integer (int32)|
|**sign**  <br>*可选*|**样例** : `"string"`|string|
|**standardDay**  <br>*可选*|**样例** : `0`|integer (int64)|
|**teacher**  <br>*可选*|**样例** : `"string"`|string|
|**thirdImgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**thirdNickName**  <br>*可选*|**样例** : `"string"`|string|
|**todayStudyTime**  <br>*可选*|**样例** : `"string"`|string|
|**totalNewOnlineTime**  <br>*可选*|**样例** : `"string"`|string|
|**totalNewVolidTime**  <br>*可选*|**样例** : `"string"`|string|
|**totalStudyTime**  <br>*可选*|**样例** : `"string"`|string|
|**uid**  <br>*可选*|**样例** : `"string"`|string|
|**wechatNickName**  <br>*可选*|**样例** : `"string"`|string|
|**wechatNum**  <br>*可选*|**样例** : `"string"`|string|
|**wechatOpenId**  <br>*可选*|**样例** : `"string"`|string|
|**weiboNickName**  <br>*可选*|**样例** : `"string"`|string|
|**weiboNumber**  <br>*可选*|**样例** : `"string"`|string|
|**weiboOpenId**  <br>*可选*|**样例** : `"string"`|string|
|**wordNum**  <br>*可选*|**样例** : `0`|integer (int64)|
|**wordsNumReview**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="appuseraccount"></a>
### AppUserAccount

|名称|说明|类型|
|---|---|---|
|**accumulatePoints**  <br>*可选*|**样例** : `0`|integer (int64)|
|**goldCoins**  <br>*可选*|**样例** : `0`|integer (int32)|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="appuserorder"></a>
### AppUserOrder

|名称|说明|类型|
|---|---|---|
|**appUserAccount**  <br>*可选*|**样例** : `"[appuseraccount](#appuseraccount)"`|[AppUserAccount](#appuseraccount)|
|**changeNum**  <br>*可选*|**样例** : `0`|integer (int32)|
|**createDate**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**des**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**personalLearnBook**  <br>*可选*|**样例** : `"[personallearnbook](#personallearnbook)"`|[PersonalLearnBook](#personallearnbook)|
|**redeemCode**  <br>*可选*|**样例** : `"[redeemcode](#redeemcode)"`|[RedeemCode](#redeemcode)|
|**relatedId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**title**  <br>*可选*|**样例** : `"string"`|string|
|**type**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="appusershowinfobean"></a>
### AppUserShowInfoBean

|名称|说明|类型|
|---|---|---|
|**bookTestInfos**  <br>*可选*|**样例** : `[ "[booktestinfo](#booktestinfo)" ]`|< [BookTestInfo](#booktestinfo) > array|
|**books**  <br>*可选*|**样例** : `{<br>  "string" : "string"<br>}`|< string, string > map|
|**classId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**className**  <br>*可选*|**样例** : `"string"`|string|
|**countBooks**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentBookName**  <br>*可选*|**样例** : `"string"`|string|
|**currentUnit**  <br>*可选*|**样例** : `"string"`|string|
|**currentWord**  <br>*可选*|**样例** : `"string"`|string|
|**currentWordName**  <br>*可选*|**样例** : `"string"`|string|
|**progress**  <br>*可选*|**样例** : `"string"`|string|
|**schoolId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**schoolName**  <br>*可选*|**样例** : `"string"`|string|
|**theLatesdScore**  <br>*可选*|**样例** : `0`|integer (int32)|
|**unitTestInfos**  <br>*可选*|**样例** : `[ "[unittestinfo](#unittestinfo)" ]`|< [UnitTestInfo](#unittestinfo) > array|
|**userId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**userName**  <br>*可选*|**样例** : `"string"`|string|


<a name="booktestinfo"></a>
### BookTestInfo

|名称|说明|类型|
|---|---|---|
|**bookId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**bookName**  <br>*可选*|**样例** : `"string"`|string|
|**isPre**  <br>*可选*|**样例** : `0`|integer (int32)|
|**score**  <br>*可选*|**样例** : `0`|integer (int32)|
|**testDate**  <br>*可选*|**样例** : `"string"`|string (date-time)|


<a name="bookunit"></a>
### BookUnit

|名称|说明|类型|
|---|---|---|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**learnBook**  <br>*可选*|**样例** : `"[learnbook](#learnbook)"`|[LearnBook](#learnbook)|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**passTime**  <br>*可选*|**样例** : `"string"`|string|
|**testScore**  <br>*可选*|**样例** : `0`|integer (int32)|
|**testTime**  <br>*可选*|**样例** : `"string"`|string|
|**unitTestStart**  <br>*可选*|**样例** : `"string"`|string|
|**unitTypeNumber1**  <br>*可选*|**样例** : `"string"`|string|
|**unitTypeNumber2**  <br>*可选*|**样例** : `"string"`|string|
|**unitTypeNumber4**  <br>*可选*|**样例** : `"string"`|string|
|**unitTypeNumber5**  <br>*可选*|**样例** : `"string"`|string|
|**unitTypeNumber6**  <br>*可选*|**样例** : `"string"`|string|


<a name="bookword"></a>
### BookWord

|名称|说明|类型|
|---|---|---|
|**aboutWords**  <br>*可选*|**样例** : `"string"`|string|
|**assistantNotation**  <br>*可选*|**样例** : `"string"`|string|
|**bookName**  <br>*可选*|**样例** : `"string"`|string|
|**englishExample1**  <br>*可选*|**样例** : `"string"`|string|
|**englishExample2**  <br>*可选*|**样例** : `"string"`|string|
|**exampleTranslation1**  <br>*可选*|**样例** : `"string"`|string|
|**exampleTranslation2**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**interpretation**  <br>*可选*|**样例** : `"string"`|string|
|**is_right**  <br>*可选*|**样例** : `true`|boolean|
|**learnBook**  <br>*可选*|**样例** : `"[learnbook](#learnbook)"`|[LearnBook](#learnbook)|
|**right**  <br>*可选*|**样例** : `true`|boolean|
|**rootAffixes**  <br>*可选*|**样例** : `"string"`|string|
|**spare1**  <br>*可选*|**样例** : `"string"`|string|
|**spare2**  <br>*可选*|**样例** : `"string"`|string|
|**stage**  <br>*可选*|**样例** : `"string"`|string|
|**unit**  <br>*可选*|**样例** : `"[bookunit](#bookunit)"`|[BookUnit](#bookunit)|
|**unitName**  <br>*可选*|**样例** : `"string"`|string|
|**version**  <br>*可选*|**样例** : `"string"`|string|
|**word**  <br>*可选*|**样例** : `"[word](#word)"`|[Word](#word)|
|**wordName**  <br>*可选*|**样例** : `"string"`|string|


<a name="classinschool"></a>
### ClassInSchool

|名称|说明|类型|
|---|---|---|
|**LAY_CHECKED**  <br>*可选*|**样例** : `true`|boolean|
|**addUser**  <br>*可选*|**样例** : `"[user](#user)"`|[User](#user)|
|**classInfo**  <br>*可选*|**样例** : `"string"`|string|
|**createTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**headMaster**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**lay_CHECKED**  <br>*可选*|**样例** : `true`|boolean|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**school**  <br>*可选*|**样例** : `"[school](#school)"`|[School](#school)|
|**studentNum**  <br>*可选*|**样例** : `0`|integer (int32)|
|**withInSevenNUm**  <br>*可选*|**样例** : `0`|integer (int32)|
|**withInTwoNum**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="errorrecovery"></a>
### ErrorRecovery

|名称|说明|类型|
|---|---|---|
|**appUser**  <br>*可选*|**样例** : `"[appuser](#appuser)"`|[AppUser](#appuser)|
|**bookWord**  <br>*可选*|**样例** : `"[bookword](#bookword)"`|[BookWord](#bookword)|
|**createTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**des**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**imgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**isResolved**  <br>*可选*|**样例** : `0`|integer (int32)|
|**reply**  <br>*可选*|**样例** : `"string"`|string|
|**resolvedTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**user**  <br>*可选*|**样例** : `"[user](#user)"`|[User](#user)|


<a name="feedback"></a>
### FeedBack

|名称|说明|类型|
|---|---|---|
|**answerContent**  <br>*可选*|**样例** : `"string"`|string|
|**answerTiem**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**answerUser**  <br>*可选*|**样例** : `"[user](#user)"`|[User](#user)|
|**askTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**askUser**  <br>*可选*|**样例** : `"[appuser](#appuser)"`|[AppUser](#appuser)|
|**content**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**ifSolve**  <br>*可选*|**样例** : `0`|integer (int32)|
|**imageInDbForCacheList**  <br>*可选*|**样例** : `[ "[imageindbforcache](#imageindbforcache)" ]`|< [ImageInDbForCache](#imageindbforcache) > array|


<a name="file"></a>
### File

|名称|说明|类型|
|---|---|---|
|**absolute**  <br>*可选*|**样例** : `true`|boolean|
|**absoluteFile**  <br>*可选*|**样例** : `"file"`|file|
|**absolutePath**  <br>*可选*|**样例** : `"string"`|string|
|**canonicalFile**  <br>*可选*|**样例** : `"file"`|file|
|**canonicalPath**  <br>*可选*|**样例** : `"string"`|string|
|**directory**  <br>*可选*|**样例** : `true`|boolean|
|**file**  <br>*可选*|**样例** : `true`|boolean|
|**freeSpace**  <br>*可选*|**样例** : `0`|integer (int64)|
|**hidden**  <br>*可选*|**样例** : `true`|boolean|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**parent**  <br>*可选*|**样例** : `"string"`|string|
|**parentFile**  <br>*可选*|**样例** : `"file"`|file|
|**path**  <br>*可选*|**样例** : `"string"`|string|
|**totalSpace**  <br>*可选*|**样例** : `0`|integer (int64)|
|**usableSpace**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="filesystemresource"></a>
### FileSystemResource

|名称|说明|类型|
|---|---|---|
|**description**  <br>*可选*|**样例** : `"string"`|string|
|**file**  <br>*可选*|**样例** : `"file"`|file|
|**filename**  <br>*可选*|**样例** : `"string"`|string|
|**inputStream**  <br>*可选*|**样例** : `"[inputstream](#inputstream)"`|[InputStream](#inputstream)|
|**open**  <br>*可选*|**样例** : `true`|boolean|
|**outputStream**  <br>*可选*|**样例** : `"[outputstream](#outputstream)"`|[OutputStream](#outputstream)|
|**path**  <br>*可选*|**样例** : `"string"`|string|
|**readable**  <br>*可选*|**样例** : `true`|boolean|
|**uri**  <br>*可选*|**样例** : `"[uri](#uri)"`|[URI](#uri)|
|**url**  <br>*可选*|**样例** : `"[url](#url)"`|[URL](#url)|
|**writable**  <br>*可选*|**样例** : `true`|boolean|


<a name="goodteaches"></a>
### GoodTeaches

|名称|说明|类型|
|---|---|---|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**imgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**isBought**  <br>*可选*|**样例** : `0`|integer (int32)|
|**score**  <br>*可选*|**样例** : `0.0`|number (double)|
|**teacherDes**  <br>*可选*|**样例** : `"string"`|string|
|**teacherName**  <br>*可选*|**样例** : `"string"`|string|
|**title**  <br>*可选*|**样例** : `"string"`|string|
|**url**  <br>*可选*|**样例** : `"string"`|string|
|**wathNum**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="imageindbforcache"></a>
### ImageInDbForCache

|名称|说明|类型|
|---|---|---|
|**createDate**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**imgName**  <br>*可选*|**样例** : `"string"`|string|
|**imgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**size**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="inputstream"></a>
### InputStream
*类型* : object


<a name="64208abcc996c5e1c6ddd01700043576"></a>
### LayPageResult«AppUserShowInfoBean»

|名称|说明|类型|
|---|---|---|
|**code**  <br>*可选*|**样例** : `0`|integer (int32)|
|**count**  <br>*可选*|**样例** : `0`|integer (int64)|
|**data**  <br>*可选*|**样例** : `[ "[appusershowinfobean](#appusershowinfobean)" ]`|< [AppUserShowInfoBean](#appusershowinfobean) > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|


<a name="learnbook"></a>
### LearnBook

|名称|说明|类型|
|---|---|---|
|**bookName**  <br>*可选*|**样例** : `"string"`|string|
|**createTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**downLoadNum**  <br>*可选*|**样例** : `0`|integer (int64)|
|**download**  <br>*可选*|**样例** : `0`|integer (int32)|
|**grade**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**imgUrl**  <br>*可选*|**样例** : `"string"`|string|
|**price**  <br>*可选*|**样例** : `0`|integer (int32)|
|**stage**  <br>*可选*|**样例** : `"string"`|string|
|**updateTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**version**  <br>*可选*|**样例** : `"string"`|string|
|**wordsNum**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="message"></a>
### Message

|名称|说明|类型|
|---|---|---|
|**classInSchool**  <br>*可选*|**样例** : `"[classinschool](#classinschool)"`|[ClassInSchool](#classinschool)|
|**createDate**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**msgContent**  <br>*可选*|**样例** : `"string"`|string|
|**msgType**  <br>*可选*|**样例** : `0`|integer (int32)|
|**pushState**  <br>*可选*|**样例** : `0`|integer (int32)|
|**relatedId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**sendUser**  <br>*可选*|**样例** : `"[user](#user)"`|[User](#user)|
|**title**  <br>*可选*|**样例** : `"string"`|string|
|**url**  <br>*可选*|**样例** : `"string"`|string|


<a name="messageread"></a>
### MessageRead

|名称|说明|类型|
|---|---|---|
|**appUser**  <br>*可选*|**样例** : `"[appuser](#appuser)"`|[AppUser](#appuser)|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**message**  <br>*可选*|**样例** : `"[message](#message)"`|[Message](#message)|
|**state**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="outputstream"></a>
### OutputStream
*类型* : object


<a name="pageapiresult"></a>
### PageApiResult

|名称|说明|类型|
|---|---|---|
|**allCount**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentPage**  <br>*可选*|**样例** : `0`|integer (int32)|
|**datas**  <br>*可选*|**样例** : `[ "object" ]`|< object > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="ddcbc4d95d389c473ed78795180271b6"></a>
### PageApiResult«AppUserOrder»

|名称|说明|类型|
|---|---|---|
|**allCount**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentPage**  <br>*可选*|**样例** : `0`|integer (int32)|
|**datas**  <br>*可选*|**样例** : `[ "[appuserorder](#appuserorder)" ]`|< [AppUserOrder](#appuserorder) > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="181331583bf47447985b7ae4b1619941"></a>
### PageApiResult«ErrorRecovery»

|名称|说明|类型|
|---|---|---|
|**allCount**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentPage**  <br>*可选*|**样例** : `0`|integer (int32)|
|**datas**  <br>*可选*|**样例** : `[ "[errorrecovery](#errorrecovery)" ]`|< [ErrorRecovery](#errorrecovery) > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="e59783b7b397fc05ce23c7bd8fbd7408"></a>
### PageApiResult«FeedBack»

|名称|说明|类型|
|---|---|---|
|**allCount**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentPage**  <br>*可选*|**样例** : `0`|integer (int32)|
|**datas**  <br>*可选*|**样例** : `[ "[feedback](#feedback)" ]`|< [FeedBack](#feedback) > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="5bd4ad597fc3b695376bfa5c1379c739"></a>
### PageApiResult«GoodTeaches»

|名称|说明|类型|
|---|---|---|
|**allCount**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentPage**  <br>*可选*|**样例** : `0`|integer (int32)|
|**datas**  <br>*可选*|**样例** : `[ "[goodteaches](#goodteaches)" ]`|< [GoodTeaches](#goodteaches) > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="5c0d4c33855dfb66d81aad86b9bfe6bd"></a>
### PageApiResult«MessageRead»

|名称|说明|类型|
|---|---|---|
|**allCount**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentPage**  <br>*可选*|**样例** : `0`|integer (int32)|
|**datas**  <br>*可选*|**样例** : `[ "[messageread](#messageread)" ]`|< [MessageRead](#messageread) > array|
|**msg**  <br>*可选*|**样例** : `"string"`|string|
|**msgCode**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="permission"></a>
### Permission

|名称|说明|类型|
|---|---|---|
|**LAY_CHECKED**  <br>*可选*|**样例** : `true`|boolean|
|**dataPath**  <br>*可选*|**样例** : `"string"`|string|
|**hasChild**  <br>*可选*|**样例** : `0`|integer (int32)|
|**icon**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**lay_CHECKED**  <br>*可选*|**样例** : `true`|boolean|
|**menuId**  <br>*可选*|**样例** : `0`|integer (int32)|
|**parentId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**permissonName**  <br>*可选*|**样例** : `"string"`|string|
|**powerList**  <br>*可选*|**样例** : `[ "[permission](#permission)" ]`|< [Permission](#permission) > array|
|**powerMenuName**  <br>*可选*|**样例** : `"string"`|string|
|**powerName**  <br>*可选*|**样例** : `"string"`|string|
|**powerUrl**  <br>*可选*|**样例** : `"string"`|string|
|**roles**  <br>*可选*|**样例** : `[ "[roles](#roles)" ]`|< [Roles](#roles) > array|


<a name="personallearnbook"></a>
### PersonalLearnBook

|名称|说明|类型|
|---|---|---|
|**appUserNumber**  <br>*可选*|**样例** : `0`|integer (int32)|
|**boughtTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**buy**  <br>*可选*|**样例** : `true`|boolean|
|**currentLeftWords**  <br>*可选*|**样例** : `"string"`|string|
|**currentUnitFinished**  <br>*可选*|**样例** : `true`|boolean|
|**currentUnitName**  <br>*可选*|**样例** : `"string"`|string|
|**currentWord**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currentWordNum**  <br>*可选*|**样例** : `0`|integer (int64)|
|**currnetWordname**  <br>*可选*|**样例** : `"string"`|string|
|**extractPoints**  <br>*可选*|**样例** : `"string"`|string|
|**freeBoughtTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**isCurrentBook**  <br>*可选*|**样例** : `0`|integer (int32)|
|**isFinished**  <br>*可选*|**样例** : `0`|integer (int32)|
|**isPassed**  <br>*可选*|**样例** : `0`|integer (int32)|
|**isPreTested**  <br>*可选*|**样例** : `0`|integer (int32)|
|**lastTestTime**  <br>*可选*|**样例** : `"string"`|string|
|**learnAfterScore**  <br>*可选*|**样例** : `"string"`|string|
|**learnBeforeScore**  <br>*可选*|**样例** : `"string"`|string|
|**learnBook**  <br>*可选*|**样例** : `"[learnbook](#learnbook)"`|[LearnBook](#learnbook)|
|**learnedWords**  <br>*可选*|**样例** : `"string"`|string|
|**preScore**  <br>*可选*|**样例** : `0`|integer (int32)|
|**score**  <br>*可选*|**样例** : `0`|integer (int32)|
|**teacherSuggest**  <br>*可选*|**样例** : `"string"`|string|
|**totalWordNum**  <br>*可选*|**样例** : `0`|integer (int64)|
|**unitId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**unitWordProgress**  <br>*可选*|**样例** : `0`|integer (int64)|
|**valiable**  <br>*可选*|**样例** : `true`|boolean|


<a name="redeemcode"></a>
### RedeemCode

|名称|说明|类型|
|---|---|---|
|**activeTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**codeMoney**  <br>*可选*|**样例** : `0`|integer (int32)|
|**codeNum**  <br>*可选*|**样例** : `"string"`|string|
|**createTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**des**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**school**  <br>*可选*|**样例** : `"[school](#school)"`|[School](#school)|
|**state**  <br>*可选*|**样例** : `0`|integer (int32)|
|**termOfvalidity**  <br>*可选*|**样例** : `0`|integer (int32)|
|**timeOut**  <br>*可选*|**样例** : `true`|boolean|
|**upLoadUser**  <br>*可选*|**样例** : `"[user](#user)"`|[User](#user)|
|**user**  <br>*可选*|**样例** : `"[appuser](#appuser)"`|[AppUser](#appuser)|


<a name="roles"></a>
### Roles

|名称|说明|类型|
|---|---|---|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**permissionIds**  <br>*可选*|**样例** : `"string"`|string|
|**permissions**  <br>*可选*|**样例** : `[ "[permission](#permission)" ]`|< [Permission](#permission) > array|
|**roleName**  <br>*可选*|**样例** : `"string"`|string|


<a name="school"></a>
### School

|名称|说明|类型|
|---|---|---|
|**LAY_CHECKED**  <br>*可选*|**样例** : `true`|boolean|
|**address**  <br>*可选*|**样例** : `"string"`|string|
|**agents**  <br>*可选*|**样例** : `"[agents](#agents)"`|[Agents](#agents)|
|**areaId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**city**  <br>*可选*|**样例** : `"string"`|string|
|**cityId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**createTime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**detailAddress**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**lay_CHECKED**  <br>*可选*|**样例** : `true`|boolean|
|**masterId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**mastername**  <br>*可选*|**样例** : `"string"`|string|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**phone**  <br>*可选*|**样例** : `"string"`|string|
|**province**  <br>*可选*|**样例** : `"string"`|string|
|**provinceId**  <br>*可选*|**样例** : `0`|integer (int64)|
|**seven**  <br>*可选*|**样例** : `0`|integer (int32)|
|**shcoolDes**  <br>*可选*|**样例** : `"string"`|string|
|**thirty**  <br>*可选*|**样例** : `0`|integer (int32)|
|**uid**  <br>*可选*|**样例** : `"string"`|string|
|**userNumber**  <br>*可选*|**样例** : `0`|integer (int32)|


<a name="uri"></a>
### URI

|名称|说明|类型|
|---|---|---|
|**absolute**  <br>*可选*|**样例** : `true`|boolean|
|**authority**  <br>*可选*|**样例** : `"string"`|string|
|**fragment**  <br>*可选*|**样例** : `"string"`|string|
|**host**  <br>*可选*|**样例** : `"string"`|string|
|**opaque**  <br>*可选*|**样例** : `true`|boolean|
|**path**  <br>*可选*|**样例** : `"string"`|string|
|**port**  <br>*可选*|**样例** : `0`|integer (int32)|
|**query**  <br>*可选*|**样例** : `"string"`|string|
|**rawAuthority**  <br>*可选*|**样例** : `"string"`|string|
|**rawFragment**  <br>*可选*|**样例** : `"string"`|string|
|**rawPath**  <br>*可选*|**样例** : `"string"`|string|
|**rawQuery**  <br>*可选*|**样例** : `"string"`|string|
|**rawSchemeSpecificPart**  <br>*可选*|**样例** : `"string"`|string|
|**rawUserInfo**  <br>*可选*|**样例** : `"string"`|string|
|**scheme**  <br>*可选*|**样例** : `"string"`|string|
|**schemeSpecificPart**  <br>*可选*|**样例** : `"string"`|string|
|**userInfo**  <br>*可选*|**样例** : `"string"`|string|


<a name="url"></a>
### URL

|名称|说明|类型|
|---|---|---|
|**authority**  <br>*可选*|**样例** : `"string"`|string|
|**content**  <br>*可选*|**样例** : `"object"`|object|
|**defaultPort**  <br>*可选*|**样例** : `0`|integer (int32)|
|**file**  <br>*可选*|**样例** : `"string"`|string|
|**host**  <br>*可选*|**样例** : `"string"`|string|
|**path**  <br>*可选*|**样例** : `"string"`|string|
|**port**  <br>*可选*|**样例** : `0`|integer (int32)|
|**protocol**  <br>*可选*|**样例** : `"string"`|string|
|**query**  <br>*可选*|**样例** : `"string"`|string|
|**ref**  <br>*可选*|**样例** : `"string"`|string|
|**userInfo**  <br>*可选*|**样例** : `"string"`|string|


<a name="unittestinfo"></a>
### UnitTestInfo

|名称|说明|类型|
|---|---|---|
|**isPre**  <br>*可选*|**样例** : `0`|integer (int32)|
|**score**  <br>*可选*|**样例** : `0`|integer (int32)|
|**testtime**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**unitName**  <br>*可选*|**样例** : `"string"`|string|
|**unitid**  <br>*可选*|**样例** : `0`|integer (int64)|


<a name="user"></a>
### User

|名称|说明|类型|
|---|---|---|
|**createTiem**  <br>*可选*|**样例** : `"string"`|string (date-time)|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**loginName**  <br>*可选*|**样例** : `"string"`|string|
|**name**  <br>*可选*|**样例** : `"string"`|string|
|**passWord**  <br>*可选*|**样例** : `"string"`|string|
|**roles**  <br>*可选*|**样例** : `[ "[roles](#roles)" ]`|< [Roles](#roles) > array|
|**rolesIds**  <br>*可选*|**样例** : `"string"`|string|


<a name="word"></a>
### Word

|名称|说明|类型|
|---|---|---|
|**aboutWords**  <br>*可选*|**样例** : `"string"`|string|
|**americanPronunciation**  <br>*可选*|**样例** : `"string"`|string|
|**assistantNotation**  <br>*可选*|**样例** : `"string"`|string|
|**englishExample1**  <br>*可选*|**样例** : `"string"`|string|
|**englishExample2**  <br>*可选*|**样例** : `"string"`|string|
|**englishPronunciation**  <br>*可选*|**样例** : `"string"`|string|
|**exampleTranslation1**  <br>*可选*|**样例** : `"string"`|string|
|**exampleTranslation2**  <br>*可选*|**样例** : `"string"`|string|
|**id**  <br>*可选*|**样例** : `0`|integer (int64)|
|**interpretation**  <br>*可选*|**样例** : `"string"`|string|
|**phonetic_symbol**  <br>*可选*|**样例** : `"string"`|string|
|**rootAffixes**  <br>*可选*|**样例** : `"string"`|string|
|**spare1**  <br>*可选*|**样例** : `"string"`|string|
|**spare2**  <br>*可选*|**样例** : `"string"`|string|
|**syllabification**  <br>*可选*|**样例** : `"string"`|string|
|**usaAudioUrl**  <br>*可选*|**样例** : `"string"`|string|
|**word**  <br>*可选*|**样例** : `"string"`|string|
|**wordAudioUrl**  <br>*可选*|**样例** : `"string"`|string|



