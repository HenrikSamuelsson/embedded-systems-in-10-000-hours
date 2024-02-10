# Linux Commands

This note holds information on Linux commands. Knowing Linux commands is useful when working with embedded systems that are based on Linux, and of course if using a computer with Linux for embedded system development.

## sed

`sed` is a stream editor [(sed, n.d.)](references.md#sed-no-date).

Stream editors are used to transform text, with the input source being a stream coming from a file or a pipeline.

`sed` have many different functions and options, only a small text replacement example is discussed here. See the [manual](https://www.gnu.org/software/sed/manual/sed.html) page for more information on `sed` capabilities and usage.

A common task is the need to replace all occurrences of a certain word in a text file with another word. This is the type of task that `sed` can be used for.

Assume that all occurrences of the word "one" is to be replaced with the word "two" in a text file called "one.txt" and the result is to be placed in a file "two.txt".

The manual presents the command `s` that stands for substitute, which can do the work as per below:

```txt
$ cat one.txt
one two three
telephone
sgr@DESKTOP-I83INQ5:~$ sed s/one/two/ one.txt > two.txt
sgr@DESKTOP-I83INQ5:~$ cat two.txt
two two three
telephtwo
```

Explanation:

1. `cat one.txt` shows us the content of one.txt
2. `sed` is run with `s` to substitute occurrences of `one` with `two` and streams the result to a file called two.txt
3. `cat two.txt` shows us the content of two.txt, note how the two occurrences of the word one have ben replaced
