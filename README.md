JS:-
https://www.w3resource.com/javascript-exercises/javascript-basic-exercises.php *
https://career.guru99.com/top-85-javascript-interview-questions/
https://github.com/nishant8BITS/123-Essential-JavaScript-Interview-Question.
https://www.doppnet.com/10-advanced-javascript-interview-questions.html
https://mindmajix.com/javascript-interview-questions
https://www.quora.com/What-data-structures-should-I-know-as-a-full-stack-JavaScript-developer
https://www.quora.com/What-are-the-most-important-JavaScript-concepts-to-know-for-a-job-interview




1) Call() & apply() & bind() => https://www.codementor.io/niladrisekhardutta/how-to-call-apply-and-bind-in-javascript-8i1jca6jp#call-or-functionprototypecall

https://www.w3schools.com/js/js_function_call.asp

2) Closures =>
http://javascriptissexy.com/understand-javascript-closures-with-ease/

3) Scope and context management =>
https://blog.kevinchisholm.com/javascript/difference-between-scope-and-context/

4) Performance =>
http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/

5) Hoisting =>
https://www.w3schools.com/js/js_hoisting.asp

6) this =>
http://www.tutorialsteacher.com/javascript/this-keyword-in-javascript

7) Asynchronous Nature of JavaScript (Event loop) =>*(search with this heading)
https://www.pluralsight.com/guides/front-end-javascript/introduction-to-asynchronous-javascript

https://stackoverflow.com/questions/21607692/understanding-the-event-loop

8) Object Oriented JavaScript (OOP in JavaScript)
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS

9) promise
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
https://coligo.io/javascript-promises-plain-simple/
https://scotch.io/tutorials/javascript-promises-for-dummies

10)callback() 
https://www.w3schools.com/jquery/jquery_callback.asp

11)How to avoid callback();
http://callbackhell.com/
http://www.dotnetfunda.com/interviews/show/10801/what-is-callback-hell-and-how-can-it-be-avoided
https://stackoverflow.com/questions/41290885/how-to-avoid-callback-hell

12) Difference b/w http and webscokets 
https://www.developerinsider.in/difference-between-http-and-http-2-0-websocket/ 

13) coding questions
https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-%28written-by-a-Frontend-Engineer%29
https://dev.to/maxpou/typical-javascript-interview-exercises-explained

14) Difference Between var, let, and const Keywords in JavaScript
https://dzone.com/articles/javascript-difference-between-var-let-and-const-ke

15) what is the difference between cookie and session
https://stackoverflow.com/questions/6339783/what-is-the-difference-between-sessions-and-cookies-in-php

16)https://www.sitepoint.com/shorthand-javascript-techniques/

17)difference between es5 and es6 javascript
https://codeburst.io/es5-vs-es6-with-example-code-9901fa0136fc
https://www.quora.com/What-is-the-difference-between-JavaScript-and-ES6
http://developmentr.com/javascript/2015/12/31/javascript-es6.html

18) var sttr = "chandra" ; console.log(sttr.split('cha').pop());  && console.log(sttr.substring(0,3)); && var nb ="chandu"; console.log(nb.substring(0,1));console.log(nb.substring(1,nb.length));

19) traingel , square , cirle , prime or not , fibanocci , assending , leapYearOrNot , dateFormat,  Quick sort, Merge sort , Heap sort ,Insertion sort , Bubble sort , factorial , find the unique elements from two arrays ,  to move an array element from one position to another , to check whether an `input` is an array or not , o join all elements of the following array into a string , to find the most frequent item of an array ,  to remove duplicate items from an array  , to perform a binary search , to compute the sum of each individual index value from the given arrays ,to find the difference of two arrays , to find the longest common starting substring in a set of strings , reverse a number & String , string is palindrome or not , Asending order and Desending order , first letter of each word of the string in upper case , Find the longest word within the string ,counts the number of vowels within the string , ake an array of numbers stored and find the second lowest and second greatest numbers , to find 1st January is being a Sunday between 2014 and 2050 , to get the extension of a filename , to replace every character in a given string with the character following it in the alphabet ,  to convert the letters of a given string in alphabetical order , to count the number of vowels in a given string. , to find the number of even digits in a given integer ,to convert a decimal number to binary, hexadecimal or octal number , to find the highest & lowest value in an array , to check to check whether a variable is numeric or not , 




