# blockchain-reference

Documentation from blockchain certification and personal research

Solidity Variable types
   Declared variable types
   
   contract VariableTypes {  
     // Fixed Size types
          bool isReady; 
          uint a; 
          address recipient;
          bytes32 data; 
          
     // Variable Size types 
        string name; 
        bytes _data; 
        uint[] amounts; // array elements must be of same type 
        mapping(uint => string) users;  // key => value 
        
     // User Defined data
        struct User {
          uint id; 
          string name; 
          uint[] friendIds;
        }
        enum Color {
          RED,
          GREEN,
          BLUE
        }
     
     // Built in Variable Types
     
     contract BuiltInVars {
      msg.sender
      msg.value
     }
      
   }
   
Constructors

contract MyContract {
  uint a; 
  
  constructor(uint _a) public {
   a = _a; 
  }
}


Declaring Functions

contract Functions {

}
     
