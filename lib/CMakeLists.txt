add_subdirectory(AST)
add_subdirectory(ASTSectionImporter)
add_subdirectory(Basic)
add_subdirectory(ClangImporter)
add_subdirectory(Driver)
add_subdirectory(Frontend)
add_subdirectory(Index)
add_subdirectory(IDE)
add_subdirectory(Immediate)
add_subdirectory(IRGen)
add_subdirectory(LLVMPasses)
add_subdirectory(Markup)
add_subdirectory(Option)
add_subdirectory(Parse)
add_subdirectory(PrintAsObjC)
add_subdirectory(Sema)
add_subdirectory(Serialization)
if(CMAKE_SYSTEM_NAME STREQUAL "Darwin")
  add_subdirectory(SwiftDemangle)
endif()
add_subdirectory(SIL)
add_subdirectory(SILGen)
add_subdirectory(SILOptimizer)

