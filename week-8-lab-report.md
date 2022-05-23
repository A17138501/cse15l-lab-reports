# Week 8 Lab Report 4 #


[Link to my markdown-parse](https://github.com/A17138501/markdown-parser)


repository and a link to the one you reviewed in week 7 

[Link to the one I reveiwed](https://github.com/ayushs2725/markdown-parser)


# Snippet1

**Part1**

what it should produce by using VScode preview:
![Picture to Sinppet1](https://user-images.githubusercontent.com/97008935/169733792-df05f847-e1e1-4644-982b-1eaf2cc10c11.png)



**Part2**

Showing the code in MarkdownParseTest.java for how you turned it into a test

![Picture to show test](https://user-images.githubusercontent.com/97008935/169734303-eeef9530-dcd3-4a1f-98e1-f7d1a9e35049.png)


**Part3**

For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Picture to show Junit](https://user-images.githubusercontent.com/97008935/169733894-2fb09328-7f00-43cb-9093-ea5fd22c6151.png)

**Part4**
For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Review1Junit](https://user-images.githubusercontent.com/97008935/169734640-27239b37-d6f1-4536-8415-da605d4654d4.png)


**Part5**
Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

For my implementation:

Yes, i think it could be fixed in a small code, I make a new field called Backtik and it is an interger showed that the index of "`", and i use a if statement to show that if openbracket - backtik !=1, i will add the substring which is form openparenthesis to closeparenthesis. Below is the picture how i fix the bug.

![Fix1](https://user-images.githubusercontent.com/97008935/169734673-71bb74b7-2672-4cb4-9f4f-2cf2b0515574.png)


For reviewed one:

Yes, i think it could be fixed a small code, the reviewed code is pretty simillar to my code the difference is that they use a one line of if statement to make that if the index of any parenthsis or brackets is equal to -1 which means that the parenthsis or brackets can not be found will break the while loop in the markdownparse class. and in my code i separate them to the blow of each parenthsis or brackets. waht i need to do is to add the same thing what i have done in my implementation part.I make a new field called Backtik and it is an interger showed that the index of "`", and i use a if statement to show that if openbracket - backtik !=1, i will add the substring which is form openparenthesis to closeparenthesis.

# Snippet2

**Part1**

what it should produce by using VScode preview:

![Snippet2](https://user-images.githubusercontent.com/97008935/169734708-f83d70a5-30e3-4cef-b476-d49a8c6b866b.png)


**Part2**

Showing the code in MarkdownParseTest.java for how you turned it into a test

![Picture to show test](https://user-images.githubusercontent.com/97008935/169734303-eeef9530-dcd3-4a1f-98e1-f7d1a9e35049.png)


**Part3**

For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Snippet2Junit](https://user-images.githubusercontent.com/97008935/169734766-3e78b4fc-90da-427c-82bb-8c4bcdb961f3.png)


**Part4**
For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![ReviewJunit2](https://user-images.githubusercontent.com/97008935/169734802-2b999ab2-a669-4b4c-a12f-e4f0e17876af.png)


**Part5**

Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

For my implementation:

No, i dont think i could fix the bug in a small code, for this problem what i would do is that i will abstract the strings that from openparenthsis to closeparenthsis and write a helper method out of the markdownParse class that called findlast, it will take an string and make it to an array, then i will use a for loop, it takes an interger i that the value set to be length of the array and then i--, it should be greater than 0. in the for loop there is a if statement that if at the index i the character is equal to ")", the function will return the value of i, and the next step is that go back to markdownparse class and change the value of the integer closeparen to openparenthsis + i which is the the fisrt"(" add the distance i. as you can see from my previous solution, the code is going to be more than 10 lines.

For reviewed one:

No, I dont think i could fix tge bug in a small code, what i should do is that i have to seperate the if statement about openparenthesis to closeparenthesis in my review code to specif place which is the place below of each parenthsis or brackets when assigning the value to them. so that their code will return the links. and the next step is the same thing what i have done above in my implement part. i will abstract the strings that from openparenthsis to closeparenthsis and write a helper method out of the markdownParse class that called findlast, it will take an string and make it to an array, then i will use a for loop, it takes an interger i that the value set to be length of the array and then i--, it should be greater than 0. in the for loop there is a if statement that if at the index i the character is equal to ")", the function will return the value of i, and the next step is that go back to markdownparse class and change the value of the integer closeparen to openparenthsis + i which is the the fisrt"(" add the distance i. as you can see from my previous solution, the code is going to be more than 10 lines.

# Snippet3

**Part1**

what it should produce by using  the CommonMark demo site preview:

![Snippet3](https://user-images.githubusercontent.com/97008935/169734947-d63f96ce-e451-4732-8240-42e5a3b9412d.png)


**Part2**

Showing the code in MarkdownParseTest.java for how you turned it into a test

![Picture to show test](https://user-images.githubusercontent.com/97008935/169734303-eeef9530-dcd3-4a1f-98e1-f7d1a9e35049.png)

**Part3**

For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![Snippet3Junit](https://user-images.githubusercontent.com/97008935/169735086-3862c9d8-8bd8-46a8-9356-b70d3fbc70f3.png)


**Part4**
For the implementation you reviewed in Week 7, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.

![ReviewJunit3](https://user-images.githubusercontent.com/97008935/169735166-4393e968-8c6a-4766-a82d-e371c816c0a7.png)


**Part5**

Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change

For my implementation:

yes, i think i could solve this solution within 10 lines, what im going to do is that i will use contain method to check the substring from openparenthsis to closeparenthsis that if there have a "/n" or not, if it is there, i will make the while loop skip this link and try to find the next link, it could be solved in 10 lines.

For reviewed one:

No, I dont think i could solve this problem in 10 lines, because i have 
to seperate the if statement about openparenthesis to closeparenthesis in my review code to specif place which is the place below of each parenthsis or brackets when assigning the value to them. so that their code will return the links. and the next step is the same thing what i have done above in my implement part. i will use contain method to check the substring from openparenthsis to closeparenthsis that if there have a "/n" or not, if it is there, i will make the while loop skip this link and try to find the next link, because i have to separate some statments in my review code so i dont think i could finish it in 10 lines. 
