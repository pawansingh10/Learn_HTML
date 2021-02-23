# HTML
***
Hypertext Markup Language
* Technology/Language used to create Webpages
* HTML Tags
* ".html" file Extension

 ## HTML Introduction
 ***
 __TEXT EDITOR__
Notepad vs VSCode

**hello.html**
```html
  <html>
  <head>
    <meta charset="UTF-8">
    <title>HTML</title>
  </head>
  <body>
        <h1>Hello WOrld!</h1>
        <p>Welcome To HTML Learning</p>
  </body>
  </html>
```

## HTML FILE
***
__Creating HTML File__
1. Create  a Folder __HTML__
2. Create a file __index.html__
3. ```html
   Hello World!
   ```
4. Basic Skeleton Of HTML File
  ```html
     <!DOCTYPE html>
     <html>
       
     </html>
   ```
HTML Document
<html></html>   Html Tag, Necessary for any html file
<head></head>    Data About the document, like title,discription,image,link etc
<body></body>
<p></p>           paragraph Tag, contains text
<title></title>   title Tag, conatin Title of website

__Browsers__
Browser is able to parse our websites and read the Tags & Figure out what is title, paragraph, image, link, heading, etc much more.

__Indentation, visually help us to decide the relationship between the TAGS__
__Parent Tag - Child Tag__

## HTML TAGS
***
Basic common HTML Tags:-
1. Meta Tag, a tag that define information  about our file.
   <meta charset="UTF-8">
   <meta name="description" content="This website do something for you">
   __Attributes or Properties__
