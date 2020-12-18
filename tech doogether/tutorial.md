# How to Install or Setup and Initialize Git in any Project with Markdown Format. 

If the reader is not familiar with **_command line_**, reader can uses       [GitHub Desktop](https://desktop.github.com)  to create and manage a Git repository without using the command line.

- ## Installation and Setting up Git
<p> This `step` will be devided in to Two parts: </p>

1. How to install Git on Linux.
2. Initial Configuration After Installing Git.

    - ##### How to Install Git on Linux

    <p> The first thing reader need to opens the terminal for download the Git package by writing this code down below: </p>

    ````
        sudo apt install git
    ````
    <p> or, reader can uses another way as down below: </p> 

    ````
        sudo apt-get install git
    ````

    <p> After that, try checking the installed version with the command:</p>

    ```
        git --version
    ```
    <p> as reader can see, if there is a detail version in the terminal, it mean that Git has successfully installed on the computer. </p>

    ![git version](versions.png)

    - ##### Initial Configuration

        <p>
            There are several configurations that need to be prepared before starting using Git, such as name and email.
        </p>

        <p>
            Please do the configuration with the following command.
        </p>

        ````
            git config --global user.name "dandihusni"
            git config --global user.email dandythamrin@gmail.com
        ````

        <p>
            Then check the configuration with the command:
        </p>

        ````
            git config --list
        ````

        <p>
            If it looks like the following picture, it means the configuration is successful.
        </p>

        ![git config](config.png)

        <p> After reader has successfully install and config github, then the writer will go to the next step.</p>
    
- ## initialize git in any git project repository




