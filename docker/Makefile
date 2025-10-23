
centos5-image:
	docker build -f Dockerfile.centos5-linux-x86_64-pic -t xerial/centos5-linux-x86_64:latest
	# dockerhub login
	# docker login --username=xerial
	# docker push xerial/centos5-linux-x86_64:latest

rockylinux8-multiarch-image:
	docker build -f Dockerfile.rockylinux8-multiarch -t xerial/rockylinux8-multiarch:latest
	# dockerhub login
	# docker login --username=xerial  
	# docker push xerial/rockylinux8-multiarch:latest

multiarch-crossbuild-image:
	docker build https://github.com/iwasakims/crossbuild.git#fix-osxcross-cmake -t xerial/crossbuild:latest
