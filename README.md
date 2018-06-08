# markdown-note
This is my note about markdown when I write README. This is a easy resource about markdown which can help you write a simple markdown example. And write down some tips to make beginners avoid some mistakes. If you want to learn more knowledge , you can find advanced resources.  
***  
![](/image/markdown_log.jpg)  

***
**Author: Guo Guanglu  
E-mail: 2360889142@qq.com  
QQ: 2360889142**  

***  
[**Back to github.io**][github.io]  

***  
## Content  
-------
* [Basic principle](basic-principle)  
	* [Header](#header)  
	* [List](#list)  
		* Unordered list
		* ordered list  
	* [Text format](#text-format)
		* Bold  
		* Italic  
		* Bold + italic  
		* delect  
	* [Link](#link)  
		* Text link  
		* Image link  
		* Image link site
		* Indirectly link  
	* [Cite](#cite)  
	* [Horizontal divided line](#horizontal-divided-line)  
	* [Code block](#code-block)  
	* [Table](#table)  
	* [Escape character](#escape-character)
	
	
	
	
	

***  
Basic principle  
-----
### Header  
```
1. '#+titlename' represents H1 header  
2. ##+titlename represents H2 header  
3. ###+titlename represents H3 header  
4. and so on....  
```  
**For example**:  
# Header1  
## Header2  
### Header3  

***  
### List  
* Unordered list  
You can use symbol `*,+,-`.  
```
* list1  
+ list2  
- list3  
```  
**For example**:  
* list1  
+ list2  
- list3  

You can keep on using list in a list.  
**For example**:  
* list1  
	* list1.1  
* Ordered list  

Use 'number+'.'' shows ordered lists.  
```
1. list1  
2. list2  
3. and so on ....
```
**For example**:  
1. list1  
2. list2  

***  
### Newline 
1. single 'enter' represents space, not newline  
2. continous 'enter' can get a new line  
3. And you can use two space in the end of the line, then one 'enter' can realize a newline.  

**For example**:  
Hello world!  
Have a good time!  
or  
hello world!

Have a good time!  

***
### Text format  
* Bold  
You can use the following formats:  
```
1. **Bold**  
2. __Bold__  
```  
**For example**:  
**Bold**  
__Bold__  
* Italic  
Use the following formats:
```
1. *Italic*  
2. _Italic_  
```  
* Bold+italic  
Use the following formats:  
```
1. ***Bolditalic***  
2. ___Bolditalic___  
```  
**For example**:  
***Bolditalic***  
___Bolditalic___  
* delect  
use the following format:  
```
~~delect~~  
```  
**For example**:  
~~delect~~  

***  
### Link  
* Text link  
rule of linking sites: `[link name](the site of link "link title")`
```
1. [baidu](http://www.baidu.com "baidu")
```  
**For example**:  
[baidu](http://www.baidu.com "baidu")  
rule of linking headers in the same file: `[link name](#header)`  
**Note**: the contents of the brackets must lower letters ，and space must be replaced by `-`or`+`or`%20`  
```
1. [Content](#content)  
2. [Text format](#text-format)  
```  
**For example**:  
[Content](#content)  
[Text format](#text-format)  
* Image link  
the rule: `![replace text](the site of link "link title")`  
```
1. ![baidu](https://www.baidu.com/img/bd_logo1.png "click baidu, know everything")  
```  
**For example**:  
![baidu](https://www.baidu.com/img/bd_logo1.png "click baidu, know everything")  
* Image link site
the rule: `[![]()]()` 
```
1. [![](https://www.baidu.com/img/bd_logo1.png "click baidu, know everything")](http://www.baidu.com "baidu")  
```
**For example**:  
[![](https://www.baidu.com/img/bd_logo1.png "click baidu, know everything")](http://www.baidu.com "baidu")  
* Indirect link  
rule :  
```
[link name][label]  
[label]: the site of link "link title"  
```  
```
1. [baidu][123]  
2. [123]:http://www.baidu.com "click baidu, knowe everything"  
```  
**For example**:  
[baidu][123]  
[123]: http://www.baidu.com "click baidu, knowe everything"  

***
### Cite  
```
1. > level1 cite  
2. >> level2 cite 
3. >>> level3 cite  
```  
**For example**:  
> level1 cite  
>> level2 cite  
>>> level3 cite  
### Horizontal divided line  
There are three forms:  
```
1. ---  
2. ___  
3. ***  
```  
**For example**:  
---  
***  
___  

***
### Code block  
* code sentence  
Use symbol \' \'  
**For example**:  
`This is a code sentence.`  
* code block  
use symbol \`\`\` \`\`\`  
```
This is a code sentence.  
There is also a code sentence.  
```  
When you add the compute programming language name，you can get surprising effect.  
\`\`\`java  
public class Test{
	public static void main(String[] arg){  
		System.out.println("Hello World");  
	}   
}   
\`\`\`  

**For example**:  
``` java
public class Test {  
    public static void main(String[] args) {  
        System.out.println("Hello World");  
    }  
}  
```  

***
### Table  
The rule is as follow:  
```
|title1|title2|title3|  
|:-----(Left alignment)|-------:(right alignment)|:-----:(middle alignment)|  
|content|content|content|  
|content|content|content|
.....
```  
**For example**:  

|item|value|number|  
|:---|-----:|:--:|  
|computer |1600 |5|  
|phone|12|12|  
|pipe|1|234|  

***  
### Escape character  
Sometimes we use some special symbols ,like \#,\+ and so on. We will use escape charater to show them. I list some escape characers.  
```
\\  
\`  
\*  
\_  
\+  
\#  
\.  
\~  
```  
**For example**:  
\\,\`,\*,\_,\+,\#,\.,\~  

***
# Reference  
https://github.com/guodongxiaren/README  
https://blog.csdn.net/sun8112133/article/details/79871702  

------------------------------------  
[github.io]: https://guoguanglu.github.io 'jump to guoguanglu github.io'

