# spring boot シェルの例
#curl  "http://wttr.in/kyoto?lang=ja&0" >  "./src/main/resources/banner.txt"
#curl -o "src/main/resourzces/banner.png" "https://app.pixelencounter.com/api/basic/svgmonsters/image/png"
number=$((RANDOM%905+1))
#curl -o "src/main/resources/banner.png" "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/$number.png"
curl -o "src/main/resources/banner.png" "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/$number.png"

#color
spring.output.ansi.enabled=always

