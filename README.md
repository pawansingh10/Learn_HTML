# HTML
Hypertext Markup Language
* Technology/Language used to create Webpages
* HTML Tags
* ".html" file Extension

 ## HTML Introduction
 
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
   
   - [x] **HTML Comments** are basically like Texts which is ignore by the Browers. 
   - [x] **Purpose of comments, Readability/Reminder of Code for ourself later or for others developers**
   - [x] ```<!-- 
           -->```
   > Note:- **COMMENTS, The best practice of Writing Code!** 
   
   ## Style & Color
   We can style HTML elements using **style** attributes through styling information\
   Basic Styling and set backround color to html elements
   ```
   <p style="color:blue;">  Applying color to paragraph.</p>
   
   <p style="background-color:red;">  Setting Background color</p>
   
   <body style="color:red;">   </body>
   
   <h1 style="background-color:lightblue;">Our Websites</h1>
   ```
   
   > **Styling HTML, We learn CSS Cascading Style Sheet later on.**
   
   | Color Name | Hex |
   |--- ---|--- ---|
   | Black | #000000|
   
   [Learn HTML](https://www.w3schools.com/html/ "link")
   
   
   
   
