build: ##Build your website structure
	hugo -s . -d dist/

clean: ##Clean content of dist directory
	rm -rf dist/

post: ##Create new post for your website
	hugo new posts/$(POST_NAME).md
	sed -i 's/title: .*/title:"$(POST_TITLE)"/' content/posts/$(POST_NAME).md

help: ##Show this help usage
	cat README.md
