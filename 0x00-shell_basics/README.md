<h1>0x00. Shell, basics</h1>
<div>
  <p>
    <img
      src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/205/image.jpg"
      alt=""
      loading="lazy"
      style=""
    />
  </p>

  <h2>Resources</h2>

  <p><strong>Read or watch</strong>:</p>

  <ul>
    <li>
      <a
        href="/rltoken/vwO91sqNBgRL03BLu-ueiA"
        title='What Is "The Shell"?'
        target="_blank"
        >What Is “The Shell”?</a
      >
    </li>
    <li>
      <a
        href="/rltoken/iblidp7yp6i-QpT8rDXHaA"
        title="Navigation"
        target="_blank"
        >Navigation</a
      >
    </li>
    <li>
      <a
        href="/rltoken/xEKUCnQsMH0esQ6fJU5vLA"
        title="Looking Around"
        target="_blank"
        >Looking Around</a
      >
    </li>
    <li>
      <a
        href="/rltoken/HUhQ73fFR1GOC5nb4r-mDw"
        title="A Guided Tour"
        target="_blank"
        >A Guided Tour</a
      >
    </li>
    <li>
      <a
        href="/rltoken/olv-1tj4d1LA57Z0PrLNvw"
        title="Manipulating Files"
        target="_blank"
        >Manipulating Files</a
      >
    </li>
    <li>
      <a
        href="/rltoken/zUtux3Pm0BkvtwXzbTtkmA"
        title="Working With Commands"
        target="_blank"
        >Working With Commands</a
      >
    </li>
    <li>
      <a
        href="/rltoken/rddGdsqLf8_kRzp12RaD4A"
        title="Reading Man pages"
        target="_blank"
        >Reading Man pages</a
      >
    </li>
    <li>
      <a
        href="/rltoken/AGxMxuS5IeW8VmEvJyhwvw"
        title="Keyboard shortcuts for Bash"
        target="_blank"
        >Keyboard shortcuts for Bash</a
      >
    </li>
    <li><a href="https://wiki.ubuntu.com/LTS" target="_blank">LTS</a></li>
    <li>
      <a href="/rltoken/cE8ZA3kgEaFhB-IDNv31bQ" title="Shebang" target="_blank"
        >Shebang</a
      >
    </li>
  </ul>

  <p><strong>man or help</strong>:</p>

  <ul>
    <li><code>cd</code></li>
    <li><code>ls</code></li>
    <li><code>pwd</code></li>
    <li><code>less</code></li>
    <li><code>file</code></li>
    <li><code>ln</code></li>
    <li><code>cp</code></li>
    <li><code>mv</code></li>
    <li><code>rm</code></li>
    <li><code>mkdir</code></li>
    <li><code>type</code></li>
    <li><code>which</code></li>
    <li><code>help</code></li>
    <li><code>man</code></li>
  </ul>

  <h2>Learning Objectives</h2>

  <p>
    At the end of this project, you are expected to be able to
    <a
      href="/rltoken/02rKNnoj4VMlA7BHYppIQg"
      title="explain to anyone"
      target="_blank"
      >explain to anyone</a
    >, <strong>without the help of Google</strong>:
  </p>

  <h3>General</h3>

  <ul>
    <li>What does RTFM mean?</li>
    <li>What is a Shebang</li>
  </ul>

  <h3>What is the Shell</h3>

  <ul>
    <li>What is the shell</li>
    <li>What is the difference between a terminal and a shell</li>
    <li>What is the shell prompt</li>
    <li>How to use the history (the basics)</li>
  </ul>

  <h3>Navigation</h3>

  <ul>
    <li>
      What do the commands or built-ins <code>cd</code>, <code>pwd</code>,
      <code>ls</code> do
    </li>
    <li>How to navigate the filesystem</li>
    <li>What are the . and .. directories</li>
    <li>What is the working directory, how to print it and how to change it</li>
    <li>What is the root directory</li>
    <li>What is the home directory, and how to go there</li>
    <li>
      What is the difference between the root directory and the home directory
      of the user root
    </li>
    <li>What are the characteristics of hidden files and how to list them</li>
    <li>What does the command <code>cd -</code> do</li>
  </ul>

  <h3>Looking Around</h3>

  <ul>
    <li>
      What do the commands <code>ls</code>, <code>less</code>,
      <code>file</code> do
    </li>
    <li>How do you use options and arguments with commands</li>
    <li>Understand the ls long format and how to display it</li>
    <li>
      <a
        href="/rltoken/HUhQ73fFR1GOC5nb4r-mDw"
        title="A Guided Tour"
        target="_blank"
        >A Guided Tour</a
      >
    </li>
    <li>What does the <code>ln</code> command do</li>
    <li>What do you find in the most common/important directories</li>
    <li>What is a symbolic link</li>
    <li>What is a hard link</li>
    <li>What is the difference between a hard link and a symbolic link</li>
  </ul>

  <h3>Manipulating Files</h3>

  <ul>
    <li>
      What do the commands <code>cp</code>, <code>mv</code>, <code>rm</code>,
      <code>mkdir</code> do
    </li>
    <li>What are wildcards and how do they work</li>
    <li>How to use wildcards</li>
  </ul>

  <h3>Working with Commands</h3>

  <ul>
    <li>
      What do <code>type</code>, <code>which</code>, <code>help</code>,
      <code>man</code> commands do
    </li>
    <li>What are the different kinds of commands</li>
    <li>What is an alias</li>
    <li>When do you use the command help instead of man</li>
  </ul>

  <h3>Reading Man Pages</h3>

  <ul>
    <li>How to read a man page</li>
    <li>What are man page sections</li>
    <li>
      What are the section numbers for User commands, System calls and Library
      functions
    </li>
  </ul>

  <h3>Keyboard Shortcuts for Bash</h3>

  <ul>
    <li>Common shortcuts for Bash</li>
  </ul>

  <h3>LTS</h3>

  <ul>
    <li>What does <code>LTS</code> mean?</li>
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
      A <code>README.md</code> file at the root of the repo, containing a
      description of the repository
    </li>
    <li>
      A <code>README.md</code> file, at the root of the folder of
      <em>this</em> project, describing what each script is doing
    </li>
    <li>
      You are not allowed to use backticks, <code>&amp;&amp;</code>,
      <code>||</code> or <code>;</code>
    </li>
    <li>
      All your scripts must be executable. To make your file executable, use the
      <code>chmod</code> command: <code>chmod u+x file</code>. Later, we’ll
      learn more about how to utilize this command.
    </li>
  </ul>
  
  <h2>Tasks</h2>
