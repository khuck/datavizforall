# Create a New Repository and Upload Code with GitHub
*By [Jack Dougherty](../../introduction/who.md), last updated March 14, 2017*

Question: If I already forked one copy of a GitHub code repository, GitHub will not allow me to fork it a second time. So how do I make a second copy of a repo?

Answer: GitHub has a "one-fork" rule for good reasons, but here's a simple way for beginners to work around it, using only your web browser and any computer (such as Mac, Windows, or Chromebook).
- Create a brand-new repository on GitHub in your browser
- Download an existing code repository and unzip the folder
- Upload the contents of that folder to your new repository and Commit Changes

## Video with step-by-step tutorial
{%youtube%}Hev2UcoLtfw{%endyoutube%}

1) Follow these steps if you have already forked a GitHub repository and wish to make a second copy of it. For example, imagine that you have already forked a copy of the Leaflet Maps with Google Sheets repository from https://github.com/jackdougherty/leaflet-maps-with-google-sheets

2) If you try to "fork" it again, GitHub will simply send you back to the first forked copy you already made. Clicking the "fork" button a second time is useless here.

3) Instead, go to your GitHub account and Create a New Repository. Give it a different name, and click the box to create a README.md file, then scroll down to click the Create button.

4) Go to the original repository where you wish to make a second copy, and click the Clone or Download button, and Download a zipped (compressed) file to your computer.

5) In your computer downloads folder, unzip the compressed file, typically by double-clicking it.

6) Go to the top level of your brand-new GitHub repository, and click the Upload Files button. Drag-and-drop all of the contents of the code repo you downloaded, EXCEPT the README.md file, because you have already created a new one. Click the Commit Changes button and be patient. During busy periods, a large upload may take 1 minute or more for GitHub to process.

7) When the upload is done, inspect the contents that you copied into your brand-new repository. To publish your new repo to the live web, go to Settings > GitHub Pages > select Master branch > Save. Then copy the link to your published live site and paste into your README.md file for future reference. If you need to review these last steps, see Part B: Publish section of the [Fork and Edit a Leaflet Map](../fork-leaflet) chapter in this book.

{% footer %}
{% endfooter %}
