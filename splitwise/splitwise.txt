# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Hybrid stepwise regression with interpretable single-split dummy encoding and optional iterative selection Use splitwise With (in) R Software
install.packages("remotes")
remotes::install_github("mtkurbucz/SplitWise")
library("SplitWise")
# Estimate Hybrid stepwise regression with interpretable single-split dummy encoding and optional iterative selection Use splitwise With (in) R Software
splitwise = read.csv("https://raw.githubusercontent.com/timbulwidodostp/splitwise/main/splitwise/splitwise.csv",sep = ";")
splitwise_ <- splitwise(splitwise ~ splitwise_1 + splitwise_2 + splitwise_3, data = splitwise, mode = "univariate")
splitwise__ <- splitwise(splitwise ~ splitwise_1 + splitwise_2 + splitwise_3, data = splitwise, mode = "iterative")
summary(splitwise_)
summary(splitwise__)
# Hybrid stepwise regression with interpretable single-split dummy encoding and optional iterative selection Use splitwise With (in) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished