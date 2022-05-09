LAB REPORT 3




**part1**:
**Streamlining ssh Configuration**


1.1

this is my .ssh/config file and what i changed is i chnage user to my own user which is cs15lsp22akg

![image](https://user-images.githubusercontent.com/97008935/167276588-1c13da4f-48f6-4bd7-b9c8-b60fb7d0945b.png)

1.2

i choose Run to replace ieng6 as alias

![image](https://user-images.githubusercontent.com/97008935/167276736-d10ba536-7a6b-4507-8138-b702df63aade.png)

1.3

i use scp to cope the file WhereAmI.java and sent it to Run which is my cs15lsp22akg@ieng6.ucsd.edu account.

![image](https://user-images.githubusercontent.com/97008935/167279204-850dad56-747b-4adf-b584-2f798d0699bf.png)

**part2**
**Setup Github Access from ieng6**

2.1 

this is the place i store my public key in my useraccount

![image](https://user-images.githubusercontent.com/97008935/167329268-fdff3c06-c713-4f42-b47a-0e7844c87a0c.png)

this is where my public key i made and stored on Github

![image](https://user-images.githubusercontent.com/97008935/167329339-cc42ca9b-6ec7-483b-a11b-95da0cc8920e.png)

2.2

thet are the private key you made is stored on your user account. Im using mac it in the user folder and store in the rundongguo.


![image](https://user-images.githubusercontent.com/97008935/167329445-e8c6c346-5520-4d90-899f-d37626d26f18.png)


2.3
what i did is that i clone a repository from github and it is named markdown-parser and i add one line in to one of the file in the markdown-parser whcih is MarkdownParseTest.java and i use git add this file name and use git commit it. in the end what i did is that git push origin main so that i could push the changes to github.

![image](https://user-images.githubusercontent.com/97008935/167337214-42b64f67-be16-49f5-85fb-d19c417dc6a5.png)

2.4

this is the link that showed my file was changed , commit and push to github sucessfully.

[link](https://github.com/A17138501/markdown-parser/commit/99838aa98fb3c360e92767415682f856027d74e5)

**part3** Copy whole directories with scp -r

3.1 

i have copied all the files to ssh. and I use ls so that you could see markdown-parse file is there and all the files is in the markdown-parse folder.

![image](https://user-images.githubusercontent.com/97008935/167281654-3a9987b7-16c8-4228-8c34-582a30a3bc36.png)


3.2 

I login ssh by using ssh Run and cd to markdown-parse, because the file i wnat to run is in there. after i go the the current directories,. I use command line to comeile and run. and As uou can see all the test passed

![image](https://user-images.githubusercontent.com/97008935/167281896-962b9362-8721-43a1-ad3d-aefd235c5435.png)



3.3

i combine all the command line together. the first part is that i cope the directories to my ssh account and i login ssh server after that i cd to the directory that i want to. the last two part are compile and run the java file.


![image](https://user-images.githubusercontent.com/97008935/167327780-e8101841-d4d2-4e86-b9d3-96efd80b4384.png)

