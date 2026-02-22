To set up my local environment, I first had to access the EC2 dashboard on AWS. Then I launched an instance with the ubuntu OS, assigned it a key pair, and enabled ssh, http, and htpps traffic. 
After launching the instance, I assigned the instance an elastic IP address via the dashboard so that the site address would remain constant. 
I then used AWS to create a set of public and private keys, downloaded them to my computer, and moved them to the directory where I would store files related to the site. 
Then, using gitbash, I ssh'd into the instance using the associated username, password, and private key. From there, I used sudo to install apache, php, and mySQL. 
After accessing mySQL, I created a password for the root user, a new database, and a new user with all permissions on the new database. Then I exited mySQL. 
From there, I downloaded WordPress via the command line and moved it to the apache root. I was then able to finish the WordPress installation via the now up and running website. After completing the basics, WordPress gave me the code to create a config file.
After creating the config file, the site was free to access and all I had left to do was edit via wordpress. 
