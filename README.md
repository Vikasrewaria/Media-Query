Task.1:- Problem Statment
Create a simple webpage with a header, a main content section, and a footer. Apply a media query that changes the background color of the header to blue when the screen width is less than 600px. <br>
Answer:-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid</title>
  <style>
    .header{
      height: 50px;
      width: 100vw;
      background-color: black;
      color: white;
      text-align: center;
    }
    @media screen and (max-width: 600px){
      .header{
        background-color:purple;
      }
    }
    .content-section{
      background-color:#ccc;
      color: black;
      text-align: center;
      padding: 20px;
    
    }
    .footer{
      background-color: black;
      color: white;
      text-align: center;

    }

  </style>
</head>
<body>
  <div class="header">
    <h1> Responsive Header</h1>
  </div>
  <div class="content-section">Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore beatae nulla modi quia quidem delectus blanditiis provident reprehenderit porro voluptate, alias maiores nam eos, illum harum velit consequuntur, quis officiis.
  Quis in officia voluptatem quisquam, quaerat velit veniam voluptas unde consequuntur id nihil pariatur, illo repellendus? Dolorem dolores exercitationem rem possimus, blanditiis sequi accusamus ratione est non, amet, fugiat a.
  Officiis inventore numquam quam, velit, odio nostrum nisi perferendis molestias dolores, labore ea debitis assumenda. Ratione suscipit odio sed sit provident quibusdam ut id obcaecati. Assumenda dicta necessitatibus cupiditate corrupti!
  Ex temporibus quam deserunt perferendis itaque cupiditate illum, aspernatur quasi repellat voluptas atque ea eaque hic aliquam quia maxime architecto consequuntur at excepturi odit fugiat officia quibusdam. Recusandae, reprehenderit magni.
  Aspernatur corrupti neque accusamus aut itaque ratione dolore voluptatibus vitae, natus ducimus cupiditate dignissimos ex placeat veniam pariatur aperiam iure quisquam reiciendis facilis amet eligendi iusto. Cum hic modi temporibus?
  Eligendi ut reprehenderit voluptatibus provident nesciunt dolores sed excepturi saepe quis ad, consequuntur dicta possimus omnis pariatur nemo quae, quo ratione quia explicabo, voluptatem quas. Laudantium nobis nisi quasi inventore.
  Aperiam temporibus nam provident esse nobis minus, explicabo blanditiis necessitatibus, deleniti officiis quaerat neque debitis fuga labore est inventore quasi. Exercitationem excepturi asperiores quod adipisci dicta vel! Eum, laudantium ad.
  Quasi facilis impedit culpa commodi, repudiandae harum architecto eveniet ad deleniti, doloribus nam tempore recusandae! Harum nesciunt placeat, asperiores rem nisi vel, sed qui alias, omnis aliquam rerum repellat aperiam.
  Dolor repellat et vero magni dolorum molestiae quis quo laboriosam distinctio, ducimus minus, fugiat in eaque eos pariatur at temporibus deserunt. Totam expedita sunt dolores soluta corrupti? Minus, ex veniam!
  In optio id omnis alias eius aspernatur itaque, dignissimos enim, ratione quaerat eos dolore eveniet earum doloremque, iste illo officia. Saepe pariatur debitis id possimus perferendis eveniet alias dolorem modi?
  Error vero ut magni in ab porro, recusandae et, reprehenderit, obcaecati maxime inventore beatae quod deleniti nulla dignissimos eum hic dolores dolorum voluptatem ipsa minima accusamus itaque! Molestiae, rerum ducimus.
  Ratione pariatur ducimus consequatur illo, unde dolorem doloremque itaque fugiat atque, veritatis blanditiis, velit odit dolores eaque repudiandae rem ipsa repellat adipisci ea. Commodi, cum repellendus culpa dolores atque libero.
  Pariatur consectetur reiciendis porro et amet nemo ducimus est quo! Atque rerum dignissimos optio qui pariatur quis voluptates enim necessitatibus fuga. Quod natus assumenda magni itaque et, corporis ratione vel.
  Asperiores pariatur deserunt eveniet voluptate ad velit, illo quos molestias repellendus soluta modi. Mollitia, debitis asperiores voluptatem optio odio vero minus quod aspernatur cum voluptatum! Ipsam pariatur inventore eaque consequatur.
  Rem veritatis explicabo fuga? Ut porro, pariatur accusantium mollitia nostrum magnam officia illo nisi earum laborum quo possimus, dolorum molestias molestiae vel et dicta numquam voluptatibus nesciunt nobis culpa ab.
  Ipsam debitis voluptatibus neque, fugit, nemo voluptatum exercitationem, placeat officia eligendi odit veniam nulla non inventore deleniti soluta distinctio maxime adipisci! Placeat eveniet sint beatae tempora culpa quia necessitatibus ducimus.
  Maxime vero totam veniam temporibus quam laudantium tempore consequuntur repudiandae, reiciendis ut? Facilis debitis expedita nihil, necessitatibus, quisquam ut illum molestias quos ex adipisci dolor nulla dolorum natus illo ipsum!
  Perferendis quisquam dolorem cumque. Officia mollitia quis quisquam rerum, asperiores, unde exercitationem laudantium dolor eligendi libero nam dicta odio perspiciatis eum omnis, voluptatibus harum dolorem sed vel odit autem nesciunt.
  Eaque rem voluptate voluptatem sed. Maiores labore repellendus nihil adipisci id, corrupti ad harum praesentium, perferendis atque quasi autem quidem placeat optio. Esse minus dolor quidem maxime eveniet odit ex.
  Repellat dolor, mollitia totam eaque, deserunt amet itaque doloribus sequi beatae repellendus, cum nulla quam excepturi reprehenderit doloremque vel aspernatur consequatur tenetur iste perspiciatis nostrum suscipit iure ipsam? Iste, earum.</div>
  <div class="footer"> made in india
   
  </div>
