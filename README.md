####################################

This file contains my POC for docker


####################################

# Docker Image Commands

- docker images  --> To list images
- docker rmi --> To remove a image but make sure the image was untagged and not attached to any container
- docker imgaes "repository name"
	Example:
	 	docker images java [Here java is a repo name"]
                You can specify the repo name along with the tag name
- docker images -q --> This command return only the image ID.

- docker inspect --> To see details about the image and container

	Example:
		docker inspect nginx

