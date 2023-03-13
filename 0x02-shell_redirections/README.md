<h1>0x02. Shell, I/O Redirections and filters</h1>

<div>
  <h2>About <span class="text-primary">Bash</span> projects</h2>

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
        href="/rltoken/fGOQQXRKbvOcd1qLRxHzLQ"
        title="Shell, I/O Redirection"
        target="_blank"
        >Shell, I/O Redirection</a
      >
    </li>
    <li>
      <a
        href="/rltoken/c1pz13vke3HPH0S8iALbtw"
        title="Special Characters"
        target="_blank"
        >Special Characters</a
      >
    </li>
  </ul>

  <p><strong>man or help</strong>:</p>

  <ul>
    <li><code>echo</code></li>
    <li><code>cat</code></li>
    <li><code>head</code></li>
    <li><code>tail</code></li>
    <li><code>find</code></li>
    <li><code>wc</code></li>
    <li><code>sort</code></li>
    <li><code>uniq</code></li>
    <li><code>grep</code></li>
    <li><code>tr</code></li>
    <li><code>rev</code></li>
    <li><code>cut</code></li>
    <li>
      <code>passwd (5)</code> (<em>i.e. <code>man 5 passwd</code></em
      >)
    </li>
  </ul>

  <h2>Learning Objectives</h2>

  <p>
    At the end of this project, you are expected to be able to
    <a
      href="/rltoken/ayxcWT-Mmymhm03Z98LaWQ"
      title="explain to anyone"
      target="_blank"
      >explain to anyone</a
    >, <strong>without the help of Google</strong>:
  </p>

  <h3>Shell, I/O Redirection</h3>

  <ul>
    <li>
      What do the commands <code>head</code>, <code>tail</code>,
      <code>find</code>, <code>wc</code>, <code>sort</code>, <code>uniq</code>,
      <code>grep</code>, <code>tr</code> do
    </li>
    <li>How to redirect standard output to a file</li>
    <li>How to get standard input from a file instead of the keyboard</li>
    <li>
      How to send the output from one program to the input of another program
    </li>
    <li>How to combine commands and filters with redirections</li>
  </ul>

  <h3>Special Characters</h3>

  <ul>
    <li>What are special characters</li>
    <li>
      Understand what do the white spaces, single quotes, double quotes,
      backslash, comment, pipe, command separator, tilde and how and when to use
      them
    </li>
  </ul>

  <h3>Other Man Pages</h3>

  <ul>
    <li>How to display a line of text</li>
    <li>How to concatenate files and print on the standard output</li>
    <li>How to reverse a string</li>
    <li>How to remove sections from each line of files</li>
    <li>What is the <code>/etc/passwd</code> file and what is its format</li>
    <li>What is the <code>/etc/shadow</code> file and what is its format</li>
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
      You are not allowed to use backticks, <code>&amp;&amp;</code>,
      <code>||</code> or <code>;</code>
    </li>
    <li>All your files must be executable</li>
    <li>You are not allowed to use <code>sed</code> or <code>awk</code></li>
  </ul>

  <h2>More Info</h2>

  <p>Read your <code>/etc/passwd</code> and <code>/etc/shadow</code> files.</p>

  <p>
    Note: You do not have to learn about <code>fmt</code>, <code>pr</code>,
    <code>du</code>, <code>gzip</code>, <code>tar</code>, <code>lpr</code>,
    <code>sed</code> and <code>awk</code> yet.
  </p>
</div>

## Tasks

0. [Hello World](./0-hello_world) : A script that prints `Hello, World`, followed by a new line to the standard output.
1. [Confused smiley](./1-confused_smiley) : A script that displays a confused smiley: `"(Ôo)'`.
2. [Let's display a file](./2-hellofile) : A script that displays the content of the `/etc/passwd` file.
3. [What about 2?](./3-twofiles) : A scipt that displays content of `/etc/passwd` and `/etc/hosts`.
4. [Last lines of a file](./4-lastlines) : A script that displays the last 10 lines of `/etc/passwd`.
5. [I'd prefer the first ones actually](./5-firstlines) : A scipt that displays the first 10 lines of `etc/passwd`.
6. [Line #2](./6-third_line) : A script that displays the third line of the file `iacta`.
   - The file `iacta` will be in the working directory and you are not allowed to use `sed`.
7. [It is a good file that cuts iron without making a noise](./7-file) : A script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.
   - For this challenge, remember to use a single backslash `\` to escape special characters and double backslash `\\` to escape the backslash itself.
8. [Save current state of directory](./8-cwd_state) : A script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content`does not exist, create it.
9. [Duplicate last line](./9-duplicate_last_line) : A script that duplicates the last line of the file `iacta`.
10. [No more javascript](./10-no_more_js) : A script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.
11. [Don't just count your directories, make your directories count](./11-directories) : A script that counts the number of directories and sub-directories in the current directory.
    - The current and present directories should not be taken into account.
    - Hidden directories should be counted.
      - **Solution:** `mindepth 1` ; To exclude root directory
      - **Others:** `maxdepth 1` ; To avoid parsing sub directories. (*you may need this in future.*)
12. [Whats12's new](./12-newest_files) : A script that prints the 10 newest files in the current directory.
    - The output should be; one file per line and sorted from the newest to the oldest.
13. [Being unique is better than being perfect](./13-unique) : A script that takes a list of words as input and prints only words that appear exactly once.
    - Input and Output format is; `One word per line`.
    - Words should be sorted. (use this [list](./list) as your input to see if the challenge will work. 😊) `cat list | ./13-unique`
14. [It must be in that file](./14-findthatword) : A script that prints lines containing the pattern `"root"` from the file `/etc/passwd`.
15. [Count that word](./15-countthatword) : A script that displays the number of lines that contain the pattern `"bin"` in the file `/etc/passwd`.
16. [What's next?](./16-whatsnext) : A script that containing the pattern `"root"` and 3 lines after them in the file `/etc/passwd`.
    - `B` : This shows the lines before your pattern match.
    - `A` : This shows the lines after your pattern match.
17. [I hate bins](./17-hidethisword) : A script that displays all the lines in the file `/etc/passwd` that do not contain the pattern `"bin"`.
18. [Letters only please](./18-letteronly) : A script that displays all lines of the file `/ect/ssh/sshd_config` starting with a letter, including capital letters as well.
    - This also works : `grep ^[[:alpha:]] /etc/ssh/sshd_config`
19. [A to Z](./19-AZ) : A script that replaces all characters `A` and `C` from input to `Z` and `E` respectively.
20. [Without C, you would live in hiago](./20-hiago) : A script that removes all letters `c` and `C` from input.
21. [esreveR](./21-reverse) : A script that reverse its input.
22. [DJ Cut Killer](./22-users_and_homes) : A scipt that displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.
23. [Empty casks make the most noise](./100-empty_casks) : A script that finds all empty files and directories in the current directory and all sub-directories.
    - Only names of the files and directories should be displayed (not the entire path.)
    - Hidden files should be listed also, one file name per line and the listing should end with a new line.
    - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`.
24. [A gif is worth ten thousand words](./101-gifs) : A script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.
    - Hidden files should be listed.
    - Only regular files (not directories) should be listed.  
    - The names of the files should be displayed without their extensions. 
    - The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`) 
    - One file name per line. 
    - The listing should end with a new line. 
    - You are not allowed to use `basename`, `grep`, `egrep`, `fgrep` or `rgrep`. 
25. [Acrostic](./102-acrostic) : A script that decodes acrostics that use the first letter of each line.
    - What to decode: `An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval.` [Read more here](https://en.wikipedia.org/wiki/Acrostic)
    - The **‘decoded’** message has to end with a new line.
    - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`.
26. [The biggest fan](./103-the_biggest_fan) : A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
    - Download this file: `wget http://indeedeng.github.io/imhotep/files/nasa_19950801.tsv`
    - Run command this way: `./103-the_biggest_fan < nasa_19950801.tsv`.
    - Order by number of requests, most active host or IP at the top.
    - You are not allowed to use `grep`, `egrep`, `fgrep` or `rgrep`.
