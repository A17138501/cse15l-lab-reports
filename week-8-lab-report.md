# Week 8 Lab Report 4 #


[Link to my markdown-parse](https://github.com/A17138501/markdown-parser)


repository and a link to the one you reviewed in week 7 

[Link to the one I reveiwed](https://github.com/ayushs2725/markdown-parser)


# Snippet1

**Part1**

what it should produce by using VScode preview:
![Picture to Sinppet1]()


**Part2**

Showing the code in MarkdownParseTest.java for how you turned it into a test

![Picture to show Junit]()

**Part3**

For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show Junit]()

**Part4**
For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show reviewed junit]

**Part5**
Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

For my implementation:

Yes, i think it could be fixed in a small code, I make a new field called Backtik and it is an interger showed that the index of "`", and i use a if statement to show that if openbracket - backtik !=1, i will add the substring which is form openparenthesis to closeparenthesis. Below is the pic how i fix the bug.

![Fix 1]()

For reviewed one:


# Snippet2

**Part1**

what it should produce by using VScode preview:
![Picture to Sinppet2]()


**Part2**

Showing the code in MarkdownParseTest.java for how you turned it into a test

![Picture to show Junit]()

**Part3**

For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show Junit]()

**Part4**
For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show reviewed junit]()

**Part5**

Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

For my implementation:

No, i dont think i could fix the bug in a small code, for this problem what i would do is that i will abstract the strings that from openparenthsis to closeparenthsis and write a helper method out of the markdownParse class that called findlast, it will take an string and make it to an array, then i will use a for loop, it takes an interger i that the value set to be length of the array and then i--, it should be greater than 0. in the for loop there is a if statement that if at the index i the character is equal to ")", the function will return the value of i, and the next step is that go back to markdownparse class and change the value of the integer closeparen to openparenthsis + i which is the the fisrt"(" add the distance i. as you can see from my previous solution, the code is going to be more than 10 lines.

For reviewed one:



# Snippet3

**Part1**

what it should produce by using VScode preview:
![Picture to Sinppet2]()


**Part2**

Showing the code in MarkdownParseTest.java for how you turned it into a test

![Picture to show Junit]()

**Part3**

For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show Junit]()

**Part4**
For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show reviewed junit]()

**Part5**

Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

For my implementation:

yes, i think i could solve this solution within 10 lines, what im going to do is that i will use contain method to check the substring from openparenthsis to closeparenthsis that if there have a "/n" or not, if it is there, i will make the while loop skip this link and try to find the next link, it could be solved in 10 lines.

For reviewed one: