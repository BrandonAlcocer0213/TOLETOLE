<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <title>PIEDRA, PAPEL o TIJERA</title>

        <script>
            function aleatorio(min, max){
                return Math.floor(Math.random()*(max-min+1)+min)
            }
            // 1 es piedra, 2 es papel, 3 es tijera
            let jugador=0
            let pc= aleatorio(1,3)
            jugador=prompt("Elige:1 para piedra, 2 para papel, 3 para tijera")
            //alert("Elegiste " + jugador)
            if(jugador ==1){
                alert("Elegiste 🥌")
                } else if (jugador ==2){
                alert("Elegiste 📃")
                }else if (jugador ==3) {
                alert("Elegiste ✂")
                } else{
                alert("Elegiste PERDER")
                }
                if(pc ==1){
                alert("PC Elige 🥌")
                } else if (pc ==2){
                alert("PC Elige 📃")
                }else if (pc ==3) {
                alert("PC Elige ✂")
                }
                 //COMBATE
                 if(pc==jugador){
                    alert("EMPATE")
                 }else if(jugador==1 &&pc==3){
                    alert("GANASTE")
                 }else if(jugador==2 &&pc==1){
                    alert("GANASTE")
                 } else if(jugador==3 &&pc==2){
                    alert("GANASTE")
                 }
                 else{
                    alert("PERDISTE")
                 }
        </script>
    </head>
    <body>
        <h1>Piedra,papel o tijera</h1>
    </body>
</html>
