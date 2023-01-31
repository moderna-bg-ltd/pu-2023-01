## Tools

### Git
- Install https://git-scm.com/downloads

### Local Dev server
- Windows - Wamp64 (64bit): https://www.wampserver.com/en/download-wampserver-64bits/
- MacOS - Mamp64.
- Linux - integrated.

### Personal SSH key
- Resource: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- Generate SSH key: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
- Start SSH agent: eval `"$(ssh-agent -s)"`
- Add your personal SSH key: `ssh-add ~/.ssh/id_your_personal_ssh`
