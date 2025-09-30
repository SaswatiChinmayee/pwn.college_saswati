
# IntrotoArguments
Let's try something more complicated: a command with arguments, which is what we call additional data passed to the command. When you type a line of text and hit enter, the shell actually parses your input into a command and its arguments. The first word is the command, and the subsequent words are arguments. Observe:

hacker@dojo:~$ echo Hello
Hello
hacker@dojo:~$

In this case, the command was echo, and the argument was Hello. echo is a simple command that "echoes" all of its arguments back out onto the terminal, like you see in the session above.

Let's look at echo with multiple arguments:

hacker@dojo:~$ echo Hello Hackers!
Hello Hackers!
hacker@dojo:~$

In this case, the command was echo, and Hello and Hackers! were the two arguments to echo. Simple!

In this challenge, to get the flag, you must run the hello command (NOT the echo command) with a single argument of hackers. Try it now!



## Solution:

We were supposed to not use the echo command to run "hello". Instead we had to provide hackers as an argument. Through this i received my flag.

- 
- 
- 

Use this blob for pasting commands you've run
```hacker@hello~intro-to-arguments:~$ hello
It looks like you've invoked this command without an argument. Please invoke 
this with a single argument of 'hackers'!
hacker@hello~intro-to-arguments:~$ hello hackers
Success! Here is your flag:
pwn.college{Mhmoh4PTxNCGUnrEAnpaRa5AyZQ.QX4YjM1wSOxQzNzEzW}
hacker@hello~intro-to-arguments:~$ 

```

## Flag: 

```
pwn.college{Mhmoh4PTxNCGUnrEAnpaRa5AyZQ.QX4YjM1wSOxQzNzEzW}
```


### References:

- [link 1](https://pwn.college)
### Notes:

I learnt how to run arguments on terminal.

