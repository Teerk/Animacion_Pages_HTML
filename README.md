# Animación en CSS para cuando se recarga la página
CSS

        .overlay{
            position: absolute;
            top:0;
            left:0;
            background:linear-gradient(90deg,#257bf9,#2426ca);
            width: 100%;
            height: 100vh;
            transform: translate(-2000px);
            animation: slideUp 2s ease;
        }

        @keyframes slideUp{
            0%{
                transform: translateX(0);
            }
            100%{
                transform: translateX(-2000px);
            }
        }
