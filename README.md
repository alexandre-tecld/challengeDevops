# challengeDevops

instale o docker

#####  baixe ou clone o gituhb
wget ou git clone https://github.com/alexandre-tecld/challengeDevops

##### execute o docker
docker image build -t (nome image) .

##### inicie o container
docker container run -p 8000:8000 (nome image)

##### Entre no container e execute
 python manage.py migrar
 python manage.py createsuperuser
 
 ##### acesse no navegador 
 Acesse em : http://localhost:8000
 
 http://localhost:8000/programas/
