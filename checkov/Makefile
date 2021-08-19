checkov:
	docker build -t checkov .

smoke-test: checkov
	docker run checkov
