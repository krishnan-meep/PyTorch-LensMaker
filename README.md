# PyTorch-LensMaker

LensMaker is a Pytorch Class Generation GUI built using Tkinter. Turns user provided architecture
specifics into Pytorch Classes, saves the hassle of writing repetitve code for new models. 

Follows really simple text replacement rules to build classes.

It may be pretty buggy at the moment. Haven't cross checked many possible model types. Don't use
delete yet.

## Things to be done
- Save and load architectures
- Specification of multiple inputs and dimensions
- Implement a smarter UI, crosscheck dimensions from layer to layer, especially with the delete
	function. That leads to softlocks.
- Graph Visuals
- Additional PyTorch modules