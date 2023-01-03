build:
    hugo -s . -d dist/

clean:
    rm -rf dist/

post:
    hugo new post/$(POST_NAME).md

.PHONY: build clean post
