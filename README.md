# LIDE_ESPOL_George_Jaramillo
#Repositorio para las pasantías LIDE
#Pregunta de investigacion: "Para determinar el ingreso de una persona, ¿prevalece mas un año de         experiencia o un año de estudio despues del grado?

if(!require(tidyverse))install.packages("tidyverse",repos="https://cran.us.r-project.org")
if(!require(readstata13))install.packages("readstata13",repos="https://cran.us.r-project.org")
library("readxl")
data<-read.csv2("C:/Users/User/Desktop/CARPETAS DE ESCRITORIO/ESPOL/Practicas Profesionales/LIDE_ESPOL_George_Jaramillo/Base_Match_dic18_dic19.csv", header=FALSE)
