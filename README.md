# Pedido
Site Meu pedido
<html>
    <head>
        <style>
            body {
                background-image: url("https://media.istockphoto.com/id/465103673/es/vector/rom%C3%A1ntica-de-fondo.jpg?s=170667a&w=0&k=20&c=hlP-DAl6xOXbPlJqakRrZD9n8tUqogEkyfZyDsTRyGg=");
                background-size: cover;
                background-position: center;
                background-repeat: no-repeat;
                background-attachment: fixed;
                display: flex; 
                justify-content: center;
                align-items: center;
                height: 100vh;
            }
            a {
                text-decoration: none;
            }
            .box {
                font-family: 'Times New Roman', Times, serif;
                font-size: 20px;
                color: rgb(255, 255, 255);
                -webkit-text-stroke-width: 100%;
                -webkit-text-stroke-color: rgb(0, 0, 0);
                height: 338px;
                width: 507px;
                border-radius: 10px;
                background-image: url("https://media.istockphoto.com/id/465103673/es/vector/rom%C3%A1ntica-de-fondo.jpg?s=170667a&w=0&k=20&c=hlP-DAl6xOXbPlJqakRrZD9n8tUqogEkyfZyDsTRyGg=");
                flex-direction: column;
                display: flex;
                align-items: center;
                justify-content: center;
            } 

            .buttons-container{
                display: flex;
                justify-content: space-around;
                height: 59px;
                width: 150px;
            }
            button {
                height: 30px;
                width: 50px;
                background: white;
                border-radius: 5px;
                color: blue;
                font-weight: 600;
            }
        </style>
    </head>
    <body>
        <div class="box">
            <p>Lu Você Aceita Namorar comigo??</p>
            <div class="buttons-container">
                <button>
                    <a href="https://wa.me/5511978031039?text=Olii,%20Nick%20Eu%20Aceito%20Seu%20Pedido,%20Agora%20Estamos%20Namorando❤️">Sim</a>
                </button>          
                <button id="no">Não</button>
            </div>
        </div>

    <script>

    let button = document.getElementById('no');
    let height = window.innerHeight - 50;
    let width = window.innerWidth  - 50;
    button.addEventListener('mouseover', function () {
        button.style.position = "absolute";
        button.style.top = Math.random() * height + "px";
        button.style.left = Math.random() * width + "px";
    }) 
           
        
</script>
</body> 
</html>
