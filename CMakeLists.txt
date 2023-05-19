cmake_minimum_required(VERSION 3.25)
project(RubiksCubeSolver1)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubiksCubeSolver1 main.cpp Model/RubiksCube.cpp Model/RubiksCube.h Model/RubiksCube3dArray.cpp Model/RubiksCube1dArray.cpp Model/RubiksCubeBitboard.cpp Solver/DFSSolver.h Solver/BFSSolver.h Solver/IDDFSSolver.h Solver/IDAstarSolver.h PatternDatabases/NibbleArray.cpp PatternDatabases/NibbleArray.h)
