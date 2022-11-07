---
id: a-lab-6
---
## View and edit a webpage

***[headphones recommended]***

This project is a **fork of CanvasFun**, an animation open-source repository.  We'll view some of the example files in the browser. To do this you need to run the Live Server extension.

On advantage of Live Server is that it auto-refreshes the web page whenever you edit the file and save the changes.

With just a couple of clicks, Live Server lets you see your page live in another browser tab. Better yet, it features live reloading, so when you update your code, the changes are also reflected in the browser.

💡 **Instructor tip:**

>Live Server let's the learners experiment with web code and instantly see the results in the browser.This works in any browser.

## Open some files

You created the codespace on the MojoCanvasFun `master` branch. In Visual Studio Code you can see all the files from that branch in the Explorer.

1. In the Activity Bar click the Explorer button
<img src='/assets/img/a-lab-10.png' alt="lab image" class="img-lab" >

2. Navigate to the TextParticles folder
3. Open the `index.html` file in the editor.
4. Open the `src\index.js` file in th editor.

### Start Live Server and view files

5. Right click the index.html file (in the TextParticles folder) and choose `Open with Live Server`.

### View the page

Visual Studio Code starts the Live Server, then opens an new browser tab that shows the webpage (the URL will end with `github.dev/TextParticles/index.html`).

1. View the webpage, move your mouse over the image to see the particles animate!


### Edit the Javascript
1. Switch browser tabs and view the Codespace.
2. In the Explorer, open the `/TextParticles/src/js/index.js` file.
3. This is the code that creates the canvas, loads the image and starts the animation.
4. You will change the image shown in the animation.
5. Comment out line 12.
   
```
let url =
    "https://github.githubassets.com/images/modules/logos_page/Octocat.png";
```

* Uncomment line 15.

```
  // let url =
  // "https://myoctocat.com/assets/images/octocat-accessories.png";

```
* Change the canvas color on line 30.

```
    c.clear("orange");
```

* Save the file, switch browser tabs and refresh the page (F5).

💡 **Instructor tip:**

> Working with web applications in Codespaces, running a web server on the VM gives the learners instant access to a full featured web app. It can work well for front-end development or server side web application. Performance of browser based code is the same as running a real site.

[Go to next lab ](/walt/lab-7.html)

