# Spring Boot in Action Sample Code

This repository contains example code from Spring Boot in Action. In as much as is possible when writing compilable/verifiable code to be injected into a not-easily-verifiable work of prose, the code should be aligned with what was printed. There may be slight variations, however.

This code will be tagged with FIRST_PRINTING to indicate that the code aligns with the first printing of the first edition of the book. This allows for further evolution of the code after publication while still maintaining a reference back to the code as it aligns with the printed book.

Please feel free to offer suggestions in the form of pull requests if you see opportunity for improvement.

And I'd certainly appreciate it if you'd please purchase a copy of _Spring Boot in Action_ ([Amazon](http://www.amazon.com/Spring-Boot-Action-Craig-Walls/dp/1617292540) | [Manning](https://www.manning.com/books/spring-boot-in-action) | [Barnes & Noble](http://www.barnesandnoble.com/w/spring-boot-in-action-craig-walls/1121907935)).


## Prepare folder with source code of Spring Boot in Action
```shell
mkdir /home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action
cd /home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action
git clone https://github.com/trifonnt/book--spring-boot-in-action.git
```

## How to install Spring CLI
```shell
cd /home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action
wget http://repo.spring.io/release/org/springframework/boot/spring-boot-cli/1.5.4.RELEASE/spring-boot-cli-1.5.4.RELEASE-bin.tar.gz
tar -zxvf spring-boot-cli-1.5.4.RELEASE-bin.tar.gz

sudo su -
echo "PATH=$PATH:/home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action/spring-1.5.4.RELEASE/bin" >> /etc/environment
exit
source /etc/environment 
```

## How to enable shell completion
```shell
cd /home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action/spring-1.5.4.RELEASE
sudo ln -s /home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action/spring-1.5.4.RELEASE/shell-completion/bash/spring /etc/bash_completion.d/spring
sudo ln -s /home/vagrant/workspace-eclipse/04_book--Spring-Boot-in-Action/spring-1.5.4.RELEASE/shell-completion/zsh/_spring /usr/local/share/zsh/site-functions/_spring
```

## Use Spring STS IDE

Install Buildship plugin in order to work with projects built by Gradle
