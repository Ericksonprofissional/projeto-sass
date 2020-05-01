Instalando o SASS (Linux):

Dê o seguinte comando :

sudo apt install ruby-full rubygems autogen autoconf libtool make

E Depois:

gem install sass

sass estilos.scss:estilos.css

O Sass é um pré-processador CSS, então a primeira coisa que devemos fazer é pedir para que ele compile o arquivo "estilos.scss", e faremos isso por meio do terminal. Depois compilamos o arquivo .scss para criar um .css

sass --watch estilos.scss:estilos.css 

O Sass está observando em busca de mudanças. Pressione Ctrl-C para parar". Agora, qualquer mudança feita na variável $cor-padrao, passará automaticamente para o arquivo .css.
