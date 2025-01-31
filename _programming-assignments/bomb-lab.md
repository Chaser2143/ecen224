---
title: Bomb Lab
icon: fa-duotone fa-bomb
number: 1
layout: lab
---

### Getting Started

You must complete this lab on one of the Spice Lab Linux computers. The Spice Lab is located in **CB 425**. You can either go physically into the lab and use one of the Linux computers, or you can SSH into one. You can not SSH into them directly. You must first SSH into `ssh.et.byu.edu` with your CAEDM username and password. From there, you can SSH into the a Spice Lab computer, `spice-##.ee.byu.edu`, where ## can be a number 14 to 48. Again, use your CAEDM username and password to log into those machines. For example, run the following commands

```bash
ssh foo@ssh.et.byu.edu
# Once SSH'd into the CAEDM computer
ssh foo@spice-20.ee.byu.edu
```

Assuming your CAEDM username is foo and the Spice Lab computer you want to log into is 20. It doesn't matter which computer you log into. Your home directory is mounted to your J Drive so all folders will be synced between computers. From this SSH session, you will need to solve your bomb.


### Instructions

Click [here]({% link assets/bomblab.pdf %}) for a pdf file describing this lab. For the website to download a bomb and look at the score board, go to the `#programming-assignments` channel on Slack.

### Resources

- [GDB Quick Reference]({% link assets/GDB Quick Reference.pdf %})

- [x86-64 Reference Sheet](https://web.stanford.edu/class/cs107/resources/x86-64-reference.pdf)

- [Jump Instructions](https://stackoverflow.com/questions/9617877/assembly-jg-jnle-jl-jnge-after-cmp)

- [Article on reading assembly](https://www.timdbg.com/posts/fakers-guide-to-assembly/)

- [Compiler Explorer](https://godbolt.org). Compare C code with its corresponding assembly code.
