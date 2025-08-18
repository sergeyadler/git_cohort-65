FROM ubuntu:24.04 
RUN apt-get update && \
    apt-get install -y cowsay fortune && \
    ln -s /usr/games/cowsay /usr/bin/cowsay && \
    ln -s /usr/games/fortune /usr/bin/fortune
	
CMD ["/bin/bash", "-c", "fortune | cowsay -f dragon-and-cow"]