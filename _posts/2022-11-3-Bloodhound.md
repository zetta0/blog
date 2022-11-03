## Setting Up Bloodhound with Parrot OS.

Hey guys, if you try to run Neo4j on ParrotOS it will not work correctly. You should receive a bunch of errors from the Java runtime.

This is because the OS does not come packaged with the JDK that is dependant by neo4j's database.

Please run the following commands to fix this issue!

```sudo apt install openjdk-11-source```

Then run:

```sudo update-alternatives --config java```

This should allow neo4j to run correctly!


HAPPY HACKING!
