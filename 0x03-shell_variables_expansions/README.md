<h1>0x03. Shell, init files, variables and expansions</h1>
<div>
  <h2>About Bash projects</h2>

  <p></p>
  <p>
    Unless stated, all your projects will be auto-corrected with Ubuntu 20.04
    LTS.
  </p>

  <p></p>
</div>
<div>
  <h2>Resources</h2>

  <p><strong>Read or watch</strong>:</p>

  <ul>
    <li>
      <a
        href="/rltoken/oXnzBjLBA9t9dr7WuftdmQ"
        title="Expansions"
        target="_blank"
        >Expansions</a
      >
    </li>
    <li>
      <a
        href="/rltoken/PLSUQnBcKKU5eEgRfRDlug"
        title="Shell Arithmetic"
        target="_blank"
        >Shell Arithmetic</a
      >
    </li>
    <li>
      <a
        href="/rltoken/SvdGNZJjKsPghzZEhaWu4Q"
        title="Variables"
        target="_blank"
        >Variables</a
      >
    </li>
    <li>
      <a
        href="/rltoken/tqud57kjsSYgDfeZDlwl3g"
        title="Shell initialization files"
        target="_blank"
        >Shell initialization files</a
      >
    </li>
    <li>
      <a
        href="/rltoken/zCemKQ8f1CxmODIs9dmcWg"
        title="The alias Command"
        target="_blank"
        >The alias Command</a
      >
    </li>
    <li>
      <a
        href="/rltoken/wYrZr3t3DeAE8PpYHYWGiw"
        title="Technical Writing"
        target="_blank"
        >Technical Writing</a
      >
    </li>
  </ul>

  <p><strong>man or help</strong>:</p>

  <ul>
    <li><code>printenv</code></li>
    <li><code>set</code></li>
    <li><code>unset</code></li>
    <li><code>export</code></li>
    <li><code>alias</code></li>
    <li><code>unalias</code></li>
    <li><code>.</code></li>
    <li><code>source</code></li>
    <li><code>printf</code></li>
  </ul>

  <h2>Learning Objectives</h2>

  <p>
    At the end of this project, you are expected to be able to
    <a
      href="/rltoken/d8LWxAXk9_gsvpPw3ICdwQ"
      title="explain to anyone"
      target="_blank"
      >explain to anyone</a
    >, <strong>without the help of Google</strong>:
  </p>

  <h3>General</h3>

  <ul>
    <li>What happens when you type <code>$ ls -l *.txt</code></li>
  </ul>

  <h3>Shell Initialization Files</h3>

  <ul>
    <li>
      What are the <code>/etc/profile</code> file and the
      <code>/etc/profile.d</code> directory
    </li>
    <li>What is the <code>~/.bashrc</code> file</li>
  </ul>

  <h3>Variables</h3>

  <ul>
    <li>What is the difference between a local and a global variable</li>
    <li>What is a reserved variable</li>
    <li>How to create, update and delete shell variables</li>
    <li>
      What are the roles of the following reserved variables: HOME, PATH, PS1
    </li>
    <li>What are special parameters</li>
    <li>What is the special parameter <code>$?</code>?</li>
  </ul>

  <h3>Expansions</h3>

  <ul>
    <li>What is expansion and how to use them</li>
    <li>
      What is the difference between single and double quotes and how to use
      them properly
    </li>
    <li>How to do command substitution with <code>$()</code> and backticks</li>
  </ul>

  <h3>Shell Arithmetic</h3>

  <ul>
    <li>How to perform arithmetic operations with the shell</li>
  </ul>

  <h3>The <code>alias</code> Command</h3>

  <ul>
    <li>How to create an alias</li>
    <li>How to list aliases</li>
    <li>How to temporarily disable an alias</li>
  </ul>

  <h3>Other <code>help</code> pages</h3>

  <ul>
    <li>How to execute commands from a file in the current shell</li>
  </ul>

  <h3>Copyright - Plagiarism</h3>

  <ul>
    <li>
      You are tasked to come up with solutions for the tasks below yourself to
      meet with the above learning objectives.
    </li>
    <li>
      You will not be able to meet the objectives of this or any following
      project by copying and pasting someone else’s work.
    </li>
    <li>You are not allowed to publish any content of this project.</li>
    <li>
      Any form of plagiarism is strictly forbidden and will result in removal
      from the program.
    </li>
  </ul>

  <h2>Requirements</h2>

  <h3>General</h3>

  <ul>
    <li>
      Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code>
    </li>
    <li>All your scripts will be tested on Ubuntu 20.04 LTS</li>
    <li>
      All your scripts should be exactly two lines long (<code
        >$ wc -l file</code
      >
      should print 2)
    </li>
    <li>
      All your files should end with a new line (<a
        href="http://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file/18789"
        >why?</a
      >)
    </li>
    <li>
      The first line of all your files should be exactly
      <code>#!/bin/bash</code>
    </li>
    <li>
      A <code>README.md</code> file, at the root of the folder of the project,
      describing what each script is doing
    </li>
    <li>
      You are not allowed to use <code>&amp;&amp;</code>, <code>||</code> or
      <code>;</code>
    </li>
    <li>
      You are not allowed to use <code>bc</code>, <code>sed</code> or
      <code>awk</code>
    </li>
    <li>All your files must be executable</li>
  </ul>

  <h2>More Info</h2>

  <p>
    Read your <code>/etc/profile</code>, <code>/etc/inputrc</code> and
    <code>~/.bashrc</code> files.
  </p>

  <p>Look at some files in the <code>/etc/profile.d</code> directory.</p>

  <p>
    Note: You do not have to learn about <code>awk</code>, <code>tar</code>,
    <code>bzip2</code>, <code>date</code>, <code>scp</code>,
    <code>ulimit</code>, <code>umask</code>, or shell scripting, yet.
  </p>
