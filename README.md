# user-friendly marketing website

This project is written in order to refactor the code of an existing website. The goal was to have a website which follows the accessiblity standards in order to be optimized for search engines and more accessible for the people with disabilities.


<br>
In order to achieve this goal, I took the following steps:

1. fixed the error of the site

2. changed the source code in order to have the semantic elements instead of non-semantic ones

3. changed the structure of the html elements to follow a logical structure

4. added alt attribute to all images to be accessible for people with disability, and to be shown when the browser does not show the original image

5. defined a unique and descriptive caption to help users understand the page's content and purpose

6. consolidated CSS selectors and properties to follow a semantic structure

<br>

## About Website

---------------------------------

Nowadays, the importance of online sales is crystal clear for everyone. This website defines the different ways that marketing companies can enhance their sales via internet and social media.

<br>

<br>


## Mock-up

---------------------------------

![image] ()

<br>

<br>


## Examples of those parts of the html code that have been changed

---------------------------------

1. The ```<div class="header">``` had substituted with the semantic elements of ```<header>``` and the same thing applied for replacing ```<div>``` with ```<nav>``` for navigation bar.

    **The original code:**

    ```<div class="header">
            <h1>Hori<span class="seo">seo</span>n</h1>
            <div>
                <ul>
                    <li>
                        <a href="#search-engine-optimization">Search Engine Optimization</a>
                    </li>
                    <li>
                        <a href="#online-reputation-management">Online Reputation Management</a>
                    </li>
                    <li>
                        <a href="#social-media-marketing">Social Media Marketing</a>
                    </li>
                </ul>
            </div>
        </div>
    ```

    **The changed code:**

    ```<header>
            <h1>Hori<span class="seo">seo</span>n</h1>
            <!--change div to nav-->
            <nav>
                <ul>
                    <li>
                        <a href="#search-engine-optimization">Search Engine Optimization</a>
                    </li>
                    <li>
                        <a href="#online-reputation-management">Online Reputation Management</a>
                    </li>
                    <li>
                        <a href="#social-media-marketing">Social Media Marketing</a>
                    </li>
                </ul>
            </nav>
        </header>
    ```

2. The property of ```<alt>``` was added to all image parts to provide more accessibility.

    **The original code:**

        ```<img src="./assets/images/search-engine-optimization.jpg" class="float-left" />```

    **The changed code:**
        
        ```<img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="search engine optimization image"/>```

<br>

<br>


## One example of those parts of the CSS code that have been changed

---------------------------------

I  gave a single name to the classes which had the same styling properties and values in html file and I unified the related code of CSS file to avoid repitition. 

**The original code**
```.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

<br>

**The changed code**

```.benefit-topics {
    margin-bottom: 32px;
}

h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-topics img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

<br>

<br>

## The link of deployed site

---------------------------------

[user-friendly-marketing-website]()

<br>

<br>

## Credits

---------------------------------

Bahareh Hosseini

Github page:      [https://github.com/Bhmerir](https://github.com/Bhmerir)

<br>

<br>

## License

---------------------------------

Licensed under the MIT license.
