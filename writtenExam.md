## Written Exam

How and when to use `.forEach`, `.map`, `.filter`, and `.find` in JavaScript?

Please give an as extensive explanation as possible with code examples and potential use cases. Write your answer below and use markdown to format your text.

.forEach
when to use: When you would like ot itterate through multiple elements.

example:
          var sum = 0;
          var numbers = [21, 32, 71, 54];

          numbers.forEach(sumFunction);

          function sumFunction(item) {
            sum += item;
            document.getElementById("example").innerHTML = sum
          }

.map
when to use: Similar to forEach, map creates/returns a new array with the results returned from mapping the function over every element.

example:
          var numbers = [4, 9, 16, 25];
          var x = numbers.map(Math.sqrt);

          document.getElementById("example").innerHTML = x;

.filter
when to use: Filter is similar to find whereas filter creates a new array will all the elements that pass the requirement set.

example:

.find
when to use: When you would like to return the first element that meets your requirement set, similar to filter except find looks for one.

example:
          var group_ages = [10, 12, 15, 17, 22, 25, 26, 28, 32, 45, 65];

          function checkWhoIsAdult(age) {
            return age >= 18;
          }

          function myFunction() {
            document.getElementById("example").innerHTML = group_ages.filter(checkWhoIsAdult);
          }


