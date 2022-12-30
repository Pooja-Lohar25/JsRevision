
#### Fill and Filter
arr.fill("chararcter",start,end) ''' this is used to fillup all or specified elements of the array with specific value <br>
index is optional argument which will fill the array with the character specified starting with that  start index till the end index. <br>
start is inclusive, end is exclusive
```js
arr = [2,3,4,5,2,6,7];
arr.fill('p');
```
Output : ['p','p','p','p','p','p','p']
```js
arr.fill('p',2);
```
Output : [2,3,'p','p','p','p','p']

```js
arr.fill('p',2,5);
```
Output : [2,3,'p','p','p',6,7]

arr.filter( () => () ) expects a call back a and returns the filtered array on the basis of callback <br>
Ex : arr.filter( (num) => (num!=10) ) <br>
INTERPRETATION : For every num in arr five only those elements which are not equal to 10 <br>

```js
arr = [10,10,2,5,6,7,10,3,10];
arr.filter( num => num!=10 );
```
Output : [2,5,6,7,3]
