# RegularExpressionTutorial
* RegularExpression Tutorial Project explain the core concept with numerous examples.
	

**Main Application Areas for RegularExpressions are :**
* To Develop Validation Frameworks.
* To Develop Pattern Matching Application.
* To Develop Translators like Compiler, Interpreter & Assembler etc.
* To Develop Communication Protocol line TCP/IP, UDP etc.


## RegularExpression Concept
* RegularExpression came in **Java 1.4** version release and present in *java.util.regex package*.
* RegularExpression is a way to represent group of string object according to a particular Pattern or Format.
* Create Pattern Object using compile method using pattern string which need to be searched.
* Create Matcher Object using matche method using target string where pattern need to be searched.
	
	

## Pattern Class
* Pattern is equivalent Java Object of RegularExpression.
* Pattern Object is created by using compile method of Pattern class using pattern string.
* This is example of Static Factory method.

	

## Matcher Class
* Used to match the given pattern in the target string.
* Matcher Object is created by using matcher method Pattern Class using target string.
* Below are important methods of Matcher Class.

Method Name | Method Descripton 
----------- | ------------------ 
**find()** | Tries to find the match, return true is available else false. 
**start()** | Returns start index of the match. 
**end()** | Returns the **`end index+1`** of the match. 
**group()** | Returns the matched string. 


## Character Class
* Used when searches group of characters.
* **^** -- Cap, This symbol represent except or exclude.
* **[ ]** -- Square Bracket, Used to search group of things.
* **-** -- Hyphen, Used to define range of pattern group.
* Below are few examples to search group of Pattern.

Example | Description
------- | -----------
**[abc]** | Search for *`either`* 'a' or 'b' or 'c'.
**[^abc]** | Search `**EXCEPT**` 'a' and 'b' and 'c'.
**[a-z]** | Search any 'a' to 'z' Lower Case alphabet symbol.
**[A-Z]** | Search any 'A' to 'Z' Upper Case alphabet symbol.
**[a-zA-Z]** | Search any alphabet. Either upper/lower case from 'a' to 'z'.
**[0-9]** | Search any digit from 0 to 9.
**[a-zA-Z0-9]** | Search any alphanumeric character.
**[^a-zA-Z0-9]** | Search except alphanumeric Character (Search for special Character).


## Pre-Defined Character Class

## Quantifiers

## Patter Class split() & String Class split()

## StringTokenizer
