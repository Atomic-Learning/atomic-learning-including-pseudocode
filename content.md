When introducing language-agnostic programming concepts, computational algorithms, pseudocode can be a useful tool to illustrate the key ideas without getting bogged down in the specific syntax of a particular programming language, or making the page inaccessible to users who are not familiar with a particular programming language. When pseudocode is used, the goal should be to clearly demonstrate the common syntactic structures, avoiding specific nuances of any particular programming language.

For example, the pseudocode block below demonstrates a simple algorithm to calculate the sum of the first 10 natural numbers:

```
START
    SET sum TO 0
    FOR i FROM 1 TO 10 DO
        sum = sum + i
    END FOR
    PRINT sum
END
```
    


To include pseudocode on a page, use the single-backtick notation for inline code, and the triple-backtick notation for code blocks, as you would for any other code. However, exclude the name of the programming language (as pseudocode is specifically not a real programming language). For example, the pseudocode block above was created using the following code:

```html
 ```
 START
     SET sum TO 0
     FOR i FROM 1 TO 10 DO
         sum = sum + i
     END FOR
     PRINT sum
 END
 ```
```

You can also view the raw `content.md` file for this page [here](https://github.com/Atomic-Learning/atomic-learning-including-pseudocode/blob/main/content.md)

# The Pseudocode Tag

Pages containing pseudocode should use the `pseudocode` tag in their metadata files. This automatically adds a warning to the top of the page, such as the one at the top of this page, which highlights to users that the code in the page is not "real" code.

# Syntax Highlighting

Unlike most other code in Atomic Learning pages, you should not specify a class that specifies the language for syntax highlighting when providing pseudocode. This is because pseudocode does not have a set structure and so cannot be reliably and consistently highlighted.
