# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Mixed Effects Regression for Linear, Non-Linear and User-Defined Models Use merlin With (In) R Software
install.packages("merlin")
library("merlin")
merlin = read.csv("https://raw.githubusercontent.com/timbulwidodostp/merlin_r/main/merlin_r/merlin_r.csv",sep = ";")
# Estimation Mixed Effects Regression for Linear, Non-Linear and User-Defined Models Use merlin With (In) R Software
merlin <- merlin(logb ~ year, family = "gaussian", data = merlin)
summary(merlin)
# Mixed Effects Regression for Linear, Non-Linear and User-Defined Models Use merlin With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished