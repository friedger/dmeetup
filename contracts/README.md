# dMeetup Contracts

## Getting Started

- install eosio https://github.com/eosio/eos  
- install eosio.cdt https://eosio.github.io/eosio.cdt/latest/index 

## Build and Deploy

- cd to `build/` directory
- run the command `cmake ..`
- run the command `make`
 
After build 
 
- The built smart contract is under the 'kanbankanban' directory in the 'build' directory
- You can then do a 'set contract' action with 'cleos' and point in to the './build/kanbankanban' directory

Additions to CMake should be done to the CMakeLists.txt in the './src' directory and not in the top level CMakeLists.txt

