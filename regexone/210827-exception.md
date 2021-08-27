## Q. The Dot
|Task|Text|
|----|----|
|Match|cat.|
|Match|896.|
|Match|v?=+.|
|Skip|abc1|

## A. Pattern
### (cat|896|\?=+.).+[^abc1]
* ```(cat|896|\?=+.)``` : act이거나 896이거나 \?=+.이거나.
* ```.+``` : . 이후
* ```[^abc1]``` : 해당 문자 제외