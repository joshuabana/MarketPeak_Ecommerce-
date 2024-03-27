firstly i created a directory called Market_Ecommerce 
then i downladed a web template from the link given 
i saved the web template file in the directory i created 
I initialzed the directory added it, then committed.
i added the git remote origin and then pushed it to my main branch
SETTING UP AWS INSTANCE 
We've been taught previously on how to crete an aws instance, so i created one 
and then ssh into the ec2 instance using mobaxterm 
we were asked to clone the repository on the linux server which the ec2 instance 
I followed the instructions on the platform and then i was able to create a key that that allowed me to ssh into github using the aws server 
after which i was able to clone the repository

NEXT STEP 
installed an apache server
we were asked to copy the web template file to the default httpd web directory
after which i reloaded httpd 

so then i copied the public ip address from the ec2 instance to my web broswer
CHALLENGED FACED 
i was expecting to see the front end of the web... but i didnt 
so after research i configure the inbound rules on the aws to allow hhtp on port 80 and https on port 443, cause at the time it only permits ssh
after then it didnt still display the web template 
after so much research and questions i figure i was was suppose to copy attach the name of the file with a forward to the ip address 
i did that and it worked 


UPDATING THE WEB SITE 
updating the site was a huge problem for me 
after some html research i was able to make some little changes on the site 
like the name, adress phone number and all
i made the changed on a different branch i created called Development branch 
i added commited my changed and then push to the github repository 
after which i created a pull request and merged (no conflicts)
i decided to ssh into the linux server (aws ec2 instance), which i did and i cloned the repository again like i did
i reloaded httpd. it didnt work
i tried every thing i could but it just didnt work
i committed the chhanges again and try to follow every thing step by step i was just missing something not from git but from the linux server 
I'm still on it hopefully when i get the final solution i'll comeback and add it to this readme file
So the major issue i had was updating the site hopefull i'll get it after this time 
