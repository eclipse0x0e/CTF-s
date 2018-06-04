# Looking for password file

From the challange title , we see that we should find the _password_ file, but we dont know what password file it is...?   
Challange URL: http://challenges.ringzer0team.com:10075/?page=lorem.php                 
The above url contains a sample webpage , _But_ what is intresting is the url with page parameter.
throwing random value to the `page` parameter  gives errors..,thus this predicts a _directoy traversal_ vulnerability is present.
so we need to traverse the dir till we get `/etc/passwd` file.    
### Steps to capture the flag:
1. Just add `../../../../../etc/passwd` to the end of the url like this `http://challenges.ringzer0team.com:10075/?page=../../../../../etc/passwd`
