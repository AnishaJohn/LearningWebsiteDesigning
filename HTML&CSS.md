Ref: 
1.	https://www.youtube.com/watch?v=QMnv3QrjZoU

STATIC WEBSITE: 
	Combination of HTML,CSS,JS
Example: As a human body entire structure 
•	skeleton is HTML;
•	skin is CSS
•	how exactly the body has to function is JS


HTML:
•	It is builing block of the website.
•	Websites are made up of three core technologies.
•	It is standard hyper text markable language for creating website
•	Defining the content

Eg: In a form every line image selectable boxes ration buttons every element in the form context is the result of HTML




CSS:
•	Css – cascading style sheet
•	It is used for how the element of the page should be
•	It is beautifying the styling component 




JS:
•	It is the functionality part
•	If click on the submit button how the functions happpend






<html> every html document starts with html tag
<head> - head section (common section for entire website)
Head section is used to define meta tags 
     Eg:meta keywords,description ,loading style sheet along with the document,before entire elements in page loads have to mention js file in header 
    <title>           <\title>
<meta name – if searching page , multiple or related source shown>
<Body> - actual content,whatever seen in the webpage top to bottom
hr – hyper link ;linking other page
<p> paragraph tag
Img – for inserting images
<a> </a> anchor tag – visiting the website ;adding hyperlink
In anchor tag  target =_blank
Link tag<link>
Styling :
Inline – changing along the element
Internal – changing in head file
External – adding style in separate file and finally have to link with it



<html>
<head>
          <title> Home – Edureka </title>
</head>
<body>
     <center>
        <h1> Welcome To Edureka </h1>
        <h2> Web Development </h2>
        <p> We are learning HTML & CSS </p>
<a href = “ https://google.com “ target=_blank  >         <h4> Visit google </h4>
 </a>
        <img src = “images/slider.jpg” width = “70%”/>
     </centre>
  </body>
</html>




Internal styling:

<html>
<head>
          <title> Home – Edureka </title>
          <style>
                h2
                  {
                   color: #       ;
                   font-family :      ;
                  }

          </style>
</head>
<body>



External styling:

<html>
<head>
          <title> Home – Edureka </title>
          <link rel = “stylesheet” type = “text/css” href= “css/style.css”/>

</head>
<body>

In new page:
                h2
                  {
                   color: #       ;
                   font-family :      ;
                  }




Button for hyper link:

<body>
     <center>
        <h1> Welcome To Edureka </h1>
        <h2> Web Development </h2>
        <p> We are learning HTML & CSS </p>
<a href = “ https://google.com “ target=_blank  >         <button class= “btn”> Visit google </button>
 </a>
        <img src = “images/slider.jpg” width = “70%”/>
     </centre>
 </body>


Two Button link two hyper links:
<body>
     <center>
        <h1> Welcome To Edureka </h1>
        <h2> Web Development </h2>
        <p> We are learning HTML & CSS </p>
<a href = “ https://google.com “ target=_blank  >         <button class= “btn”> Visit google </button>
 </a>
<a href = “web page link“ target=_blank  >         <button class= “btn1”> Visit webpage name </button>
 </a>

        <img src = “images/slider.jpg” width = “70%”/>
     </centre>
 </body>


In exterenal styling:
In new page:
                .btn
                  {
                   Background - color: #       ;
                   font-family :      ;
                   boarder : none ;
                   padding : 10px;
                  }

.btn:hover
{
  background - Color: #    ;
}
