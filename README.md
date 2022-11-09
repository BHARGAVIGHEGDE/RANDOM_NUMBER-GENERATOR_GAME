# RANDOM_NUMBER-GENERATOR_GAME
This is the code of basic random  number generator game using javascript and basic html.
<html>
    <head><title>Random number generator</title></head>
    <body>
        <script>
            let a=prompt("enter a number")
            a=Number.parseInt(a)
            let b=Math.floor(Math.random()*100)+1
           
            while(a!=b){
                if(a<b){
                    a = Number.parseInt(prompt("is smaller"))
                } else {
                    a = Number.parseInt(prompt("is bigger"))
                }
            }
            alert("the guess is right")
            
            
            
        </script>
    </body>
</html>
