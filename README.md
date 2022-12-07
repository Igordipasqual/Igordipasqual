<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
  
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | QR code component</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <style>
    @import url("https://fonts.googleapis.com/css2? family=Open+Sans:ital@0;1&family=Outfit:wght@400;500&family=Poppins:wght@200;300&family=Ubuntu:ital,wght@0,300;0,400;0,500;1,700&display=swap");


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Outfit", sans-serif;
}
body{
    display: flex;
    align-items:center;
    justify-content: center;
    min-height:100vh;
    background:var(--Light-gray);
}
:root{
    --mobile-phone: 375px;
    --desktop:1440px;
    --weight1 : 400;
    --weight2 :700;
    --p:15px;
    --White: hsl(0, 0%, 100%);
    --Light-gray: hsl(212, 45%, 89%);
    --Grayish-blue: hsl(220, 15%, 55%);
    --Dark-blue: hsl(218, 44%, 22%);
}
.container{
    text-align: center;
    border-radius: 20px;;
    padding:20px;
    background:var(--White);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.container .photo{
    margin-bottom:20px;
    width:var(--mobile-phone);
    height: var(--mobile-phone);

}
.container .photo img{
    width:100%;
    height:100%;
    object-fit: cover;
    border-radius: 20px;
}
.container .content{
    padding-bottom: 20px;
}
.container .content h2{
    margin-bottom:10px;
    color:var(--Dark-blue);
    font-weight: var(--weight2);
}
.container .content p{
    color:var(--Grayish-blue);
}
  </style>
  <div class="container">
    <div class="photo">
      <img src="./images/image-qr-code.png">
    </div>
    <div class="content">
      <h2>Improve your fronted-end <br> skills by building projects</h2>
      <p>Scan QR code to visit Fronted <br> Mentor and taking your code skills <br> to next level</p>
    </div>
  </div>
</body>
</html>
