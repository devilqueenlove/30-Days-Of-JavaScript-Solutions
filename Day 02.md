## 💻 Day 2: Exercises

### Exercise: Level 1

1. Declare a variable named challenge and assign it to an initial value **'30 Days Of JavaScript'**.
```
let challenge = '30 Days Of JavaScript';
```
2. Print the string on the browser console using __console.log()__
```
let challenge = '30 Days Of JavaScript';
console.log(challenge);
```
3. Print the __length__ of the string on the browser console using _console.log()_
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.length);
```
4. Change all the string characters to capital letters using __toUpperCase()__ method
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.toUpperCase());
```
5. Change all the string characters to lowercase letters using __toLowerCase()__ method
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.toLowerCase());
```
6. Cut (slice) out the first word of the string using __substr()__ or __substring()__ method
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.substring(0,3));
console.log(challenge.substr(3));
```
7. Slice out the phrase *Days Of JavaScript* from *30 Days Of JavaScript*.
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.slice(3,20));
```

8. Check if the string contains a word __Script__ using __includes()__ method
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.includes('Script'));
```
9. Split the __string__ into an __array__ using __split()__ method
```
let challenge = '__string__ into an __array__ using __split()__ method';
console.log(challenge.split('__'));
```

10. Split the string 30 Days Of JavaScript at the space using __split()__ method
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.split(' '));
```

11. 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' __split__ the string at the comma and change it to an array.
```
let challenge = 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon';
console.log(challenge.split(','));
```

12. Change 30 Days Of JavaScript to 30 Days Of Python using __replace()__ method.
```
let challenge = '30 Days Of JavaScript'
console.log(challenge.replace('JavaScript', 'Python'));
```
13. What is character at index 15 in '30 Days Of JavaScript' string? Use __charAt()__ method.
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.charAt(15));
```
14. What is the character code of J in '30 Days Of JavaScript' string using __charCodeAt()__
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.charCodeAt(challenge.indexOf('J')));
```
15. Use __indexOf__ to determine the position of the first occurrence of __a__ in 30 Days Of JavaScript
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.indexOf('a'));
```
16. Use __lastIndexOf__ to determine the position of the last occurrence of __a__ in 30 Days Of JavaScript.
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.lastIndexOf('a'));
```
17. Use __indexOf__ to find the position of the first occurrence of the word __because__ in the following sentence:__'You cannot end a sentence with because because because is a conjunction'__
```
let challenge = 'You cannot end a sentence with because because because is a conjunction';
console.log(challenge.indexOf('because'));
```
18. Use __lastIndexOf__ to find the position of the last occurrence of the word __because__ in the following sentence:__'You cannot end a sentence with because because because is a conjunction'__
```
let challenge = 'You cannot end a sentence with because because because is a conjunction';
console.log(challenge.lastIndexOf('because'));
```
19. Use __search__ to find the position of the first occurrence of the word __because__ in the following sentence:__'You cannot end a sentence with because because because is a conjunction'__
```
let challenge = 'You cannot end a sentence with because because because is a conjunction';
console.log(challenge.search('because'));
```
20. Use __trim()__ to remove any trailing whitespace at the beginning and the end of a string.E.g ' 30 Days Of JavaScript '.
``` 
let challenge = ' 30 Days Of JavaScript ';
console.log(challenge.trim());
```
21. Use __startsWith()__ method with the string *30 Days Of JavaScript* and make the result true
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.startsWith('30'));
```
22. Use __endsWith()__ method with the string *30 Days Of JavaScript* and make the result true
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.endsWith('JavaScript'));
```
23. Use __match()__ method to find all the __a__’s in 30 Days Of JavaScript
```
let challenge = '30 Days Of JavaScript';
console.log(challenge.match(/a/g));
```
24. Use __concat()__ and merge '30 Days of' and 'JavaScript' to a single string, '30 Days Of JavaScript'
```
let challenge = '30 Days of';
let language = " " + 'JavaScript';
console.log(challenge.concat(language)));
```
25. Use __repeat()__ method to print 30 Days Of JavaScript 2 times
```
let word = 'JavaScript'
console.log(word.repeat(2));
```

### Exercise: Level 2

1. Using console.log() print out the following statement:
    ```sh
    The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.
    ```
```
let quote = 'There is no exercise better for the heart than reaching down and lifting people up.'
console.log(quote);
```

2. Using console.log() print out the following quote by Mother Teresa:
    ```sh
    "Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead."
    ```
```
let quote = 'Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead.'
console.log(quote);
```

3. Check if typeof '10' is exactly equal to 10. If not make it exactly equal.
```
let num = '10';
console.log(typeof num === typeOf(10));
console.log(typeOf Number(num) == typeOf(10))
```
4. Check if parseFloat('9.8') is equal to 10 if not make it exactly equal with 10.
```
let num = '9.8';
console.log(parseFloat(num) == 10);
console.log(Math.floor(num)== 10);
```
5. Check if 'on' is found in both python and jargon
```
let python = 'python';
let jargon = 'jargon';
console.log(python.includes('on') && jargon.includes('on'));
```
6. _I hope this course is not full of jargon_. Check if _jargon_ is in the sentence.
```
let sentence = 'I hope this course is not full of jargon';
console.log(sentence.includes('jargon'));
```
7. Generate a random number between 0 and 100 inclusively.
```
let random = Math.floor(Math.random() * 100);
```
8. Generate a random number between 50 and 100 inclusively.
```
let random = Math.floor(Math.random()*(100-50) + 50);
```
9. Generate a random number between 0 and 255 inclusively.
```
let random = Math.floor(Math.random()* 255);
```
10. Access the 'JavaScript' string characters using a random number.
```
let str = 'JavaScript';
let random = Math.floor(Math.random() * str.length);
console.log(str[random]);
```
11. Use console.log() and escape characters to print the following pattern.
    ```js
    1 1 1 1 1
    2 1 2 4 8
    3 1 3 9 27
    4 1 4 16 64
    5 1 5 25 125
    ```
```
console.log(`1 1 1 1`);
console.log(`2 1 2 4 8`);
console.log(`3 1 3 9 27`);
console.log(`4 1 4 16 64`);
console.log(`5 1 5 25 125`);
```
12.  Use __substr__ to slice out the phrase __because because because__ from the following sentence:__'You cannot end a sentence with because because because is a conjunction'__
```
let sentence = 'You cannot end a sentence with because because because is a conjunction';
console.log(sentence.substr(31, 23));
```
### Exercises: Level 3

1. 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Count the number of word __love__ in this sentence.
```
let sentence = 'Love is the best thing in this world. Some found their love and some are still looking for their love.';
let lowerCaseSentence = sentence.toLowerCase();
let count = lowerCaseSentence.split(" ").filter(word => word === 'love').length + 1;
console.log(count);
```
2. Use __match()__ to count the number of all __because__ in the following sentence:__'You cannot end a sentence with because because because is a conjunction'__
```
let sentence = 'You cannot end a sentence with because because because is a conjunction';
console.log(sentence.match(/because/g)).length;
```
3. Clean the following text and find the most frequent word (hint, use replace and regular expressions).

    ```js
        const sentence = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
    ```
```
let  sentence = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
let cleanSentence = sentence.replace(/[%@#&;$.,!?]/g, '').toLowerCase();
let wordsArray = cleanSentence.split(/\s+/);
let  wordsCount = wordsArray.reduce((count, word)=>{
    count[word] = (count[word] || 0)+1;
    return count
},{});
let max = Object.keys(wordsCount).reduce((a,b)=>
    wordsCount[a] > wordsCount[b] ? a: b
);
console.log(max)
```

4. Calculate the total annual income of the person by extracting the numbers from the following text. 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'
```
let annualIncome ;
let monthlySalary = 5000;
let annualBonus = 10000;
let monthlyOnlineCourses = 15000;
annualIncome = monthlySalary*12+annualBonus+monthlyOnlineCourses*12;
console.log(annualIncome)
```

# 🎉 CONGRATULATIONS, YOU HAVE COMPLETED 2ND DAY! 🎉
