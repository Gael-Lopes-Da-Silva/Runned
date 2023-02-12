<h3 align="center">Runned</h3>

---

<p align="center">:gear: Runned is a simple tool to check the execution time of terminal commands.</p>

---

### :question: How to use

~~~
USAGE: Runned.exe <your commands>

OPTIONS:
  -ec --exitcode    # Display the exit code of the executed command.
  -si --showinput   # Display the input given by the user.
~~~

### :question: How to build

To build, you will first need to download the nim compiler. You can find it [here](https://nim-lang.org/install.html).

Then, run the following command. You will need to change the os and cpu type to math your computer.

```shell
$ nimble install --define:release --opt:speed --app:console
```

If you want to download a build, check the <a href="./Build/">Build</a> folder. For now, there is only a windows build because it's hard to build for multiple platform without owning one of them.
