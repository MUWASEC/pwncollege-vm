# build for software-exploitation - kernel-exploitation
$ docker buildx create --name vps --driver docker-container ssh://vps --use	# setup buildx name vps that connected to a "real" vps
$ docker buildx inspect --bootstrap 						# check vps docker-buildx (optional)
$ docker buildx build --progress=plain --builder vps --load -t pwncollege-vm .	# build & pull them to local


# ps
all i say is use high-end vps and prepare to spend 30+ min and 10 gb of storage ꉂ(´∀｀)ʱªʱªʱª
