#The SQL Pojo Memory Database   

* * *

Have you ever felt the need to mock a database in you Unit tests? Have you ever set up a memory db without cursing? Have you ever run into problems with maven and its repositories for resolving all the required dependencies?

The little jar here is a fake db implemented to be used most easily in unit tests that contain database accesses.

It's based only on plain Java and only needs joda-time, commons-lang3 and commons-collection to compile and run.

Only one short command to have a connection instance.

Supports a number of the most basic SQL operation you need (create, update, delete and select).

It is really fast in execution.

* * *

Have you ever felt the need to mock a database access in you Unit tests? Have you ever set up a memory db? Have you ever run into problems with maven and its repositories for resolving all the dependencies?

The little jar presented here is fake db implemented to be used most easily in unit tests that contain database accesses.

It's based only on plain Java and only needs joda-time, commons-lang3 and commons-collection to compile and run.

With a one short command, you get an Connection to the database.

It supports a number of the most basic SQL operation you need (create, update, delete and select).

It is quick in execution.
>>>>>>> branch 'master' of https://github.com/iks-github/SqlPojoMemoDB.git


Have a try:
  
<dependency>
   <groupId>com.iksgmbh</groupId>
   <artifactId>sql-pojo-memo-db</artifactId>
   <version>0.0.1-SNAPSHOT</version>
</dependency>


* * *

Copyright by [IKS GmbH](https://www.iks-gmbh.com)

Licenced under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

Current version: **0.0.1**

* * *


Versioning convention: major.minor.revision

major:    will change for basic framework modification

minor:    will change for new features and larger improvements

revision: will change for bug fixes and smaller improvements


* * *


####Markdown Documentation

you can find documentation around markdown here:
- [Daring Fireball] [1]
- [Wikipedia - markdown] [2]

  [1]: http://daringfireball.net/projects/markdown/syntax
  [2]: http://en.wikipedia.org/wiki/Markdown