<!DOCTYPE HTML>
<html>
    <head>
        <style>
            body {
                margin: 0px;
                padding: 0px;
            }
        </style>
    </head>
    <body>
        <div>
            In  console
            <input type="date" name="bday"> 
        </div>
        <script type="text/javascript">
            //================= 1) - area of Tiangle +++++++++++Foramulaee = half-traingle = ((side1 side2 + side3)/2 ) , 
            //Trangle = Math.sqrt(half-traingle * ((half-traingle - side1) * (half-traingle - side2) * (half-traingle - side3)));
            function areaOfTriangle(a, b, c) {
                var side1 = a;
                var side2 = b;
                var side3 = c;
                var perimeter = (side1 + side2 + side3) / 2;
                var area = Math.sqrt(perimeter * ((perimeter - side1) * (perimeter - side2) * (perimeter - side3)));
                console.log(area);
            };
         //================== 2)- area of Circle+++++++++++Foramulaee = area of circle = PI * R  * R , circumference of circle = 2 * PI * R ;
            function areaAndCircumferenceOfCirecle(radius) {
                var area = Math.PI * radius * radius;
                var circumferance = 2 * Math.PI * radius
                console.log(area + " -- " + circumferance)
            };
            //================= 3)- area of rectangle+++++++++Formulaee = area of rectangle = width * length
            function areaRectangle(w,l){
                var area= w * l ;
                console.log(area);
            };
            //================= 4 )- prime or not+++++++ a positive integer which is only devisible by 1 
            
            function primeNumOrNoT(num){
                if(num === 1){return false;}
               else if(num === 2){return true;}
               else {
                  for(var x=2; x < num; x++ ){
                      if(num % 2 === 0){return false}
                  } 
                  return true;
               }
            };
            //================= 5 )- fibonaci series+++++++  the first two Fibonacci numbers are 0 and 1, and each subsequent number is the sum of the previous two.
            // Its recurrence relation is given by Fn = Fn-1 + Fn-2.
            
            function fibonaciSeries(num){
                var fibo = [];
                 fibo[0] = 0;
                 fibo[1] = 1;
                for(var i=2; i<= num ; i++){
                    fibo[i] = fibo[i-1] + fibo[i-2];
                    console.log(fibo[i]);
                }
            };
           ////================= 6 )- factorial ++++++ 
           function factorial(num){
                if(num === 0){ return 1}
                return num * factorial(num - 1);
                }
           ////================= 7 )- PailndromeOrNot ++++++ 
           function pailndromeOrNot(str){
               var pail= str.split("").reverse().join("");
               if(str == pail){return true}
               return false;
           }
           ////================= 8 )- Asending and Desending Order ++++++ 
            function asendingOrder(array1){
              var asendingOrder = array1.sort(function(a,b){return a-b});
   console.log(" --- asendingOrder --- " +asendingOrder );  
            };
             function desendingOrder(array1){
    var desendingOrder = array1.sort(function(a,b){return b-a});
   console.log(" --- desendingOrder --- " +desendingOrder );  
            };
            ////================= 9 )- leapYearOrNot ++++++  
             function leapYearOrNot(year) {
                x = (year % 100 === 0) ? (year % 400 === 0) : (year % 4 === 0);
                console.log(x);
            };
            ////================= 10 )- dateFormat ++++++              
             function dateFormat() {
                var date = new Date();
                console.log(date);
                var yyyy = date.getFullYear();
                var mm = date.getMonth();
                var dd = date.getDate();
                var day = date.getDay();
                var weeks = ["Mon","Tue" ,"Wed","Thu","Fri","Sat"];
                console.log(mm + "/" + dd + "/" + yyyy);
                console.log("day -- "+weeks[day]);
            };
             ////================= 11 )- Find Unique num in two arrays ++++++              
             function findUniqueValuesInArray(arr1, arr2){
              let unique1 = arr1.filter((o) => arr2.indexOf(o)=== -1);
              let unique2 = arr2.filter((o) => arr1.indexOf(o) === -1);
              var unique = unique1.concat(unique2);
              console.log(unique);
             }
            ////================= 12 )- to move an array element from one position to another ++++++      
            function array_move(arr, old_index, new_index) {
                if (new_index >= arr.length) {
                    var k = new_index - arr.length + 1;
                    while (k--) {
                        arr.push(undefined);
                    }
                }
                arr.splice(new_index, 0, arr.splice(old_index, 1)[0]);
                return arr; 
                };
            ////================= 13 )- to check whether an `input` is an array or not ++++++      
                 function isArray(arr1){
                if(toString.call(arr1) === "[object Array]" ){return true}
                return false;
            };
            ////================= 14 )- to join all elements of the following array into a string 
           function toJoinArrayIntoString(arr1){
                            var finalOutPut = arr1.toString();
            var some = arr1.join("+");
            console.log(some);
                        }
            ////================= 15 )-  to remove duplicate items from an array   eg:- console.log(new Set(arr1));           
             function removeDuplicates(arr){
                    let unique_array = []
                    for(let i = 0;i < arr.length; i++){
                        if(unique_array.indexOf(arr[i]) == -1){
                            unique_array.push(arr[i])
                        }
                    }
                    return unique_array
                    };
            //================= 16 )- Find 1st January is being a Sunday between 2014 and 2050.
            function findFirstSunday(startYear, endYear) {
                console.log('--------------------');
                for (var year = startYear; year <= endYear; year++)
                {
                    var d = new Date(year, 0, 1);
                    if (d.getDay() === 0)
                        console.log("1st January is being a Sunday  " + year);
                }
                console.log('--------------------');
            }              
            //================= 17 )- reverse a number & String
            function reverse(input){
                var op = input.split("").reverse().join("");
                console.log(op);
            }
            //================= 18 )- first letter of each word of the string in upper case
            function uppercase(str) {
                var array1 = str.split(' ');
                var newarray1 = [];
                for(var x = 0; x < array1.length; x++){
                    newarray1.push(array1[x].charAt(0).toUpperCase()+array1[x].slice(1));
                }
                return newarray1.join(' ');
              }   
             
            document.writeln("<br/>navigator.appCodeName: " + navigator.appCodeName);
            document.writeln("<br/>navigator.appName: " + navigator.appName);
            document.writeln("<br/>navigator.appVersion: " + navigator.appVersion);
            document.writeln("<br/>navigator.cookieEnabled: " + navigator.cookieEnabled);
            document.writeln("<br/>navigator.language: " + navigator.language);
            document.writeln("<br/>navigator.userAgent: " + navigator.userAgent);
            document.writeln("<br/>navigator.platform: " + navigator.platform);
            document.writeln("<br/>navigator.onLine: " + navigator.onLine);
        
        function strPostion() {
                var arr1 = ["king", "queen", "minister", "quiz"];
                var str = ""
                for (i = 0; i <= arr1.length; i++) {
                    console.log(arr1[i]);
                    str = arr1[i]
                    if (str.substring(0, 1) == "q") {
                        console.log("---- " + str);
                    }
                }
            }
            const twoSum = (arr, target) => {
  let results = [];
  for (let i=0; i<arr.length; i++) {
    for (let j=i+1; j<arr.length; j++) {
      if (arr[j] === target - arr[i]) {
        results.push([arr[i], arr[j]])
      }
    }
  }
  return results;
}
        </script>
    </body>
