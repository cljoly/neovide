.PHONY: content_update
content_update:
	@mkdir -p static/assets
	@cp -r ../assets static/
	@awk -f ./riss.awk < ../README.md >content/_index.md

all: content_update
	@zola build

serve: content_update
	@zola serve
