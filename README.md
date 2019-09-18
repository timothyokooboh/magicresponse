<!DOCTYPE html>
<html>


   <head>
    
       <meta name = "viewport" content = "width=device-width, initial-scale=1.0">
       
      <title>Javascript lessons</title>
       
       <style>
           
           body {
              
               background-color: azure;
               height:7000px;
               font-family: sans-serif;
           }
           
           a {
               
               color:white;
               font-weight: bold;
               text-decoration: none;
               font-size: 25px;
           }
       
           
           button{
               
               background-color: darkblue;
               border-radius: 18px;
           }
           
           .response-area{
               
               max-width: 400px;
               margin: auto;
               padding-bottom: 10px;
               padding-top: 10px; 
               text-align: center;
               font-size: 20px;
               border:none;
               box-shadow: 0px 20px 20px rgba(0, 0, 0, 0.1) ;
               background-color: white;
               border-radius: 20px;
              
           }
           
           img{
               
               width: 100px;
               //height: 100px;
           }
       
       </style>
       
   </head>
   
   <body>
       
       <div class = "response-area">
    
         <img src= "homer.png" ><p id = "demo1"></p>

          <button><a href="file:///Users/futurewox-timothy/Desktop/webdevelopment/javascript.html">Ask me anything</a></button>
    
        </div>  
    
   
   <script>
   //Magic response game
    var question = prompt("Ask me anything");
    var output = "";
    var demo = document.getElementById("demo1")
    var random = Math.floor(Math.random()*21)
    
    
    switch(random){
    case 0:
    output = "Hmm, I really don't know about that..sorry!";
    break;
    case 1:
    output = "Well, just drink water and mind your business.";
    break;
    case 2:
    output = "OMG! Let me think, I'll get back to you.";
    case 3:
    output = "I'm not omniscient. So phone a friend or ask the audience (laughs).";
    break;
    case 4:
    output = "Just a minute. Spider man is on his way with the answer on his web.";
    break;
    case 5:
    output = "Actually according to logistics, it will take ten professors to get right!";
    break;
    case 6:
    output = "You had better go see a movie and stop thinking too much.";
    break;
    case 7:
    output = "Wow.. honestly, I never saw that coming. But you'll be fine.";
    break;
    case 8:
    output = "Ouch!, I'll have to fast and pray to get that one right.";
    break;
    case 9:
    output = "In 1942, someone asked me that question. Trust me, you don't wanna know what I said";
    break;
    case 10:
    output = "Even if I tell you, you still won't believe me";
    break;
    case 11:
    output = "LOL. Tell me the truth, do you really want to know?";
    break;
    case 12:
    output = "Hmm, you talk like someone who is in love";
    break;
    case 13:
    output = "Sorry, I'm driving. I'll text you when I get home.";
    break;
    case 14:
    output = "You'll have to sing for me before I'll answer that.";
    break;
    case 15:
    output = "Like seriously! I was wondering about that too";
    break;
    case 16:
    output = "Ask that lady in the other room. She will give you a honest reply";
    break;
    case 17:
    output = " I'll tell you if you go out on a date with me";
    break;
    case 18:
    output = "Ok let's reason together. What do you really think?";
    break;
    case 19:
    output = "I'll get back to you. But for now, the weather is cold so drink tea and relax your mind.";
    break;
    case 20:
    output = " Wow! Wait a minute, you said what???"
       
       }
       
       
        demo.innerHTML = "<strong>" + "You asked me: " + "</strong>" + "<i>" + question + "</i>" + "?" + "<br>" + "<strong>" + "Magic response: " + "</strong>" + output;
        
    </script>
    
    </body>
    
    </html>
