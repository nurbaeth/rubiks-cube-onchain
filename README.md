Rubik's Cube (On-Chain)      
🎯 Fully On-Chain Rubik's Cube Puzzle Game Built with Solidity      
      
Features    
🧩 6 faces, 54 stickers, real 3x3 cube structure   
       
🔄 Rotate any face clockwise with a smart contract call    
       
🎲 Scramble the cube with a random seed  
  
✅ Check if the cube is solved
      
📜 100% on-chain — no off-chain logic or storage
 
🛡️ Gas-optimized and simple design
   
How It Works
Initialization: Each face starts with a single color.
  
Rotation: Rotate faces and manipulate the cube via smart contract functions.
    
Scramble: Randomize the cube using a pseudo-random seed.
 
Solve Check: Automatically validate if the cube is completed. 
    
Smart Contract Functions
   
Function	Description 
rotateFaceClockwise(Face face)	Rotates a selected face clockwise
scramble(uint256 seed)	Scrambles the cube based on seed
isSolved()	Returns true if the cube is solved