2. Body Tag, All the stuff we see on the websites generally inside body tag
   ```
   <body>
   <h1> This is the Header</h2>  header tag, Header(h1,h2,h3,h4,h5,h6) of our website
   <p> This is paragraph</p>  paragraph tag, some text on websites
   <b> </b>   bold tag, style text as BOLD
   <i> </i>   itallic tag, style text as *itallic*
   <p> Welcome TO <b>HTML</b></p>
   <br/>  break tag, used for space
   <hr/> hrizontal role tag, basically give us a straight line that helps to seperate contents on websites
   <big> </big>
   <small> <small/> using big nad small tag we can controll our text size
   <sub> </sub> subscript tag H2O (Water)
   <sup> </sup> superscript tag 10^2 (100)
   </body>
   ```
   * **Order of Tags Matters in body Tag** The way we order tags, render by the browsers
   * **HTML doesn't care about white space** because it's only care out what is inside in their tags
   * **Single Tag** that has only one tag like <br/>, <hr/>
   
   ## HTML Comments
   ***
   
   - [x] **HTML Comments** are basically like Texts which is ignore by the Browers. 
   - [x] **Purpose of comments, Readability/Reminder of Code for ourself later or for others developers**
   - [x] ```<!-- 
           -->```
   > Note:- **COMMENTS, The best practice of Writing Code!** 
   
   ## Style & Color
   ***
   We can style HTML elements using **style** attributes through styling information\
   Basic Styling and set backround color to html elements
   ```
   <p style="color:blue;">  Applying color to paragraph.</p>
   
   <p style="background-color:red;">  Setting Background color</p>
   
   <body style="color:red;">   </body>
   
   <h1 style="background-color:lightblue;">Our Websites</h1>
   ```
   
   > **Styling HTML, We learn CSS Cascading Style Sheet later on.**
   
   | Color Name | Hex   |
   |------------|-------|
   | Black | #000000|
   | White | #ffffff|
   
   [Learn HTML](https://www.w3schools.com/html/ "link")
   
   
   ## Formatting a Page
   ***
   
   Using various HTML Tags  to Layout the Structure  of Website
   
   > **Using Right tags at Right Place is Important.**
   
   - [x] 1. __Header__ || Every websites has a header like **Website Name, Logo, Navigation Menu, Links**
   - [x] 2. __Main Section__ || Back-Bone, All the contents like **Article, Sections, Images** 
   - [x] 3. __Footer__ || Websites has also a footer like **Navigation link, Copyright Info, Social-Media links**
   
   
   **HTML has tags used to define all of these Header, Main and Footer**
   ***
   ```
      <body>
          <header>
                 <nav>
                       <!-- Naviagational Link, Naviagtional List Navigational Image/Logo-->
                       
                 </nav>
          </header>
          
          <main>
                <article>
                     <section>
                          <h2></h2>     
                     </section>
                     <section>
                          <aside>
                              <!-- Thhis content is on the page & getting shown to the users but it's not directly related to core content-->
                          </aside>
                     </section>
                </article>
          
          </main>
         
          <footer>
         
          </footer>
         
      </body>
   ```
   ***
   * **Side Tag**, basically a tag that does not directly related to main content of webpage
     Example- **Advertisement** like google adsense
   ***
   
  **Advantages of Using the Specific HTMl Tags**
  
  * Look and Feel
  * separate Section of websites.
  * Organised Code for anyone from the Organization use it.
  * Readability, easy to read the file
  * Structure the skeleton of website
  * Search Engine Optimization, when we use these html tags google could easily going to our file and figure-out where are the different sections.\
    Google can use this information to display website better.

  > **Search Engine Optimization**, basically how your websites is viewed by a search engines.
    Like Google
  > **Don't Ingnore the power of HTML Tags**
  
   Best Practice to define tag hierarchy
   ```
      h1
           h2
              h3
                 h4
                     h5
                       h6 h6
                     h5
                 h4
             h3
         h2
      h1
   ```
   
## Links
***
Using Links in HTML
* A Link is one of the most popular HTML Element, used to link a website to another website on the Intenet
Example- google.com
         linkedin.com
         another page of our own website
* Links are also used to link Navigational List, images, pdf etc

```
   <a href="https://www.google.com"> Google Home Page</a>
```

* When you do not want to redirect on that given link and open it up in new tab
```
<a href="https://www.google.com" target="_blank"> Google </a>
```
> Websites are not of a single webpage, Every websites has a number of webpages.

* Link to another pages of our websites
  Like: index.html
        contact.html
        about.html
        page2.html
 ```
   <a href="about.html"> About Us </a>
 ```
 **Here we only mention the file name because browsers already know this file is in the same directory.**
 
 ## Images
 ***
 Using Images on websites, basics of working with Images
 * Resizing Images
 * Placing on our HTML Pages
 __Image Tag___
 ```
      <img src="https://www.abc.com/a.png" alt="Alter of Img" />
 ```
 * One common problem with images are thier size differ, so we can resize Images.
 ```
      <img width="100" height="100" src="dice.png" alter="Dice Image"/>
 ```
 > **px, pixel is a unit of measurement of size depending on the resolution of the screen.**
 
 > __Note In addtion to both the width and height, we can set either height or width. By setting anyone of them HTML automatically adjust the aspect ration of height and width.__
  
  * __We can combine our images to a link__
  ```
     <a href="https://www.google.com">
        <img width="100" height="100" src="dice.png" alter="Dice Image Link"/>
     </a>
  ```
  
  ## Videos and YouTube iFrames
  ***
  Using **Videos from your device** + **Youtube Videos** on wensites
  
  ### Local Videos
     Working with file introduction.mp4
    ```
       <body>
           <video src="introduction.mp4"> introduction </video>
       </body>
    ```
  * Make video playable using **controls** property
     ```
          <video src="introduction.mp4" controls> introduction </video>
     ```
  * **Resize the frame of video using  height and width attributes**
    > ```
    >    <video width="300" height="200" src="introduction.mp4" controls> Introduction </video>
    > ```
  
  * We can add **Thumbnail/poster** to our video using **poster** attribute
    > ```
    >    <video width="300" height="200" src="introduction.mp4" poster="thumbnail.png" controls> Introduction </video>
    > ```
    
  * **Autoplay** **loopinging** video using **autoplay** , **loop** attributes respectively
    > ```
    >    <video width="300" height="200" src="introduction.mp4" poster="thumbnail.png" autoplay controls> Introduction </video>
    > ```
  
  ### YouTube Videos
   * Open any youtube video
       * Go to share option
       * clicked on Embed
       * copy iframe code        
                 
  ![ScreenShot1](youtube.png)
 
  ![Screenshot2](youtube2.png)
  
 ```
     <body>
           <iframe width="560" height="315" src="https://www.youtube.com/embed/khcxA7U_HsY" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen>
           </iframe>
     </body>
 ```
 
 ## Lists in HTML
 ***
 Creating List in HTML, using different tags
 * **ul**  unordered List
    ``` 
      <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
      </ul>
    ```
    > We can add more functionality to our lists
    ```
      <li><a href="#">HTML</a></li>
      <li><a href="#">CSS</a></li>
      <li><a href="#">JavaScript</a></li>
    ```
 * **ol**  ordered list
    ```
      <ol>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
      </ol>
    ```
    > We can give the types of numbering either 1 2 3 or A B C or a b c or i ii iii or I II III etc using **type** attribute
     ```
       <ol type="a">
          <li><a href="#">HTML</a></li>
          <li>CSS</li>
          <li>JavaScript</li>
      </ol>
     ```
     > We can make it nested also
     ```
           <li> Country
               <ol>
                  <li>India</li>
                  <li>USA</li>
                  <li>China</li>
               </ol>
           </li>
     ```
  * **dl**   discription list
     Not popular, but if you want use where lists need discription
     * Country
        * India
           * It is a democratic country
        * USA
           * It is a democratic country
        * China
           * It is a communist country
      ```
      <dl>
        <dt>Discription Term</dt>
        <dd> -- Discribe the Discription</dd>
      </dl>
      ```
      
   ## Tables in HTML
   ***
   * HTML provides us to display contents in the Tabular forms to the users by using differents tag
   * **table**  table
   * **caption** caption of the table
   * **th** table header
   * **tr**  table row  (horizontal)
   * **td**  table data (vertical)
  
        
   | Roll No| Name | Class|
   |--------|------|------|
   | 1      | Abc  | X    |
   | 2      | Def  | XI   |
   | 3      | Ghi  | XII  |
   
   ```
      <table>
          <thead>
             <caption> List of Items </caption>
             <tr>
                <th> Col 1 </th>
                <th> Col 2 </th>
                <th> Col 3 </th>
              </tr>
           </thead>
           <tbody>
               <tr>
                 <td> One </td>
                 <td> Two </td>
                 <td> Three </td>
               </tr>
               <tr>
                 <td> Four </td>
                 <td> Five </td>
                 <td> Six </td>
               </tr>
               <tr>
                 <td> Seven </td>
                 <td> Eight </td>
                < td> Nine </td>
              </tr>
          </tbody> 
      </table>
   ```
   > **Tables are responsive or resizable or flexible to the screen**
   
   * For Readability of code, we can use **thead** and **tbody**
   * **colspan** attribute
   ```
       <td colspan="2">one</td>
   ```
   
   
   ## Divs and Spans in HTML
   ***
   * **Container** in HTML, basically a set of Tags that wraps up bunch of another tags.
   * Generally While write HTML is recommended or good to wrap tags, because when we go to advance HTML we need this.
   * Like CSS styling the element, your Wrapper tags only requires changes not all inside tags to be change
   * Popular Container **div** and **span**
   ###### Difference between div and span
   **Two basic ways to display element**
   1.**Block**
   2.**Inline
  
   > **Block Element**, that take **entire width** of the page
   ```
      <p>Paragraph1</p>
      <p>Paragraph2</p>
   ```
   These are block HTML element
   
   > **Inline Element**, that take **only that much need**
   ```
      <a href="#">Link1</a>
      <a href="#">Link2</a>   
   ```
   These are inline css element
   
   * **Note : spans are inline container while divs are block container**
   
    ```html
         <span> span1 </span>
         <span> span1 </span>
         <div> Div1 </div>
         <div> Div2 </div> 
     ```
     
  > **Styling HTML using span while Learning CSS**
  
  ## Input and Forms in HTML
  ***
  Using Input tag in HTML,basically use to take input from user.
  Use for Interaction with user
  * **TextBox**
  * **TextArea**
  * **CheckBox**
  * **RadioButton**
  
  > **Note : Defining HTML Tags doesn't means It's Functional**
  
- [x] In order to get information from the user through these textboxes we need a language called **JavaScript**
  
  ```
     <input type="text" />
     <input type="password" />
     
  ```
  * Giving default value to input tag
  ```
     <input type="text" value="Enter name"/>
     <input type="password" value="Enter password" />
  ```
  * **text, password, number, date, email, range, file, checkbox, radiobutton etc**
  * TextArea
  ```
      <textarea rows="5" cols="7">
             Enter a paragraph
      </textarea>
  ```
  * Radiobutton
  ```
     <input name="btn" type="radio" />
     <input name="btn" type="radio" />  
  ```
  * Submit 
  ```
     <input name="btn" type="submit" />
  ```
  ###### Form
  Form is basically used to store all the inputs.
  ```
      <form>
           <input type="text" />
      </form>
  ```
