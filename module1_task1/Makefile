build:
	hugo -s . -d dist/

clean:
	rm -rf dist/

post:

    POST_TITLE=$(shell shuf -n1 /usr/share/dict/words)
    hugo new post/$(POST_NAME).md


.PHONY: build clean post
