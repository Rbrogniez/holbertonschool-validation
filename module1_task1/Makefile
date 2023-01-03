build:
	@hugo
clean:
	rm -rf dist/*
post:
	hugo new ./content/posts/$(POST_NAME).md
	sed -i '/title:*/c\title: "$(POST_TITLE)"' ./content/posts/$(POST_NAME).md
