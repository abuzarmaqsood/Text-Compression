# Text-Compression

A Text Compression software that helps zip/Unzip files using these 2 algorihtms:

1. Huffmans Code
2. Lempel-Ziv-Wells algorithm

# About Huffmans Code

The Huffmans algorithm creates a 1-1 mapping for each byte of the input file 
and replaces each byte with the mapped bit sequence. For this you need 
to store a dictionary that describes each 1-1 mapping of input byte and
binary sequence.(which needs extraspace)

# About Lempel-Ziv-Wells

Unlike Huffmans code LZW dont need an extra dictionary to be saved. Also
LZW does not create a mapping to byte to bin sequence. It creates mapping
of multiple byte to binary sequence.

## Running Instruction:

## Zip a file
file>open>click zip>the zipped file will be created on the same folder


## Unzip a file
file>open>click unzip>the unzipped file will be created on the same folder

