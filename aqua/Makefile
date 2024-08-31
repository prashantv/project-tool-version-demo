.PHONY: bootstrap
bootstrap:
	# verify that aqua is in the path
	aqua

.PHONY: list-packages
list-packages:
	bin/yq '.packages' < aqua.yaml
