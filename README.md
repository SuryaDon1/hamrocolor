<!DOCTYPE html>
<html lang="en-np">
<head>
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1, shrink-fit=cover">
    <script src="https://kit.fontawesome.com/f6816dd194.js" crossorigin="anonymous"></script>

   
        <title>blog post</title>
    <style>
*{
        padding:0;
        margin:0;
        box-sizing:border-box;
        }
        body{
        
        background:#dddddd;
        }
        form{
        width:100%;
        height:100%;
        display:flex;
        }
        .left{ 
        width:70%;
        height:100%;
        border:none;
        }
        .left-div{
        margin-left:3%;
        margin-right:3%;
        margin-top:10px;
        
        
        }
        .title{   
        width:100%;
        height:3rem;
        border-radius:2px;
        background:white;
        border:none;
        
          }
         .textcss{   
        margin-top:10px;
        width:100%;
        height:30rem;
        border-radius:2px;
        background:white;
        border:none;
        padding:10px;
        font-weight:bold;
        font-size:1rem;
        
          }
         
        /*right*/
        .right{ 
        width:30%;
        height:100%;
        border:none;
        } 
        .imagecss{
        display:none;
        }
        .right-div{
        width:100;
        height:100%;
        background:#dddddd;
        }
        .right-image{
        margin-top:10px;
        margin-right:5%;
        margin-left:5%;
        width:90%;
        background:white;
        height:2rem;
        border-radius:2p;
        border-radius:0.2rem;
        }
        label{
        font-size:1rem;
        font-weight:bold;
        padding:1rem;
        margin-top:1rem;
        color:grey;
        
        
        }
        .btn-div{
        margin-top:1rem;
        }
        .btn-btn{
        margin-right:5%;
        margin-left:5%;
        width:90%;
        background:blue;
        height:2rem;
        border-radius:0.2rem;
        border:none;
        color:white;
        font-size:0.8rem;
        font-weight:bold;
        }
        .btn-btn:hover{
        background:green;
        color:white;
        } 
        /* mobile virsion*/
        @media (max-width: 765px) {
        form{
        width:100%;
        height:100%;
        display:block;
        }
        .left{
        width:100%;
        height:100%;
        }
        .right{
        width:100%;
        height:100%;
        }
        
        }
</style>
    </head>
    <body>
    <div class="first">
    <form action="#" method="post" enctype="multipart/form-data">
 <div class="left">
 <div class="left-div">
 <div class="div11">
 <input type="text" name="title" class="title" required>
 </div>
 
 <textarea name="dis" class="textcss" required></textarea>
 </div>
 </div
 <!--right-->
 <div class="right">
 
 <div class="right-div">
 <div class="right-image">
 <input type="file" name="image" id="fileuploader" class="imagecss" required>
 <label for="fileuploader"><i class="far fa-images" for="fileuploader"></i> Upload image</label>
 </div>
 <div class="btn-div">
 <button name="submit" class="btn-btn">Publlish</button>
</div>
 </div>
 </div>
    </form>
    
    </div>
        
    </body>
</html>