</div>

## Tasks

0. [\<o>](./0-alias) : A script that creates an alias.
   - Name of alias: `ls`
   - Value: `rm *` 
1. [Hello you](./1-hello_you) : A script that prints `hello user`, where user is the current Linux user.
2. [The path to success is to take massive, determined action](./2-path) : A script that adds `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.
3. [If the path be beautiful, let us not ask where it leads](./3-paths) : A script that counts the number of directories in the `PATH`.
4. [Global variables](./4-global_variables) : A script that prints all the enviroment variables.
5. [Local variables ](./5-local_variables) : A script that lists all local variables and enviroment variables, and functions.
   - Name of variable : `HOLBERTON`
   - Value : `Betty`
6. [Local variable](./6-create_local_variable) : A script that creates a new local variable.
7. [Global variable](./7-create_global_variable) : A script that creates a new global variable.
   - Name of variable : `BEST`
   - Value : `School`
8. [Every addition to true knowledge is an addition to human power](./8-true_knowledge) : A script that prints the results of the addition of 128 with the value stored in the enviroment variable `TRUEKNOWLEDGE`, followed by a new line.
   - Remember to export variable TRUEKNOWLEDGE : `export TRUEKNOWLEDGE=1209`
   - Run command this way: `./8-true_knowledge | cat -e`
9. [Divide and rule](./9-divide_and_rule) : A script that prints the result of `POWER` divide by `DIVIDE`, followed by a new line.
   - `POWER` and `DIVIDE` are environment variables.
   - Variables values;
    - export POWER=42784
    - export DIVIDE=32
   - Run command this way: `./9-divide_and_rule | cat -e`
10. [Love is anterior to life, posterior to death, initial of creation, and the exponent of breath](./10-love_exponent_breath) : A script that displays the result of `BREATH` to the power of `LOVE`.
    - `BREATH` and `LOVE` are enviroment variables.
    - The script should display the result, followed by a new line.
11. [There are 10 types of people in the world -- Those who understand binary, and those who don't](./11-binary_to_decimal) : A script that converts a number from base 2 to base 10.
    - The number in base 2 is stored in the enviroment variable `BINARY`.
    - The script should display the number in base 10, followed by a new line.
12. [Combination](./12-combinations) : A script that prints all possible combinations of two letters, except `oo`.
    - Letters are lower cases, from `a` to `z`.
    - One combination per line.
    - The output should be alpha ordered, starting with `aa`.
    - Do not print `oo`.
    - Your script file should contain maximum 64 characters.
13. [Floats](./13-print_float) : A script that prints a number with two decimal places, followed by a new line.
    - The number will be stored in the enviroment variable `NUM`.
14. [Decimal to Hexadecimal](./100-decimal_to_hexadecimal) : A script that converts a number from base 10 to base 16.
    - The number is base 10 is stored in the enviroment variable `DECIMAL`.
    - The script should display the number in base 16, followed by a new line.
15. [Everyone is a proponent of strong encryption](./101-rot13) : A script that encodes and decodes text using the rot13 encryption. Assume ASCII.
16. [The eggs of the brood need to be an odd number](./102-odd) : A script that prints every other line from the input, starting with the first line.
17. [I'm an instant star. Just add water and stir.](./103-water_and_stir) : A script that adds the two numbers stored in the enviroment variables `WATER` and `STIR` and prints the results.
    - `WATER` is in base `water`.
    - `STIR` is in base `stir`.
    - The result should be in base `bestchol`.
