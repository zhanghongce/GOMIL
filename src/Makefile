GUROBI_INCLUDE = "/home/hongcez/gurobi1200/linux64/include/"
GUROBI_LIB = "/home/hongcez/gurobi1200/linux64/lib"
SRC = Adder_Tree_Optimization.cpp Multiplier_Tree_Optimization.cpp main.cpp
HEADER = Adder_Tree_Optimization.h Multiplier_Tree_Optimization.h

main: $(SRC) $(HEADER)
	g++ -I$(GUROBI_INCLUDE) -L$(GUROBI_LIB) $(SRC) -lgurobi_c++ -lgurobi120 -o main
  
  
