# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Cumulative Link Models for Ordinal Regression Use clm (ordinal) With (In) R Software
install.packages("ordinal")
library("ordinal")
clm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/clm/main/clm/clm.csv",sep = ";")
# Estimation Cumulative Link Models for Ordinal Regression Use clm (ordinal) With (In) R Software
clm <- clm(as.factor(rating) ~ temp + contact, data = clm)
summary(clm)
# Cumulative Link Models for Ordinal Regression Use clm (ordinal) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished