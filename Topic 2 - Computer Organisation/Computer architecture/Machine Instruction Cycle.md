- Fetch
	- The [[CU]] moves the address of the instructions it wants to execute from the [[RAM]] to the [[MAR]] through the memory address bus. 
- Decode
	- The instructions are decoded in the [[CU]], allowing for the CPU to be aware of additional data needed for the execution of the instructions. 
	- The [[CU]] moves required data for the instructions to run from the [[RAM]] to the [[MDR]]. 
- Execute
	- The [[CU]] tells the [[ALU]] to execute the instructions. 
	- The required data gets sent to the [[ALU]] through the data bus. 
- Store
	- The results of the instructions move from the [[ALU]] to the [[MDR]] through the data bus. 
	- The fetch-decode-execute cycle begins again. 