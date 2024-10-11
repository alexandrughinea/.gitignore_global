# .gitignore_global
A growing list of things which definitely shouldn't be tracked in a project

## Why Use a Global `.gitignore`?

When working with Git, you may want to exclude certain files or directories that are specific to your operating system, IDE, or temporary files from being tracked by Git. Instead of adding these files to the `.gitignore` file for each project, you can set up a global `.gitignore` file that will apply to all repositories on your system.

## Steps to Set Up a Global `.gitignore`

Follow these steps to create and use a global `.gitignore` file on your macOS system:

### 1. Open Terminal

You can use any terminal emulator of your choice. The default **Terminal** app works perfectly.

### 2. Create a Global `.gitignore` File

Run the following command to create a global `.gitignore` file in your home directory:

```bash
touch ~/.gitignore_global
```

### 3. Add Common Files and Directories to Ignore

Open the .gitignore_global file in your text editor to add the files and directories you want to ignore globally

```bash
nano ~/.gitignore_global
```

### 4. Paste the contents of `.gitignore_global` fromt his repository or add your own.

### 5. Configure Git to Use the Global .gitignore

```bash
git config --global core.excludesfile ~/.gitignore_global
```
