# Lab Report 3

## Streamlining ssh Configuration

### using text editor to edit config file:
![image](https://user-images.githubusercontent.com/103202818/166837800-1ed6f561-af84-48e1-9bc8-ebb8dcb74e7d.png)
I used the text editor software on my macbook to edit the config file where I gave it the alias 'ieng6'.

### streamlined ssh login:
![image](https://user-images.githubusercontent.com/103202818/166835623-d7af7003-44e3-487e-a605-0d23a8d4e4a3.png)
As you can see it has streamlined my login process.

### copying a file using `scp` command with the alias I chose:
![image](https://user-images.githubusercontent.com/103202818/166846045-8d09913d-6736-47e6-8cf7-185853e2b3a1.png)
I have created a file called 'testfile' in the directory of my desktop and used the `scp testfile ieng6:~/` command to copy the file into the remote server. 

***

## Setup Github Access from ieng6

### The public key is stored under settings in my Github uder account: 
![image](https://user-images.githubusercontent.com/103202818/167040723-baed5706-864e-4c1f-a2e6-ffbd5db148f5.png)

### The private key is stored on my laptop under `.ssh` as "id_rsa.pub"
![image](https://user-images.githubusercontent.com/103202818/167040843-8a87b6f3-1be2-4d45-99f9-3faef5402614.png)

### I created a new .txt file `a.txt` and used `git` commands to commit and push a change to origin
![image](https://user-images.githubusercontent.com/103202818/167040938-f81ff4a3-52ca-45f6-9c3a-8bf51c02dec4.png)
![image](https://user-images.githubusercontent.com/103202818/167040945-3cfb6f1d-6f5a-4a2a-a4b1-d5dc3191d4bb.png)

the [link](https://github.com/jadechng/test) to the the resulting commit. There is now a new a.txt file.

***

## Copy whole directories with `scp -r`
Using the command `scp -r . cs15lsp22@ieng6.ucsd.edu:~/markdown-parse` we are able to copy whole directories into the ieng6 account.

### copying markdown-parser directory into my ieng6 account:
![image](https://user-images.githubusercontent.com/103202818/167029404-7c5efef3-24eb-49f4-9b3f-ec328347a5e9.png)


### loging into ieng6 and compiling and running tests in the remote server:
![image](https://user-images.githubusercontent.com/103202818/167029412-c7673d3c-6654-4fc4-abda-02e093dd6340.png)
![image](https://user-images.githubusercontent.com/103202818/167029416-bdf5deef-d23f-4553-b6cd-74308f2307d1.png)

