# RegularExpressionTutorial
* RegularExpression Tutorial Project explain the core concept with numerous examples
	

### Main Application Areas for RegularExpressions are :
..*To Develop Validation Frameworks
..*To Develop Pattern Matching Application
..*To Develop Translators like Compiler, Interpreter & Assembler etc
..* To Develop Communication Protocol line TCP/IP, UDP etc


## RegularExpression Concept
..* RegularExpression came in **Java 1.4** version release and present in java.util.regex package.
..* RegularExpression is a way to represent group of string object according to a particular Pattern or Format.
..* Create Pattern Object using compile method using pattern string which need to be searched.
..* Create Matcher Object using matche method using target string where pattern need to be searched.
	
	

## Pattern
..* Pattern is equivalent Java Object of RegularExpression.
..* Pattern Object is created by using compile method of Pattern class using pattern string.
..* This is example of Static Factory method.

	

## Matcher
..* Used to match the given pattern in the target string.
..* Matcher Object is created by using matcher method Pattern Class using target string.
..* Has below important methods of Matcher Class.
..* **find()** -- trying to find the match,  return true is available else false.
..* **start()** -- returns start index of the match.
..* **end()** -- returns the end index+1 of the match.
..* **group()** -- returns the matched string.


## Character Class

## Pre-Defined Character Class

## Quantifiers

## Patter Class split() & String Class split()

## StringTokenizer