</html>      

















mongodb, documents , difference b/w sql and non  sql , aggregation , sharding , replication , CRUD operations , why we use mongoose,
what is the use of mongoose , Ad hoc queries , indexing , yield 

https://www.mongodb.com/what-is-mongodb
https://www.javatpoint.com/sql-vs-nosql
https://docs.mongodb.com/manual/aggregation/
https://docs.mongodb.com/manual/sharding/
https://docs.mongodb.com/manual/replication/
https://docs.mongodb.com/manual/crud/
https://stackoverflow.com/questions/18531696/why-do-we-need-what-advantages-to-use-mongoose
https://code.tutsplus.com/articles/an-introduction-to-mongoose-for-mongodb-and-nodejs--cms-29527
https://www.pcmag.com/encyclopedia/term/37486/ad-hoc-query
https://stackoverflow.com/questions/6576664/nosql-adhoc-queries-millions-of-rows
https://www.simplilearn.com/indexing-and-aggregation-mongodb-tutorial-video
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield


angular2 , component and modules,template , Directives, dependecy injection ,
routing , input and output , observers , how to pass the data in one component to another,
lazyloading , forms using react.


https://angular.io/docs
https://www.tutorialspoint.com/angular2/angular2_components.htm
https://www.tutorialspoint.com/angular2/angular2_modules.htm
https://www.tutorialspoint.com/angular2/angular2_templates.htm
https://www.tutorialspoint.com/angular2/angular2_directives.htm
https://www.tutorialspoint.com/angular2/angular2_dependency_injection.htm
https://scotch.io/tutorials/routing-angular-2-single-page-apps-with-the-component-router
https://www.sitepoint.com/angular-2-components-inputs-outputs/
https://angular-2-training-book.rangle.io/v/v2.3/handout/observables/using_observables.html
https://angularfirebase.com/lessons/sharing-data-between-angular-components-four-methods/
https://toddmotto.com/passing-data-angular-2-components-input
https://stackoverflow.com/questions/34088209/how-to-pass-object-from-one-component-to-another-in-angular-2
https://angular-2-training-book.rangle.io/v/v2.3/handout/modules/lazy-loading-module.html
https://medium.com/aviabird/complete-angular2-guide-reactive-forms-in-depth-part-1-21a8e2428904
