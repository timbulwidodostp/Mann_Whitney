# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Mann Whitney U Test In R Software
install.packages("coin")
install.packages("exactRankTests")
library("coin")
library("exactRankTests")
Mann_Whitney = read.csv("https://raw.githubusercontent.com/timbulwidodostp/Mann_Whitney/main/Mann_Whitney/Mann_Whitney.csv",sep = ";")
Mann_Whitney = read.table("https://raw.githubusercontent.com/timbulwidodostp/Mann_Whitney/main/Mann_Whitney/Mann_Whitney.csv",sep = ";"
,header=TRUE, stringsAsFactors=TRUE, text="")
# Estimate Mann Whitney U Test In R Software
wilcox.test(Result ~ Group, data=Mann_Whitney)
wilcox_test(Result ~ Group, data=Mann_Whitney, distribution = "exact")
wilcox_test(Result ~ Group, data=Mann_Whitney, distribution = "approximate")
wilcox.exact(Result ~ Group, data=Mann_Whitney, exact=TRUE)
# Mann Whitney U Test In R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished