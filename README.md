# FR_Reg_sans_Mayotte
France sans Mayotte


mygrid <- data.frame(
  REGION = c("GUADELOUPE", "HAUTS-DE-FRANCE", "ILE-DE-FRANCE", "MARTINIQUE", "NORMANDIE", "BRETAGNE", "GRAND EST", "BOURGOGNE-FRANCHE-COMTE", "GUYANE", "PAYS DE LA LOIRE", "CENTRE-VAL DE LOIRE", "AUVERGNE-RHONE-ALPES", "PROVENCE-ALPES-COTE D'AZUR	", "LA REUNION", "NOUVELLE-AQUITAINE", "OCCITANIE", "CORSE"),
  row = c(1, 1, 2, 2, 2, 2, 2, 2, 3, 3, 3, 3, 4, 4, 4, 4, 5),
  col = c(8, 3, 3, 8, 2, 1, 5, 4, 8, 2, 3, 4, 4, 8, 2, 3, 6),
  stringsAsFactors = FALSE
)
geofacet::grid_preview(mygrid)