</body>
</html>

<br>

Task.2:-  Create an image gallery with three images in a row. Use media queries to adjust the layout to two images in row for screen smaller than 800px and one image in a row for screens smaller than 500px.
Answer:-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photo gallery </title>
  <style>
    .image-gallery{
          display: flex;
          flex-wrap: wrap;
           justify-content: space-between;
    }
    .image-gallery img{
      width: 30%;
      margin: 10px;
    }
    @media screen and ( max-width:800px)  {
      .image-gallery img{
        width: 45%;
      }
    }
    @media screen and (max-width:500px){
      .image-gallery img{
        width:100%;
      }
    }
  </style>
</head>
<body>
  <div class=" image-gallery">
    <img src="https://fastly.picsum.photos/id/548/200/300.jpg?hmac=dXVAc-s_U8QgoYUrMld43VmrOby1cluk-akWgxY6b9Y" alt="image-1">
    <img src="https://fastly.picsum.photos/id/548/200/300.jpg?hmac=dXVAc-s_U8QgoYUrMld43VmrOby1cluk-akWgxY6b9Y" alt="image-2">
    <img src="https://fastly.picsum.photos/id/548/200/300.jpg?hmac=dXVAc-s_U8QgoYUrMld43VmrOby1cluk-akWgxY6b9Y" alt="image-3">
  </div>
</body>
</html>

Task.3:- Create a navigation bar with five link. Apply a media query that converts the navigation into a vertical list for screens smaller than 768px and also changes the bacground color to gray.
Answer:- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar</title>
    <style>
        .navigation{
            display: flex;
            justify-content: space-between;
            background-color: black;
            
        }
        .navigation a{
            text-decoration:none;
            color: white;
        }
        @media screen and (max-width:768px){
            .navigation{
                flex-direction: column;
                text-align: center;
                background-color:grey;

            }
        }
    </style>
</head>
<body>
        <div class="navigation">
            
                <a href="#">Home</a>
                <a href=""> About</a>
                <a href="">Services</a>
                <a href="">Portfolio</a>
                <a href="">Contact</a>
           
        </div>
</body>
</html>

Task.4:- Create a grid based layout containing four grid items which arranges them as the screen siize changes.
Answer:- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>grid layout</title>
    <style>
        body{
            margin: 0;
            padding: 0;

        }
        .grid-container{
            display: grid;
            grid-template-columns: repeat(3,3fr);
            gap:20px;
            padding: 20px;
            background-color: rgb(167, 166, 166);
            min-height: 100vh;
        }
        .header{
            background-color:red;
            color:white;
        }
        .sidebar{
            background-color: green;
            color: white;
        }
        .main{
            background-color: blue;
            color: white;
        }
        .footer{
            background-color: rgb(166, 52, 52);
            color: white;
        }
        @media screen and (max-width:768px)
        {
            .grid-container{
                grid-template-columns:1fr;
            }
        }
        .box{
            text-align:center
            }
         
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="header box"> Box 1</div>
        <div class="sidebar box">Box 2</div>
        <div class="main box">Box 3</div>
        <div class="footer box">Box 4</div>
    </div>
    
</body>
</html>

Task.5:- Create the below given layout using the flexbox in css, which should adapt itself on mobile screen as per given below output.
Answer:- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>webpage Layout</title>
    <Style>
        .container{
            display: flex;
            flex-direction: column;
            min-height: 100vh;

        }
        .header , .footer{
            background-color:Black;
            color:white;
           padding: 20px;
        }
        .main{
            display: flex;
            flex-direction: column;
            flex: 1;
         }
        .sidebar{
            background-color: aqua;
            color:white;
            padding: 20px;
            
        }
        .content{
            Background-color:orange;
            color: white;
            padding: 20px;
           
        }    
        @media screen and ( min-width:768px)
        {
            .container{
              
                flex-direction:row;

            }
            .sidebar,
            .content{
                flex: 1;
            }
        }
    </Style>
</head>
<body>
    <div class="container">
        <div class="header">Box 1</div>
        <div class="main">
            <div class="sidebar">Box 2</div>
            <div class="content">Box 3</div>
        </div>
        <div class="footer">Box 4</div>
    </div>
    
</body>
</html>
