Learn Bash by Building a Boilerplate

Review

**The first thing you need to do is start the terminal.** Do that by clicking the "hamburger" menu at the top left of the screen, going to the "terminal" section, and clicking "new terminal". Once you open a new one, type `echo hello terminal` into the terminal and press enter.

 

---

What you see in the terminal below is a folder (or directory) on this machine. Type `pwd` into the terminal and press enter to see the path of the folder. `pwd` stands for "print working directory".

 

---

The output tells you where the folder you are in is located. You are in the `project` folder, which is in the `workspace` folder. Type `ls` into the terminal to see what's in this folder. `ls` stands for "list".

 

---

The output is showing everything in this folder. There's one folder in here. You can use `cd <folder_name>` to go into a folder. `cd` stands for "change directory". Change to the `freeCodeCamp` directory.

 

---

You are in the `freecodecamp` folder now. You may have noticed that the prompt changed to include it. Print the working directory of the `freeCodeCamp` folder to see the full path of where you are.

 

---

You can see the path of the `freeCodeCamp` folder. It's in the `project` folder you were just in. List the contents of the `freeCodeCamp` folder to see what's here.

 

---

There's several folders and files here. The folders are blue or green and the files include their extension. Next, change to that `test` directory.

 

---

You can see you are in the `test` folder now. It shows `test` in the prompt. Print the full path of this directory. Remember that "folder" and "directory" are the same thing.

 

---

That's the path to the `test` folder, it's in the `freeCodeCamp` folder. **List** the contents of this folder.

 

---

These are all files. There's no more folders to go into here. You can use `cd ..` to go back a folder level. The two dots will take you back one level. Go back to the `freeCodeCamp` folder.

 

---

`test` got removed from the prompt since you left that folder and you're back in the `freeCodeCamp` folder. List the contents of what's here to remind yourself.

 

---

There's the `test` folder you were just in. You can see what's in a file with `more <filename>`. Use it to view what's in the `package.json` file.

 

---

It looks like a JSON object. You can empty the terminal with `clear`. The terminal looks a little cluttered, why don't you clear it.

 

---

Now you have a fresh screen 😄 List what's in here again.

 

---

You checked out the `test` folder and the `package.json` file. What next? Why don't you go into that `node_modules` directory.

 

---

Now the prompt includes `node_modules` since that's where you are. List what's in the folder.

 

---

That's a lot of folders. You can add a **flag** to a command to use it different ways like this: `ls <flag>`. List the contents of the `node_modules` folder in "long list format". Do that by adding the `-l` flag to the "list" command.

 

---

It is showing more details about each item in here and it's a little easier to read. One of the folders is named `has`, why don't you change into it.

 

---

You are now in the `has` folder. List its contents.

 

---

There's a few files and folders here. Can you tell the difference? Take a look at **more** of that `README.md` file.

 

---

Nothing noteworthy in there. You can't see what's in the here anymore, list the contents again.

 

---

That one file doesn't appear to have an extension. Strange. Take a look at **more** of the that "license" file that doesn't show an extension.

 

---

Pretend you read all that. It looks a little messy in here again so why don't you clear the terminal.

 

---

Better. Remind yourself what's in here with the list command.

 

---

Go into that `src` directory to see what you can find in there.

 

---

View the full path of this folder.

 

---

Getting deeper still. You can see that each new folder has a `/` in front of it. Take a look at what's in this folder.

 

---

Only one file here. Show me what's in it with `more`.

 

---

It's some JavaScript 😄 I think you've fooled around enough. Why don't you navigate out of here. Change back to the `has` directory.

 

---

You're getting pretty good. Change back to the `node_modules` directory.

 

---

You can go back two folders with `cd ../..`. Each set of dots represents another folder level. Go back to the `project` directory from the `node_modules` directory.

 

---

You are back in the `project` folder where you started. List what's in here again.

 

---

That's right. Why don't you get a fresh start by clearing the terminal.

 

---

You will be making a website boilerplate. You can make a new folder with `mkdir <folder_name>`. `mkdir` stands for "make directory". Make a `website` directory in this `project` folder. Remember that "directory" and "folder" mean the same thing.

 

---

List what's here to make sure it got created.

 

---

