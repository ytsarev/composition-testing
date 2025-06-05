render-no-observed:
	crossplane render \
  	--include-full-xr \
  	xr.yaml composition.yaml functions.yaml | yq

render-with-observed:
	crossplane render \
  	--observed-resources observed \
  	--include-full-xr \
  	xr.yaml composition.yaml functions.yaml | yq
