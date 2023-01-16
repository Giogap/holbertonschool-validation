
build:	## Generate the website from the markdown and configuration files in the directory dist/
		hugo -s . -d dist/

post:	## Create a new blog post whose filename and title come from the environment variables POST_TITLE and POST_NAME
		hugo new posts/$(POST_NAME).md
		sed -i 's/title: .*/title:"$(POST_TITLE)"/' content/posts/$(POST_NAME).md 

clean:	## Cleanup the content of the directory dist/
		rm -rf dist/

help:
		@sed -ne '/@sed/!s/## //p' Makefile

package:
		@hugo
		@zip awesome-website.zip dist/ 

lint:
		@markdownlint README.md
		@markdownlint DEPLOY.md