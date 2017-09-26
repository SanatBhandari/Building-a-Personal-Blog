# Building-a-Personal-Blog
I use Dash, an online tool for learning to build web-applications as projects, to build a personal blog using HTML, CSS and WEB Design Circuit

<!DOCTYPE html>
<head>
  <link href="/normalise.css" res="stylesheet">
  <style>
    
    header{
      text-align: center;
      background: url('https://wallpapersafari.com/w/kTdK52');
      background-size: cover;
      color: white;
      }
      
    a{
      color: white;
      }
      
    h1{
      font-size: 70px;
      }
      
    img{
      margin: 40px 0px 0px 0px;
      border: solid white;
      border-radius: 20px;
      }
      
    ul{
      padding: 10px;
      background: rgba(0, 0, 0, 0.5);
      }
      
    li{
      display: inline;
      padding: 0px 10px 0px 10px;
      }
      
    article{
      max-width: 500px;
      padding: 20px;
      margin: 0 auto;
      }
      
    @media (max-width: 500px){
      h1{
        font-size: 36px;
        padding: 5 px;
        }
        
      li{
        padding: 5 px;
        display: block;
        }
      }
      
  </style>    
</head>

<body>
  <header>
    <img src="http://www.planwallpaper.com/static/images/3d_Creative_guitar_desktop_wallpaper_TUZQIme.jpg">
    <h1>Sanat's Blog</h1>
    
    <ul>
      <li><a href="#">About Me</li>
      <li><a href="#">My Thoughts</li>
      <li><a href="#">My Life</li>
    </ul>
    
  </header>
  
  <article>
    <h2>Heading 1</h2>
    <p> The Content of the the first article goes here </p>
    <button>Like</button>
  </article>
  
  <article>
    <h2>Heading 2</h2>
    <p> The Content of the second article goes here </p>
    <button>Like</button>
  </article>
  
  <script>
    $("button").on("click", function(){
      alert("Clicked!");
    });
  </script>
  
</body>
  
    
