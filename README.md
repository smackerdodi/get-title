# get-title
multi threaded python tool to get pages's title 
# Description 
some times you need to get the title of every subdomain or every page to search for specific pages and this tool will help you do this and it is multi threaded to be so fast . grepping page title is similar to subdomain screenshot we do grep title instead of open every page in browser 

# Installation :

1- git clone https://github.com/smackerdodi/get-title.git

2- cd get-title

3- pip3 install -r requirements.txt 

# Usage :

python3 get-title.py subs.txt

subs.txt : file contain subdomains or pages must start with http(s)://

note that pages you want to grep title must have http(s):// in the first of each line so i suggest to take the output of httprobe tool as input for this tool 
