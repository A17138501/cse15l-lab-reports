# Lab Report 5


## Part 1 
How you found the tests with different results (Did you use vimdiff on the results of running a bash for loop? Did you search through manually? Did you use some other programmatic idea?)

Yes, I use vim to find the tests with different results, I didn't search it through manually. 

## Part 2
Provide a link to the test-file with different-results (in the provided repository or your repository , either is fine)

[Link to the first testfile](https://github.com/nidhidhamnani/markdown-parser/edit/main/test-files/41.md)

[Link to the second testfile](https://github.com/nidhidhamnani/markdown-parser/edit/main/test-files/481.md)


**Test1** 

1. Describe which implementation is correct, or neither if both give the wrong output


My implementation is not correct, and the givne implementation is correct.

2. Indicate both actual outputs (provide screenshots) and also what the expected output is (list the links that are expected in the output).

![Picture]()

expect output:  []

actual output: [url &quot;tit&quot;]


3. For the implementation that’s not correct (or choose one if both are incorrect), describe the bug (the problem in the code) in about 2-3 sentences. You don’t have to provide a fix, but you should be specific about what is wrong with the program, and show the code that should be fixed (Provide a screenshot of code and highlight where the change needs to be made).

![picture need to be fixed]()

The reason why i have the worng output is that in my code i only have decide to find everything in from openparathsis"(" to  ")" and everything i have found in there is my output. It is not correct, how im going to fix it is that I would make everything from open parenthisis to close parenthisis an arraylist and use a if statement that if this arraylist contain a " ", i will make it skip the while loop for the current iteration.



**Test2**

1. Describe which implementation is correct, or neither if both give the wrong output

My implementatioin is corrcet, and the implementation in the given file is not correct

2. Indicate both actual outputs (provide screenshots) and also what the expected output is (list the links that are expected in the output).

![Picture]()

expect output:  [/uri "title"]

actual output: []



3. For the implementation that’s not correct (or choose one if both are incorrect), describe the bug (the problem in the code) in about 2-3 sentences. You don’t have to provide a fix, but you should be specific about what is wrong with the program, and show the code that should be fixed (Provide a screenshot of code and highlight where the change needs to be made).

The reason why it have no output is that there is a extra empty line after the link at line two. which the openparenthsis can not be found. so that the openparent count can not be increased. which will cause an infinite while loop.
![picture need to be fixed]()
we need to add a if statement in the while loop that if we have find the close parenthsis, we need to break this while loop.