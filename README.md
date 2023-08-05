<h3 align="center">
    Runned
</h3>

---

<p align="center">
    :gear: Runned is a simple tool to check the execution time of terminal commands or applications launched in the terminal.
</p>

---

### :question: How to use
~~~
runned your_command
runned --version  or -v      # Print the version
runned --github   or -g      # Give the GitHub link
runned --exitcode or -e      # Display the exit code of the executed command or application
runned --input    or -i      # Display the input given by the user
~~~

### :question: How to build
To build the interpreter you will first need to download the Go compiler [here](https://go.dev/dl/).

If you want a precompiled executable, run this.
~~~console
go install github.com/gael-lopes-da-silva/runned
~~~

If you want to build the application from the source, run this.
~~~console
git clone https://github.com/Gael-Lopes-Da-Silva/Runned
cd Brainfuck
go build .
~~~
