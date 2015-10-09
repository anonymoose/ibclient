# Interactive Brokers Java Client

Interactive Brokers provides Java source code that can act as an async client to talk to IB.  It's not so bad once you get it set up.

The problem is that it is distributed like its 1999.  This project wraps the source code they provide, adds a maven POM.

From here, its up to you.

Interactive Brokers guys:

Cool product, your API could use some work.  If you don't want this up as a conveninence mechanism for your users, let me know and I can take it down, but you really should embrace maven like everybody else.

# Installation Instructions
```
git clone https://github.com/anonymoose/ibclient.git
cd ibclient
mvn clean
mvn package
mvn install
```
At the end of this you will have a built library, installed in your local repository, that you can now use in your library.

```
  <dependencies>
    <dependency>
      <groupId>interactivebrokers</groupId>
      <artifactId>ibclient</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>
  <dependencies>
```

# Warranty / License

This is not my code and is simply packaged as-is/where-is.  You use it at your own risk and I have no liability.  If you blow up
your account, it is on you.  I am packaging it as a convenience.  The license in the source reads as follows.

```
/* Copyright (C) 2013 Interactive Brokers LLC. All rights reserved.  This code is subject to the terms
 * and conditions of the IB API Non-Commercial License or the IB API Commercial License, as applicable. */
```
