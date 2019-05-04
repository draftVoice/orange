## Functions

<dl>
<dt><a href="#find">find(arr, callback)</a> ⇒ <code>*</code></dt>
<dd><p>find</p>
</dd>
<dt><a href="#every">every(arr, fn)</a> ⇒ <code>Boolean</code></dt>
<dd><p>every</p>
</dd>
<dt><a href="#some">some(arr, fn)</a> ⇒ <code>Boolean</code></dt>
<dd><p>some</p>
</dd>
<dt><a href="#once">once(fn)</a> ⇒ <code>function</code></dt>
<dd><p>once</p>
</dd>
<dt><a href="#isObj">isObj(obj)</a> ⇒ <code>Boolean</code></dt>
<dd><p>isObj</p>
</dd>
<dt><a href="#isArray">isArray(obj)</a> ⇒ <code>Boolean</code></dt>
<dd><p>isArray</p>
</dd>
<dt><a href="#distinctValuesOfArray">distinctValuesOfArray(arr)</a> ⇒ <code>Array</code></dt>
<dd><p>Returns all the distinct values of an array.</p>
</dd>
<dt><a href="#timeTaken">timeTaken(callback)</a> ⇒ <code>*</code></dt>
<dd><p>Measures the time taken by a function to execute.</p>
</dd>
<dt><a href="#randomColor">randomColor()</a> ⇒ <code>String</code></dt>
<dd><p>生成随机颜色</p>
</dd>
<dt><a href="#randomString">randomString(length)</a> ⇒ <code>String</code></dt>
<dd><p>生成随机字符串</p>
</dd>
<dt><a href="#checkStringType">checkStringType(str, type)</a> ⇒ <code>Boolean</code></dt>
<dd></dd>
<dt><a href="#randomNum">randomNum(Min, Max)</a> ⇒ <code>Number</code></dt>
<dd><p>生成随机数.</p>
</dd>
<dt><a href="#quickSort">quickSort(arr)</a> ⇒ <code>Array</code></dt>
<dd><p>数组排序.</p>
</dd>
<dt><a href="#base64">base64()</a> ⇒ <code>String</code></dt>
<dd><p>Base64加密</p>
</dd>
<dt><a href="#md5">md5()</a> ⇒ <code>String</code></dt>
<dd><p>MD5加密（Message-Digest Algorithm 5 ／ 消息摘要算法）</p>
</dd>
<dt><a href="#sha1">sha1()</a> ⇒ <code>String</code></dt>
<dd><p>sha1加密（Secure Hash Algorithm ／ 安全哈希算法）</p>
</dd>
</dl>

<a name="find"></a>

## find(arr, callback) ⇒ <code>\*</code>
find

**Kind**: global function  

| Param | Type |
| --- | --- |
| arr | <code>Array</code> | 
| callback | <code>function</code> | 

<a name="every"></a>

## every(arr, fn) ⇒ <code>Boolean</code>
every

**Kind**: global function  

| Param | Type |
| --- | --- |
| arr | <code>Array</code> | 
| fn | <code>function</code> | 

<a name="some"></a>

## some(arr, fn) ⇒ <code>Boolean</code>
some

**Kind**: global function  

| Param | Type |
| --- | --- |
| arr | <code>Array</code> | 
| fn | <code>function</code> | 

<a name="once"></a>

## once(fn) ⇒ <code>function</code>
once

**Kind**: global function  

| Param | Type |
| --- | --- |
| fn | <code>function</code> | 

<a name="isObj"></a>

## isObj(obj) ⇒ <code>Boolean</code>
isObj

**Kind**: global function  

| Param | Type |
| --- | --- |
| obj | <code>\*</code> | 

<a name="isArray"></a>

## isArray(obj) ⇒ <code>Boolean</code>
isArray

**Kind**: global function  

| Param | Type |
| --- | --- |
| obj | <code>\*</code> | 

<a name="distinctValuesOfArray"></a>

## distinctValuesOfArray(arr) ⇒ <code>Array</code>
Returns all the distinct values of an array.

**Kind**: global function  
**Returns**: <code>Array</code> - - new array  

| Param | Type | Description |
| --- | --- | --- |
| arr | <code>Array</code> | source array |

<a name="timeTaken"></a>

## timeTaken(callback) ⇒ <code>\*</code>
Measures the time taken by a function to execute.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| callback | <code>function</code> | callback function |

<a name="randomColor"></a>

## randomColor() ⇒ <code>String</code>
生成随机颜色

**Kind**: global function  
<a name="randomString"></a>

## randomString(length) ⇒ <code>String</code>
生成随机字符串

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| length | <code>Number</code> | 随机字符串长度 |

<a name="checkStringType"></a>

## checkStringType(str, type) ⇒ <code>Boolean</code>
**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| str | <code>String</code> | 被检测的字符串 |
| type | <code>String</code> | 检测类型 |

<a name="randomNum"></a>

## randomNum(Min, Max) ⇒ <code>Number</code>
生成随机数.

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| Min | <code>Number</code> | 最小值 |
| Max | <code>Number</code> | 最大值 |

<a name="quickSort"></a>

## quickSort(arr) ⇒ <code>Array</code>
数组排序.

**Kind**: global function  
**Returns**: <code>Array</code> - - new array  

| Param | Type | Description |
| --- | --- | --- |
| arr | <code>Array</code> | source array |

<a name="base64"></a>

## base64() ⇒ <code>String</code>
Base64加密

**Kind**: global function  
**Example**  
```js
let base64 = new pumelo.base64();
加密
base64.encode("some string");
解密
base64.decode(base64.encode("some string"));
```
<a name="md5"></a>

## md5() ⇒ <code>String</code>
MD5加密（Message-Digest Algorithm 5 ／ 消息摘要算法）

**Kind**: global function  
**Example**  
```js
let md5 = new pumelo.md5()
加密
md5.hex_md5("some string")
```
<a name="sha1"></a>

## sha1() ⇒ <code>String</code>
sha1加密（Secure Hash Algorithm ／ 安全哈希算法）

**Kind**: global function  
**Example**  
```js
let sha1 = new pumelo.sha1()
加密
sha1.hex_sha1("some string")
```