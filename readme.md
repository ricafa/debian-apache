#criar imagem de acordo com dockerfile
docker image build -t debian-apache:1.0 .


#rodar imagem
 docker run -dti -p 80:80 --name meu-apache debian-apache:1.0
 

done

