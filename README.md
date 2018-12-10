configure nginx and php 7.2

nginx threads,iao, stream, ssl compile installation
# source: https://gist.github.com/AysadKozanoglu/8f95343bb5e4e97ab09461ef92dd3124#file-nginx_compile_install-sh
<pre>wget -O - https://git.io/fpujF | bash</pre>

php7.2 installation (execute two times)
#source: https://gist.github.com/AysadKozanoglu/52aa3439f87703edaa2163795896b526#file-php7-install-debian_jessie
<pre>wget -O - https://git.io/fpDRd | bash</pre>

php7 settings (multi worker cluster mode for nginx ):
<pre> copy -R php/etc/php/7.2/* > etc/php/7.2/</pre>
