# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a robust generalized linear model Use glmRob (robust) With (In) R Software
install.packages("robust")
library("robust")
glmRob = read.csv("https://raw.githubusercontent.com/timbulwidodostp/glmRob/main/glmRob/glmRob.csv",sep = ";")
# Estimation Fit a robust generalized linear model Use glmRob (robust) With (In) R Software
glmRob <- glmRob(sumY ~ Age10 + Base4*Trt, family = poisson(), data = glmRob, method = "cubif")
summary(glmRob)
# Fit a robust generalized linear model Use glmRob (robust) With (In) R Software
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished