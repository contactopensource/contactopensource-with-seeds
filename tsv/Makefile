default:
	jq '.artists[] | [.id, .attributes[]] | join("\t")' -r ../api.json > artists.tsv
	jq '.movies[]  | [.id, .attributes[]] | join("\t")' -r ../api.json > movies.tsv
	jq '.offers[]  | [.id, .attributes[]] | join("\t")' -r ../api.json > offers.tsv
	jq '.persons[] | [.id, .attributes[]] | join("\t")' -r ../api.json > persons.tsv 
	jq '.posts[]   | [.id, .attributes[]] | join("\t")' -r ../api.json > posts.tsv
	jq '.sports[]  | [.id, .attributes[]] | join("\t")' -r ../api.json > sports.tsv
