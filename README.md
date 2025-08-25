# RAIK183H Starter Guide: Cursor + Java

Welcome to RAIK183H! This guide will help you set up your coding environment step by step.

---

## ✅ Step 1: Get Cursor (Free for Students!)

Cursor is an AI-assisted code editor that will help you learn programming. The best part? **It's completely free for students for 1 year!**

### 1a. Create Your Cursor Account

1. Go to [https://cursor.com](https://cursor.com)
2. Click "Sign Up" or "Get Started"
3. Choose "Sign up with email"
4. Enter your school email address (ending in .edu)
5. Create a password
6. Verify your email address

### 1b. Verify Your Student Status

**Important:** To get your free year of Cursor, you need to verify you're a student!

1. **Go to [cursor.com/students](https://cursor.com/students)**
2. **Click "Verify Student Status"**
3. **Choose your school** from the dropdown list
4. **Enter your school email** (the same .edu email you used to sign up)
5. **Check your email** for a verification link
6. **Click the verification link** in your email

**If you have trouble:**
- Make sure you're using your school email address (.edu)
- Contact Cursor support at [support@cursor.com](mailto:support@cursor.com)

**What this gives you:** A full year of Cursor Pro completely free!

### 1c. Download and Install Cursor

1. After creating your account, you'll be taken to the download page
2. Click the big "Download" button
3. Install Cursor on your computer:
   - **Mac**: Double-click the downloaded file, then drag Cursor to your Applications folder
   - **Windows**: Double-click the downloaded file and follow the installation wizard
   - **Linux**: Extract the file and run the installer

### 1d. Sign In to Cursor

1. Open Cursor from your Applications/Programs menu
2. Sign in with the email and password you created
3. You should see a welcome screen - you're all set!

---

## ✅ Step 2: Create Your First Java Program

Now let's create your first program! We'll start by choosing where to store your projects.

### 2a. Choose Where to Store Your Projects

You need to pick a place on your computer to keep all your RAIK183H projects. Here are some good options:

**Option 1: Desktop (Easiest)**

- Right-click on your Desktop
- Select "New Folder" (Windows) or "New Folder" (Mac)
- Name it "RAIK183H" and press Enter

**Option 2: Documents Folder**

- Open your Documents folder
- Right-click inside it
- Select "New Folder" (Windows) or "New Folder" (Mac)
- Name it "RAIK183H" and press Enter

**Option 3: Ask Your Instructor**

- If you're not sure where to put it, ask your instructor for help!

### 2b. Create Your First Project Folder

Inside your RAIK183H folder, create another folder for today's work:

1. Open your RAIK183H folder
2. Right-click inside it
3. Select "New Folder"
4. Name it "labone" and press Enter

### 2c. Open Cursor and Create Your First File

1. Open Cursor (if it's not already open)
2. Click "File" → "Open Folder" (or press Ctrl+O / Cmd+O)
3. Navigate to your RAIK183H folder and select the "labone" folder
4. Click "Select Folder"

Now you should see your labone folder open in Cursor!

### 2d. Create Your Hello World Program

1. In Cursor, right-click on the left side where it shows "labone"
2. Select "New File"
3. Name it "HelloWorld.java" (make sure to include the .java part!)
4. Click Enter

Now you have a blank file called HelloWorld.java!

### 2e. Write Your First Code

Click inside the HelloWorld.java file and type this exactly:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

**Important:** Type this code yourself - don't copy and paste! This helps you learn.

---

## ✅ Step 3: Install Java (Required!)

Before you can run your Java program, you need to install Java on your computer. Don't worry - it's free and easy!

### 3a. Download Java Development Kit (JDK)

1. Go to [https://adoptium.net](https://adoptium.net)
2. Click the big "Latest LTS Release" download button
3. Choose your operating system:
   - **Mac**: Download the .pkg file
   - **Windows**: Download the .msi file
   - **Linux**: Download the .tar.gz file

### 3b. Install Java

**Mac:**

- Double-click the downloaded .pkg file
- Follow the installation wizard
- Click "Install" when prompted

**Windows:**

- Double-click the downloaded .msi file
- Click "Next" through the installation
- Click "Install" when ready

**Linux:**

- Extract the .tar.gz file
- Follow your instructor's guidance for installation

### 3c. Verify Java is Installed

1. Open Cursor
2. Open the Terminal (View → Terminal or Ctrl+`)
3. Type this command and press Enter:
   ```
   java --version
   ```
4. You should see something like "OpenJDK version 17.0.x" - this means Java is working!

---

## ✅ Step 4: Install Java Extensions in Cursor

Cursor needs some extra tools to work with Java. Let's install them!

### 4a. Install Java Extension Pack

1. In Cursor, click the Extensions icon on the left sidebar (looks like four squares)
2. In the search box, type "Extension Pack for Java"
3. Look for the one by vscjava (it should be the first result)
4. Click "Install"
5. Wait for it to finish installing

**What this gives you:**

- Java language support
- Code completion and error checking
- Run and debug buttons
- Project management tools

### 4b. Install Additional Java Tools

After the Extension Pack installs, Cursor might ask you to install additional Java tools:

1. If you see a popup asking to install Java tools, click "Install"
2. Wait for all installations to complete
3. You might need to restart Cursor

---

## ✅ Step 5: Run Your Program!

Now let's make your program actually work! With the Java extensions installed, you'll have run buttons.

### 5a. Check Your Code

First, make sure your HelloWorld.java file looks exactly like this:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

**Important:** Check that:

- You have the `.java` extension on your filename
- There are no extra spaces or typos
- All the brackets `{` and `}` match up

### 5b. Run Your Program

1. Look for a small "Run" button (▶️) above your code or in the top-right corner
2. Click on it, or press `F5`
3. Cursor will compile and run your Java program automatically

**What happens:** The Java extension will compile your code and show the output!

**If the play button doesn't work:**

1. **Check the bottom status bar** - Look for any error messages in red
2. **Try restarting Cursor** - Close and reopen Cursor completely
3. **Check Java installation** - Make sure Java is properly installed (Step 3)
4. **Verify file extension** - Your file must end with `.java`
5. **Ask for help** - If nothing works, raise your hand and ask your instructor!

**Alternative way to run:**
If the button still doesn't work, you can also:

1. Right-click anywhere in your HelloWorld.java file
2. Look for "Run Java" in the context menu
3. Click on it to run your program

### 5c. See Your Results

If everything works correctly, you should see:

- A new panel at the bottom of Cursor called "Output" or "Terminal"
- The words "Hello, world!" displayed (after a complicated-looking command)

**Congratulations!** You just wrote and ran your first Java program! 🎉

---

## ✅ Step 6: Add Course Rules to Your Project

Your instructor has provided special rules for using Cursor's AI features. These rules help you learn programming with best practices for styling, growth mindset messaging, and more!

### 6a. Create the Rules Folder

1. In Cursor, right-click on your "labone" folder in the left sidebar
2. Select "New Folder"
3. Name it `.cursor` (include the dot at the beginning)
4. Press Enter

### 6b. Create the Rules Subfolder

1. Right-click on the `.cursor` folder you just created
2. Select "New Folder"
3. Name it `rules`
4. Press Enter

### 6c. Copy the Rules File

1. In GitHub, at the top-ish section of the page, there is a file called `cs1cursor.md`. Copy the contents of that file.
2. Right-click on the `rules` folder
3. Select "New File"
4. Name it `cs1cursor.md`
5. Copy and paste the content your instructor provided into this file
6. Save the file (Ctrl+S or Cmd+S)

**Your project structure should now look like this:**

```
labone/
  ├── .cursor/
  │   └── rules/
  │       └── cs1cursor.md
  └── HelloWorld.java
```

**What this does:** These rules tell Cursor's AI how to help you learn programming step by step, without just giving you complete solutions!

---

## ✅ Step 7: Use Cursor's AI to Enhance Your Program

Now let's see how Cursor's AI can help you learn programming! We'll use it to add some cool features to your Hello World program.

### 7a. Open the AI Chat Panel

1. Look for the AI Chat icon on the left sidebar (looks like a chat bubble or message icon)
2. Click on it to open the AI chat panel
3. You should see a chat interface where you can talk to Cursor's AI

### 7b. Ask the AI for Help

Let's give your program a fun goal! We want it to:

1. Print "Hello, world!" (you already have this!)
2. Print your name
3. Print a celebratory cheer

Start by asking the AI:

```
"I want my program to print my name after 'Hello, world!'. What do I need to learn to do this?"
```

**What to expect:** The AI will:

- Explain programming concepts in simple terms
- Give you small examples to understand
- Guide you through learning one concept at a time
- Ask you to explain what you understand before moving forward

**For beginners:** Don't ask for complete solutions! Ask for explanations of concepts first.

### 7c. Learn Step by Step

1. **Start with printing your name** - Ask "How do I make my program print my name?"
2. **Ask for small examples** - "Can you show me a simple example of this?"
3. **Explain back** - Tell the AI what you think you understand
4. **Build gradually** - Add one feature at a time

**What you'll see:** The AI will explain concepts, show tiny code examples (5 lines or less), and help you understand before creating any code that you can apply to your own work.

**Your learning path:**

- First: Learn how to print your name (variables)
- Then: Learn how to add a celebratory cheer
- Finally: Have a program that does three things in sequence!

**Remember:** It's okay to not know everything! The AI is here to teach you step by step. We'll build this together!

---

## ✅ Step 8: Submit Your Work to Canvas

Great job! Now let's submit your completed project to Canvas so your instructor can see your work.

### 8a. Zip Your Project Folder

1. **On your computer** (not in Cursor), navigate to where you created your RAIK183H folder
2. **Right-click** on the "labone" folder (not the RAIK183H folder)
3. **Select "Compress"** (Mac) or "Send to → Compressed (zipped) folder" (Windows)
4. **Wait** for the zip file to be created
5. **Rename** the zip file to "YourName_Lab1.zip" (replace "YourName" with your actual name)

**What you should have:** A file called "YourName_Lab1.zip" that contains your entire labone project.

### 8b. Upload to Canvas

1. **Go to Canvas** and find your RAIK183H course
2. **Look for the Lab 1 assignment** (your instructor will tell you where to find it)
3. **Click "Submit Assignment"**
4. **Click "Choose File"** and select your "YourName_Lab1.zip" file
5. **Click "Submit Assignment"**

**What you're submitting:**

- Your HelloWorld.java file
- Your .cursor/rules/cs1cursor.md file
- Any other files you created during the lab

---

**Congratulations!** 🎉 You've completed your first programming lab! You've learned how to:

- Set up a professional coding environment
- Write and run Java code
- Use AI tools to learn programming
- Submit your work properly

**What's Next?** Your instructor will review your work and give you feedback. Keep practicing and exploring with Cursor!

---

_Note: If you have any trouble with these steps, raise your hand in class or ask your instructor for help._
