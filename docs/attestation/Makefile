all: amd/sev/certchain.dot.png amd/sev/process.msc.png ibm/pef/certchain.dot.png ibm/pef/process.msc.png ibm/pef/process-1.msc.png ibm/pef/process-2.msc.png

%.dot.png: %.dot
	dot -T png -o $@ $<

%.msc.png: %.msc
	mscgen -T png -o $@ $<
