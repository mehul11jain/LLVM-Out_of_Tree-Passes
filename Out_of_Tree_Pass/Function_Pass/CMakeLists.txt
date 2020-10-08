add_llvm_library(LLVMHello MODULE
  Hello.cpp
  IRConstructPass.cpp
  ../IR_Abstraction/Arith_IR_Stmt.cpp
  ../IR_Abstraction/Branch_IR_Stmt.cpp	
  ../IR_Abstraction/Call_IR_Stmt.cpp	
  ../IR_Abstraction/IR_Stmt.cpp	
  ../IR_Abstraction/Label_IR_Stmt.cpp	
  ../IR_Abstraction/Load_IR_Stmt.cpp	
  ../IR_Abstraction/Logical_IR_Stmt.cpp	
  ../IR_Abstraction/Return_IR_Stmt.cpp
  ../IR_Abstraction/Store_IR_Stmt.cpp	
  PLUGIN_TOOL
  opt
)
# cmake -DLT_LLVM_INSTALL_DIR=$LLVM_DIR ..