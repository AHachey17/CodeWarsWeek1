# CodeWarsWeek1
## Every week I will be posting a weekly Repo that I update daily with complete CodeWar Katas
### Week1
Day 1: 8KYU, PRINT FALSE - created a function that returned false without using the word 'false' at all (Functions, Conditional operator)
```
function ifChuckSaysSo(){
  return 0 === 1;
}
```
Day 2: 8KYU, COUNT SHEEP - created a function that only counted the sheep in the given array that were considered true. (Functions, Arrays, Conditionals) 
```
function countSheeps(arrayOfSheep) {
  const newArray = []
  arrayOfSheep.forEach(sheep =>  {
    if (sheep){
      newArray.push(sheep)
    }
    
    
  })
   return newArray.length 
 }
```
Day 3: 8KYU, SQUARE(n)SUM - created a function that took an array and summed each element in the array the squared it.
```
function squareSum(numbers){
  let sum = 0
  numbers.forEach(number => sum += number ** 2)
    return sum
  }
```
Day 4: 8KYU, COUNT MONKEYS - Given that there is n monkeys at the zoo, I created a function that counts n monkeys at the zoo an stores in array.
```
function monkeyCount(n) {
  const monkeyCage = []
  for(let i = 1; i <= n; i++){
    monkeyCage.push(i)
  }
   return monkeyCage
 }
```
Day5: 8KYU, SIMPLE MULTIPLICATION - created a function that multipies any give number by 8 if it is even and by 9 if it is odd.
```
function simpleMultiplication(number) {
  if (number % 2 === 0){
    return number * 8
  }else{
    return number * 9
  }
}
```

