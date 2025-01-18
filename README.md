<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>


body{
  font-family: 'Poppins', sans-serif;
  color: rgb(45, 45,45);
  background: rgb(30, 200, 197);
  font-size: 1.2rem;
  background: linear-gradient(
    90deg,
    rgba(30, 200, 197, 1) 0%,
    rgba(250, 250, 138, 1) 100%
  );
}

.container{
  background-color: rgba(255, 255,255, 0.5);
  border-radius: 20px;
  padding: 5px; 
  margin-top: 5rem;
  margin-bottom: 5rem;
}

.profile{
  text-align: center;
  padding-top: 15px;
}
.profile h1{
  font-size: 3rem;
  font-weight: 800;
  margin: 0;
}
.avatar{
  height: 150px;
  width: 150px;
  border:3px solid rgba(255, 255,255, 0.5);
  border-radius: 50%;

}
.heighlight{
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 2.5px;
  -webkit-text-stroke-color: rgb(45, 45,45);
}
.icons a{
  font-size: 28px;
  margin-right:8px; 
}
.icons a:hover{
  font-size: 28px;
  margin-right:8px; 
  color: var(--blue);
  background-color: transparent;
  padding:0;
  border: none;
}
</style>
<body>
    <main class="container">
   <div class="profile">
     <img src="https://i.postimg.cc/GpJd6R8x/Profile-Pic.jpg" alt="" class="avatar">
     <p class="">Hello. Hola. Namaste</p>
     <h1>👋 Hi,<span class="heighlight"></span>I’m Sameer Kumar</h1>
     <p class="">I am a full Stack developer <br> who loves tech.</p>
    
   </div>
 </main>
</body>
</html>
