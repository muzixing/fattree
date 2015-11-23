# Fattree Topo

This repository contains a fattree topo scripts of mininet.

You can run it to create a fatree topology. The default value of arguments is (pod=8, host desity=4), which means that the number of pod is 8 while 4 host access to each access switch.

The style of switch name shows below:
  
  * S1XXX: core switches
  * S2XXX: aggregation switches
  * S3XXX: edge switches

### Getting started

	git clone https://github.com/muzixing/fattree.git
	cd fatree
	python fatree.py


