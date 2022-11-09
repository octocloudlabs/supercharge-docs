---
id: customizing-06
---
# Code Tour

Another way to enhance your tutorials is to provide an onboarding experience that is annotated. You can do that with a special extension called [Code Tour](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour).

![Code Tour](screenshots/2022-11-08_04-03-05.png)

---

## Seeing Other Branches
![Branch Popup](screenshots/2022-11-08_04-09-58.png)

Although the repository has a lot of branches, the codespace doesn't have information about them by default. In order to see the other branches, you'll need to pull information about them.

![Pull Information](screenshots/2022-11-08_04-14-55.png)

### Exercise

1. Open the terminal
1. run the following command:

```bash
`git pull --all`
``` 

---

## Open the codetour Branch
![Switch to codetour branch](screenshots/2022-11-08_04-45-02.png)

The CodeTour extension adds a tab to your sidebar with some new features.

Let's go ahead and record a tour.

### Exercise
![Start a Tour](screenshots/2022-11-08_04-51-03.png)
1. Click on the Plus icon in the CodeTour tab.
1. Type in `Walkthrough` for the name of the Tour
![Apply to Branch](screenshots/2022-11-08_04-55-57.png)
1. You can make a tour apply to every commit in a single branch or a single commit. Choose the branch option.
![Changes](screenshots/2022-11-08_04-58-59.png)
1. Notice the changes in the interface. You get a notice telling you that recording has started, The CodeTour tab tells you that it's ready for you to record a step and there is a new folder called `.tours`
![Navigate to File](screenshots/2022-11-08_05-02-57.png)
1. Go to the index.html document
1. Roll over line 1 in the document, notice that there is a Plus sign next to the line number.
1. Click on the plus sign to add a step to the tour.
![Welcome](screenshots/2022-11-08_05-05-18.png)
1. Add a welcome message.

![Alt text](screenshots/2022-11-08_05-06-15.png)

You'll notice that there's a new step on the tour and that your message was added to the file as a popup. There are some new controls available.


Try clicking on the pencil icon to edit the message.

---

## Change the Line Number
You can also change the line number that the popup appears on.

Roll over the message, then click on the three dots.

![Three dots](screenshots/2022-11-08_05-10-31.png)

Now, you can type in the line number to assign this message to a new line. Since line 7 has the title of the document, type that and hit enter.

![Assign to a new line](screenshots/2022-11-08_05-12-37.png)

---

## Annotate Another File

You can add steps in the same file or another file.


1. In the src folder, open the App.jsx file.
1. Click on the plus sign next to line 1.
1. Add a message that says "The App.jsx file is the main component in our application."
![Annotate new file](screenshots/2022-11-08_05-19-12.png)

When you add this step, the tour shows you the second step and there is now a new arrow where you can navigate between your tour steps.

Use the arrows to go from one step to another. 

**Note:** Sometimes the annotations will collapse, look by the line number for an icon to expand the annotation.

You can now also change the order that the annotation appears in, either in the Code Tour tab or in the `...` menu. Try changing the order of the two steps.

![Changing Order](screenshots/2022-11-08_05-28-28.png)

---

## Adding a Selection Block

You can also add an entire selection group as a step instead of a single line.

![Alt text](screenshots/2022-11-08_06-25-16.png)

1. Select a few lines in the editor.
1. Right click on the selection
1. Choose `Add CodeTour Step` from the menu.

---

## Changing Titles

The automated Titles aren't always the best, so you can change them. 

1. Right click on a step's title 
1. Change the title of the step.

![Alt text](screenshots/2022-11-08_06-28-39.png)

---

## Full Markdown Support

You have the full power of markdown inside the messages. You can add links, images, and even code blocks.

If you add a title ## to the message, it will also become the title for the tour automatically.

---

### Exercise

![Alt text](screenshots/2022-11-08_06-42-22.png)

1. Select line 29 in the code.
1. Cut the line into the clipboard
1. Add a new step on line 29.
1. Start a code bock with three backticks.
1. You can add a shortcode to the backticks for proper syntax highlighting,so we can add `jsx` in this case.
1. Paste the line you cut into the code block.

---

## Insert the Code Block

We often ask students to type in some code, you can let CodeTour automatically insert some complex codeblocks into a line.

![Alt text](screenshots/2022-11-08_06-50-54.png)

1. Pull up the current tour step.

Click on insert code.

---

## Finishing the Tour
![Finish the tour](screenshots/2022-11-08_06-58-19.png)

When you're done with a tour, you can use the `Finish Tour` button. Its available in several places in the interface.

---

## The Tour Files
![Alt text](screenshots/2022-11-08_07-02-04.png)
A tour is really just a json document inside a tours folder. You can take a peek at the file in the editor and modify it there. However, you might need to restart the tour to see changes.

---

## Other Features

Codetour has a lot of other features, including the ability to run terminal and other commands, run a series of commands to, for example, pull up a browser URL, set up tours that are inside other tours. For more information, check the [documentation](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour).

[Go to next lab section](/ray/lab-6.html)