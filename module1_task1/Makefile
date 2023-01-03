HUGO=hugo
RM=rm -rf

build:
	$(HUGO)

post:
	$(HUGO) new posts/$(POST_NAME).md
	echo '# $(POST_TITLE)' >> ./content/posts/$(POST_NAME).md

clean:
	$(RM) dist/*
