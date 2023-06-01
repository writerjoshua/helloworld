<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Blog</title>
    <meta name="description" content="This is my awesome blog.">
    <meta name="keywords" content="blog, articles, writing">
    <style>
        body {
            background-color: black;
            color: white;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        
        #header {
            background-color: gray;
            padding: 10px;
            display: flex;
            justify-content: space-between;
        }
        
        #logo {
            width: 100px;
            height: 100px;
        }
        
        #site-title {
            font-size: 24px;
        }
        
        #announcements {
            background-color: gray;
            padding: 10px;
        }
        
        #navigation {
            background-color: gray;
            padding: 10px;
        }
        
        #tag-cloud {
            background-color: gray;
            padding: 10px;
        }
        
        #recent-entries {
            padding: 10px;
        }
        
        #footer {
            background-color: gray;
            padding: 10px;
            text-align: center;
        }
        
        .menu-item {
            display: inline-block;
            margin-right: 10px;
        }
        
        .category {
            display: inline-block;
            margin-right: 5px;
        }
    </style>
</head>
<body>
    <div id="header">
        <img id="logo" src="logo.png" alt="Logo">
        <h1 id="site-title">My Blog</h1>
    </div>
    
    <div id="announcements">
        <h2>Announcements</h2>
        <p>Welcome to my blog! Check out the latest announcements and updates.</p>
    </div>
    
    <div id="navigation">
        <ul>
            <li class="menu-item"><a href="#">Home</a></li>
            <li class="menu-item"><a href="#">About</a></li>
            <li class="menu-item"><a href="#">Contact</a></li>
        </ul>
    </div>
    
    <div id="tag-cloud">
        <h2>Categories</h2>
        <span class="category">Technology</span>
        <span class="category">Fashion</span>
        <span class="category">Travel</span>
        <span class="category">Food</span>
        <span class="category">Lifestyle</span>
    </div>
    
    <div id="recent-entries">
        <h2>Recent Entries</h2>
        <ul>
            <li><a href="#">Post 1</a></li>
            <li><a href="#">Post 2</a></li>
            <li><a href="#">Post 3</a></li>
        </ul>
    </div>
    
    <div id="footer">
        &copy; 2023 My Blog. All rights reserved.
    </div>
</body>
</html>
