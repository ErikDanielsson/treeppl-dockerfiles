username = erikdanielsson
repo = host-rep-python
build:
	docker build  \
		--tag ${USERNAME}/${REPO}:${TAG} \
		--no-cache \
		.
	docker push $(USERNAME)/$(REPO):${TAG}

tag = latest
latest:
	$(MAKE) build \
		USERNAME=username	
		REPO=repo
		TAG=tag