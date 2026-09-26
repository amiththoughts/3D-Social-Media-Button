# 3D-Social-Media-Button
Learn how to create 3D Social Media Buttons with Hover Effects using HTML and CSS! 🚀 In this quick and easy tutorial, you’ll learn how to design modern and attractive social media buttons with 3D effects, smooth hover animations, and CSS transitions.

![image alt](https://github.com/amiththoughts/3D-Social-Media-Button/blob/e26a19c16068e4e0eee76fbc09574121fe9a34e8/Social.png)

# HTML Program
      <!DOCTYPE html>
      <html lang="en">
        <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, inital-scale=1.0">
         <title> Amith Thoughts | Social Circle 3D button effect </title>
         <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" />
         <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <ul>
            <li><a href="#"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
            <li><a href="#"><i class="fa fa-youtube" aria-hidden="true"></i></a></li>
            <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
            <li><a href="#"><i class="fa fa-google-plus" aria-hidden="true"></i></a></li>
            <li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
        </ul>
      </body>
      </html>

  # CSS Program
      body {
      margin: 0;
      padding: 0;
      background-color: #fff;
      }

      ul {
       position: absolute;
       top: 50%;
       left: 50%;
       transform: translate(-50%, -50%);
       display: flex;
       margin: 0;
       padding: 0;
     }

     ul li {
       list-style: none;
     }

     ul li a {
      position: relative;
      width: 60px;
      height: 60px;
      display: block;
      text-align: center;
      margin: 0 10px;
      border-radius: 50%;
      padding: 6px;
      box-sizing: border-box;
      text-decoration: none;
      box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3);
      background: linear-gradient(0deg, #dddddd, #ffffff);
      transition: 0.5s;
     } 

      ul li a:hover{
         box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
     }

     ul li a .fa {
       width: 100%;
       height: 100%;
       display: block;
       background: linear-gradient(0deg, #dddddd, #ffffff);
       border-radius: 50%;
       line-height: 50px;
       font-size: 24px;
       color: #262626;
       transition: 0.5s;
      }

     ul li:nth-child(1) a:hover .fa {
       color: #dd4b39;
     }
    ul li:nth-child(2) a:hover .fa {
        color: #00aced;
    }
    ul li:nth-child(3) a:hover .fa {
       color: #dd4b39;
    }
    ul li:nth-child(4) a:hover .fa {
       color: #007bb6;
    }
    ul li:nth-child(5) a:hover .fa {
       color: #bc2a8d;
     }
