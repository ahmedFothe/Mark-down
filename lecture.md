### 01. What and Why Read.md?  ✅
Ans:- It shows the summary of project code 


### 02. How to make a comment? ✅ 
Ans:- You can use like HTMl style comment
      <!--Markdown comment -->

### 03. Normal text? and New line? ✅ 
Ans:- If you wirte, The write will execute window.  
Ans:- You have 2 option for using new line in markdown.  
       __1. Use double space.__   
        __2. Use break tag like HTML <br>__

### 04. Horizontal rule?  ✅
Ans:- Triple hipen use. (---)
---

### 05. headings?  ✅
Ans:- Use # symbol.
# Fothe Ahmed
## Fothe Ahmed
### Fothe Ahmed
#### Fothe Ahmed
##### Fothe Ahmed
###### Fothe Ahmed  

### 06. Paragraph?  ✅
Ans:- Use P tag like HTML.
<p>Hello brother, How are you?</p>

### 07. Italic?   ✅
Ans:- Use I tag like HTML Or Use under score between start and end.   
<i>Hello brother, How are you?</i>  
_Hello brother, How are you?_

### 08. Bold?  ✅
Ans:- Use B tag like HTML  Or Use double under score between start and end.  
<b>Hello brother, How are you?</b>  
__Hello brother, How are you?__

### 09. Strikethrough? ✅
Ans:- Use del tag like HTML  Or Use ~~ between start and end.  
<del>Hello brother, How are you?</del>   
~~Hello brother, How are you?~~  

### 10. Inline code block?  ✅ 
Ans:- Use ``   

` console.log("Hello Brother"); ` 

### 11. Multiple line code block?   ✅
Ans:- Use ```  
 
 ```html
 <!DOCTYPE html>
 <html>
    <head>
        <title>Web Title</title>
    </head>
    <body>
        <h1>What is your name?</h1>
        <p>Ans:- My name is Fothe Ahmed.</p>
    </body>
</html>

 ```


  ```css
 body{
    background-color: tomato;
    width: 100vw;
    height: 100vh;
    color: #fff;
    font-family: Arial;
 }
 p,h1{
    font-size: 1rem;
 }

 ```

### 12. List?  ✅
Ans:- There are 2 types of list. 
      1. order list,
      2. unorder list
      3. task list

#### 1. order list
Ans:- You use ol tag of HTML OR (number. space and write)
<ol>
<li>Apple</li>
    <ol>
    <li>Green</li>
    <li>Red</li>
    </ol>
<li>Mango</li>
    <ol>
    <li>Green</li>
    <li>Yellow</li>
    </ol>
<li>Banana</li>    
    <ol>
    <li>Green</li>
    <li>Yellow</li>
    </ol>
<li>Orange</li>
<li>Guava</li>
    </ol>
    

1. Apple
    1. Green
    2. Red
2. Mango
    1. Yellow
    2. Green
3. Banana
    1. Yellow
    2. Green
4. Orange
5. Guava


#### 2. unorder list
Ans:- You use ul tag of HTML OR - Use.

<ul>
<li>Apple</li>
    <ul>
    <li>Green</li>
    <li>Red</li>
    </ul>
<li>Mango</li>
    <ul>
    <li>Green</li>
    <li>Yellow</li>
    </ul>
<li>Banana</li>    
    <ul>
    <li>Green</li>
    <li>Yellow</li>
    </ul>
<li>Orange</li>
<li>Guava</li>
    </ul>


- Apple
   - Green
    - Red
- Mango
    - Yellow
    - Green
- Banana
    - Yellow
    - Green
- Orange
- Guava


#### 3. task list  
-[x] Task 1  
-[x] Task 2  
-[x] Task 3  
-[] Task 4  
-[] Task 5  

### 13. Link? ✅
Ans:- There are three types of link.  
    __1. automatic link__
    __2. Disable automatic link__
    __3. actually link markdown__

#### 1. Automatic Link
https://www.youtube.com

#### 2. Disable Automatic Link
` https://www.youtube.com `

#### 3. Actually Link Markdown
<!-- [Title](link) -->
<!-- 
[youtube](https://www.youtube.com)
[facebook](https://www.youtube.com)
[messengar](https://www.youtube.com)
[linkedin](https://www.youtube.com) 
-->


[youtube][youtubeLink]
[facebook][facebookLink]
[linkedin][linkedinLink]
[google][googleLink]

<!-- all link is here -->
[youtubeLink]: https://youtube.com
[facebookLink]: https://youtube.com
[linkedinLink]: https://youtube.com
[googleLink]: https://youtube.com


### 14. Image? ✅
<!-- ![alt text](source) -->
<!-- ![Profile](profile.jpg) -->
<img src="profile.jpg" width="200px" alt="Profile" title="Profile">


### 15. Emoji ✅
❤️❤️❤️


### 16. Table ✅

| Name | Email |
| ---- | ---- |
|Fothe | fothe@gmail.com |
|Ahmed | ahmed@gmail.com |
|Shafa | shafa@gmail.com |