It worked. The website files will be in the new directory. Change to the `website` directory so you can start creating them.

 

---

List the contents of the `website` folder.

 

---

It's brand new, there's nothing in it yet. The `echo` command lets you print anything to the terminal. You used it in the first lesson. Just type what you want to print after it. Use it to print `hello website` to the terminal.

 

---

Websites usually have an `index.html` file. You can use `touch <filename>` to create a new file. Create `index.html` in the `website` folder.

 

---

They usually have a CSS file as well. Create `styles.css` in the `website` folder using the same method.

 

---

List the contents of the `website` folder to make sure they got created.

 

---

There they are. Next is a JavaScript file. Create `index.js` in the `website` folder with the method you have been using.

 

---

You might turn this into a git repository. Create `.gitignore` in the `website` folder with the same method.

 

---

List the contents of the `website` folder to see your new files.

 

---

There's three files, but where's the `.gitignore` file? I think it's hidden. Most commands have a `--help` flag to show what the command can do. Display the "help" menu for the `ls` command. Here's an example: `command <flag>`

 

---

Scroll through the menu to see the flags that go with `ls`. The flag you are looking for is `--all`, or `-a` for short. List **all** the contents of the `website` folder using the correct flag.

 

---

There's the hidden file. Do you see it? It didn't display before. It also includes `.` and `..`. You used `cd ..` to go back a folder earlier. Change to the `.` directory.

 

---

You didn't go anywhere. The `.` takes you to the folder you are in, and `..` takes you back, or up, a folder. Websites need some images. Create `background.jpg` in the `website` folder.

 

---

Next, add a header image. Create `header.png` in the `website` folder.

 

---

Finally, create `footer.jpeg` in the `website` folder.

 

---

Use the **list** command to check out the images you just added.

 

---

Looks like images show up in pink. There's also three fonts to use for the website. The first one is "roboto". Create `roboto.font` in the `website` folder.

 

---

The next one is "lato". Create `lato.font` in the `website` folder.

 

---

Lastly, create `menlo.font` in the `website` folder.

 

---

List the contents of this folder to see your new font files.

 

---

Your three font files are there. There's three icons for the website as well. Create `CodeAlly.svg` in the `website` folder.

 

---

Next, create `CodeRoad.svg` in the `website` folder.

 

---

Finally, create `freeCodeCamp.svg` in the `website` folder.

 

---

Check out the new icons you just added by listing the contents of the folder they are in.

 

---

The icons are pink as well. I think the images should go in a separate folder to clean it up a little. Make an `images` directory in the `website` folder to put them in.

 

---

List the contents of the `website` folder to make sure your new folder is there.

 

---

There's your new `images` folder. It's blue. You can copy a file with `cp <file> <destination>`. `cp` stands for "copy". Copy `background.jpg` to your `images` folder.

 

---

Better make sure it worked. Change to the `images` directory.

 

---

List the contents to see if `background.jpg` is here.

 

---

There it is. Looks like the copy worked. Change back to the `website` directory so you can copy the other ones.

 

---

Remind yourself of the files here by listing the contents.

 

---

You copied the background image to the `images` folder so you don't need the one here anymore. You can remove a file with `rm <filename>`. Remove `background.jpg` from the `website` folder.

 

---

List the contents to make sure it's gone.

 

---

Okay, it's gone. Next, copy `header.png` to the `images` folder.

 

---

Last, copy the "footer" image to the `images` folder.

 

---

All the images should be copied over. Change to the `images` directory so you can make sure.

 

---

Check if the images are here by listing the contents.

 

---

They all made it here. Go back to the `website` folder so you can delete the original files.

 

---

List the contents to remind yourself of the filenames to delete.

 

---

There's two that you don't need anymore. Remove the "header" image file from the `website` folder since you copied to the images folder.

 

---

It should be gone. Remove the "footer" image from the `website` folder as well.

 

---

List the contents of the `website` folder to check if they are gone.

 

---

Looks like they're all deleted. There was a mistake with the extensions for the font files. You can rename them with `mv` like this: `mv <filename> <new_filename>`. `mv` stands for "move", it can **rename or move** something. Rename `roboto.font` to `roboto.woff`.

 

---

Use "list" to check if it worked.

 

---

