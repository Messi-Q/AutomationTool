# Automation Tool

This is the automation tools for generating code gadgets and graphs from programs automatically.
Currently the tool is limited to the solidity program. In future research, we will make the tool suitable for more programming languages, including C/C++, java, etc.
It is worth mentioning that our work is mainly aimed at the analysis of smart contracts, include [Ethereum](https://etherscan.io/) solidity and [VNT](http://www.vntchain.io/) C/C++.

## Code Files

`automatic_generate_code_fragment.py`: Used to extract code fragments from key information of the program, namely code fragment.

`automatic_generate_graph.py`: Used to extract key information of the program into graph data, mainly edges and points.

`UtilTool/delete_comment_officail.py`: Used to remove comments from the program, like '//' and '/**/'.

## Usage

We mainly use this tool to extract key information from the program and make dataset for deep learning techniques. 
The method of our tool will be introduced in a later paper.