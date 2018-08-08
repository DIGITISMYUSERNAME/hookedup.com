# hookedup.com
a above average site that hookes up up with anything in the world no exceptions 
Skip to content


  
Pull requests 
Issues 
Marketplace 
Explore 
 


Sign out 


 Watch 
653 
 Star 
5,694 
 Fork 
2,333 

desktop/desktop 
 Code 
 Issues 388 
 Pull requests 25 
 Projects 7 
 Insights 
Browse files
this is the syntax for using the default values. ew. 
 master (#5272) 
 
shiftkey committed 6 days ago 
1 parent 1fb5453 commit ea957f973db07c098965b3ed015f521ad9c39757 
Unified 
Split 

Showing 1 changed file with 2 additions and 0 deletions. 
View  
2 .circleci/config.yml 
 
@@ -7,6 +7,7 @@ defaults: &defaults


 
 


 
jobs: 


 
  build: 


 
    <<: *defaults 


 
    parallelism: 1 


 
    shell: /bin/bash --login 


 
    environment: 
 
@@ -62,6 +63,7 @@ jobs:


 
        paths: . 


 
 


 
  deploy: 


 
    <<: *defaults 


 
    steps: 


 
      - attach_workspace: 


 
          at: ~/desktop/desktop 
 

        


0 comments on commit ea957f9 


 
 
 
 
 
 
 
 
 
 
 
 
Write Preview 
 
Attach files by dragging & dropping or selecting them. 

 Styling with Markdown is supported 
Comment on this commit
  Subscribe You’re not receiving notifications from this thread. 
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
 
Contact GitHub
API
Training
Shop
Blog
About

Press h to open a hovercard with more details. 
