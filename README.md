# Welcome to @drdanteaches Flipbook Repository
This is a folder of image flipbooks (aka "carousels") to help students learn Statics, Dynamics, or Mechanics of Materials. This work is part of a much larger U.S. Department of Education-funded project housed at Seeing.Engineering. 
## Using Flipbooks 
Here are some tips if you are attempting to access these flipbooks 
1. The easiest way to use these flipbooks is to go to Seeing.Engineering and find the flipbook and all supporting documentation.
2. If you would like to access the flipbooks directly  
     - The GitHub pages will be located at https://USERNAME.github.io/REPOSITORY/FOLDER/ (for example: https://dantheboatman.github.io/vector_flipbooks/frames_machines_1/ )  
     - The flipbook can also be embedded in another website or LMS page by using an iframe. For example:  `<p><iframe style="border: medium none currentcolor;" src="https://dantheboatman.github.io/vector_flipbooks/frames_machines_1/" width="100%" height="700" loading="lazy"></iframe></p>`
## Duplicating Flipbooks: 
Here are some tips if you are attempting to duplicate a flipbook to deploy on GitHub Pages:
1. First, you'll need to clone either this full repository or just one of the flipbook folders https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository. After you have your own cloned copy, you can add it to your own GitHub repository.
2. Now, let's take a tour of the file structure. The `index.html` and `styles.css` files must be located in the root directory
     - The portions of `index.html` that need to be edited to use in a new flipbook are labeled with an <!-- EDIT --> comment, including the <title> and list of slides.
     - There is nothing in the 'styles.css' file that you need to update, unless you want to change colors or some other formatting.
4. The images, using the default names of slide1.jpg, slide2.jpg, etc are located in the `images` folder and must have the exact same name as the list in the index.html file
     - Images can be created in any software. @drdanteaches likes using Affinity Designer v2, which has been replaced by the new version Affinity by Canva https://www.affinity.studio/
     - In Affinity by Canva, you can set up individual artboards for each image and then export them all at once using the Slice Studio https://www.affinity.studio/help/artboards-artboards-export/
5. Any source documents, like a .svg or the Affinity Designer (.afdesign) can be placed in the source folder. The website does not use these files; they are simply a backup in case others want to make edits.
6. Once you've built your website as index.html, you can deploy your site via GitHub Pages. This help page walks you through the process https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
     - The GitHub pages will be located at `https://USERNAME.github.io/REPOSITORY/FOLDER/` (for example: `https://dantheboatman.github.io/vector_flipbooks/frames_machines_1/` )
     - The flipbook can also be embedded in another website or LMS page by using an iframe. For example:  `<p><iframe style="border: medium none currentcolor;" src="https://dantheboatman.github.io/vector_flipbooks/frames_machines_1/" width="100%" height="700" loading="lazy"></iframe></p>`

**AI Use Statement:** @drdanteaches used ChatGPT to help him code index.html and styles.css. Additionally, Dall-E within ChatGPT was used to help produce the images in the slides.
Last updated: 2026.07.28
