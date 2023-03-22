[![Stargazers][stars-shield]][stars-url]
[![Forks][forks-shield]][forks-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

[forks-shield]: https://img.shields.io/github/forks/ShahjalalShohag/Competitive-Programming-A-Complete-Guideline.svg?style=for-the-badge
[forks-url]: https://github.com/ShahjalalShohag/Competitive-Programming-A-Complete-Guideline/network/members
[stars-shield]: https://img.shields.io/github/stars/ShahjalalShohag/Competitive-Programming-A-Complete-Guideline.svg?style=for-the-badge
[stars-url]: https://github.com/ShahjalalShohag/Competitive-Programming-A-Complete-Guideline/stargazers
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/ShahjalalShohag

### Table of Contents
- [Table of Contents](#table-of-contents)
- [Discord Server](#discord-server)
- [What is Competitive Programming(CP)?](#what-is-competitive-programmingcp)
- [What is a Problem?](#what-is-a-problem)
- [The Ultimate Question: Why should I start Competitive Programming?](#the-ultimate-question-why-should-i-start-competitive-programming)
- [The Secret](#the-secret)
- [Seriously vs Sincerely](#seriously-vs-sincerely)
- [What Progress is Really Like](#what-progress-is-really-like)
- [Which language should I use for CP?](#which-language-should-i-use-for-cp)
- [Where to write codes? What are the best IDEs?](#where-to-write-codes-what-are-the-best-ides)
- [Competitive Programming Platforms](#competitive-programming-platforms)
- [How to Use Codeforces](#how-to-use-codeforces)
- [Details about problem statements, how contests work and the rating system on Codeforces (and a few other platforms) <a name = "ratingsys"></a>](#details-about-problem-statements-how-contests-work-and-the-rating-system-on-codeforces-and-a-few-other-platforms-)
- [What to do if I don't know how to solve a problem?](#what-to-do-if-i-dont-know-how-to-solve-a-problem)
- [How to check others solutions?](#how-to-check-others-solutions)
- [How to practice a problem efficiently?](#how-to-practice-a-problem-efficiently)
- [Virtual Contests](#virtual-contests)
- [Kidlin's Law](#kidlins-law)
- [[Contest]Solve some very basic problems.](#contestsolve-some-very-basic-problems)
- [[Codes] Check how to solve the problems of Contest 1](#codes-check-how-to-solve-the-problems-of-contest-1)
- [[Codes] Check how to solve the problems of Contest 2](#codes-check-how-to-solve-the-problems-of-contest-2)
- [[Editorials and Codes] Check how to solve the problems of Contest 3](#editorials-and-codes-check-how-to-solve-the-problems-of-contest-3)
- [FAQ](#faq)
- [Important Notes](#important-notes)
- [Getting into Competitive Programming](#getting-into-competitive-programming)
- [Tutorial](#tutorial)
- [Life Hack(if you are from Bangladesh)](#life-hackif-you-are-from-bangladesh)
- [How to do Topicwise Practice?](#how-to-do-topicwise-practice)
- [Topic List (As you are feeling lazy to collect them by yourself!)](#topic-list-as-you-are-feeling-lazy-to-collect-them-by-yourself)
- [Code Library](#code-library)
- [Common Mistakes](#common-mistakes)
- [The Art of Debugging](#the-art-of-debugging)
- [Stress Testing](#stress-testing)

### Discord Server
Join the best Competitive Programming Discord Server to get any kinda help instantly for free: [BCS - Bangladesh CP Server](https://discord.gg/hDSMZATsrM)

### What is Competitive Programming(CP)?
  Writing code to solve problems or tasks is the essence of programming. Competitive programming turns this into a sport, with competitors competing (typically online) to solve a bunch of such problems in a restricted period of time.

  "A programming competition generally involves the host presenting a set of logical or mathematical problems, also known as puzzles, to the contestants (who can vary in number from tens to several thousand), and contestants are required to write computer programs capable of solving each problem. Judging is based mostly upon several problems solved and time spent for writing successful solutions." - Wikipedia

### What is a Problem? 
  A problem is often based on arithmetic, logic, and/or algorithms and looks somewhat like [this](https://codeforces.com/problemset/problem/630/A). Such challenges often include a statement (detailing the task), the input and output format, and input, time and memory constraints.

  Try to understand [this](https://codeforces.com/problemset/problem/630/A) problem, read the statement carefully, check the input-output constraints and solve this. When you get the idea of how to solve it, then code it and submit it to get your first AC (Accepted solution).

  Here is the code for the problem in C++.

  ``` c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    long long n; cin >> n;
    cout << 25 << '\n';
    return 0;
  }
  ```

### The Ultimate Question: Why should I start Competitive Programming?
  Well, I believe that the ultimate goal of my existence is to be happy. And I have learned from many well-established people that getting a great job or being famous or other common stereotypical goals won't make you happy as when you get used to those they become meaningless.

  I think happiness is living your present with excitement.

  That being said, now your main goal is to find something that will make you happy. There are lots of things you can do like being a musician or an artist etc. For me it was CP. I can lose myself in CP for hours and hours and still hold my excitement. A good contest is enough to make my day.

  Man, I am not saying that you have to choose CP too. Find anything that suits you well, delve into that and maybe you will find peace.

  Because I wanna spend my precious time on something so that in the end I can say with Heisenberg, "I did it for me. I liked it, I was good at it, and I was really... I was alive".
  
  **So what kinda benefits you will get by doing CP?**
    - Fun and excitement(tons of it).
    - "Competitive programming builds the basics in you. You became so expert in coding anything that learning framework then becomes a very very easy task. Because when you learn to read the codes of hard or advanced algorithms, what can be more complex than those?  

"CP programming makes you versatile, so you can move from any stack to other. But when you only learn a specific framework or stack, your knowledge gets bounded.
  You can compare learning any natural language with this. Let's say you want to learn German/English. You need to learn grammar first then you can write a paragraph. In coding, you can think of CP programming as grammar learning and frameworks as paragraph writing! When you know grammar you can write a paragraph on any topic.
  Even after a good or average (not the best) career in CP, you will find the database, distributed system, machine learning topics very much understandable to you."- Raihat Zaman Neloy
  - You will find Interview problems much much easier if you do CP. Problem-solving skill is required in interviews and CP is the best and most exciting way to learn problem-solving.
  - "Competitive programming is recognized and supported by several multinational software and Internet companies, such as Google and Meta (Facebook). Several organizations host programming competitions on a regular basis." - Wikipedia
  - [and many more...](https://www.quora.com/What-have-you-gained-from-competitive-programming-Did-you-go-into-research-Did-it-help-you-in-any-aspect-as-a-software-engineer-Did-it-help-you-get-an-in-depth-knowledge-of-a-programming-language-Did-it-affect-your-problem-solving-skills)

  Let's discuss something if you think CP is the thing that you wanna do.

  Many of us set this goal like I wanna be red and continuously **looking at the goal** and not enjoying our **current** hard works. I am not red but I can guarantee myself that when I will be red I will be happy for a day or two and will get used to it. So what was my 3-4 years of hard work all about? Just a day of excitement? I don't believe in so. Wouldn't it be great if I could live those 3-4 years of my life with excitement? Well yes. This is what I am currently doing. I am living in the present, working hard and whether I become successful or not I will still be happy as I was **alive** throughout the whole process and lived my life to the fullest.

  May you find that something that you have been looking for throughout your life!  

### The Secret
  Not everyone has the privilege to do the things that they enjoy doing. If you have that privilege, then it's really cool. But most people don't have that privilege. So "Instead of doing things you enjoy, learn to enjoy the things you do". And CP is one of the things that you can easily fall in love with.

### Seriously vs Sincerely
  If you find yourself approaching things too seriously like it's no fun playing a game if you take it "too seriously". So if you want to have fun, you should switch to approaching things sincerely, like you are still gonna give it all, but you are gonna recognize that this is a game and you are gonna try and enjoy yourself while doing it. This philosophy also applies in CP. Watch [this](https://www.youtube.com/watch?v=FbSNfj2S6Pw) for more.

### What Progress is Really Like
  Imagine that you have an ice cube sitting on the table in front of you.

  The room is cold and you can see your breath. It is currently twentyfive degrees. Ever so slowly, the room begins to heat up.

  Twenty-six degrees. <br>
  Twenty-seven. <br>
  Twenty-eight.

  The ice cube is still sitting on the table in front of you.

  Twenty-nine degrees. <br>
  Thirty. <br>
  Thirty-one.

  Still, nothing has happened.

  Then, thirty-two degrees. The ice begins to melt. A one-degree shift, seemingly no different from the temperature increases before it, has unlocked a huge change. 

  Breakthrough moments are often the result of many previous actions, which build up the potential required to unleash a major change. This pattern shows up everywhere. Cancer spends 80 percent of its life undetectable, then takes over the body in months. Bamboo can barely be seen for the first five years as it builds extensive root systems underground before exploding ninety feet into the air within six weeks.

  Credit: The book Atomic Habit by  James Clear

  So don't get depressed after starting CP. It takes time to get your work reflected on your progress.
### Which language should I use for CP?
  Most Competitive Programmers (more than 95%) use C++ mostly because it's quite faster than other languages and it has some great built-in libraries(Standard Template Library (STL)) to ease your life. There are also many [other reasons](https://www.quora.com/Why-do-competitive-programmers-prefer-to-use-C++-instead-of-Java-in-the-programming-contests) for using C++.

  You can also use other languages too but for CP C++ is better. Languages are just tools and it doesn't take more than a few days to understand the basics of a language.

  Note that you don't have to be a master in C++ to start your CP journey. If you know the basics i.e. variables, data types, operators, conditions, functions and loops, then you are ready to start CP. You can learn them from [here](https://www.javatpoint.com/cpp-tutorial) or any of your favourite youtube channels.

### Where to write codes? What are the best IDEs?

  IDEs are where you will write your codes. You can use Sublime Text, Codeblocks, VS Code or any other IDE that you like. 

  I use Sublime Text. Check [this](https://www.geeksforgeeks.org/setting-up-sublime-text-for-cpp-competitive-programming-environment/) to set up C++ in Sublime Text for Competitive Programming. Check [this](https://github.com/the-hyp0cr1t3/CC/blob/master/Sublime%20Text%20Setup.md) to set up useful tools and snippets for Sublime Text and [this](https://kirankoduru.github.io/python/sublime-text-ninja.html) to find useful shortcuts.

  <details> <summary> Your sublime text should be something like this </summary>
  <a href="https://ibb.co/xfYv6Tk"><img src="https://i.ibb.co/3MvXcZ3/image.png" alt="image" border="0"></a>
  </details>

  Check [this](https://medium.com/@chinmaykulkarni8/how-to-setup-visual-studio-code-for-c-c-java-python-competitive-programming-angular-22fdc9b1f4c6) to setup C, C++, Java, Python in Visual Studio Code for Competitive Programming.


### Competitive Programming Platforms

  The most famous CP platform is [Codeforces](https://codeforces.com/). Check [this](https://blog.codingblocks.com/2019/sites-and-tools-for-competitive-programming/) to know about more platforms.

### How to Use Codeforces
  Check this [guide](https://codeforces.com/blog/entry/99660).

### Details about problem statements, how contests work and the rating system on Codeforces (and a few other platforms) <a name = "ratingsys"></a>

  Check [this](https://github.com/the-hyp0cr1t3/CC/blob/master/Competitve%20Programming%20Platforms.md) to get a detailed understanding of whats in a problem, what is meant by different verdicts (AC, WA, TLE, MLE, CE etc) and how contests work.

### What to do if I don't know how to solve a problem?
  Most of the problems have editorials/tutorials. The tutorial link is normally attached to the problem statement. In particular, on Codeforces, you can find the link to the tutorial at the lower right side of the problem statement. 
  <details> <summary> Example </summary>
  <a href="https://ibb.co/MRxm4XK"><img src="https://i.ibb.co/cNSjHmR/tutorial.jpg" alt="tutorial" border="0"></a>
  </details>

  Also, **join this discord server(if you are from Bangladesh) to get help**. Link: [Bangladesh CP Server](https://discord.gg/hDSMZATsrM)

### How to check others solutions?
  Check [this](https://codeforces.com/blog/entry/17012) to check solutions for a specific problem on Codeforces.

  For other platforms the way is similar. Just go to the submissions page for that problem and click on the ID of the submission.

  You can follow other users on Codeforces and make them friends (click the star button on the right of the username on CF) and check their solutions using the "friends only" button. I like the coding styles of the following users:
  - [neal](https://codeforces.com/profile/neal)
  - [YouKn0wWho](https://codeforces.com/profile/YouKn0wWho)
  - [mango_lassi](https://codeforces.com/profile/mango_lassi)
  - [jiangly](https://codeforces.com/profile/jiangly)
  - [tourist](https://codeforces.com/profile/tourist)
  - [Anachor](https://codeforces.com/profile/Anachor)
  - [Bruteforceman](https://codeforces.com/profile/Bruteforceman)
  - [Others](https://codeforces.com/blog/entry/77865)

### How to practice a problem efficiently?
  - First of all, **deeply** understand what the problem asks you to do.
  - Then you should try to solve it by yourself.
  - At the first glance, it may look like you have no idea what that random alien-made problem is asking you to do. But take your time. Always try to solve the problem using brute force. After that try to make your solution more efficient. 
  - Ok, so still you have no idea how to solve the problem? Try to look at it from a whole new angle.
  - "Keep trying while you have new ideas, then look up the editorial/tutorial after **15+ minutes of being completely stuck**." - Kamil Debowski
  - To be more precise, if you think you are getting into the solution, then take more time and try to solve it. But if you have no clue on how to solve it, then what is the point of wasting your valuable time? It will only slow down your improvement process.
  - After solving a problem by looking at the editorial/others codes, **think about why your way of thinking was not correct, what did you miss**. This is reallyyyy important.
  - Time to implement the problem. Try not to use any unnecessary macros. Try to make it more readable. It will help you debug the solution.
  - After that read implementations of some skilled users (searching for some useful tricks or really nice implementations). **This part is really important which will significantly improve your skill.**
  - If the problem uses a new idea/trick/algorithm which is a classic one i.e. it might be helpful in future then try to write that down so that in future you can easily access it.
  - Now, let me ask you a question, what did you learn from this problem?

### Virtual Contests
Virtual contests will give you a real-time experience. It enables the users to run the past contests in a special mode that would imitate a real competition. It feels just like a real contest with real contestants competing alongside the participant who writes a virtual contest. It won't affect your rating.

Do at least 3 virtual contests per week. Just pick any time and start a virtual contest from here: [link](https://codeforces.com/contests).

Do upsolve. Problems you can't solve during a contest but was in your range should be solved after the contest. What is the meaning of a contest if you don't learn something that wasn't already known to you?

### Kidlin's Law
  Kidlin's law: If you can write the problem down clearly then the matter is already half solved.

  This is also the same here in CP. First, understand what the problem asks you to do. Then proceed to solve it. If you understand it correctly, then you are half done. So don't start solving without understanding what the problem demands.

### [Contest]Solve some very basic problems.
Get familiar with problem-solving by solving these problems. You won't need to know anything other than the basics of a language to solve them. 

**Hint:** [How to Practice?](https://github.com/ShahjalalShohag/Competitive-Programming-A-Complete-Guideline#how-to-practice-a-problem-efficiently) <br>

**Goal:** Solve ALL problems.
- Contest 1: [link](https://codeforces.com/group/MWSDmqGsZm/contest/219158)
- Contest 2: [link](https://codeforces.com/group/MWSDmqGsZm/contest/219432)
- Contest 3: [link](https://vjudge.net/contest/468964)

**Pro Tip:** To check your ranking on the standings page on Vjudge, click on [settings](https://i.ibb.co/x7b1LQ6/image.png) on the contest page and then click on [Show Practice Submissions](https://i.ibb.co/R2CZ1Wg/image.png).

IT IS HIGHLY RECOMMENDED TO READ AND UNDERSTAND THE FOLLOWING CODES EVEN IF YOU SOLVE A PROBLEM ON YOUR OWN.
You will find very detailed commented out solutions here. Try to follow the same coding style (better spacing, better variable naming, modularized and readable codes etc). You may learn lots of new stuff by reading other's solutions.

### [Codes] Check how to solve the problems of Contest 1
<details> <summary> smash me </summary>

<b>1. Problem A</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  char name[100]; // considering the name has at most 100 characters
  cin >> name; // take the name as input
  cout << "Hello, " << name << '\n'; // output in the correct format
  return 0;
}
```

</details>
<br>

<b>2. Problem B</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  // make sure to declare the correct data types for each variable
  // use meaningful and readable variable names
  // use proper spacing to make your code look cooler (spaces before and after all operators)
  int int_variable;
  long long int long_long_variable;
  char char_variable;
  float float_variable;
  double double_variable;

  cin >> int_variable >> long_long_variable >> char_variable >> float_variable >> double_variable;
  cout << int_variable << '\n';
  cout << long_long_variable << '\n';
  cout << char_variable << '\n';
  cout << float_variable << '\n';
  cout << double_variable << '\n';
  // don't forget to output newlines after each variable
  return 0;
}
```

</details>
<br>

<b>3. Problem C</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  // int data type is enough for this problem as values are <= 10^5
  // always check the constraints in the problem statement
  // you can also use long long here but thats unnecessary and 2 times slower
  // because long long is 64 bit but int is 32 bit
  // Also use long long only when its necessary, do not overuse it, not a good practice
  int x, y; cin >> x >> y;

  // output in the EXACT SAME format as the problem suggests
  // 5 + 10 = 15 and 5+10=15 are different from each other! Spaces do matter when you output them
  cout << x << " + " << y << " = " << x + y << '\n';
  // cout << x << "+" << y << "=" << x + y << '\n'; // wrong! because we are not printing enough spaces
  // cout<<x<<" + "<<y<<" = "<<x+y<<'\n'; // correct but looks ugly. we are printing enough spaces IN THE OUTPUT but not using spaces IN THE CODE

  // typecast to long long as 1 <= x, y <= 10^5, so in the worst case (the case when the product will be the highest)
  // x = y = 10^5, so x * y = 10^5 * 10^5 = 10^10 and 10^10 is big enough
  // that we can't store it using 32 bits (int). So we should use 64 bit data types
  // As a rule of thumb, you can store upto 2*10^9 in int data type
  // and upto 9*10^18 in long long data type
  // but the exact value is of course 2^31 - 1 for int and 2^63-1 for long long
  cout << x << " * " << y << " = " << (long long)x * y << '\n';
  // cout << x << " * " << y << " = " << x * y << '\n'; // wrong, overflow!

  cout << x << " - " << y << " = " << x - y << '\n';
  return 0;
}
```

</details>
<br>

<b>4. Problem D</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  // note that the variable names do not have to be the exactly same as the problem statement
  // but it is intuitive to use the same variable names
  int A, B, C, D; cin >> A >> B >> C >> D; // int is enough as max value is <= 10^5

  // in the worst case A = B = 10^5, so A * B = 10^10
  // and 10^10 can't be stored in int,
  // - so we typecast it when multiplying A and B
  // - we also store it in a variable (AB) that has long long data type
  long long AB = (long long)A * B;
  // int AB = (long long) A * B; // wrong! as AB is in int, so overflow
  // long long AB = A * B; // wrong! as in the right hand side, A and B both are in int
                        // so A * B will also be in int, and so it will overflow
                        // even before storing the result in the AB variable

  long long CD = (long long) C * D;

  long long answer = AB - CD;

  cout << "Difference = " << answer << '\n';
  // cout << "Difference=" << answer << '\n'; // wrong! as not enough space before and after =
  // cout << answer << '\n'; // wrong! as not in the same output format as the problem tells us to do
  return 0;
}
```

</details>
<br>

<b>5. Problem E</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include<iomanip> // for using setprecision
using namespace std;

// its better to use const for variables that do not change
// you can't modify const variables and thats what we want for PI!
const double PI = 3.141592653;

int main() {
  // always use double instead of float as double has more bits
  // -> means more precisions -> more accurate results
  double R; cin >> R;
  double area = PI * R * R;

  // use setprecision to print UPTO 9 digits after the decimal point
  // use fixed to print EXACLTLY 9 digits after the decimal point
  // so if the result is 1.4569 then using setprecision(9) will output 1.4569
  // and using fixed << setprecision(9) will output 1.456900000
  // it is always better to use fixed when you use setprecision
  cout << fixed << setprecision(9) << area << '\n';
  return 0;
}
```

</details>
<br>

<b>6. Problem F</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  // use long long as values are upto 10^18
  long long n, m; cin >> n >> m;

  int last_digit_of_n = n % 10; // if you divide a number by 10 then the remainder will always be the last digit
  int last_digit_of_m = m % 10;
  int answer = last_digit_of_n + last_digit_of_m;
  cout << answer << '\n';
  return 0;
}
```

</details>
<br>

<b>7. Problem G</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  // the formula for the summation of numbers from 1 to n is = n * (n + 1) / 2
  // in the worst case, n = 10^9
  // so sum = 10^9 * (10^9 + 1) / 2 = around 10^18 / 2
  // and we can't store it in int, so we need long long here
  long long sum = 0;

  // we need to typecast in the right hand side as otherwise the right hand side will overflow
  sum = (long long) n * (n + 1) / 2;
  cout << sum << '\n'; // always output a newline at the end of the output file


  // sum = 0;
  // for (int i = 1; i <= n; i++) {
  //   sum += i;
  // }
  // cout << sum << '\n';
  //
  // this is also correct
  // but it will give you time limit exceeded verdict
  // as in the worst case, n = 10^9 and then the loop will run 10^9 times
  // in general it takes around 1s to run 10^8 operations (loops/additions/etc)
  // so it will take around 10s to run 10^9 operations
  // but the time limit in the problem is 0.25s
  // thats why it will give you TLE
  // note that you should ALWAYS understand why your code gives TLE
  return 0;
}
```

</details>
<br>

<b>8. Problem H</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include <cmath> // for using floor, ceil and round functions
using namespace std;

int main() {
  int a, b; cin >> a >> b;

  int floor_value = a / b; // c/c++ division operator does floor division by default IF a and b are integers
  // int floor_value = floor((double)a / b); // also corrects

  // ceil of a / b = floor of (a + b - 1) / b when a, b >= 1
  // for example, ceil of 9 / 5 = floor of (9 + 5 - 1) / 5 = 2
  // why is it true? think for yourself
  int ceil_value = (a + b - 1) / b; // great approach as we are not using any double here
  // int ceil_value = ceil((double)a / b); // also corrects, but it uses doubles which we normally should avoid because of precision issues

  int round_value = round((double) a / b);

  cout << "floor " << a << " / " << b << " = " << floor_value << '\n';
  cout << "ceil " << a << " / " << b << " = " << ceil_value << '\n';
  cout << "round " << a << " / " << b << " = " << round_value << '\n';
  return 0;
}
```

</details>
<br>

<b>9. Problem I</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b; cin >> a >> b;
  if (a >= b) { // notice where I am using spaces to make the code look better!
    cout << "Yes\n";
    // cout << "YES\n"; // wrong! as everything is case sensitive in general
  }
  else {
    cout << "No\n";
  }
  return 0;
}
```

</details>
<br>

<b>10. Problem J</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b; cin >> a >> b;
  // a is divisible by b means the remainder after dividing a by b is 0
  if (a % b == 0 or b % a == 0) { // you can use "or", "||" for the OR operator
    // we aren't using the AND operator here as we want the whole condition to be true
    // if any of the condition is true
    cout << "Multiples\n";
  }
  else {
    cout << "No Multiples\n";
  }
  return 0;
}
```

</details>
<br>

<b>11. Problem K</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b, c; cin >> a >> b >> c;
  int minimum = min(a, min(b, c)); // take the min of b and c first and then minimize it with a
  // int minimum = min(min(a, b), c); // also correct
  int maximum = max(a, max(b, c));

  // print the minimum first as suggested by the problem
  cout << minimum << ' ' << maximum << '\n';
  return 0;
}
```

</details>
<br>

<b>12. Problem L</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include <cstring> // for strings
using namespace std;

int main() {
  // assume each name has at most 1000 characters
  char first_name_first_person[1000], second_name_first_person[1000];
  char first_name_second_person[1000], second_name_second_person[1000];

  cin >> first_name_first_person >> second_name_first_person;
  cin >> first_name_second_person >> second_name_second_person;

  // check if the second names are equal
  bool is_equal = true; // stores if the strings are equal or not
  int len_1 = strlen(second_name_first_person);
  int len_2 = strlen(second_name_second_person);
  if (len_1 != len_2) { // if the lengths are not equal then the strings can't be equal
    is_equal = false;
  }
  else {
    // now check if all characters are equal in both strings
    for (int i = 0; i < len_1; i++) {
      if (second_name_first_person[i] != second_name_second_person[i]) {
        is_equal = false;
        break;
      }
    }
  }

  if (is_equal) {
    cout << "ARE Brothers\n";
  }
  else {
    cout << "NOT\n";
  }
  return 0;
}
```

</details>
<br>

<b>13. Problem M</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  char x; cin >> x;
  int ascii = (int)x; // convert to ascii value
  if (isalpha(x)) {
    // same as if ((x >= 'A' and x <= 'Z') or (x >= 'a' and x <= 'z'))
    // same as if ((ascii >= 65 and ascii <= 90) or (ascii >= 97 and ascii <= 122))
    cout << "ALPHA\n";
    if (isupper(x)) {
      // same as if ((x >= 'A' and x <= 'Z'))
      // same as if ((ascii >= 65 and ascii <= 90))
      cout << "IS CAPITAL\n";
    }
    else {
      // similar function: islower(x) -> to check if x is a small letter
      cout << "IS SMALL\n";
    }
  }
  else {
    // similar function: isdigit(x) -> to check if x is a digit
    cout << "IS DIGIT\n";
  }
  return 0;
}
```

</details>
<br>

<b>14. Problem N</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  char x; cin >> x;
  if (x >= 'A' and x <= 'Z') {
    // notice that all ascii values of 'A' to 'Z' are one after another from 65 to 90
    int ascii_of_capital_X = (int)x;
    int ascii_of_capital_A = (int)'A'; // = 65
    int position_of_capital_X = ascii_of_capital_X - ascii_of_capital_A;
    int ascii_of_small_a = (int)'a'; // = 97
    int ascii_of_small_x = ascii_of_small_a + position_of_capital_X;
    char small_x = (char)ascii_of_small_x;
    cout << small_x << '\n';
  }
  else {
    int ascii_of_small_x = (int)x;
    int ascii_of_small_a = (int)'a'; // = 97
    int position_of_small_x = ascii_of_small_x - ascii_of_small_a;
    int ascii_of_capital_A = (int)'A'; // = 65
    int ascii_of_capital_X = ascii_of_capital_A + position_of_small_x;
    char capital_X = (char)ascii_of_capital_X;
    cout << capital_X << '\n';
  }


  // also correct! and short!
  // if (x >= 'A' and x <= 'Z') {
  //   cout << (char)((x - 'A') + 'a') << '\n';
  // }
  // else {
  //   cout << (char)((x - 'a') + 'A') << '\n';
  // }

  // also correct! and perfect!
  // if (isupper(x)) {
  //   cout << (char)tolower(x) << '\n';
  // }
  // else {
  //   cout << (char)toupper(x) << '\n';
  // }
  return 0;
}
```

</details>
<br>

<b>15. Problem O</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b; char s;
  // for 7+54
  // cin >> a will add all the digits to a until it finds a non digit character
  // then it will find the non digit char +, and then cin >> s will trigger itself
  // then as s is a char data type, s will be equal to + and then cin >> b will get triggered
  // and then the rest of the digits will get added to b
  cin >> a >> s >> b;
  if (s == '+') {
    cout << a + b << '\n';
  }
  else if (s == '-') {
    cout << a - b << '\n';
  }
  else if (s == '*') {
    cout << a * b << '\n';
  }
  else {
    cout << a / b << '\n'; // integer division
  }
  return 0;
}
```

</details>
<br>

<b>16. Problem P</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int x; cin >> x;
  // notice that the number is from 1000 to 9999
  // so the first digit can be found by dividing the number by 1000

  int first_digit = x / 1000; // floor division
  if (first_digit % 2 == 0) {
    cout << "EVEN\n";
  }
  else {
    cout << "ODD\n";
  }

  // the following is another of way of getting the first digit
  // notice that we can take the input in any format we like
  // the judging system only cares about what we print in the output file!
  //
  // char x[100];
  // cin >> x;
  // int first_digit = x[0] - '0';
  return 0;
}
```

</details>
<br>

<b>17. Problem Q</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	double x, y;
	cin >> x >> y;
	if (x == 0 and y == 0) cout << "Origem\n";
	else if (y == 0 and (x > 0 or x < 0)) cout << "Eixo X\n";
	else if (x == 0 and (y > 0 or y < 0)) cout << "Eixo Y\n";
	else if (x > 0 and y > 0) cout << "Q1\n";
	else if (x < 0 and y > 0) cout << "Q2\n";
	else if (x < 0 and y < 0) cout << "Q3\n";
	else cout << "Q4\n";
	return 0;
}
```

</details>
<br>

<b>18. Problem R</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	int age_in_days; cin >> age_in_days;
	int years = age_in_days / 365;
	cout << years << " years\n";
	age_in_days = age_in_days % 365;

	int months = age_in_days / 30;
	cout << months << " months\n";

	age_in_days = age_in_days % 30;
	cout << age_in_days << " days\n";
	return 0;
}
```

</details>
<br>

<b>19. Problem S</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	double x; cin >> x;
	if (0 <= x and x <= 25) cout << "Interval [0,25]\n";
	else if (25 < x and x <= 50) cout << "Interval (25,50]\n";
	else if (50 < x and x <= 75) cout << "Interval (50,75]\n";
	else if (75 < x and x <= 100) cout << "Interval (75,100]\n";
	else cout << "Out of Intervals\n";
	return 0;
}
```

</details>
<br>

<b>20. Problem T</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b, c; cin >> a >> b >> c;

  int minimum = min(a, min(b, c));
  int maximum = max(a, max(b, c));
  int mid = a + b + c - minimum - maximum; // the other number that is neither min nor max

  cout << minimum << '\n' << mid << '\n' << maximum << '\n';
  cout << '\n'; // blank line is important as the problem said so
  cout << a << '\n' << b << '\n' << c << '\n';
  return 0;
}
```

</details>
<br>

<b>21. Problem U</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	float number; cin >> number;

	int integer_part = (int)number; // convert number to integer to get the integer part

	if (number == integer_part) {
		cout << "int " << integer_part << '\n';
	}
	else {
		float decimal_part = number - integer_part;
		cout << "float " << integer_part << " " << decimal_part << '\n';
	}
	return 0;
}
```

</details>
<br>

<b>22. Problem V</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	int a, b; char s;
	cin >> a >> s >> b;

	if(s == '<') {
		if (a < b) cout << "Right\n";
		else cout << "Wrong\n";
	}
	else if (s == '=') {
		if (a == b) cout << "Right\n";
		else cout << "Wrong\n";
	}
	else if (s == '>') {
		if (a > b) cout << "Right\n";
		else cout << "Wrong\n";
	}
	return 0;
}
```

</details>
<br>

<b>23. Problem W</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	int num1, num2, num3;
	char sign1, sign2;
	cin >> num1 >> sign1 >> num2 >> sign2 >> num3;

	if (sign1 == '*') {
		if (num3 == num1 * num2) cout << "Yes\n";
		else cout << num1 * num2 << '\n';
	}
	else if (sign1 == '+') {
		if (num3 == num1 + num2) cout << "Yes\n";
		else cout << num1 + num2 << '\n';
	}
	else if (sign1 == '-') {
		if (num3 == num1 - num2) cout << "Yes\n";
		else cout << num1 - num2 << '\n';
	}
	return 0;
}

```

</details>
<br>

<b>24. Problem X</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int l1, r1, l2, r2; cin >> l1 >> r1 >> l2 >> r2;
  int left_boundary = max(l1, l2);
  int right_boundary = min(r1, r2);
  if (left_boundary <= right_boundary) {
    cout << left_boundary << ' ' << right_boundary << '\n';
  }
  else {
    cout << -1 << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>25. Problem Y</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
	// solution explanation: https://youtu.be/6MSIMpWNRRg
	int a, b, c, d;
	cin >> a >> b >> c >> d ;
	a %= 100;
	b %= 100;
	c %= 100;
	d %= 100;
	int product = a * b * c * d;
	int last_digits = product % 100;
	if (last_digits < 10) {
		cout << 0 << last_digits << '\n'; // append 0 to the front to make 2 digits!
	}
	else {
		cout << last_digits << '\n';
	}
	return 0;
}
```

</details>
<br>

<b>26. Problem Z</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include <math.h>
using namespace std;

int main() {
	long long a, b, c, d ;
	cin >> a >> b >> c >> d ;
	// notice that the values a, b are large, so a^b will be an astronomical value
	// and we cant store it in long long either, so we need to think a bit
	// notice that we dont need the exact value of a^b, we just have to check
	// if a^b is > c^d or not.
	//
	// => a^b > c^d
	// => log(a^b) > log(c^d)  // take log in both sides
	// => b*loga > d*logc
	// now we can do this!

	if (b * log(a) > d * log(c)) {
		// this log is in base e by default (natural logarithm (ln)),
		// also the base doesn't matter here. You can also try with log2
		cout << "YES\n";
	}
	else {
		cout << "NO\n";
	}
	return 0;
}
```

</details>

  </details>

### [Codes] Check how to solve the problems of Contest 2
  <details> <summary> smash me </summary>
<b>1. Problem A</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  for (int i = 1; i <= n; i++) {
    cout << i << '\n'; // never use endl, use '\n' as it is faster than endl
  }
  return 0;
}
```

</details>
<br>

<b>2. Problem B</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  if (n == 1) {
    // no even numbers under 1
    cout << -1 << '\n';
  }
  else {
    for (int i = 2; i <= n; i += 2) {
      cout << i << '\n';
    }

    // // should also work
    // for (int i = 1; i <= n; i++) {
    //   if (i % 2 == 0) {
    //     cout << i << '\n';
    //   }
    // }
  }
  return 0;
}
```

</details>
<br>

<b>3. Problem C</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  int even_numbers = 0;
  int odd_numbers = 0;
  int positive_numbers = 0;
  int negative_numbers = 0;
  for (int i = 1; i <= n; i++) {
    int x; cin >> x;
    // taking absolute of x first before taking the modulo to get non negative remainder values
    // for example: -5 % 2 = -1, 5 % 2 = 1
    if (abs(x) % 2 == 0) {
      even_numbers++;
    }
    if (abs(x) % 2 == 1) {
      odd_numbers++;
    }
    if (x > 0) {
      positive_numbers++;
    }
    if (x < 0) {
      negative_numbers++;
    }
    // notice that 0 is neither positive, nor negative. It is neutral
  }
  cout << "Even: " << even_numbers << '\n';
  cout << "Odd: " << odd_numbers << '\n';
  cout << "Positive: " << positive_numbers << '\n';
  cout << "Negative: " << negative_numbers << '\n';
  return 0;
}
```

</details>
<br>

<b>4. Problem D</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

// use const for constant variables
// make constant variables all uppercase by convention
const int PASSWORD = 1999;

int main() {
  int x;
  // use while (cin >> x) to take input until End Of File (EOF)
  while (cin >> x) {
    if (x == PASSWORD) {
      cout << "Correct\n";
      break; // breaking the loop, as we dont need to take any more input as the problem said
    }
    else {
      cout << "Wrong\n";
    }
  }
  // note that this while loop will run until there is nothing in the file to take input from
  // or when we hit the correct password
  return 0;
}
```

</details>
<br>

<b>5. Problem E</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  int maximum = 0; // set maximum to a very small value that is <= any value in the input
  for (int i = 1; i <= n; i++) {
    int x; cin >> x;
    maximum = max(maximum, x);
  }
  cout << maximum << '\n';
  return 0;
}
```

</details>
<br>

<b>6. Problem F</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  for (int i = 1; i <= 12; i++) {
    cout << n << " * " << i << " = " << n * i << '\n';
    // print in the exact same format as the problem suggests
    // do not print extra spaces, do not print less spaces
    // 2 * 1 = 2 vs 2*1=2 are different!
  }
  return 0;
}
```

</details>
<br>

<b>7. Problem G</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int t; cin >> t;
  while (t--) {
    int n; cin >> n;
    // use long long data type as in the worst case
    // when n is the largest, that is n = 20
    // n! = 20! = 2432902008176640000 which we can't store in a 32 bit int data type
    long long factorial = 1;
    for (int i = 1; i <= n; i++) {
      factorial *= i;
    }
    cout << factorial << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>8. Problem H</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  // prime numbers are not divisible by any number i (2 <= i < n)
  for (int i = 2; i < n; i++) {
    if (n % i == 0) { // check if n is divisible by i
      cout << "NO\n";
      // print NO and return from the program as we don't want to print NO multiple times
      return 0;
    }
  }
  // special case: 1 is not prime!
  // also try to take 1 as input and run your program
  // always run your code against special cases
  if (n == 1) {
    cout << "NO\n";
    return 0;
  }
  cout << "YES\n";
  return 0;
}
```

</details>
<br>

<b>9. Problem I</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int number; cin >> number;
  int original_number = number; // remember the number!

  int reversed_number = 0;
  // get the digits from right to the left and append them one after another
  // for example, for 123, get the digits from right to left -> 3, 2, 1
  // then append them together: 321 (reversed number)
  while (number > 0) {
    int last_digit = number % 10;

    // append last_digit to the reversed_number
    reversed_number = reversed_number * 10 + last_digit;

    int number_without_last_digit = number / 10;
    number = number_without_last_digit;
  }
  cout << reversed_number << '\n';


  // in the while loop we have modified the value of number
  // thats why we remembered the original value
  if (original_number == reversed_number) { // palindrome
    cout << "YES\n";
  }
  else {
    cout << "NO\n";
  }
  return 0;
}
```

</details>
<br>

<b>10. Problem J</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

// function to check if the number is a prime or not
// returns a boolean of true if it is a prime or false otherwise
bool is_prime(int n) {
  // always check for special cases!
  if (n == 1) return false;
  for (int i = 2; i < n; i++) {
    // if it is divisible by some number other than 1 and n, then it is not a prime for sure
    if (n % i == 0) {
      return false;
    }
  }
  // now we know that it is a prime for sure!
  return true;
}
int main() {
  int n; cin >> n;
  // use functions to solve smaller subproblems
  // this will make your code cleaner and less buggy
  for (int i = 1; i <= n; i++) {
    if (is_prime(i)) {
      cout << i << ' ';
    }
  }
  cout << '\n';
  return 0;
}
// Also how many operations the program is making?
// In the worst case, n = 1000
// so we are running the loop in the main function 1000 times
// and then in the is_prime function for each number we running the loop
// 1000 times again. So in total we are making at most 1000 * 1000 = 10^6 operations
// And in general it takes 1s to run 10^8 operations.
// So we are good and won't get TLE
```

</details>
<br>

<b>11. Problem K</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main(){
  int n; cin >> n;
  for (int i = 1; i <= n; i++) {
    if (n % i == 0) {
      cout << i << '\n';
    }
  }
  return 0;
}
```

</details>
<br>

<b>12. Problem L</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include<algorithm> // for using the gcd function
using namespace std;

int main() {
  int a, b; cin >> a >> b;
  cout << __gcd(a, b) << '\n'; // use the builtin function
  return 0;
}
```

</details>
<br>

<b>13. Problem M</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

bool is_lucky_digit(int digit) {
  // use OR operator here as if digit is 4 OR digit is 7 it returns true
  // if you use AND operator here, it would mean digit would have to be 4 AND 7 at the same time!
  return digit == 4 or digit == 7;
}
bool is_lucky_number(int n) {
  // get the digits of n from right to left
  // and check if there is any non lucky digit
  while (n > 0) {
    int last_digit = n % 10;
    if (!is_lucky_digit(last_digit)) {
      // if there is at least one non lucky digit then we are fucked
      // return false immediately
      return false;
    }
    int number_without_last_digit = n / 10;
    n = number_without_last_digit;
  }
  return true;
}

// hey you! while reading others' codes, always start from the main function!
int main() {
  int a, b; cin >> a >> b;
  bool got_lucky_number = false;
  for (int i = a; i <= b; i++) {
    if (is_lucky_number(i)) {
      cout << i << ' ';
      got_lucky_number = true;
    }
  }
  if (!got_lucky_number) {
    cout << -1 << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>14. Problem N</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

// dont forget to use meaningful variable names!
int main() {
  char symbol; cin >> symbol;
  int n; cin >> n;
  for (int i = 1; i <= n; i++) {
    int count; cin >> count;
    // now print the symbol count times
    for (int j = 1; j <= count; j++) { // use a different variable name in this nested loop as we have already used i in the parent loop
      cout << symbol;
    }
    cout << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>15. Problem O</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int row_count; cin >> row_count;
  for (int row = 1; row <= row_count; row++) {
    // there will be "row" number of * in the "row"th row
    // for example, 1 * in the 1st row
    // 2 * in the 2nd row and so on
    int count_of_stars = row;
    for (int i = 1; i <= count_of_stars; i++) {
      cout << "*";
    }
    cout << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>16. Problem P</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int row_count; cin >> row_count;
  for (int row = 1; row <= row_count; row++) {
    // there will be "row_count - row + 1" number of * in the "row"th row
    // for example, if row_count = 4, then 4 * in the 1st row
    // 3 * in the 2nd row, 2 * in the 3rd row and 1 * in the 4th row
    int count_of_stars = row_count - row + 1;
    for (int i = 1; i <= count_of_stars; i++) {
      cout << "*";
    }
    cout << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>17. Problem Q</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int t; cin >> t;
  while (t--) {
    int n; cin >> n;
    if (n == 0) {
      cout << 0 << '\n';
      continue;
      // we can't use return 0 here as we are running multiple test cases
      // and return 0 will terminate the whole program which we dont want
    }
    while (n > 0) {
      int last_digit = n % 10;
      cout << last_digit << ' ';

      int number_without_last_digit = n / 10;
      n = number_without_last_digit;
    }
    cout << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>18. Problem R</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n, m;
  while (cin >> n >> m) {
    // The program should be TERMINATED as soon as any of these two numbers
    // is less than or equal to zero and don't print any thing.
    if (n <= 0 or m <= 0) {
      break;
    }
    // make n <= m for easier implementation
    if (n > m) {
      swap(n, m);
    }
    int sum = 0;
    for (int i = n; i <= m; i++) {
      cout << i << ' ';
      sum += i;
    }
    cout << "sum =" << sum << '\n'; // be careful with the spaces
  }
  return 0;
}
```

</details>
<br>

<b>19. Problem S</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int t; cin >> t;
  while (t--) {
    int x, y; cin >> x >> y;
    // make x <= y for easier implementation
    if (x > y) {
      swap(x, y);
    }
    int sum_of_odds = 0;
    // loop exluding x and y
    for (int i = x + 1; i < y; i++) {
      if (i % 2 == 1) { // odd number
        sum_of_odds += i;
      }
    }
    cout << sum_of_odds << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>20. Problem T</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int row_count; cin >> row_count;
  for (int row = 1; row <= row_count; row++) {
    // there will be "2 * row - 1" number of * in the "row"th row
    // for example, 1 * in the 1st row
    // 3 * in the 2nd row, 5 * in the 3rd row and 7 * in the 4th row
    int count_of_stars = 2 * row - 1;

    // before the stars there will be "row_count - row" number of spaces in the "row"th row
    // for example, if row_count = 4, then 3 spaces in the 1st row
    // 2 spaces in the 2nd row, 1 space in the 3rd row and 0 space in the 4th row
    int count_of_spaces = row_count - row;

    for (int i = 1; i <= count_of_spaces; i++) {
      cout << " ";
    }
    for (int i = 1; i <= count_of_stars; i++) {
      cout << "*";
    }
    // you can use the same variable names in loops if they are not nested
    cout << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>21. Problem U</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int get_sum_of_digits(int n) {
  int sum = 0;
  // get the digits of n from right to left
  // sum them up
  while (n > 0) {
    int last_digit = n % 10;
    sum += last_digit;
    int number_without_last_digit = n / 10;
    n = number_without_last_digit;
  }
  return sum;
}
int main() {
  int n, a, b; cin >> n >> a >> b;
  int sum_of_numbers = 0;
  for (int i = 1; i <= n; i++) {
    int sum_of_digits = get_sum_of_digits(i);
    if (a <= sum_of_digits and sum_of_digits <= b) {
      sum_of_numbers += i;
    }
  }
  cout << sum_of_numbers << '\n';

  // notice that we don't need to use long long in sum_of_numbers
  // as in the worst case, n = 10000. And we might have to take sum of all these numbers
  // from 1 to 10000. And it is at max 10000 * (10000 + 1) / 2. And this number
  // can be stored in an int variable
  // Rule: Do not use long long when its not necessary
  // this will make you a better coder
  return 0;
}

```

</details>
<br>

<b>22. Problem V</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  // notice that for each row the first number gets incremented by 4
  // and in each row, then 3 numbers are consecutive
  int first_number_in_row = 1;
  for (int row = 1; row <= n; row++) {
    for (int i = first_number_in_row; i <= first_number_in_row + 2; i++) {
      cout << i << ' ';
    }
    cout << "PUM\n";

    first_number_in_row += 4;
  }
  return 0;
}
```

</details>
<br>

<b>23. Problem W</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;

  // print the first half of the diamond
  for (int row = 1; row <= n; row++) {
    // there will be "2 * row - 1" number of * in the "row"th row
    // for example, 1 * in the 1st row
    // 3 * in the 2nd row, 5 * in the 3rd row and 7 * in the 4th row
    int count_of_stars = 2 * row - 1;

    // before the stars there will be "n - row" number of spaces in the "row"th row
    // for example, if n = 4, then 3 spaces in the 1st row
    // 2 spaces in the 2nd row, 1 space in the 3rd row and 0 space in the 4th row
    int count_of_spaces = n - row;

    for (int i = 1; i <= count_of_spaces; i++) {
      cout << " ";
    }
    for (int i = 1; i <= count_of_stars; i++) {
      cout << "*";
    }
    cout << '\n';
  }

  // print the last half of the diamond
  for (int row = 1; row <= n; row++) {
    // there will be "2 * (n - row + 1) - 1" number of * in the "row"th row
    // for example, if n = 4, 7 * in the 1st row
    // 5 * in the 2nd row, 3 * in the 3rd row and 2 * in the 4th row
    int count_of_stars = 2 * (n - row + 1) - 1;

    // before the stars there will be "row - 1" number of spaces in the "row"th row
    // for example, if n = 4, then 0 space in the 1st row
    // 1 space in the 2nd row, 2 spaces in the 3rd row and 3 spaces in the 4th row
    int count_of_spaces = row - 1;

    for (int i = 1; i <= count_of_spaces; i++) {
      cout << " ";
    }
    for (int i = 1; i <= count_of_stars; i++) {
      cout << "*";
    }
    cout << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>24. Problem X</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int t; cin >> t;
  while (t--) {
    int n; cin >> n;
    int number_of_ones_in_binary = 0;
    while (n > 0) {
      int last_bit = n % 2;
      if (last_bit == 1) {
        number_of_ones_in_binary++;
      }
      int drop_last_bit = n / 2;
      n = drop_last_bit;
    }
    int decimal = 0;
    for (int i = 1; i <= number_of_ones_in_binary; i++) {
      decimal = decimal * 2 + 1;
    }
    cout << decimal << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>25. Problem Y</b>

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

const int N = 45; // max value of n
int fib[N + 1]; // int data type is enough, try printing for n = 45
int main() {
  int n; cin >> n;
  fib[1] = 0;
  fib[2] = 1;
  for (int i = 3; i <= n; i++) {
    fib[i] = fib[i - 1] + fib[i - 2];
  }
  for (int i = 1; i <= n; i++) {
    cout << fib[i] << ' ';
  }
  cout << '\n';
  return 0;
}
```

</details>
<br>

<b>26. Problem Z</b>

<details> <summary> Code(C++) </summary>

```c++
// // bruteforce (direct) solution
// #include<iostream>
// using namespace std;

// int main() {
//   int k, s; cin >> k >> s;
//   int count = 0;
//   for (int x = 0; x <= k; x++) {
//     for (int y = 0; y <= k; y++) {
//       for (int z = 0; z <= k; z++) {
//         if ((x + y + z) == s) {
//           count++;
//         }
//       }
//     }
//   }
//   cout << count << '\n';
//   return 0;
// }
// // in the worst case, k = 3000
// // so we will have to run the loops 3000 * 3000 * 3000 = 27 * 10^9 times
// // but in general it takes 1s to run 10^8 operations.
// // so running 27 * 10^9 operations will take around 27 * 10^9 / 10^8 = 270s
// // but the time limit is 3s. So it will give you TLE

// optimized solution
#include<iostream>
using namespace std;

int main() {
  int k, s; cin >> k >> s;
  int count = 0;
  for (int x = 0; x <= k; x++) {
    for (int y = 0; y <= k; y++) {
      // notice that
      // => x + y + z = s
      // => z = s - x - y
      // so if we fix x and y, then z will also be fixed
      // we will just have to check if z >= 0 and z <= k or not
      int z = s - x - y;
      if (z >= 0 && z <= k) {
        count++;
      }
    }
  }
  cout << count << '\n';
  return 0;
}
```

</details>
<br>


  </details>

### [Editorials and Codes] Check how to solve the problems of Contest 3
  <details> <summary> smash me </summary>
<b>1. Problem A</b>

Editorial: [link](https://img.atcoder.jp/abc169/editorial.pdf)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b; cin >> a >> b;
  cout << a * b << '\n';
  return 0;
}
```

</details>
<br>

<b>2. Problem B</b>

Editorial: [link](https://atcoder.jp/contests/abc209/editorial/2242)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b; cin >> a >> b;
  if (a <= b) {
    cout << b - a + 1 << '\n';
  }
  else {
    cout << 0 << '\n';
  }
  return 0;
}
```

</details>
<br>

<b>3. Problem C</b>

Editorial: [link](https://img.atcoder.jp/abc124/editorial.pdf)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int button_1, button_2;
  cin >> button_1 >> button_2;

  int ans = 0;
  // press the first button twice
  ans = max(ans, button_1 + (button_1 - 1));

  // press the second button twice
  ans = max(ans, button_2 + (button_2 - 1));

  // press the first and second buttons once
  ans = max(ans, button_1 + button_2);

  cout << ans << '\n';

  return 0;
}
```

</details>
<br>

<b>4. Problem D</b>

Editorial: [link](https://atcoder.jp/contests/abc226/editorial/2903)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include <math.h> // for using the round function
using namespace std;

int main() {
  double x; cin >> x; // we need double data type
  cout << round(x) << '\n'; // use the builtin round function
  return 0;
}
// Can you solve it without using a builtin function?
// Try yourself and if you can't then ask on discord
```

</details>
<br>

<b>5. Problem E</b>

Editorial: [link](https://atcoder.jp/contests/abc222/editorial/2757)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int n; cin >> n;
  // just handle seperate cases
  if (n < 10) cout << "000" <<  n << '\n';
  else if (n < 100) cout << "00" <<  n << '\n';
  else if (n < 1000) cout << "0" <<  n << '\n';
  else cout << n << '\n';
  return 0;
}
```

</details>
<br>

<b>6. Problem F</b>

Editorial: [link](https://img.atcoder.jp/abc125/editorial.pdf)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b, t;
  cin >> a >> b >> t;
  int total_biscuits = 0;
  for (int time = a; time <= t; time += a) {
    // produces b biscuits at this time
    total_biscuits += b;
  }
  cout << total_biscuits << '\n';


  // notice that the for loop runs exactly floor(t / a) times
  // and each time we are adding b biscuits
  // so you can solve the problem like this
  // cout << (t / a) * b << '\n';
  return 0;
}

```

</details>
<br>

<b>7. Problem G</b>

Editorial: [link](https://atcoder.jp/contests/abc220/editorial/2700)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b, c; cin >> a >> b >> c;
  for (int i = a; i <= b; i++) { // go through the numbers that are between a and b
    // check if i is a multiple of c
    // that means the remainder if we divide i by c will be 0
    if (i % c == 0) {
      // awesome! we just found a multiple
      cout << i << '\n';
      return 0; // return immediately as we don't wanna print anything else
    }
  }
  // if we are here, it means we haven't found any multiple
  // so print -1 as asked by the problem
  cout << -1 << '\n';
  return 0;
}
```

</details>
<br>

<b>8. Problem H</b>

Editorial: [link](https://codeforces.com/blog/entry/43392)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int evony_damage, ivory_damage, damage_goal;
  cin >> evony_damage >> ivory_damage >> damage_goal;

  // evony and ivory can do any non-negative number of shots
  // so lets try all possible shots
  for (int evony_shots = 0; ; evony_shots++) {
    if (evony_shots * evony_damage > damage_goal) {
      break; // it doesn't make sense to loop further as the damage is already more than our goal
    }
    for (int ivory_shots = 0; ; ivory_shots++) {
      int total_damage = evony_shots * evony_damage + ivory_shots * ivory_damage;
      if (total_damage == damage_goal) { // yayy
        cout << "Yes\n";
        return 0; // return immediately
      }
      if (total_damage > damage_goal) { // no need to take more shots, its already bigger
        break;
      }
    }
  }

  // we are here means we haven't the damage goal
  cout << "No\n";
  return 0;
}

/**
In our problem damage_goal is at most 10000
The first loop will run at most damage_goal = 10000 times as in the worst case
evony_damage = 1 and each time he can deal 1 damage, so after 10000 loops the loop will break

But the nested inside loop will also run damage_goal = 10000 times by the same logic

So in total, as the loops are nested, the total number of operations will be around 10000 * 10000 = 10^8
In general 10^8 operations take around 1s or less. So we are good.

It is REALLY important to understand how many operations your problem is doing.
It is a CRIME if you don't understand this. Ask on discord if you have any questions.
**/
```

</details>
<br>

<b>9. Problem I</b>

Editorial: [link](https://atcoder.jp/contests/abc199/editorial/1165)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int a, b, c; cin >> a >> b >> c;
  // for doing a^2 use a * a instead of pow(a, 2) as pow function works for double numbers
  // and it is not 100% accurate for integer calculations
  if (a * a + b * b < c * c) {
    cout << "Yes\n";
  }
  else {
    cout << "No\n";
  }
  return 0;
}
```

</details>
<br>

<b>10. Problem J</b>

Editorial: [link](https://atcoder.jp/contests/abc193/editorial/822)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include <iomanip>
using namespace std;

int main() {
  int regular_price, discounted_price;
  cin >> regular_price >> discounted_price;

  int total_discounts = regular_price - discounted_price;
  double discount_percentage = (double) total_discounts / regular_price * 100; // typecast to double to do double divisions

  cout << fixed << setprecision(10) << discount_percentage << '\n';
  // in the problem it says "Your answer will be judged as correct when its absolute or relative error from our answer is at most 10^-2"
  // so we will have to print at least 2 digits after the decimal point
  // for being safe, we are printing 10 digits after the decimal point
  // ALWAYS use the fixed keyword as it will make sure that you are printing exactly 10 digits after the decimal point
  // without using << fixed, printing 2.63 will print 2.63, but with << fixed it will print 2.6300000000
  return 0;
}
```

</details>
<br>

<b>11. Problem K</b>

Editorial: [link](https://img.atcoder.jp/abc152/editorial.pdf)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int total_test_cases, passed_test_cases;
  cin >> total_test_cases >> passed_test_cases;
  if (passed_test_cases == total_test_cases) {
    cout << "Yes\n";
  }
  else {
    cout << "No\n";
  }
  return 0;
}
```

</details>
<br>

<b>12. Problem L</b>

Editorial: [link](https://codeforces.com/blog/entry/24160)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

/**
expression | product  | last two digits
    5^2    |   25     |    25
    5^3    |   125    |    25
    5^4    |   625    |    25
    5^5    |   3125   |    25

So???
**/
int main() {
  long long n; cin >> n;
  cout << 25 << '\n';
  return 0;
}
```

</details>
<br>

<b>13. Problem M</b>

Editorial: [link](https://atcoder.jp/contests/abc214/editorial/2444)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

int main() {
  int sum, product; cin >> sum >> product;
  int count = 0;
  // try all possible triplets such that their sum is <= sum
  for (int a = 0; a <= sum; a++) { // we start from a = 0 as they asked for triples of NON-NEGATIVE integers
    for (int b = 0; b <= sum; b++) {
      for (int c = 0; c <= sum; c++) {
        if (a + b + c <= sum) {
          // check for the product
          if (a * b * c <= product) {
            count++;
          }
        }
      }
    }
  }
  cout << count << '\n';
  return 0;
}

// in the max case, sum = 200
// so the 3 nested loops will run sum * sum * sum = 200^3 = 8 * 10^6 times
// so we are good
```

</details>
<br>

<b>14. Problem N</b>

Editorial: [link](https://codeforces.com/blog/entry/21590)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

/**
Imagine we need to find S = 1 + 2 + 3 + ... + (n - 1) + n
How to find it without using a loop?

Do you remember the formula for this from school?
If not, lets find its formula again!

S  =    1    +    2    +    3    + ... + (n - 1) +    n
S  =    n    + (n - 1) + (n - 2) + ... +    2    +    1  (showing in reverse order)
----------------------------------------------------------
2S = (n + 1) + (n + 1) + (n + 1) + ... + (n + 1) + (n + 1) (sum the first and second equations)

so 2S = (n + 1) * n (as there are n variables in total)
so S = (n + 1) * n / 2
So instead of running a loop we can just use this formula to find the sum from 1 to n. Great!


Note that the powers of twos are 2^0 = 1, 2^1 = 2, 2^2 = 4, 2^3 = 8, 2^4 = 16, 2^5 = 32, ...
But in this problem we have to find P = -1 - 2 + 3 - 4 + 5 + 6 + 7 - 8 + 9 + 10 + ... upto n (only powers of twos have negative sign)

How to do this?

  S   =    1  +   2 + 3 + 4   + 5 + 6 + 5 + 8 + 9 + 10 + ...
  P   =   -1  -   2 + 3 - 4   + 5 + 6 + 7 - 8 + 9 + 10 + ...
----------------------------------------------------------
S - P = 2 * 1 + 2 * 2 + 2 * 4 +          + 2 * 8 + ...       (subtracting the second equation from the first)

So basically,
S - P = 2 * (1 + 2 + 4 + 8 + ....)
S - P = 2 * (sum of powers of 2 that are <= n)

so P = S - 2 * (sum of powers of 2 that are <= n)

We can compute S fast, so we have to compute the sum of powers of 2 that are <= n
But the thing is there aren't that many powers of 2 under n.
There are log2(n) powers of 2 under n. For n = 10^9, there are only 30 powers of 2 uner 10^9.
So we can just loop over them!
**/
int main() {
  int t; cin >> t;
  while (t--) {
    int n; cin >> n;
    long long S = (long long) (n + 1) * n / 2; // typecast to long long so that we don't overflow
    long long sum_of_powers_of_2 = 0;
    for (int i = 1; i <= n; i *= 2) { // traversing through all powers of 2, one is just the double of the previous one
      sum_of_powers_of_2 += i;
    }
    long long P = S - 2 * sum_of_powers_of_2;
    cout << P << '\n';
  }
  return 0;
}

// we can't run a loop n times in this problem thats because n can be as large as 10^9
// and in 1s we can do around 10^8 operations
// so it will take arounf 10^9 / 10^8 = 10s to run a loop n times which is way more than our time limit
```

</details>
<br>

<b>15. Problem O</b>

Editorial: [link](https://img.atcoder.jp/abc051/editorial.pdf)

<details> <summary> Code(C++) </summary>

```c++
// // bruteforce (direct) solution
// #include<iostream>
// using namespace std;

// int main() {
//   int k, s; cin >> k >> s;
//   int count = 0;
//   for (int x = 0; x <= k; x++) {
//     for (int y = 0; y <= k; y++) {
//       for (int z = 0; z <= k; z++) {
//         if ((x + y + z) == s) {
//           count++;
//         }
//       }
//     }
//   }
//   cout << count << '\n';
//   return 0;
// }
// // in the worst case, k = 2500
// // so we will have to run the loops 2500 * 2500 * 2500 = 15625000000 times
// // but in general it takes 1s to run 10^8 operations.
// // so running 15625000000 operations will take around 15625000000 / 10^8 = 156s
// // but the time limit is 2s. So it will give you TLE

// optimized solution
#include<iostream>
using namespace std;

int main() {
  int k, s; cin >> k >> s;
  int count = 0;
  for (int x = 0; x <= k; x++) {
    for (int y = 0; y <= k; y++) {
      // notice that
      // => x + y + z = s
      // => z = s - x - y
      // so if we fix x and y, then z will also be fixed
      // we will just have to check if z >= 0 and z <= k or not
      int z = s - x - y;
      if (z >= 0 && z <= k) {
        count++;
      }
    }
  }
  cout << count << '\n';
  return 0;
}
```

</details>
<br>

<b>16. Problem P</b>

Editorial: [link](https://codeforces.com/blog/entry/2393)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
#include<string.h>
using namespace std;

const int N = 1e5 + 9;
char number_as_string[N];
int main() {
  // as the number is at most 10^100000 so the number can have 100000 digits!
  // so we can't store it in int or long long
  // we have to read it as a string
  cin >> number_as_string;
  int len = strlen(number_as_string);
  // edge case: if the length is already 1 then we don't have to perform any spell
  if (len == 1) {
    cout << 0 << '\n';
    return 0;
  }

  // now we will have to convert it to its sum of digits
  // but the funny thing is that the sum of digits can be stored in int
  // as in the worst case every digit is 9, and sum of 100000 9s = 999999
  int sum_of_digits = 0;
  for (int i = 0; i < len; i++) {
    sum_of_digits += number_as_string[i] - '0';
  }
  int spell_count = 1; // we just performed one spell

  // now we can perform the spells as long as we don't hit only one digit number
  int current_number = sum_of_digits;

  while (current_number > 9) { // it has more than one digit
    int sum_of_digits = 0;
    while (current_number > 0) {
      int last_digit = current_number % 10;
      sum_of_digits += last_digit;
      int number_without_last_digit = current_number / 10;
      current_number = number_without_last_digit;
    }
    // replace the number with its sum of digits and increment the spell count
    current_number = sum_of_digits;
    ++spell_count;
  }
  cout << spell_count << '\n';
  return 0;
}
```

</details>
<br>

<b>17. Problem Q</b>

Editorial: [link](https://codeforces.com/blog/entry/610)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

/**
Divide the problem into multiple steps.

Thinking Process:

Level 1:
  Loop i from 1 to n and check if i is an almost prime number,
  so we can have a function for that. Lets call it is_almost_prime() function.

  Level 2:
  is_almost_prime(n) function:
    In the function we have to check if the number n is an almost prime number.
    That is we have to check if the number has exactly two prime divisors.
    So we can loop over i from 1 to n and check if i is a prime divisor of n
    then count it. If the count is 2 then OK.
    To check if it is a divisor we can check if n % i == 0
    And to check if it is a prime we need another function!

        Level 3:
        is_prime(n) function:
          In this function we need to check if n is a prime or not.
          We can loop over i from 2 to n - 1, if any number divides it
          then n is not a prime, otherwise it is a prime.

So we are done! but note that we are doing 3 nested for loops in this solution.
As n = 3000, running 3 nested loops is not good as 3000 * 3000 * 3000 operations will take more than our time limit (2s)

But notice that we are calling the is_prime(n) function tons of times.
But is_prime(n) can take 1 <= n <= 3000, so 3000 different inputs.
So we can remember which of these are prime and which are not BEFORE our solution
and we can store the answers in an array.

By doing so, we don't have to call the is_prime(n) function in Level 3.
We can just get the info from our answer array. Check the code to understand more.

This way we can remove one nested loop.
So we will have two nested loops = 3000 * 3000 operations which is OK

**/

const int N = 3030;

bool is_prime[N];
bool check_prime(int n) {
  if (n == 1) return false; // 1 is not a prime by definition
  for (int i = 2; i < n; i++) {
    if (n % i == 0) { // n is divisible by i but i is neither 1, nor n, so n must not be a prime
      return false;
    }
  }
  return true;
}
bool is_almost_prime(int n) { // Level 2
  int prime_divisor_count = 0;
  for (int i = 1; i <= n; i++) {
    if (n % i == 0) { // i is a divisor
      if (is_prime[i]) { // prime divisor (check if it is a prime from the answer array that we precalculated!)
        prime_divisor_count++;
      }
    }
  }
  if (prime_divisor_count == 2) return true; // almost prime when it has two prime divisors
  else return false;
}
int main() {
  int n; cin >> n;
  // Level 3: precalculate which numbers are prime and which are not
  for (int i = 1; i <= n; i++) {
    is_prime[i] = check_prime(i);
  }
  int ans = 0;
  // Level 1
  for (int i = 1; i <= n; i++) {
    if (is_almost_prime(i)) {
      ++ans;
    }
  }
  cout << ans << '\n';
  return 0;
}
```

</details>
<br>

<b>18. Problem R</b>

Editorial: [link](https://codeforces.com/blog/entry/6662)

<details> <summary> Code(C++) </summary>

```c++
#include<iostream>
using namespace std;

bool has_distinct_digits(int year) { // year has 4 digits
  // get all digits from right to left
  int d4 = year % 10;
  year /= 10;
  int d3 = year % 10;
  year /= 10;
  int d2 = year % 10;
  year /= 10;
  int d1 = year % 10;

  if (d1 != d2 and d1 != d3 and d1 != d4
    and d2 != d3 and d2 != d4
     and d3 != d4) { // check if all digits are distinct
    return true;
  }
  return false;
}
int main() {
  int year; cin >> year;
  // in this problem 1000 <= year <= 9000
  // as 9012 has all distinct digits so in the following loop
  // year will always have 4 digits and it will never exceed 9012
  while (year++) {
    if (has_distinct_digits(year)) {
      cout << year << '\n';
      return 0;
    }
  }
  return 0;
}
```

</details>
<br>
    </details>
    
 **REMEMBER THAT SOLVING MORE PROBLEMS IS THE KEY**

### FAQ
  - [What is the key to CP?](https://codeforces.com/blog/entry/47516)
  - [Regarding Interviews and Jobs](https://redgreencode.com/cpwiki/Category:FAQs_about_interviews_and_jobs)
  - [CP or Development?](https://redgreencode.com/cpwiki/Should_I_spend_my_time_on_competitive_programming_or_real-world_software_development%3F)
  - [I need Advice](https://redgreencode.com/cpwiki/What_advice_does_(person)_have_for_competitive_programming_success%3F)
  - [When will I be a good CPer?](https://codeforces.com/blog/entry/53341?#comment-373965)

### Important Notes
  - **Exercise** (at least running) and drink more water. It will surprisingly boost up your learning capability.
  - **Getting AC is not the final goal, learning something new is the final goal**. Exactly, for this reason, people solve thousands of problems but can't get better. You need to solve harder problems than your current level so that you can learn something new by solving that problem. Also, after you solve a problem, try to do it more efficiently if possible, look at others solutions. This way you will learn better and become better faster in the long run.
  - After solving a problem, **think about why your way of thinking was not optimal**. This is important too.
  - **SOLVE MORE PROBLEMS**.

### Getting into Competitive Programming
  - [Getting into CP](https://github.com/the-hyp0cr1t3/CC)
  - [Basic Blocks](https://www.hackerearth.com/practice/notes/getting-started-with-the-sport-of-programming/ )
  - [Book](https://cses.fi/book/book.pdf)

### Tutorial
  - [A way to Practice Competitive Programming : From Rating 1000 to 2400+ by Masataka Yoneda](https://drive.google.com/file/d/1J2x8pIYQ3MXANgvzOgBciWd3d79j_Exa/view)
  - [From Beginner to Grandmaster - Complete Roadmap for Competitive Programming by Galen Colin](https://www.youtube.com/watch?v=bSdp2WeyuJY)
  
**Note: If your Codeforces rating is not at least 1900 then the aftermentioned topicwise practice is not needed, just learn basic stuffs and follow the tutorial linked above.**
 
### Life Hack(if you are from Bangladesh)
If you want a complete guideline like this for EVERYTHING about CP and you are from Bangladesh, then you can check out my academy and enroll in some courses that fits you well. 

Link: [YouKn0wWho Academy](https://academy.shahjalalshohag.com/). 

Actually the whole part of this repo till now is taken from a **single class** from one of my academy courses!

### How to do Topicwise Practice?
  1. Create a topic list(every possible category, from easy to advanced).
  2. Select a topic.
  3. Learn the topic.
  4. Solve lots of problems about that topic.
  5. Go to ii.

  And of course, participate in every possible contests in every online judge.                                                            
  
### Topic List (As you are feeling lazy to collect them by yourself!)
- [The Ultimate Topic List (with Resources, Problems and Templates)](https://codeforces.com/blog/entry/95106)

### Code Library
- [Almost all the important templates that you will need in CP](https://github.com/ShahjalalShohag/code-library)

### Common Mistakes
Check out [[Tutorial] Common Mistakes in Competitive Programming and How to Avoid Them](https://codeforces.com/blog/entry/111217)

### The Art of Debugging
  - Run with n=1.
  - Check overflow(long long vs int).
  - Check all array bounds.
  - Check if m, n aren’t misused.
  - Printed enough new lines or extra new lines?
  - Make sure output format is right(including YES/NO vs Yes/No or
  newline vs spaces).
  - Have you cleared the vectors ?
  - Make sure two ints aren’t multiplied to get a long long.
  - Output enough digits after decimal point.
  - Check the constraints again.
  - When using multiple dfs recursions check if inside one dfs another dfs
  is called or not.
  - Shouldn't you print the case number?
  - Are you using the correct mod value?
  - "I spent a lot of my time debugging my solution without any success,
  after the contest I discovered that the obstacles in the input is 'x'
  (small one) while I was thinking it was 'X' (capital), I lost a bronze
  medal because of it :(" - kingofnumbers
  - Set or multiset?
  - Different Variables with the same name?
  - Inside 2d loop are you using i++ instead of j++?
  - Are you using ceil function? Then remove it!
  - Is inf large enough?
  - For multiple queries are you returning 0 inside the queries?
  - For max and min have you initialized the values by a good enough
  value?
  - Are you using the local variable of the same name when global variable was
  required to be used?
  - "Declared a counter of type char instead of int , resulted in passing of
  pretests and failing of system test. :)" - A random CF user
  - "I subtracted 1 in a for loop from v.size(). Guess what happened when
  the input vector is empty?" - A random CF user
  - "for (int i = n - 1; i--; i >= 0)
  instead of:
  for (int i = n - 1; i >= 0; i--)
  It passed pretests and failed systests" - A random CF user
  - Are you using memset correctly?
  - Use bool operators using brackets. Beware!!! E.g. ans = ans + k == 0 vs ans = ans + (k == 0).
  - Have you deleted debug(x) lines? It might get you TLE!
  - It may be scanf("%d" , x). where &x is missing.
  - Instead of printing NO printed N0. (with a zero).
  - Are you erasing values from a set or an stl while parallelly traversing
  the elements of the stl? Please don’t. This is not nice!
  - Don't use scanf or printf while using ios_base.
  - Still have no idea? Try to recode from scratch or see others solutions.
### Stress Testing
  - [Find a counter-test](https://ali-ibrahim137.github.io/competitive/programming/2020/08/23/Stress-Testing.html)

Also, remember to exercise and drink more water. It helps a lot. 

Good luck <a href="https://emoji.gg/emoji/8771_blobheart"><img src="https://emoji.gg/assets/emoji/8771_blobheart.png" width="16px" height="16px" alt="blobheart"></a>.
