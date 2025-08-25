# CS1 Starter Guide: Cursor + Java

Welcome to CS1! Follow these steps to set up your coding environment and run your first Java program.

---

## ✅ 1. Download and Install Cursor
Cursor is an AI-assisted code editor that helps you learn step by step.

- **Download Cursor**: [https://cursor.com/download](https://cursor.com/download)
- Install it like any other app:
  - **Mac**: Drag to Applications.
  - **Windows**: Run the installer.

---

## ✅ 2. Create Your Project Folder
Pick a folder where you want your CS1 projects. Example:

/CS1
/Projects

---

## ✅ 3. Create a Folder for Today's Lab
In your projects folder, create a new folder for today's lab.
Name the folder "labone".

---

## ✅ 4. Add Course Rules (No Copy-Paste Fixes)
Your instructor provided `.cursor/rules` files to guide learning.  
In labone, create a folder called .cursor/rules. In that folder,
create a file called cs1cursor.md and paste the provided file.

---

## ✅ 5. Create Your First Java File
Inside of labone, create a new folder called src.
In that folder, create a new file called HelloWorld.java.

Right now, your project structure should look something like this:

/CS1
  /labone
    /.cursor/rules/cs1cursor.md
    /src/HelloWorld.java

Inside of HelloWorld.java, paste the following code:

```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

---

## ✅ 6. Compile and Run

Open a terminal in the labone folder:

javac src/HelloWorld.java;
java -cp src HelloWorld;

You should see:

```
Hello, world!
```

---

## ✅ 7. Using Cursor

Open the HelloWorld folder in Cursor.

Use the AI Chat panel for help—but follow the course rules:

Explain your reasoning before asking for fixes.

Patches will be created automatically (no copy-paste needed).
