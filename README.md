# GreatFinds
Public version published at [GreatFinds.ml](https://greatfinds.ml) (possibly unstable due to deployment limitations).

USC CS201 Final Project

### Overview
GreatFinds is a platform that allows users to share and discover all kinds of media content (books, movies, TVs, etc.) in the form of a personalized feed.

### Features
* User Authentication
* Personalization: Tagging system (create and follow tags)
* Suggested Movies & TVs (thanks to [TMDb](https://tmdb.org))
* Real-time feed & status update (via WebSocket and AJAX requests)
* Search posts based on genre, keywords, or tags
* Like/Unlike posts
* Automatically generated user Bio (thanks to [twitterbiogenerator.com](https://www.twitterbiogenerator.com/))

### Tech Stack
* [Java EE](https://www.oracle.com/java/technologies/java-ee-glance.html)
* [JSF](https://www.oracle.com/java/technologies/javaserverfaces.html)
* [JPA](https://jakarta.ee/specifications/persistence/) ([Hibernate](https://hibernate.org) with [MySQL](https://www.mysql.com/))
* [Tomcat](http://tomcat.apache.org/)

### Other third-party libraries
* [Hibernate](https://hibernate.org) (JPA provider)
* [Primefaces](https://primefaces.org) (UI components)
* [Omnifaces](https://omnifaces.org) (JSF utilities)
* [DeltaSpike](https://deltaspike.apache.org) (CDI extensions such as [WindowScoped](https://deltaspike.apache.org/documentation/jsf.html#@WindowScoped))
* [TheMovieDB API](https://github.com/holgerbrandl/themoviedbapi) ([TMDb API](https://api.tmdb.org) wrapper)

### Screenshots
![image1](https://i.imgur.com/w24ElRA.png)
![image2](https://i.imgur.com/0xwfKUf.png)
![image3](https://i.imgur.com/LNHP9k6.png)
![image4](https://i.imgur.com/ufM3aJc.png)
![image5](https://i.imgur.com/2mU3DvM.png)
