# Book CoverPage Design

## AIM:

To design a static web site for a book cover page.

## DESIGN STEPS:

### Step 1:
Clone the  Github Respository and create a Django admin interface.

### Step 2:
Write HTML and CSS Code for designing book cover page and execute them.


## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title> ZERO TO CODERS</title>
        <style>
        h1{
           color:goldenrod;
        }
         .bookpage{
             width: 400px;
             height: 600px;
             
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url('/static/images/bg.jpg');
  background-size: cover;
  background-repeat: no-repeat;
         }
         .toptext{
             color:goldenrod;
             padding-left: 5px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;
             
         }
         .tophr{
             color:goldenrod;
              width: 180px;
         }
         hr{
             color:goldenrod;
            
         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
              font-size: 24px;
              
             
         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
              display: flex;
            
            
  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }
  
.footer {
  
  padding-top: 90px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr { 
    color:gold;
              width: 400px;

}
img {
    width: 85px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:goldenrod;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height: 20px;
 
}


        </style>
        </head>
            <body>
                <div class="bookpage">
                    
                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT DESIGN</div>
                    <div class="tophr"><hr></div> 
               <div class="booktitle"><h1> ZERO TO CODERS </h1></div>
               <h3 class="sub-text">Coding for Beginners</h3>
                    <h3 class="sub-text">C,C++,Python,HTML,CSS and More</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;fourth Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="/static/images/author.jpeg" alt="Author Image"></h2>
                      
                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;HARINI&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>
                    
                </div>
                </div> 
                
            </body>
        
    
</html>
```

## OUTPUT:
![out](/output.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
