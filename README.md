# Front End Development - Brainnest Training Program

## Week 1 - HTML Project

### According to the 4. Assignment(Main HTML project): 
For presentation make a few page presentation website about your hobby/favorite books/movies etc. Your website should contain a homepage with a link to go inside to the page where your material should be presented in list form, with links leading to pages with the description(text & image) of your chosen subject. As an added bonus, you can make each list element into a link, leading to the page where additional information about said subject can be found(images are always welcomed, just don't over do it :D)

## <a href="https://fabiolpgomes.github.io/Training_Brainnest_Html/" target="_blank">HTML Project</a>


### Overview Pages
![Pageview homepage](https://user-images.githubusercontent.com/99607827/204093201-17e80bbb-3d7b-4434-a3ea-f5ea4bd7da92.png)

![aboutpageview](https://user-images.githubusercontent.com/99607827/204093253-02abe832-8d05-4184-ac2c-85d1cc9c38b2.png)

![image](https://user-images.githubusercontent.com/99607827/204093281-110b6394-984e-4b36-9afd-01b9faf8ee70.png)


**3. Assignment(Links & Images):**
a. Create a new directory named **links-and-images**

b. Within that directory, create a new file named **index.html**

c. Fill in the usual **HTML boilerplate**

d. Set the title to **_“Links & Images”_**

e. Finally, add the following **h1** to the body: `<h1>`Homepage`</h1>`

f. Create another HTML file named about.html
g. Back in the index page, add the following anchor element below the `<h1>` element: `<a` href=”https://theuselessweb.com/”>click me `</a>`
`<a` href="about.html">About`</a>`

h. Open the index file in a browser and click on the **About** link to make sure it is all wired together correctly. Clicking the link should go to the empty about page you just created (you can fill it in if you like)

i. Create a directory named **pages** within the **links-and-images** directory and move the **about.html** file into this new directory. Refresh the index page in the browser and then click on the about link. It will now be broken. This is because the location of the **About** page file has changed. To fix this, you just need to update the about link **href** value to include the **pages** directory since that is the new location of the about file relative to the index file. `<a href="./pages/about.html">About</a>`

j. In many cases, this will work just fine; however, you can still run into unexpected issues with this approach. Prepending ./ before the link will in most cases prevent such issues. By adding ./ you are specifying to your code that it should start looking for the file/directory relative to the current directory. You can also add a link to get back from the **About** page to your homepage

k. To use images on your own websites, you can use a relative path:

i.Create a new directory named **images** within the links-and-images project

ii. Next, download any image **.jpg/.png** and move it into the images
directory you just created

iii. Rename the image to **first-img.jpg/.png**

iv. Add the image to the index.html file:
`<img` src="images/first-img.jpg">

v. Save the **index.html** file and open it in a browser to view your image in all its glory. **Remember** to use ./ before the **images/first-img.jpg** if your image isn’t loading

l. As a bit of practice, add an alt attribute to the first-img you added to the **links-and-images** project.

[favoritesmoviespage](https://user-images.githubusercontent.com/99607827/204093300-193dcc86-b751-4fa6-8811-526df8d0cff3.png)


#### Repository created to run the proposed exercises

## Built With

<code>
  <img align="center" alt="Ane-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
</code>  

## What benefits will you gain?

### Participants will receive the best possible practical training with the prospects of a job. This is the purpose of the whole program. Some of the benefits you will gain from this practicum program are listed below:

* Priority to be selected for a full-time, part-time, or contractor osition at Brainnest or the companies we work with (90% of our recruitments are internal);
* Business certificate from Brainnest – German consulting company;
* Reference/recommendation letter from your training tutor;
* Working on business cases based on current or past Brainnest projects;
* Lectures given by experienced industry professionals;
* Close supervision and orientation from your mentor;
* Working an average of one to two hours per day with a flexible schedule;
* Fully remote positions with access to online tools and platforms;
* Unlocking your potentials and getting prepared to be hired right away;
* Professional business training, guidance, and experience;
* Having your work criticized,assessed, and corrected;
* Professional projects experience to put on your CV.

#### The training program consists of four weeks.





