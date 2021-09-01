# SpringBoot_Authentication
A Springboot web app to authenticate user using a postgresql database hosted in Apache web server in okeanos.gr cloud


for starters we check if the firewall works on our centOS7 machine 

We added 2 rules so http and https will be accessible from everywhere(e.g a browser)
     1.firewall-cmd --permanent --zone=public --add-service=http
     2.firewall-cmd --permanent --zone=public --add-service=https
and we reload so it will save the configurations
     firewall-cmd --reload
 
we inserted the command yum -y install httpd in case there wasnt in our machine

and we enabled the httpd with the command
    sudo systemtc1 start httpd 
  
 
 
