We usually use the Finder app or another file explorer application to open our files and folders. But you can do the same thing (and more) using the Terminal.

## Finder Folders

Let's go through an example scenario using the Finder app:

1. Open Finder
2. See there's an example folder with name "MyProjects"
3. "Go into" the folder
4. Now we are _inside_ the folder.

## Folders are directories

Let's do the same thing using the Terminal:

1. Open the Terminal (Git Bash if you're a windows user).

2. See the files and folders we have

   ```bash
   $ ls
   ```

   This `$` is not part of the command, it's only tot indicate that this line is a Terminal command.

3. Go into the `MyProjects/` directory

   ```bash
   $ cd MyProjects
   ```

4. New we are _inside_ the directory.

5. See what files and folders there are inside

   ```bash
   $ ls
   ```

## Going back one step: `..`

How do we go _out_ of a directory we're in? Wherever you are, you can always run the following command to **exit** the current directory you're in:

```bash
$ cd ..
```

The `..` means _one directory out_.

---

### **Task**: Take 5 minutes to explore these commands and navigate the directories in your computer.

---

Here's a list of the Terminal commands we just used:

- `ls`: Lists files and directories.
- `cd`: Changes directory. Example: `cd MyProjects` to go into the `MyProjects` directory.
- `cd ..`: Exiting current directory.
