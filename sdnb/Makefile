BARTOC=http://bartoc.org/en/node/20049
include ../Makefile

$(CONCEPTS): sdnb-concepts.csv $(SCHEME) 
	$(jskos-convert) concepts -l de -f csv -s $(SCHEME) -m $< > $@
