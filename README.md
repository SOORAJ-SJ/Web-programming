# Web-programming
 
 Steps to Prepare html file:
 --------------------------
 1.The HTML document itself begins with <html> and ends with </html>
 2.The visible part of HTML document is between <body> and </body>
 3.HTML heading tags are defined with the <h1> to <h6> tags.
 4.HTML paragraphs are defined with the <p> tag.
 5.HTML Links are defined with the <a> tag.And link's destination is specified in the href attribute.And In this html file TKM College link is given.
 6.HTML images are defined with the <img>tag.The sourcefile(src),alternative text(alt),width,height are provided as attribiutes.In the htmlfile gallery is set by this <img> tag.
 7.The <table> tag defines the HTML table.An HTML table consists of one <table> element and one or more <tr><th> and <td>
   <tr> element defines the table row.The <th> element defines a table header,and the <td> element defines the table cell.
 8.The <div> tag defines a division or a section in HTML document.Which is then styled with CSS.
 9.With CSS,control the color and backgroundcolors,font,the size of text,the spacing between elements,how elements are positioned and laid out.
   In this webpage external CSS is used.To use external stylesheet,add a link to it in <head> section of each HTML page.
   In CSS class selector is a name preceded by a fullstop(.) and id selector is a name preceded by a hash character(#).id can be used to identify one element,class can be used to identify more than one.
10.Navigation bar is also used in this webpage.Navigation bar is a list of link.

Steps to set up git
-----------------------

Git is the version control system(ie,a piece of software) that helps you tokeep track of your computer programs and files and the changes that aremade to them over time.
Step1:  From your shell, install Git using apt-get
         $ sudo apt -get update
         $ sudo apt-get install git
Step2: Verify installation was successful by typing
         $ git - -version
Step3: Create a GitHub account.
Step4: Enter your email address and a password ,and click Sign up for GitHub
Step5: Then create a new repository.
        A repository is like a place or a container where something is stored; in this case we are
        creating a Git repository to store code.
        
To create a new repository, select New Repository from the +sign dropdown menu.Enter a name for your repository(“eg ,”Demo”) and click Create Repository.
Step6: Create a file
Step7: Open the terminal program on your
Step8: Configure your Git username and email.
        $ git config - -global user. email you@example.com
        $ git config - -global user.name “Your name”
 Then,
$ git init
Step9: Connect your GitHub repo with your computer
       $ git remote add origin https://github.com/<your_username>/Demo.git
Step10: Pushing to Staging area
         $git add text.txt
Step11: You just create a Git commit and included a message that says first commit
       $ git commit -m “first commit”
Step 12: Push files to git hub repository
      $git push origin master
