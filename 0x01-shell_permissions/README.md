<h1>0x01. Shell, permissions</h1>
<div class="panel-body">
  <h2>Resources</h2>

  <p><strong>Read or watch</strong>:</p>

  <ul>
    <li>
      <a
        href="/rltoken/aQmRB6ms-SDHUhqY0Rsa3g"
        title="Permissions"
        target="_blank"
        >Permissions</a
      >
    </li>
  </ul>

  <p><strong>man or help</strong>:</p>

  <ul>
    <li><code>chmod</code></li>
    <li><code>sudo</code></li>
    <li><code>su</code></li>
    <li><code>chown</code></li>
    <li><code>chgrp</code></li>
    <li><code>id</code></li>
    <li><code>groups</code></li>
    <li><code>whoami</code></li>
    <li><code>adduser</code></li>
    <li><code>useradd</code></li>
    <li><code>addgroup</code></li>
  </ul>

  <h2>Learning Objectives</h2>

  <p>
    At the end of this project, you are expected to be able to
    <a
      href="/rltoken/ku9cNLQc4XzHnVXH6YFE7A"
      title="explain to anyone"
      target="_blank"
      >explain to anyone</a
    >, <strong>without the help of Google</strong>:
  </p>

  <h3>Permissions</h3>

  <ul>
    <li>
      What do the commands <code>chmod</code>, <code>sudo</code>,
      <code>su</code>, <code>chown</code>, <code>chgrp</code> do
    </li>
    <li>Linux file permissions</li>
    <li>
      How to represent each of the three sets of permissions (owner, group, and
      other) as a single digit
    </li>
    <li>How to change permissions, owner and group of a file</li>
    <li>Why can’t a normal user <code>chown</code> a file</li>
    <li>How to run a command with root privileges</li>
    <li>How to change user ID or become superuser<br /></li>
  </ul>

  <h3>Other Man Pages</h3>

  <ul>
    <li>How to create a user</li>
    <li>How to create a group</li>
    <li>How to print real and effective user and group IDs</li>
    <li>How to print the groups a user is in</li>
    <li>How to print the effective userid</li>
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
  </ul>
</div>

## Tasks

0. [My name is Betty](./0-iam_betty) : A script that switches the current user to the user betty.
1. [Who am I](./1-who_am_i) : A script that prints the effective username of the current user.
2. [Groups](./2-groups) : A script that prints all the groups the current user is part of.
3. [New owner](./3-new_owner) : A script that changes the owner of the file `hello` to the user `betty`.
4. [Empty!](./4-empty) : A script that creates an empty file called `hello`.
5. [Execute](./5-execute) : A script that adds execute permission to the owner of the file `hello`.
6. [Multiple permissions](./6-multiple_permissions) : A script that adds execute permission to the owner and the group owner, and read permission to the other users, to the file `hello`.
7. [Everybody!](./7-everybody) : A script that adds execution permissions to the owner, the group owner and the other users, to the file `hello`.
8. [James Bond](./8-James_Bond) : A script that gives the gives the rest of the users permission and removes all permission for the owner and the group owner.
9. [John Doe](./9-John_Doe) : A script that sets the mode of the file `hello`; where owner has all the permissions set, group owner has execute permissions set and others have only write and read permissions set.
10. [Look in the mirror](./10-mirror_permissions) : A script that sets the mode of the file `hello` the same as `olleh`'s mode.
11. [Directories](./11-directories_permissions) : A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. (**NB:** *Regular files should not be changed.*)
12. [More directories](./12-directory_permissions) : A script that creates a directory called `my_dir` with permissions **751** in the working directory.
13. [Change group](./13-change_group) : A script that changes the group owner to `school` for the file `hello`.
14. [Owner and group](./100-change_owner_and_group) : A script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.
15. [Symbolic links](./101-symbolic_link_permissions) : A script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.
16. [If only](./102-if_only) : A script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.
17. [Star Wars](./103-Star_Wars) : A script that will play the StarWars IV episode in the terminal.
