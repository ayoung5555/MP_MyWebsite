***
## Contents
- Tutorial without a code editor
	- [Getting Started](#getting-started-without-a-code-editor-like-vscode-xcode-etc)
	- [Removing Buttons & Content](#removing-buttons--content-twitter)
	- [Editing Links 1](#editing-links-email)
	- [Editing Links 2](#editing-links-external-website)
	- [Adding Content](#adding-content-bullet-points)
	- [Editing Content](#editing-content-resume)
- Tutorial with a code editor
	- [Getting Started](#getting-started-with-a-code-editor-like-vscode-xcode-etc)
	- [Removing Buttons & Content](#removing-buttons--content-twitter-1)
	- [Editing Links 1](#editing-links-email-1)
	- [Editing Links 2](#editing-links-external-website-1)
	- [Adding Content](#adding-content-bullet-points-1)
	- [Editing Content](#editing-content-resume-1)
- Publishing your website for free
	- [GitHub Pages](#using-github-pages)
	- incomplete section

***
# Getting Started *without* a code editor like VSCode, XCode, etc

1. Create an easily accessible folder in your Documents folder or Desktop
2. Navigate to [https://brackets.io](brackets.io)
	- Launch web editor
3. Import project - Github project
	- Paste link to ayoung5555.github.io git repo
	- Import the folder you created in step 1
4. Click trust/accept/execute
5. On the left side file explorer, click on index.html
	- A preview should appear
6. To simplify the interface, toggle the triangle to the right of line number 19
    - This is the line that starts with `<svg xmlns...`
    - This hides the code used to show the contact/social media icons
7. In the menu at the top (File/Edit/Find/View/Navigate/Debug/Help)
	- Navigate to Find and click Find
	- Note that you can use CTRL + F or COMMAND + F as a shortcut
8. Once the Find popup has opened, type in EDITME
	- This will highlight all the places that you should make changes!
9. Don’t edit blue, green, or orange text unless you are familiar with HTML
	- Instructions on what to modify continue below
10. Let's move on modifying bigger parts of the HTML first!

## Removing Buttons & Content (Twitter):


1. As an example, let's remove the link to Twitter
    
2. Navigate to “EDITME Contact Information”
	- You can use CTRL+F or Command+F
    
3. Note that one of the buttons (should be button 2) contains the text “Twitter/X”
    
	- To remove this button from the webpage, delete the HTML between the comment that says BUTTON 2 and BUTTON 3.![](https://lh7-us.googleusercontent.com/l7ThuXvYWcPi2cSQuiZvhCLoevKcMoyLh1aIKDBcSr2-CVLZiPu26AK7oLF0d8GPeHaidVaccsMJ8VTmlwb0QuBYYhKxa_m-XB3GNnJFOJkveUyOrYris8vEWv6oFbwybu9G2Uzgtuy-FfUVdDMaf3E)
    
4. Now, click the refresh button above the preview window to see your changes:  
    ![](https://lh7-us.googleusercontent.com/R10L54BKi8VOVb8gTluLhHc857-NJzWEshvZ7QEo6WZKns5gR0snIHqlSIKr8UQo9wTwJ6iJosKusOt1d7_-5jenNeznL6XHQy2n_BemGLIHw5Byy4K6IHDr5yfAuxqKpw8MACp-54iJ0DVgPt1MxN8)
5. If the Twitter button is gone, then you've done this part correctly!
6. Feel free to remove any other buttons you don't want to be on your website, like the Phone button or Instagram button.

## Editing Links (Email):

1. Now, let’s update the email to the correct email. 
2. Below the BUTTON 1 comment, replace the text "[mailto:user@domain.ext](mailto:user@domain.ext)" with your email. Don’t forget to keep the `mailto:` and quotes there.
	- If a lot of text turns red, then you may have accidentally deleted a quote or another symbol. To undo, use the Control+Z or Command+Z shortcut.

## Editing Links (External Website):

1. Now, let’s update the LinkedIn link. 
2. Below the BUTTON 4 comment, replace the text "https://domain.ext/path" with your LinkedIn URL. Don’t forget to keep the quotes and include `https://`.
3. You can repeat this to update the links for the other buttons.

## Adding Content (Bullet Points)

1. Now, we'll add additional content: Another bullet point to the 'Recent Work' section
	- You can update this website anytime, so if you want to add another bullet point in a few months, this explains how to do it
2. Scroll up to 'EDITME Recent Work'
3. There are 3 bullet points. Copy and paste the HTML structure of the 3rd bullet point (Everything from `<li>` to `</li>`, including them) to create a 4th bullet point (below the 3rd `</li>)`![](https://lh7-us.googleusercontent.com/2RG0ejv3qwNw7aB0-I8sfmyP67TOsmXfWZmDIov-FjASY5MegmUO751Me_rHpzP4ygikeui69M3z01ov1gsCSGxmQRltd13CSkDXEM7lRoWtlJJuIfdo6jpTw5pv8eVZxX82nysAnvgYbMatF6zy-F4)
4. Click the refresh button above the preview window to see these changes
5. Note how the additional bullet point on the webpage is below the rest, just like where you pasted in the HTML. If you want a bullet point to come before the other bullet points on the webpage, it needs to go before them in the HTML.

## Editing Content (Resume)

1. Scroll to the About section 'EDITME About Section'
2. Let's add your resume to the website. 
3. First, on the left-hand side file explorer, click the assets folder to open it.
4. Right click and delete `resume.pdf`
5. In the folder you created on your computer at the beginning, add a copy of your resume in pdf form to the assets folder contained within it.
	- Make sure the filename for your resume has no spaces. To save time, name it `resume.pdf`.
	- Before you upload this website, remove any personal information on your resume (like an address) that you don't want the world to see.
6. Once you've added your resume to the assets folder, return to your browser
7. On the file explorer on the left-hand side, right click to open the context menu.
8. At the bottom of the context menu, click the option to 'Refresh File Tree'. This may take a few seconds, but you should confirm that your resume is in the assets folder.
9. There is already a link to the resume in the About section 'EDITME About Section' but if you wish to insert your resume elsewhere, here is the HTML (assuming you named your resume `resume.pdf`).
   `<a href="assets/resume.pdf">EDITME TEXT HERE</a>`
10. Note that clicking links in the online editor might not work, but it will when you publish the webpage. To verify that your links are correct, you can open the folder from your desktop/documents folder and open `index.html` in a web browser. All the links should now function correctly, but if you make changes they won't refresh immediately.

Continue to the '[[#Publishing your website for free]]' section

***

# Getting Started *with* a code editor like VSCode, XCode, etc
 
These steps are slightly more condensed because they assume knowledge of basic functions of an IDE.

1. Create a project folder on your computer
2. Do not simply clone [this repo](https://github.com/ayoung5555/ayoung5555.github.io.git):
	- Instead, select 'Download ZIP' under the green 'Code' dropdown button
	- This is so you do not have to deal with changing the git remote settings and will save you time
	- Unzip the folder into your project folder
3. Open your IDE and open the index.html file
4. To simplify things, minify the code block on line 19
    - This is the line that starts with `<svg xmlns...`
    - This hides the code used to show the contact/social media icons
5. Do a Control+F or Command+F search for 'EDITME'
	- This will highlight all the places that you should make changes before you upload.
6. Let's move on modifying bigger parts of the HTML!

## Removing Buttons & Content (Twitter):


1. As an example, let's remove the link to Twitter
    
2. Navigate to “EDITME Contact Information”
	- You can use CTRL+F or Command+F
    
3. Note that one of the buttons (should be button 2) contains the text “Twitter/X”
    
	- To remove this button from the webpage, delete the HTML between the comment that says BUTTON 2 and BUTTON 3.![](https://lh7-us.googleusercontent.com/l7ThuXvYWcPi2cSQuiZvhCLoevKcMoyLh1aIKDBcSr2-CVLZiPu26AK7oLF0d8GPeHaidVaccsMJ8VTmlwb0QuBYYhKxa_m-XB3GNnJFOJkveUyOrYris8vEWv6oFbwybu9G2Uzgtuy-FfUVdDMaf3E)
    
4. Save the file, and open `index.html` in a browser.
5. If the Twitter button is gone, then you've done this part correctly!
6. Feel free to remove any other buttons you don't want to be on your website, like the Phone button or Instagram button. Note that unless you have a live preview extension like [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms.vscode.live-server)(highly recommend), you will have to save and refresh the page every time you want to see a change.

## Editing Links (Email):

1. Now, let’s update the email to the correct email. 
2. Below the BUTTON 1 comment, replace the text "[mailto:user@domain.ext](mailto:user@domain.ext)" with your email. Don’t forget to keep the `mailto:` and quotes there.
	- Be careful not to accidentally delete a quote or another symbol. To undo, use the Control+Z or Command+Z shortcut.

## Editing Links (External Website):

1. Now, let’s update the LinkedIn link. 
2. Below the BUTTON 4 comment, replace the text "https://domain.ext/path" with your LinkedIn URL. Don’t forget to keep the quotes and include `https://`.
3. You can repeat this to update the links for the other buttons.

## Adding Content (Bullet Points)

1. Now, we'll add additional content: Another bullet point to the 'Recent Work' section
	- You can update this website anytime, so if you want to add another bullet point in a few months, this explains how to do it.
2. Scroll up to 'EDITME Recent Work'
3. There are 3 bullet points. Copy and paste the HTML structure of the 3rd bullet point (Everything from `<li>` to `</li>`, including them) to create a 4th bullet point (below the 3rd `</li>)`![](https://lh7-us.googleusercontent.com/2RG0ejv3qwNw7aB0-I8sfmyP67TOsmXfWZmDIov-FjASY5MegmUO751Me_rHpzP4ygikeui69M3z01ov1gsCSGxmQRltd13CSkDXEM7lRoWtlJJuIfdo6jpTw5pv8eVZxX82nysAnvgYbMatF6zy-F4)
4. Click the refresh button above the preview window to see these changes
5. Note how the additional bullet point on the webpage is below the rest, just like where you pasted in the HTML. If you want a bullet point to come before the other bullet points on the webpage, it needs to go before them in the HTML.

## Editing Content (Resume)

1. Scroll to the About section 'EDITME About Section'
2. Let's add your resume (or any other local file on your computer) to the website. 
3. In the file explorer, delete `resume.pdf`
4. In the `assets` folder, add a copy of your resume in pdf form.
	- VS Code supports file drag and drop, idk about xcode or others.
	- Make sure the filename for your resume has no spaces. To save time, name it `resume.pdf`.
	- Before you upload this website, remove any personal information on your resume (like an address) that you don't want the world to see.
5. Once you've added your resume to the assets folder, return to your code editor
6. There is already a link to the resume in the About section 'EDITME About Section' but if you wish to insert your resume elsewhere, here is the HTML (assuming you named your resume `resume.pdf`).
     `<a href="assets/resume.pdf">EDITME TEXT HERE</a>`
7. To verify that your links are correct, you can open `index.html` in a web browser. All the links you've edited should now function correctly. Also verify that `index.html` is saved and then refresh your browser if something isn't updated.

***

# Publishing your website for free
INCOMPLETE - IGNORE THIS FOR NOW

## Using GitHub Pages
1. Create a [GitHub](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E&source=header-repo&source_repo=ayoung5555%2Fayoung5555.github.io) account if you don't already have one
	- Make your username close to your real name: your username is the start of your website URL
2. If you are familiar with creating a repo from the command line or your IDE, skip ahead to step X, otherwise continue on the GitHub website.
3. In the top right hand corner, click the `+` icon and the 'New Repository' link
4. Name your repository 'username.github.io'
   ![](https://lh7-us.googleusercontent.com/Oxfs19CQs7UHo94_PkEpbk_nm9Ju6_Yu8lvqW32CnXaOG_TtJA13Y-Tl1Zz2OzvSzD340U3iNszB60Q3qAgGoI8EvKldBIXYTJwguFcujIJ4BI5Ow0lMBslctNiq3akgBjcJC8vuIQtzFNBf5wmwMbU)
5. Leave it on public settings for now. To change it to private, you must have GitHub Pro which can be unlocked for free by adding your school email and registering [here](https://education.github.com/discount_requests/application). Approval may take a few days.
6. Ignore the other settings and 'Create repository'
7. Click the link to 'upload an existing file'   ![](https://lh7-us.googleusercontent.com/-VjpL7s2a__HIp06VGJMyaIIF-DWpM-lmqyVXWdLTfzTPY02RODA7cfbSxgN_DrvkNWTjo-Yxcn_iro4dZz40_Oy5WtuZPFe3veS8T69SzbQKJjMZmvT5giqCDRY-HmRSCzuDWBPB4Og3AB6x7V51KE)
8. On the next page, click choose your files and navigate to the folder you originally created in step 1. Select ALL the files and folders within the folder that you created (including `assets` and `index.html`) and upload them
9. Wait for GitHub to finish uploading them, then scroll down and click the green "Commit changes" button
10. Once it's finished, navigate to the repository settings:
    ![](https://lh7-us.googleusercontent.com/O7ObxMfWQkYl_tZo9tfX7zx9-t6NFGtwEhlm_ArdnSPD6_gtF4itmT4ZXHNZhApk_dK42jXB5pi4js8KV-S1LsGlRBIMEy01_5PBCcIREHsaO4heH-DXN3AmDRF9QzQJRU-oUCCXSprLR8aMTXMl5B8)
11. On the left side, in the 'Code and automation' category, go to the 'Pages' section
