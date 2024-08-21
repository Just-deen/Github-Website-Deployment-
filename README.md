# Github-Website-Deployment-
Deploying your static website on Github can sometimes become a bit of a hassle. I'm going to cover the common problems people face when deploying their websites and the solutions to these problems. I'll also provide you with a step-by-step process for deploying your static website on Github. Hope this helps. Cheers!


#(1.1) Common Issues (with Solutions) Faced When Hosting Static Websites on GitHub:-

• Always change the HTML filename to index.html.

• Use "root" or "docs" as needed on the following page: "Repository > Settings > Pages". Then scroll down. Check the 5th step in section 1.2 to know when to use either of them.

• Track the hosting progress (read through steps 6 and 7 in section 1.2 to learn how to do this). If it fails, restart the process by going to "Repository > Settings > Pages", selecting "none" under the branch options, saving it, then going back and selecting the "main" branch, and saving it again. This will restart the hosting process. Keep in mind that the deployment process will time out if it takes more than 10 minutes, so ensure you have a stable internet connection, as I've experienced this issue in the past.

• After making changes to the code in your repository, always remember to republish the website.

• The maximum size limit for files being uploaded is 100 MB, and files larger than 25 MB will require a different approach to hosting, not the usual process.


(1.2) How to Host a Static Website on GitHub:

• Create a new repository.

• Before uploading files to the repository, rename your HTML file to index.html. Without this change, you'll receive a "404 error" message when you click on the web link. GitHub only recognizes HTML files saved as index.html.

• Upload the HTML file, along with CSS (optional) and JS files (optional). Keep in mind that the HTML file is the primary file that must be uploaded for the website to be hosted.

• Open the repository you just created and uploaded files to, go to the "Settings" of the repository, and select "Pages."

• Scroll down and select the branch where your files are saved; this is usually the default branch called "main." Then proceed to select either "root" or "docs." If your files are simple and straightforward, choose "root." If you have a more complex collection of files, such as website files, source code, documentation, etc., choose "docs," as it is used for repositories with files stored in multiple folders. Save the changes.

• After completing the previous step, your website will begin to deploy. You can track the deployment progress by going back to the repository and clicking on the "three-dot horizontal menu," also popularly known as the "meatball menu (😅)," below the green "Code" button.

• After clicking the "three-dot menu," you'll see a yellow dot. Click it, and you'll be able to view the deployment progress. If the process was successful, the yellow dot will turn into a green checkmark, and you can now visit the website. If it wasn't successful, check section 1.1 to see what might have gone wrong.

• To get the web link, go to the "Settings" of that particular repository, select "Pages," scroll down, and you'll see the web link.

That's all you need to know about hosting your static website on GitHub 😇
