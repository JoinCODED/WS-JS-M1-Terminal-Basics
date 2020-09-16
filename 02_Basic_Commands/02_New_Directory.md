Using the Finder app, you can create a new directory by right-clicking and picking "New Folder". Let's see how we can do that in the Terminal. Inside "MyProjects":

1. Create a new directory with the name "NewWebsite"

   ```bash
   $ mkdir NewWebsite
   ```

2. Navigate into the new directory

   ```bash
   $ cd NewWebsite
   ```

3. Verify that you're now inside the new directory

   ```bash
   $ pwd
   ```

   `pwd` is short for _`p`rint `w`orking `d`irectory_. It displays your current location in the computer file system. We can use it to make sure we are where we expect to be.

## Directory within a directory **(+ Command History)**

We can also create a directory within a directory, and can keep nesting folders like this indefinitely.

1. Move into `NewWebsite/`

   ```bash
   $ cd NewWebsite
   ```

2. Create a new folder named `ExampleSite`

   ```bash
   $ mkdir ExampleSite
   ```

3. Hit up-arrow three times to run `pwd`. This'll show us the previous commands we ran, so we don't have to type them everytime.

---

## Task (10 min)

1. Use this [Terminal Cheat Sheet](https://github.com/0nn0/terminal-mac-cheatsheet#english-version) and explore the Terminal.
2. Create a directory called "Development" either in your home directory (mac/linux) or in your Desktop (windows). You'll put all your work in the bootcamp in this Development directory.

---
