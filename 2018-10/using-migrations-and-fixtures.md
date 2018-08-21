Title: Using migrations and fixtures
Speaker: Miro Svrtan

Abstract:

Manually adding data to our development environment is tedious and boring, not being sure on what changes will be applied to production database after deployment can be dangerous. To battle this issues, developers decided to load gigabytes of production data on their machines or run queries manually before or after deployment. 

In the world of crazy fast changes, working with more and more team mates and on more complex projects, automation and reliabilty are becoming a must have. Fixtures will give you opportunity to have small yet relevant data set so you dont have to import production data or enter testing data into the system your self, every time system changes. By using migrations we can easily transfer database changes amongst the team and get the confidence on the changes that will be applied to staging/production. 

In my case, both concepts helped communicate changes better and allowed us to modify the system with more confidence and at a faster pace. 

While some popular frameworks and ORM's dont ship with fixtures or migrations support by default, there are great extensions to provide this. I will showcase ones for Symfony and Doctrine but talk is more about their concepts and not the implementations. 
