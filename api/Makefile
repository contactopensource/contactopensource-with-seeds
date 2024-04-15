default:
	find . -type d -depth 1 | while read x; do pushd "$$x"; jq '.data[] | [.id, .attributes[]] | join("\t")' -r index.json > index.tsv; popd; done