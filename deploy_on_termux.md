<h2 align="center">  👨‍🔧 DEPLOY ON TERMUX </h2>
<br><br>
  
  ~ Deploy [Commands](#commands) ~ <br>
  ~ [About](#about) Commands ~

<a name = "commands">


```
apt update

apt install git nodejs -y

git clone https://github.com/DarkMakerofc/OpenAi-ChatGPT-Bot.git

cd OpenAi-ChatGPT-Bot

npm install

npm start 
```

</a>

 <br/> 

1. `apt update`: This command updates the package lists of the APT package manager on your system. It ensures that you have the latest information about available packages and their versions.

2. `apt install git nodejs -y`: This command installs the `git` version control system and `nodejs` JavaScript runtime on your system. The `-y` flag automatically confirms any prompts during installation, so you don't need to manually confirm.

3. `git clone https://github.com/DarkMakerofc/OpenAi-ChatGPT-Bot.git`: This command clones (downloads) a GitHub repository from the specified URL. In this case, it's cloning the "OpenAi-ChatGPT-Bot" repository hosted on GitHub.

4. `cd OpenAi-ChatGPT-Bot`: This command changes your current working directory to the "OpenAi-ChatGPT-Bot" directory. You use this directory to access the cloned repository's contents.

5. `npm install`: This command installs the Node.js project's dependencies. It reads the `package.json` file in the project directory and installs the required Node.js packages specified there.

6. `npm start`: This command starts the application defined in the `package.json` file under the `scripts` section. Typically, it's used to launch the main functionality of the application, in this case, the ChatGPT Bot.
<a name = "about">
By following these commands, you'll be updating your package lists, installing necessary software, cloning the repository, navigating to its directory, installing dependencies, and finally starting the ChatGPT Bot using Node.js.

</a>
