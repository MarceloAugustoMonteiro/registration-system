# Registration system
Employee/Dependent Registration System using SQLite database.  
# Example of Java DAO and SQLite

## COMPILE

To compile via command line, create a file containing all your source files:

**On Windows:**

```bash
dir /s /B *.java > sources.txt
```

**On Linux:**

```bash
find -name "*.java" > sources.txt
```

Then, compile the project with:

```bash
javac @sources.txt
```

## RUN

Assuming the JDBC driver is located in the `libs` folder and you are in the root directory, run the following command:

```bash
java -classpath .:libs/sqlite-jdbc-3.32.3.2.jar src.com.app.main.Main
```
