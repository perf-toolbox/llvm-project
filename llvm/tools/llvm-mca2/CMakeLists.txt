set(LLVM_LINK_COMPONENTS
  AllTargetsAsmParsers
  AllTargetsMCAs          # CustomBehaviour and InstrPostProcess
  AllTargetsDescs
  AllTargetsDisassemblers
  AllTargetsInfos
  MCA
  MC
  MCParser
  Support
  TargetParser
  )

add_llvm_tool(llvm-mca2
  llvm-mca2.cpp
  )

set(LLVM_MCA2_SOURCE_DIR ${CURRENT_SOURCE_DIR})