Do you see the "roboto" font? The rename worked. Next, rename the "lato" font file to `lato.ttf`.

 

---

Lastly, rename the "menlo" font to `menlo.otf`.

 

---

Use the "list" command to make sure those last two got renamed.

 

---

Take a look at the files to make sure they got renamed. Those font files could be organized into a folder as well. Make a `fonts` directory in the `website` folder to put them in.

 

---

List the contents of the `website` folder to make sure your new folder is there.

 

---

See it? You renamed the font files with `mv`, you can also move files with it. Move the "roboto" font to the new `fonts` folder. Here's an example: `mv <file> <destination>`.

 

---

You can use `find` to find things or view a file tree. Enter `find` to view the file tree of the `website` folder to see all the files and folders within it.

 

---

You can see everything in this `website` folder and its descendant folders. Notice that they all start with `./` to represent this folder. You can see that your font moved to the `fonts` folder. Next, move the "lato" font to the `fonts` folder.

 

---

There's one more font to move. Move the "menlo" font to the `fonts` folder.

 

---

Use `find` again to list the whole file tree and make sure those two got moved.

 

---

Yes, you can see them all in the `fonts` folder. Let's organize some more. Make a `client` directory in the `website` folder for the client side files.

 

---

You can make a folder in that `client` folder from here by adding it to the path like this: `mkdir client/<new_folder_name>`. Make a `src` directory in the `client` folder from here.

 

---

You can move files all the way across the system from here with the right path. Move `index.html` to the `client/src` folder from here.

 

---

Use `find` to view the file tree and make sure it moved.

 

---

Can you see the `index.html` file in your new `src` folder? Looks like it moved 😄 There's some more files that can go in the `src` folder. Move `index.js` to it from here.

 

---

Last is the CSS file. Move `styles.css` to the `src` folder.

 

---

Seems like you can do anything right from here. Take another look at the tree with `find`.

 

---

Things are looking more organized 😄 You can use `find <folder_name>` to display the tree of a different folder. View the file tree of the `client` folder from the `website` folder.

 

---

Now you just see what's in the `client` folder. What else can `find` do? View the "help" menu of the `find` command to look around.

 

---

The menu isn't very pretty, but there's a `-name` flag in there. You can use it to search for something with `find -name <filename>`. Use `find` with the `-name` flag to search for `index.html`.

 

---

It shows you where that file is. Using the same command, find where the `styles.css` file is.

 

---

You can search for folders with it, as well. Using the same command and flag, find the `src` folder.

 

---

😄 View the file tree of the `website` folder to see what else you need to do.

 

---

What's next? More organizing! You should put all the assets in one spot. Change into the `client` folder.

 

---

Make a new directory named `assets` in the `client` folder.

 

---

Change into the new `assets` folder.

 

---

All the images and other assets can go here. Make an `images` directory in the `assets` folder for all the images.

 

---

Go to your new `images` folder.

 

---

You want the images here. Create `background.jpg` in this folder.

 

---

Wait. You don't need to recreate them. You can just move the other images here. Go back to the `website` folder from here. It's three folder back.

 

---

Now go to where the original images are. Change into the `images` folder.

 

---

List the contents of the `images` folder to see the files here.

 

---

Umm, first I think you should move them back to the website folder. Move `header.png` back to the `website` folder. The destination for the file is `..`

 

---

List the contents of the `images` folder to see if it's gone.

 

---

It's gone. Go back to the `website` folder.

 

---

List what's here.

 

---

There's the file you just moved. Next, you will move it to the `client/assets/images` folder. First, use `find` with the correct flag to search for `images`.

 

---

There's your two image folders. Move `header.png` to the one with the longer path. Just use it as the destination to do so.

 

---

Use `find` to search for your `header.png` file and make sure it moved.

 

---

There it is. Right where you put it. Next, search for your `footer.jpeg` file so you can move that over there.

 

---

It's in the original `images` folder. You can **use that path** with the move command to move it. Move `footer.jpeg` to the `client/assets/images` folder while in the `website` folder.

 

---

View the file tree of this folder to make sure all your images are over in their new folder. Don't use any flags.

 

---

