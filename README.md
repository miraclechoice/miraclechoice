<style>
    @import url('https://fonts.googleapis.com/css2?family=Rubik:wght@700&display=swap');    
    body {
        font-family: 'Rubik';
        background-color: #15151B;
    }
    img, svg {
        vertical-align: middle;
        width: 40px;
        height: 40px;
    }
    .links {
        display: flex;
        gap: 5px;
    }   
    .links_item {
        background-color: #070712;	
        border-radius: 5px;
        padding: 5px 10px 5px 30px;
        position: relative;
        color: #fff;
    }
    .links_item:nth-child(1)::before {
        content: '';
        width: 15px;
        height: 15px;
        filter: invert(1);
        top: 8px;
        background-repeat: no-repeat;
        left: 10px;
        position: absolute;
        background-image: url('https://simpleicons.org/icons/html5.svg');
    }
    .links_item:nth-child(2)::before {
        content: '';
        width: 15px;
        height: 15px;
        filter: invert(1);
        top: 8px;
        background-repeat: no-repeat;
        left: 10px;
        position: absolute;
        background-image: url('https://simpleicons.org/icons/css3.svg');
    }
.links_item:nth-child(3)::before {
    content: '';
    width: 15px;
    height: 15px;
    filter: invert(1);
    top: 8px;
    background-repeat: no-repeat;
    left: 10px;
    position: absolute;
    background-image: url('https://simpleicons.org/icons/javascript.svg');
    }
    .links_item:nth-child(4)::before {
        content: '';
        width: 15px;
        height: 15px;
        filter: invert(1);
        top: 8px;
        background-repeat: no-repeat;
        left: 10px;
        position: absolute;
        background-image: url('https://simpleicons.org/icons/tailwindcss.svg');
    }
    .links_item:nth-child(5)::before {
        content: '';
        width: 15px;
        height: 15px;
        filter: invert(1);
        top: 8px;
        background-repeat: no-repeat;
        left: 10px;
        position: absolute;
        background-image: url('https://simpleicons.org/icons/typescript.svg');
    }               
</style>
<body>
  <div class="links">  
    <div class="links_item">HTML</div>
    <div class="links_item">CSS</div>
    <div class="links_item">JS</div>
    <div class="links_item">TAILWIND</div>
    <div class="links_item">TYPESCRIPT</div>
  </div>
</body>