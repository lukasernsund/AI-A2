# Artificial Intelligence - Assignment 2
Where's Croc assignment 2 in Uppsala University Artificial Intelligence course (1DL340)

Instruction to get started:
install.packages("WheresCroc_1.2.2.tar.gz",repos = NULL, type= "source")
library(WheresCroc)
runWheresCroc(manualWC, doPlot = T)


To test function:
testWC(myFunction, verbose = 1, n = 500)


optimize
- search on path if prob is high
- Make sure to 0 out the probabilities of locations when you search them: If Croc is there and you search, the game ends; if it isn’t, then you know Croc isn’t there!
- 