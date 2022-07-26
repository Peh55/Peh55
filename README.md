## Bem-vindo(a) ao perfil do Peh55 😁

 <div>
   <a href="https://github.com/Peh55">
   <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Peh55&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
   <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Peh55&layout=compact&langs_count=6&theme=tokyonight"/>

</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>
 
 <br>
 
<div> 
 
  ![Snake animation](https://github.com/devemdobro/devemdobro/blob/output/github-contribution-grid-snake.svg)

</div>

<div>
<link rel="stylesheet" href="stylep.css">
    <ul>
        <li style="--i:#a955ff;--j:#ea51ff;">
            <span class="icon"><ion-icon name="home-outline"></ion-icon></span>
            <span class="title">Home</span>
        </li>
        <li style="--i:#56CCF2;--j:#2F80ED;">
            <span class="icon"><ion-icon name="chatbubble-outline"></ion-icon></span>
            <span class="title">Messages</span>
        </li>
        <li style="--i:#FF9966;--j:#ff5500;">
            <span class="icon"><ion-icon name="heart-outline"></ion-icon></span>
            <span class="title">Favourite</span>
        </li>
        <li style="--i:#80FF72;--j:#7EE8FA;">
            <span class="icon"><ion-icon name="videocam-outline"></ion-icon></span>
            <span class="title">Videos</span>
        </li>
        <li style="--i:#ffa9c6;--j:#f434e2;">
            <span class="icon"><ion-icon name="camera-outline"></ion-icon></span>
            <span class="title">Photos</span>
        </li>
    </ul>
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</div>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800;900&display=swap');
*
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins' , sans-serif;
}
body
{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
ul
{
    position: relative;
    display: flex;
    gap: 25px;
}
ul li 
{
    position: relative;
    list-style: none;
    width: 60px;
    height: 60px;
    background: #fff;
    border-radius: 60px;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0 16px 25px rgba(0,0,0,0.1);
    transition: 0.5s;
}
ul li:hover
{
    width: 180px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}
ul li::before
{
    content: '';
    position: absolute;
    inset: 0;
    border-radius: 50px;
    background: linear-gradient(45deg,var(--i),var(--j));
    opacity: 0;
    transition: 0.5s;
}
ul li:hover::before
{
    opacity: 1;
}
ul li::after
{
    content: '';
    position: absolute;
    top: 10px;
    width: 100%;
    height: 100%;
    border-radius: 60px;
    background: linear-gradient(45deg,var(--i),var(--j));
    transition: 0.5s;
    filter: blur(15px);
    z-index: -1;
    opacity: 0;
}
ul li:hover::after
{
    opacity: 0.5;
}
ul li ion-icon
{
    color: #777;
    font-size: 1.75em;
    transition: 0.5s;
    transition-delay: 0.25s;
}
ul li:hover ion-icon
{
    transform: scale(0);
    color: #fff;
    transition-delay: 0s;
}
ul li span
{
    position: absolute;
}
ul li .title
{
    color: #fff;
    font-size: 1.25em;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    transform: scale(0);
    transition: 0.5s;
    transition-delay: 0s;
}
ul li:hover .title
{
    transform: scale(1);
    transition-delay: 0.25s;
}
