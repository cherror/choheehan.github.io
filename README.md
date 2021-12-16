# Hello, This is choheehan.github.io!!

***

### *How to Build UP*
> 1. Produce **Repository**
> 2. Install **Jekyll**
> 3. Apply the **theme**
> 4. **Edit themes** and **write posts**
> 5. Edit **favicon**
> 6. Implement the **comment function**
> 7. Add **Google Analytics**

***

### *Produce Repository*
> 1. Create a github **account**
> 2. Create 'Repository **<username.github.io>**' ex. ***<choheehan.github.io>***

***

### *Install Jekyll*
> Ruby installation site : https://rubyinstaller.org/downloads/
> 1. Download **Ruby for Windows + DevKit** program
> 2. Install **Jekyll bundle** through ```gem install Jekyll bundler```
> 3. **Check** if it's installed normally through ```jekyll -v```
> 4. Create a **new blog file** inside the directory through ```jekyll new .```
> 5. Implement Jekyll through ```jekull serve```

***

### *Apply the Theme*
> Jekyll Themes Site
>> : http://jekyllthemes.org/
>> : https://jekyllthemes.io/free
>
> 1. **Download** your favorite
> 2. **Copy and overwrite** all internal files on **<choheehan.github.io>**

***

### *Edit themes and write posts*
> 1. Change the title of the page by modifying **title of \_config.yml**
> 2. **Navigation**, **social** parts are also modified appropriately
> 3. **Remove unnecessary headers** from header file in the \_includes folder
> 4. **Replace** with my github and velog
> 5. Write in **html format** in each post file
> 6. **Put the created post files** in the \_post folder
> 7. Photos used in the \_post configuration are **included in the assets/img folder**
> 8. Modify the style.css of the asset/css folder to **adjust the design and placement** of several posts

***

### *Edit favicon*
> 1. Find the picture you want, and change it to **.ico**
> 2. **Change the file name** to "favicon"
> 3. Put it in the assets/img and **replace** it with the existing one

***

### *Implement the comment function*
> Disqus Subscribe site : https://disqus.com/
> 1. Select **"I want to install Disqus on my site"**
> 2. Write **Website name** *(REMEMBER it!!!)*
> 3. Set the category to **Tech**
> 4. Click **Create Site**
> 5. Select **Basic**, click the **Subscribe Now** at the bottom
> 6. Select **Jekyll**
> 7. Click **configure** button
> 8. Enter **Website name**, **Website URL**
> 9. Select **Balanced**
> 10. Click **Complete Setup**
> 11. Click **Admin** at the top of Disqus Home
> 12. Click **installing Disqus**
> 13. Click **Universal Embedded Code**
> 14. Modify **\_config.yml** file
> ```google_analytics: "UA-215461057-1"
> comment:
>   provider: "disqus"
>   disqus:
>     shortname: "choheehan"
> ```
> 15. Open \_layouts/post.html and paste the **copied code** *(could be different for each theme!!)*
> 16. Add ```comments: true``` to the post that you want to add the comment function to

***

### *Add Google Analytics*
>
