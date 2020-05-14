## Getting Started with Git

#### Sign up for github

https://github.com/

#### Setup SSH

- open terminal
- do command: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
- press enter through enter pass phrase prompts
- do command: `pbcopy < ~/.ssh/id_rsa.pub`
  - copies SSH key onto clipboard, CMD + V (mac) or CTRL + V (windows) to paste
- hook up SSH key with github

  - Go to profile > settings https://github.com/settings/profile
  - Go to SSH and GPG Keys
  - Click new SSH Key
  - Enter a name for title (usually your computer model. example: Dko's Macbook Pro 13 2019)
  - Paste Key
  - Click Add SSH Key

- references:
  - https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

You can now clone/push/pull/etc repositories from github without signing in every time!
