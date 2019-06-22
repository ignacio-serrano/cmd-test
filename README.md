A testing tool for CMD (.bat) scripts
=====================================

The idea is simple: resolving the most common problems that appear when you try
to write automatic tests for .bat scripts. This common problems include:
  * Comparing a .bat command output with the expected output.
  * Comparing the files/directories created by a .bat command with the expected
    files/directories.
  * Comparing environment variables with their expected values after running a
    command.
  * Doing all of the above without worrying about how much may I have messed the
    environment variables in my current CMD process.

TODO:
-----
  * Implement std I/O tests like those in split-path.
  * Replace all those things surrounded by ${}.

Project layout
--------------
  * `src`: Here it is where source code is.
    * `main`: Here it is where source code meant to be part of the application
              lives.
    * `test`: Here it is where the test scripts and other test related files 
              live (so they are not copied when it is installed).

---
Below, a markdown cheatsheet.

Heading
=======
Sub-heading
-----------
### Another deeper heading

---

Paragraphs are separated
by a blank line.

Two spaces at the end of a line leave a  
line break.

Text attributes _italic_, *italic*, __bold__, **bold**, `monospace`.

Bullet list:

  * apples
  * oranges
  * pears

Numbered list:

  1. apples
  2. oranges
  3. pears

A [link](http://example.com).

```javascript
function {
  //Javascript highlighted code block.
}
```

    {
    Code block without highlighting.
    }