</div>
  
  0. [Where am I?](./0-current_working_directory) : A script that prints the absolute path of the current working directory.
  1. [What's in there?](./1-listit) : A script that displays the contents of your current directory.
  2. [There is no place like home](./2-bring_me_home) : A script that changes the working directory to the user's home directory.
  3. [The long format](./3-listfiles) : A script that displays the current directory contents in a long format.
  4. [Hidden files](./4-listmorefiles) : A script that displays the current directory contents including hidden files.
  5. [I loce numbers](./5-listfilesdigitonly) : A script that displays the current directory contents, using long format, while displaying group IDs in numeral and show hidden files.
  6. [Welcome](./6-firstdirectory) : A script that will create a directory named `my_first_directory` in the `/tmp/` directory.
  7. [Betty in my first directory](./7-movethatfile) : A scipt that will move a file called `betty` from home to the new directory created above.
  8. [Bye bye Betty](./8-firstdelete) : A script that will delete file `betty` from the new location.
  9. [Bye bye My first directory](./9-firstdirdeletion) : A script that will delete the directory `my_first_directory` that is in the `/tmp/` directory path.
  10. [Back to the future](./10-back) Change working directory to the previous one.
  11. [Lists](./11-lists) List all files (*even ones with names beginning with a period character, which are normally hidden*) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
  12. [File type](./12-file_type) A script that prints the type of the named file `iamafile`. The `iamafile` will be in the `/tmp/` directory when we will run your script.
  13. [We are symbols, and inhabit symbols](./13-symbolic_link) Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.
  14. [Copy HTML files](./14-copy_html) Create a script that copies all `html` files from the current working directory to the parent working directory while only copying files that did not exist.
  15. [Let's move](./100-lets_move) A script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.
  16. [Clean Emacs](./101-clean_emacs) A script that deletes all files in the current directory that end with the character `~`.
  17. [Tree](./102-tree) A script that creates the directory `welcome/`, `welcome/to/` and `welcome/to/school`.
  18. [Life is a series of commas, not periods](./103-commas) A script that lists all the files and directories of the current directory separated by commas `,`.
  19. [File type: School](./school.mgc) Create a magic file `school.mgc` that can be used with the command `file` to detect `School` data files always contain the string `SCHOOL` at offset 0.
