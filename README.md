## Getting Started with Git

#### Sign Up for Github

https://github.com/

#### Setup SSH with Github

- Open terminal
- Do command: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
- Press enter through enter pass phrase prompts
- Do command: `pbcopy < ~/.ssh/id_rsa.pub`
  - Copies SSH key onto clipboard, CMD + V (mac) or CTRL + V (windows) to paste
- Hook up SSH key with github

  - Go to profile > settings https://github.com/settings/profile
  - Go to SSH and GPG Keys
  - Click new SSH Key
  - Enter a name for title (usually your computer model. example: Dko's Macbook Pro 13 2019)
  - Paste Key
  - Click Add SSH Key

#### References:

- https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

You can now clone/push/pull/etc repositories from github without signing in every time!
