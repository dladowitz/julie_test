## Things that you need to do:

#### Clone or Create a new repo

#### Add variables
* Update Variables in the '_config.yml' file. 

#### Publishing as a github page
* Create a branch named 'gh-pages'
* Push the gh-pages branch
* This results in a live site at 'username.github.io/repo-name'


#### Connecting a custom domain
* On the DNS provider create a subdomain. Ex: 650anderson.captivaterealestate.com
* On that subdomain create a CNAME record pointing to usename.github.com. Ex: dladowitz.github.com (This routes to the github account)
* Create a file named 'CNAME' in the root of the github repo. 
* Add the referencing subdomin to the cname file. Here the subdomain is '650anderson.captivaterealestate.com'. (This allows github to properly route any incomming CNAMES to the proper repo)


* https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/
* https://help.github.com/articles/adding-a-cname-file-to-your-repository/