You don't need the old `images` folder anymore. You can use `rmdir <directory_name>` to remove a folder. `rmdir` stands for "remove directory". Try to remove the `images` folder with `rmdir`. Make sure it's the one in the `website` folder.

 

---

Directory not empty? Oh yeah, there's still the background image in there. Remove the background image file in the `images` folder from here. Make sure it's the one in the `website/images` folder.

 

---

Try to remove the `images` folder again with `rmdir`. Make sure it's the one in the `website` folder.

 

---

I think it worked this time. List the contents to find out.

 

---

It worked, the `images` folder is gone. Make a new `icons` folder in your `assets` folder while in the `website` folder.

 

---

Move the `CodeAlly.svg` file to your new `icons` folder.

 

---

View the file tree of the `website` folder and make sure it moved.

 

---

Verify that the file moved to the `icons` folder. Next, move the "CodeRoad" file to your `icons` folder.

 

---

Lastly, move the "freeCodeCamp" file to your `icons` folder.

 

---

View the file tree and make sure the files moved.

 

---

This looks much better. The three icons are now in the `icons` folder. Make a `fonts` folder in your `assets` folder from here for all the font files.

 

---

Turns out you want some different fonts for the website. From here, create `roboto-bold.woff` in your new `fonts` folder. You can put the path in front of the filename of where you want it to go.

 

---

Next, create `roboto-light.woff` in your new `fonts` folder from here.

 

---

View the file tree of the `client/assets/fonts` folder from here to see if your new files are there.

 

---

Two more fonts to go. Create `lato-bold.ttf` in the new `fonts` folder from here.

 

---

Lastly, create `lato-light.ttf` in your new `fonts` folder from here.

 

---

View your file tree and make sure the files are there.

 

---

Things are looking more organized 😄 The new fonts are there. Now you can remove the old `fonts` folder and everything in it. You can't do that with `rmdir` since it's not empty. View the "help" menu of the `rm` command to see if you can find anything.

 

---

There's a `-r` flag that says, `remove directories and their contents recursively`. That will remove the folder and everything in it. Use the "remove" command with that flag to remove the `fonts` folder. Make sure it's the one in the `website` folder. Be careful not to remove the wrong folder.

 

---

List what's here to see if it's gone.

 

---

Looks like it’s gone. Surely, it went to the trash can right? No, it’s just gone. You should **be very careful when recursively removing files** like that. It will delete everything, and can destroy your operating system. There's a few more files for the boilerplate. Create `package.json` in the `website` folder.

 

---

Next, create `server.js` in the `website` folder.

 

---

Lastly, create `README.md` in the `website` folder.

 

---

List the content of this folder to make sure your new files are there.

 

---

The boilerplate is complete. Use `echo` to print `Yay!` to the terminal.

 

---

Print `I finished the boilerplate!` to the terminal.

 

---

Print `one more thing...` to the terminal

 

---

You can print to a file instead of the terminal with `echo text >> filename`. Use it to print `I made this boilerplate` to your `README.md` file.

 

---

Use `more` to view your `README.md` file.

 

---

Now that line is in the file. Add `from the command line` to your `README.md` file with the `echo` command and the same method.

 

---

Use `more` to view the "readme" file again.

 

---

Now the file has two lines. Add `for the freeCodeCamp bash lessons` to your "readme" file with the `echo` command like you did before.

 

---

View your "readme" file again like you did before.

 

---

😄 Change to the `project` folder.

 

---

You are back where you started. List what's here.

 

---

Still the same items. Rename the `website` folder to `website-boilerplate`.

 

---

List the contents of this folder to see the new name.

 

---

Thanks for making this. You need to make a copy of it. Take a look at the "help" menu of the "copy" command.

 

---

Scroll up to find that "recursive" flag. You need to use it again to copy the whole folder. Copy the whole boilerplate into a folder named `toms-website`.

 

---

List the contents of the `project` folder to see the new copy.

 

---

Thanks. Use `find` to view the tree of `toms-website`.

 

---

Use `find` to view the tree of the boilerplate folder to make sure it matches.

 

---

Awesome! You are finished for now. Clear the terminal one last time.

 

---

Print "goodbye terminal" to the terminal.

 

---

Use the "exit" command to exit the terminal.

 

### Congratulations on completing "Learn Bash by Building a Boilerplate"!