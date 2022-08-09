# Starting Tutorial

----
--> docker run --name repo alpine/git clone https://github.com/docker/getting-started.git
--> docker cp repo:/git/getting-started/ .

--> cd getting-started
--> docker build -t docker101tutorial .    {name can anything after -t -- "." this is for current folder to take contents from }

## In Below port can be anything
   --> docker run -d -p 80:80 \ --name docker-tutorial docker101tutrial  
   { after --name  You can choose Your name for dockerfile  and then your given name of docker used above line } 
----
