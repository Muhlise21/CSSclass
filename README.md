<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gridFotoGaleria1</title>
    <link rel="stylesheet" href="gridFotoGaleria.css">
    <link rel="preconnect" href="https://fonts.googleapis.com"> 
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
    <link href="https://fonts.googleapis.com/css2?family=Shalimar&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <div class="grid-box grid-box-1">
            <img class="img-flw" src="gImages/flw1.jpg" alt="flw1"><p class="description" id="description-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-2">
            <img class="img-flw" src="gImages/flw2.jpeg" alt="flw2"><p class="description" id="description-2">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-3">
            <img class="img-flw" src="gImages/flw3.jpeg" alt="flw3"><p class="description" id="description-3">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-4">
            <img class="img-flw" src="gImages/flw4.jpeg" alt="flw4"><p class="description" id="description-4">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-5">
            <img class="img-flw"src="gImages/flw5.jpeg" alt="flw5"><p class="description" id="description-5">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-6">
            <img class="img-flw" src="gImages/flw6.jpeg" alt="flw6"><p class="description" id="description-6">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-7">
            <img class="img-flw" src="gImages/flw7.jpeg" alt="flw7"><p class="description" id="description-7">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>
        <div class="grid-box grid-box-8">
            <img class="img-flw"src="gImages/flw8.jpeg" alt="flw8"><p class="description" id="description-8">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel fugit atque possimus blanditiis voluptatibus quasi quas porro laboriosam exercitationem mollitia, aliquam libero dicta beatae fugiat velit cum, eaque omnis nostrum?</p></div>

    </div>
    
    
</body>
</html>
.grid-box{
    width: 100%;
    border-radius: 20px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.4);
    font-family: "Shalimar", cursive;
    transition: 0.3s;

}
.grid-box :hover{
    box-shadow: 0 8px 16px 0 rgb(34, 8, 8) (0, 0, 0, 0.7);
    opacity: 0.2 ;
    transition: 0.3s;

}
.description{
    padding: 20px;
    text-align: justify ;
    line-height: 3rem;
    font-size: 2rem;
    /* grid-template-areas: 2 / 1 / 2 / 2 / 3 / 1 / 2 / 1; */

}
.grid-box-1{
    grid-row: 1 / 3;
}
.grid-box-2 {
    grid-column: 2 / 4;
}
.grid-box-3 {
    grid-row-end: 3;
}
.grid-box-4{
    grid-row-end: 3;
}
.grid-box-5{
    grid-column: 2 span;
}
.grid-box-6{
    grid-row-end: 2 span ;
}
.grid-box-7{
    grid-column: 2 span;
}
.grid-box-8{
    grid-column-end: 3 span ;
}
.img-flw {
    width: 100%;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
}

.container{
    display: grid;
    margin: 5vh auto;
    grid-template-columns: repeat(3, 30%);
    grid-gap: 4vh;
    justify-content: space-between;
}
#description-1{
    color: #9E7777
}

#description-2{
    color: #BFA2DB;
}
#description-3{
    color: #8F4068
}

#description-4{
    color: #F6C6EA
}

#description-5{
    color: #3A6351
}

#description-6{
    color: #CC7351
}

#description-7{
    color: #A1CAE2
}

#description-8{
    color: #FFABE1
