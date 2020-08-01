# mac-tips-tech
##### MAVEN #####
tar -xvf apache-maven-3.1.1-bin.tar.gz

$pwd
/Users/mkyong/apache-maven-3.1.1

vim ~/.bash_profile
/Users/sivajiapireddy/Softwares/apache-maven-3.6.3

/Users/sivajiapireddy/Softwares/apache-maven-3.6.3
export M2_HOME=/Users/sivajiapireddy/Softwares/apache-maven-3.6.3
export PATH=$PATH:$M2_HOME/bin

zsh: command not found: mvn

sivajiapireddy@Sivajis-MBP ~ % source ~/.bash_profile
sivajiapireddy@Sivajis-MBP ~ % mvn
No Java runtime present, requesting install.


/usr/share/maven/conf/
sivajiapireddy@Sivajis-MBP ~ % mvn -version
Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
Maven home: /Users/sivajiapireddy/Softwares/apache-maven-3.6.3
Java version: 1.8.0_261, vendor: Oracle Corporation, runtime: /Library/Java/JavaVirtualMachines/jdk1.8.0_261.jdk/Contents/Home/jre
Default locale: en_GB, platform encoding: UTF-8
OS name: "mac os x", version: "10.15.6", arch: "x86_64", family: "mac"
