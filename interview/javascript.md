1. [JavaScript�ı������ڶ���ʱ��Ҫ������Щ����](https://github.com/pwstrick/daily/issues/246)
2. [���ܱ�encodeURIComponent()����������ַ�����Щ��](https://github.com/pwstrick/daily/issues/247)
3. [��λ��SelectԪ�أ�ѡ�����ѡ�����������](https://github.com/pwstrick/daily/issues/248)
4. [JavaScript�����ö�������Щ��](https://github.com/pwstrick/daily/issues/249)
5. [���Ϊһ��\<p>Ԫ�����CSS��primary��](https://github.com/pwstrick/daily/issues/250)
6. [�������ص��¼�����Щ��](https://github.com/pwstrick/daily/issues/251)
7. [���ͨ��jQuery�ķ�ʽ��ô����е�ѡ���ѡ��ֵ��](https://github.com/pwstrick/daily/issues/252)
8. [ִ������Ĵ��룬�ڿ���̨�����xΪ__________��yΪ__________��](https://github.com/pwstrick/daily/issues/253)
```javascript
var x = 0, y = 0;
x
++
y
console.log(x, y);
```
9. [������������еĺ��������շ��صĽ��Ϊ__________��](https://github.com/pwstrick/daily/issues/254)
```javascript
function isArray() {
  return
  true;
}
isArray();
```
10. [ִ������Ĵ�����ڿ���̨�����yΪ__________��](https://github.com/pwstrick/daily/issues/255)
```javascript
var y,
  x = 1;
y = x+++x;
```
11. [2+true����__________��'6'+9����__________��](https://github.com/pwstrick/daily/issues/256)
12. [4+3+2+"1"����__________��"1"+2+4����__________��](https://github.com/pwstrick/daily/issues/257)
13. [(1, 5 - 1) * 2 ����__________��](https://github.com/pwstrick/daily/issues/258)
14. [ִ������Ĵ�����ڿ���̨�����yΪ__________��](https://github.com/pwstrick/daily/issues/259)
```javascript
var x = "1", y;
switch (x) {
  case 1:
    y = 1;
    break;
  case 2:
    y = 2;
    break;
  default:
    y = 0;
}
console.log(y);
```
15. [!function(){}�ķ���ֵ��__________��](https://github.com/pwstrick/daily/issues/260)
16. [7 - "a"����__________��7 / 0����__________��](https://github.com/pwstrick/daily/issues/261)
17. [3..toFixed(2)�õ��Ľ��Ϊ__________��](https://github.com/pwstrick/daily/issues/262)
18. [parseFloat('12.3.4')���صĽ��Ϊ__________��](https://github.com/pwstrick/daily/issues/263)
19. [Number(012)���صĽ��Ϊ__________��Number("0xA")���صĽ��Ϊ__________��](https://github.com/pwstrick/daily/issues/264)
20. [������Ĵ����У�Number()�����Ĳ�����һ���������յĽ��Ϊ__________��](https://github.com/pwstrick/daily/issues/265)
```javascript
var numberObj = {
  valueOf: function() {
    return {};
  },
  toString: function() {
    return "10";
  }
};
Number(numberObj);
```
21. [~{}����__________��~1.25����__________��](https://github.com/pwstrick/daily/issues/266)
22. [���´��������ڿ���̨����Ľ��Ϊ__________��](https://github.com/pwstrick/daily/issues/267)
```javascript
var a = {},
  b = { name: "ping" },
  c = { name: "wen" };
a[b] = 10;
a[c] = 20;
console.log(a[b]);
```
23. [[] == ![]�õ��Ľ��Ϊ__________��](https://github.com/pwstrick/daily/issues/268)
24. [[] + {}�õ��Ľ��Ϊ__________��{} + []�õ��Ľ��Ϊ__________��](https://github.com/pwstrick/daily/issues/269)
25. [Array.prototype.isPrototypeOf([1, 2])�Ľ��Ϊ__________��](https://github.com/pwstrick/daily/issues/270)
26. [����������յĴ�ӡ�����__________��](https://github.com/pwstrick/daily/issues/271)
```javascript
var obj1 = {
  names: []
};
var obj2 = obj1.names;
obj2.push("strick");
console.log(obj1.names);
```
27. [������Ĵ����У�����������test()�������õ��Ľ���ֱ���__________��__________ ��__________��](https://github.com/pwstrick/daily/issues/272)
```javascript
var str = "pw1",
  pattern1 = /\d/,
  pattern2 = /\d/g;
pattern1.test(str);
pattern2.test(str);
pattern2.test(str);
```
28. [ִ������Ĵ����arr1.lengthΪ__________��](https://github.com/pwstrick/daily/issues/273)
```javascript
var arr1 = "ping".split(""),
  arr2 = arr1.reverse(),
  arr3 = "pw".split("");
arr2.push(arr3);
```
29. [ִ������Ĵ����arr�����ֵΪ__________��](https://github.com/pwstrick/daily/issues/274)
```javascript
var arr = [4, 1, 5, 2, 3];
arr.sort(function(a, b) {
  return a > b;
});
```
30. [[1, 2, 3, 4, 5].splice(-2)��ֵΪ__________��](https://github.com/pwstrick/daily/issues/275)
31. [[1, 2, 3, 4, 5].slice(NaN, 1)��ֵΪ__________��](https://github.com/pwstrick/daily/issues/276)
32. [�������ִ�к��ڿ���̨�����b�������õ��Ľ����__________��](https://github.com/pwstrick/daily/issues/277)
```javascript
(function() {
  var a = b = 5;
})();
console.log(b);
```
33. [1 instanceof Number�ķ���ֵ��__________��2 in [1,2]�ķ���ֵ��__________��](https://github.com/pwstrick/daily/issues/278)
34. [typeof undefined�ķ���ֵ��__________��typeof null�ķ���ֵ��__________��](https://github.com/pwstrick/daily/issues/279)
35. [��Object��toString()�����ֱ�Ӧ����null��undefined��������ʾ�����õ��Ľ��Ϊ__________��__________��](https://github.com/pwstrick/daily/issues/280)
```javascript
var toString = Object.prototype.toString;
toString.call(null);
toString.call(undefined);
```
36. [ִ������Ĵ��룬��������˳����__________��__________�� __________��](https://github.com/pwstrick/daily/issues/281)
```javascript
console.log(1);
setTimeout(function() {
  console.log(2);
}, 0);
console.log(3);
```
37. [�������һ�����JavaScript����⡣](https://github.com/pwstrick/daily/issues/4)
38. [JavaScript����Щ���ƺ����ƣ�](https://github.com/pwstrick/daily/issues/282)
39. [��ȣ�==����ȫ�ȣ�===�����������Щ����](https://github.com/pwstrick/daily/issues/283)
40. [��JavaScript�У���������ָʲô��](https://github.com/pwstrick/daily/issues/284)
41. [�ֺŻ���ʲôʱ���Զ���ȫ���Զ���ȫ��ʲô�׶ˣ�](https://github.com/pwstrick/daily/issues/285)
42. [ʲô���ϸ�ģʽ���ϸ�ģʽ����Щ���ƣ�](https://github.com/pwstrick/daily/issues/286)
43. [undefined��null������Щ��ͬ��](https://github.com/pwstrick/daily/issues/287)
44. [��˵��JavaScript�е�ԭ������native objects������������host objects����](https://github.com/pwstrick/daily/issues/288)
45. [ȫ�ֺ���eval()��ʲô���ã�](https://github.com/pwstrick/daily/issues/289)
46. [�������һ����������ԭ������](https://github.com/pwstrick/daily/issues/290)
47. [��new�������������ʱ������new Fn()������Ĵ����������ļ�����](https://github.com/pwstrick/daily/issues/291)
48. [JSON��ʽ��������XML��ʽ��������ȣ�����Щ���ƣ�](https://github.com/pwstrick/daily/issues/292)
49. [���������ͺ������ʽ����Щ����](https://github.com/pwstrick/daily/issues/293)
50. [Function����������Щ���ܣ�](https://github.com/pwstrick/daily/issues/294)
51. [ִ������Ĵ��룬Ϊ������Ķ���3��](https://github.com/pwstrick/daily/issues/295)
```javascript
for (var i = 0; i < 3; i++) {
  setTimeout(function() {
    console.log(i);
  }, 0);
}
```
52. [��̸̸��Ահ�����⡣](https://github.com/pwstrick/daily/issues/296)
53. [ʲô���¼�ѭ����](https://github.com/pwstrick/daily/issues/297)
54. [���һ��ȫ�ֱ���û��������������ô�ڿ���̨�ܷ��������ֵ��](https://github.com/pwstrick/daily/issues/298)
55. [����ýű���ȡ��ǰ��ʾ���ķֱ��ʣ�](https://github.com/pwstrick/daily/issues/299)
56. [document.write()��innerHTML����Щ����](https://github.com/pwstrick/daily/issues/300)
57. [�����һ��DocumentFragment���͵Ľڵ㡣](https://github.com/pwstrick/daily/issues/301)
58. [HTMLԪ�ص����Ժ���������ô����ģ�](https://github.com/pwstrick/daily/issues/302)
59. [jQuery����Щ��ɫ��](https://github.com/pwstrick/daily/issues/303)
60. [��jQuery������Щ��������ɾ��Ԫ�ء�](https://github.com/pwstrick/daily/issues/304)
61. [jQuery UI��ʲô��](https://github.com/pwstrick/daily/issues/305)
62. [����JavaScriptʵ��ð������](https://github.com/pwstrick/daily/issues/306)
63. [��ʵ��һ��������100��ѭ�������ܱ�3����ʱ�����three�������ܱ�5����ʱ��� ��five��������ͬʱ��3��5����ʱ�����all����](https://github.com/pwstrick/daily/issues/307)
64. [��װһ��isInteger()���������ڼ�⴫���ֵ��������](https://github.com/pwstrick/daily/issues/308)
65. [�����·�װһ��isNaN2()�������˺����ֲ���ȫ�ֺ���isNaN()�Ĳ��㡣](https://github.com/pwstrick/daily/issues/309)
66. [��дһ�����������������������С����ȷ��ˡ�](https://github.com/pwstrick/daily/issues/310)
67. [ͳ���ַ�����xxxxyyydda����ÿ����ĸ���ֵĴ�����](https://github.com/pwstrick/daily/issues/311)
68. [ִ��a == 1 && a == 2 && a == 3�����صĽ����true����ôa��ֵ��ʲô��](https://github.com/pwstrick/daily/issues/312)
69. [����ж϶����е�ĳ�������Ǽ̳ж����ģ�](https://github.com/pwstrick/daily/issues/313)
70. [�����JavaScriptʵ�ֶ���̳У�](https://github.com/pwstrick/daily/issues/314)
71. [��ôʵ�������](https://github.com/pwstrick/daily/issues/315)
72. [����ҳ��ʵ��һ������ʱ���ܹ���̬��ʾ�����������ʱ�����֡����롱 ��](https://github.com/pwstrick/daily/issues/316)
73. [���ö��ַ�ʽ��ȡ��ǰʱ��ĺ�������](https://github.com/pwstrick/daily/issues/317)
74. [����ж�ĳһ�������ꣿ](https://github.com/pwstrick/daily/issues/318)
75. [��μ����������������������](https://github.com/pwstrick/daily/issues/319)
76. [���дһ����ʽ���ַ����ĺ��������紫�롰�ҵ����ֽ�{0}���͡�strick�������ء��ҵ����ֽ�strick����](https://github.com/pwstrick/daily/issues/320)
77. [��JavaScript��װһ����������ʵ��������ǧ��λ���ŷָ��������ÿ���С����������12345��12,345��ʾ��](https://github.com/pwstrick/daily/issues/321)
78. [��дһ����������������ַ���ǰ��Ŀո�](https://github.com/pwstrick/daily/issues/322)
79. [��ν��ַ�����get-element-by-id��ת�����շ��ʾ���ġ�getElementById����](https://github.com/pwstrick/daily/issues/323)
80. [�����鷽���������е�Ԫ�أ�����Ԫ��ֵ�������֣����������õ��ĺ͸���result������](https://github.com/pwstrick/daily/issues/324)
81. [����ѭ����䣨for��while�ȣ�����һ������Ϊ50�����飬ÿ��Ԫ�ص�ֵ��������������](https://github.com/pwstrick/daily/issues/325)
82. [���һ�������ܹ���ȫ������ǰ���㣬����Ϊ3��ȫ����ǰ���㣬�õ��Ľ��Ϊ��003����](https://github.com/pwstrick/daily/issues/326)
83. [��һ�����飬��ֵΪ[1,[2,[3,4,2],2],5,[6]]����β������[1,2,3,4,2,2,5,6]��](https://github.com/pwstrick/daily/issues/327)
84. [���װһ�������������ж�ĳ�����Ƿ���������](https://github.com/pwstrick/daily/issues/328)
85. [���װһ�������������л�URL�еĲ�ѯ�ַ�����Ҳ���ǰ��ַ���ת��Ϊһ���������в����Ķ���](https://github.com/pwstrick/daily/issues/329)
86. [���һ�������������ж�һ��HTMLԪ������һ��HTMLԪ�صĺ����](https://github.com/pwstrick/daily/issues/330)
87. [����һ��\<dd>Ԫ�أ����ø�Ԫ�ص�����Ϊ4�������뵽id����Ϊ��third����\<dd>Ԫ��֮ǰ��Ҫ����DOM����ʵ�֡�](https://github.com/pwstrick/daily/issues/331)
88. [��ζ�̬������ⲿ�ű���](https://github.com/pwstrick/daily/issues/332)
89. [�ö��ַ�ʽΪһ��<div>Ԫ������һ����Ϊui-border��CSS�ࡣ](https://github.com/pwstrick/daily/issues/333)
90. [���װһ��������ģ��getBoundingClientRect()��������ֻҪ����Ԫ�ص��ӿڶ�����top������ߣ�left���ľ��롣](https://github.com/pwstrick/daily/issues/334)
91. [��ν���HTML�ĵ��е��ύ��ť��](https://github.com/pwstrick/daily/issues/335)
92. [��JavaScriptΪHTMLԪ����������CSS���ԣ������С�Ϳ�ȣ��������С��Ϊ18px�������Ϊ100px�����ö��ַ�ʽʵ�֡�](https://github.com/pwstrick/daily/issues/336)
93. [��һ��divԪ�أ�������Ϊ�˰ٷ����������JavaScript��þ���������������ȣ�](https://github.com/pwstrick/daily/issues/337)
94. [�����JavaScript����һ����ť��](https://github.com/pwstrick/daily/issues/338)
95. [������һ����ť������ڵ�����͵��¼������������ֹ�¼�������](https://github.com/pwstrick/daily/issues/339)
96. [���װһ��ע���¼��ĺ�����Ҫ���ܹ�����������С�](https://github.com/pwstrick/daily/issues/340)
97. [ʲô���¼�ί�У�����һ������������ί�У�](https://github.com/pwstrick/daily/issues/341)
98. [��ʹ�õ�������⣬��DOM������ȡ��ѡ����ѡ�е�ֵ��](https://github.com/pwstrick/daily/issues/342)
99. [�ö��ַ�ʽ�Ƴ�ѡ���SelectԪ�أ��е�ѡ�OptionԪ�أ���](https://github.com/pwstrick/daily/issues/343)
100. [�����<iframe>Ԫ��ʵ����ˢ���ļ��ϴ���](https://github.com/pwstrick/daily/issues/344)
101. [HTML5������FileReader����������������������ȡ�ϴ���ť��ѡ����ļ���](https://github.com/pwstrick/daily/issues/345)
102. [��������������⣬��ʵ��һ�μ򵥵�Ajax����](https://github.com/pwstrick/daily/issues/346)
103. [�����JSONP�Ĺ���ԭ�����ô�����������̡�](https://github.com/pwstrick/daily/issues/347)
104. [�����jQuery�����������](https://github.com/pwstrick/daily/issues/348)


