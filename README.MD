# about the last review

  - getBlockHeight() will give you the new height for a new block, not the current height. the functionality is working fine.
  
  - You said, "You are returning the number of blocks that are in the chain" which is false.
I'm reading a stream of keys "createReadStream({ reverse: true, keys: true, values: false })"
and I return the biggest key + 1 (as a height for a new block).

  - getBlockHeight() will be a bad implementation if blockchain supports deleting blocks.
other than that it's working fine.

  - when I add a new block for the first time the addBlock function will first create a genesis block.
  - your code review is just an opinion.
  - the code is working fine.
