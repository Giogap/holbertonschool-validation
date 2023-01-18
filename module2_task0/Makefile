.SILENT:
help: ## implemente and print a list of all the goals
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'

build: ## Compiles the source code
	@go mod init github.com/paosua86/awesome-api
	@go build

run: ## Runs the application in background
	@./awesome-api >./awesome.log 2>&1 &

stop: ## Stops the application
	@kill $(shell pgrep awesome-api)

clean: ## Delete
	@make stop
	@rm -r awesome-api
	@rm -r awesome.log

test: ## Tests the application
	@curl http://localhost:9999
	@curl http://localhost:9999/health