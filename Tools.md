## Tools

### Git
- Install https://git-scm.com/downloads
- Windows - Git Bash (console).
- Windows console commands: https://www.thomas-krenn.com/en/wiki/Cmd_commands_under_Windows

#### Git commands
- `git clone <repository_address> .` (current folder)
- `git clone <repository_address> <folder_name>` (clone repo into folder)
- Learn Git: https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud

#### Git Servers
- Local Git usage.
- Github
- Gitlab
- Bitbucket
- Other Git servers.

### Local Dev server
- Windows - Wamp64 (64bit): https://www.wampserver.com/en/download-wampserver-64bits/
- MacOS - Mamp64.
- Linux - integrated.
- Docker - Linux Containers: https://www.docker.com/

### Personal SSH key
- SSH protocol (file transfers): https://www.ssh.com/academy/ssh/protocol
- SSH commands: https://www.hostinger.com/tutorials/ssh/basic-ssh-commands
- Resource: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- Generate SSH key: `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`.
- Start SSH agent: `eval "$(ssh-agent -s)"`
- Add your personal SSH key: `ssh-add ~/.ssh/id_your_private_ssh_key`

### PHP Development IDE
- PhpStorm (trial, paid): https://www.jetbrains.com/phpstorm/
- Notepad++, other text editors.
- Comodo, Netbeans, Eclipse, Visual Studio Code (VS Code), etc.

### PHP
- https://www.php.net/
- Learning resources: https://www.w3schools.com/php/
- PHP tutorial list: https://kinsta.com/blog/php-tutorials/

### Create your personal website
- PHP - .php filenames - https://www.w3schools.com/php/
- HTML, CSS, Javascript - https://www.w3schools.com/w3css/default.asp
- Designs - https://www.w3schools.com/w3css/w3css_templates.asp
- Free hosting (web server) for your personal web site: https://www.000webhost.com/free-php-hosting
- Repository (+ live example): https://github.com/moderna-bg-ltd/personal-website

### Composer (PHP Libraries)
- Install (windows, macos, linux): https://getcomposer.org/download/
- Usage: https://getcomposer.org/
- PHP packages: https://packagist.org/

### Symfony PHP Framework
- Source: https://symfony.com/
- Composer, Symfony CLI, Symfony console.
- Documentation: https://symfony.com/doc/current/index.html
- Symfony Video Tutorials: https://symfonycasts.com/
- Twig templating system: https://twig.symfony.com/

### Database and other related servers
- In house supported by PHP databases: https://www.php.net/manual/en/refs.database.php
- MySQL: https://www.mysql.com/
- MariaDB: https://mariadb.org/
- PostgreSQL: https://www.postgresql.org/
- Apache Solr: https://solr.apache.org/
- Cache servers: https://dev.to/he110/boosting-up-php-project-with-cache-16hi
- Redis: https://redis.io/
- MS SQL: https://www.microsoft.com/en-us/sql-server/sql-server-downloads
- MongoDB: https://www.mongodb.com/

### Docker 
- https://www.docker.com/
- Install Docker Desktop: https://docs.docker.com/engine/install/

#### Ready for use PHP docker images:
- Docker LAMP (Linux, Apache, MySQL and PHP) stack: https://hub.docker.com/r/mattrayner/lamp
- Docker LEMP (Linux, Nginx, MariaDB, PHP) stack: https://linuxiac.com/how-to-set-up-lemp-stack-with-docker-compose/
- Docksal: https://docksal.io/
- DDEV: https://ddev.readthedocs.io/en/stable/
- Lando: https://lando.dev/
- Docker4PHP, Docker4Drupal: https://github.com/wodby/

### Local Drupal 9 on Docksal (Docker Desktop)
- Install Docker Desktop & Docksal - https://docksal.io/installation#windows-docker-desktop
- Get (clone) the Docksal Ddrupal 9 repo - https://github.com/docksal/boilerplate-drupal9-composer
- Run the Web Application smoothly.
