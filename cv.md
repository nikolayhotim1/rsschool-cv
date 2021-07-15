# Mikalai Khotsim #
## Contacts: #
* __Phone:__ +375(33)613-67-27;
* __E-mail:__ hotim_nikolay@mail.ru;
* __G-mail:__ n1kolayhotim@gmail.com;
* __Skype:__ nikolay.hotim1;
* __Telegram:__ Nikolay Hotim;
* __GitHub:__ nikolayhotim1
### Some information and facts about me: #
* I am striving to become a __javascript front-end developer__ in the near future;
* I am very hardworking, diligent, conscientious, perfectionist, persistent and assertive in achieving the best result in my work;
* I like and want to constantly develop and improve as a good specialist, learn new useful information and not to stop there.
### Hard skills: #
1. Basic knowledge of:
    * JavaScript;
    * HTML;
    * CSS;
    * GIT;
    * Markdown
1. Development tools & IDE:
    * VS Code;
    * WebStorm;
    * Atom;
    * Brackets;
    * Browsers:
        + Google Chrome;
        + Mozilla Firefox;
        + Yandex;
        + Opera, itc
1. GIT tools:
    * GitHub;
    * Git Bash

### My code examples #
1. **Codewars tasks:**
    1. _Palindrome Strings_
    ```
    function isPalindrome(line) {
        line += "";
        return line == line.split("").reverse().join("");
    }
    ```
    2. _Reversed Strings_
    ```
    function solution(str) {
        return str.split("").reverse().join("");
    }
    ```
    3. _Century From Year_
    ```
    function century(year) {
        return Math.ceil(year/100);
    }
    ```
    4. _Even or Odd_
    ```
    function even_or_odd(number) {
        if (number % 2 === 0) {
            return "Even";
        } else {
            return "Odd";
        }
    }
    ```
    5. _Opposite number_
    ```
    function opposite(number) {
        return -(number);
    }
    ```
    6. _Multiply_
    ```
    function multiply(a, b) {
        return a * b;
    }

    multiply(2, 4);
    ```
1. **Other tasks:**
    * _Cheesboard_
    ```
    let size = 8;

    let board = "";

    for (let y = 0; y < size; y++) {
        for (let x = 0; x < size; x++) {
            if ((x + y) % 2 === 0) {
                board += " ";
            } else {
                board += "#";
            }
        }
        board += "\n";
    }

    console.log(board);
    ```
    * _Calculator_
    ```
    function Calculator() {

        this.read = function() {
            this.a = +prompt('a?', 0);
            this.b = +prompt('b?', 0);
        };

        this.sum = function() {
            return this.a + this.b;
        };

        this.mul = function() {
            return this.a * this.b;
        };
    }

    let calculator = new Calculator();
    calculator.read();

    alert( "Sum = " + calculator.sum() );
    alert( "Mul = " + calculator.mul() );
    ```
    * _Pow_
    ```
    function pow(x, n) {
        let result = 1;

        for (let i = 0; i < n; i++) {
            result *= x;
        }

        return result;
    }

    let x = prompt('x?', '');
    let n = prompt('n?', '');

    if (n < 0) {
        alert (`Power ${n} is not supported, 
        please enter a non-negetive integer number`);
    } else {
        alert( pow(x, n) );
    }
    ```
    * _Keys Push_
    ```
    "usestrict";
    let map = new Map();

    map.set("name", "Nikolay")
        .set("surname", "Hotim");

    let values = Array.from(map.values());

    values.push("is #1");
    alert(values);
    ```

### Work experience #
**Company Name:** _JSC "GIAP"_;
**Position:** _Design Engineer_;
**Period:** _02.03.2018 - until now_

### Education #
**City of training:** _Grodno_;
**Educational institution:** _Yanka Kupala Grodno State University_;
**Faculty:** _Engineering and construction_;
**Department:** _Construction Materials Science_;
**Form of training:** _Full-time_;
**Status:** _Graduate (specialist)_;
**Year of graduation:** _2015_;
**Mandatory distribution:** _I am not subject to distribution_

### Training courses #
**Rolling Scopes School**:
* _JavaScript/Front-end 2021 Q1_;
* _JavaScript/Front-end Pre-School 2021 Q3 (my current course)_

### English level #
**A1+ (Basic Medium)**