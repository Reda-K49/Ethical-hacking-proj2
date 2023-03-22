# Ethical-hacking-proj2
ethical hacking for project 2 scripting

I first had to understand where in the html files we will find sub domains and files etc.
Then in python I imported re for regular expressions and sys to read arguments given in the terminal.
I used regular expression to fetch the domain name from given argument.
What had taken me a very long time to understand is how to fetcch the html file f the given website in python! In bash it is very easy you just put curl command, but in python I dont know why it is very difficult and is why I took long. The best I could find is it translates the html to an object, but I need it as a string if i want to read through the page and detect the domain names and such after href or meta etc.
I want to put all href lines in a list to extract possible subdomains found in these lines.
But the full html is counting as a single element of the list, how useless.
Then I would loop through input files and see if any sub domain after https:// matches and this would be added to list of subdomains.
