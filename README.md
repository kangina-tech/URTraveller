This is the first website I have created.

Key things to note:
- No tutorial was followed
- It is a continuous project i.e., I will be building on it as time progresses.

The languages being used are:
- HTML, CSS and JavaScript

The framework I will reach out to:
- React

(08.01.24 - 12.01.24)
Language:
HTML and CSS

A couple of problems I encountered
- The navbar CSS.
      The intial stress had been adding in the CSS. The navbar seemed to not take in the background colour assigned. This was solved by using even more specific nested classes than     using the overall nav indicator. 

    '''<nav class="navbar">
        <ul>
            <a href="#" class="logo">URTraveller</a>
            <li href="#">Blog</li>
            <li href="#">About</li>
            <li href="#">Contact</li>
        </ul>
    </nav>

    .navbar {
        display: inline;
        width: 100%;
        height: 100vh;
    }
    .navbar ul {
        background-color: black;
        padding: 30px;
        margin: 0;
        width: 100%;
        position: sticky;
        z-index: 100;
        top: 0;
    }  

- Creating space between images in the right column
        As of the moment of noting this, I seem to be unable to create space by either padding or margin because the color overlay stretches out leaving the image behind. I have tried         to solve this problem in the same way I have the navbar but it is not working. All the nested classes work about the same. 

- Creating hover effect on images
        I am working under the assumption that the same problem encounters in the previous comment is at fault. 
