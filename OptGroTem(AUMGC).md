#' @name pistachio-anthracnose (OptGroTem(AUMGC))
#'
#' @title Characterization studies of \emph{Colletotrichum karstii} and \emph{C. fioriniae} causing the pistachio anthracnose in       
#' California
#'
#' @description Optimal Growth Temperature - using the AUMGC (optimal temperature for the mycelial growth of \emph{Colletotrichum karstii}      
#' (Ck, n=1) and \emph{C. #' fioriniae} (Cf, n=6) tested for six different temperatures (10, 15, 20, 25, 30 and 35 Celsius degree).       
#' For each combination of isolate (n=6) and temperature (n=6), three plates (repetitions were prepared). Each repetition received one       
#' mycelial plug of 4 mm from a 5-day-old colony, transferred to the center of a new Acidified PDA plate. Plates were incubated at the        
#' respective temperatures and two perpendicular diameters (mm) were daily measured from day one to day seven. Experiment was repeated      
#' three times).      
#'
#' @format Um \code{data.frame} with 2646 lines and 8 collunms, where
#'
#' \describe{
#'
#' \item{\code{exp}}{factor variable for experiment replication. Experiment was performed three times.}
#'
#' \item{\code{spp}}{factor variable for pathogen species. In total two \emph{Colletotrichum} species were used, Ck (n=1) and Cf (n=6).}      
#'      
#' \item{\code{iso}}{factor variable for isolate code. As previously mentioned Cf included six isolates: 11J23, 11K11, 11K17, 12D46,      
#' 12J05 and 12J41, while Ck included only the isolate 3G23.}
#'
#' \item{\code{rep}}{Integer variable for repetition. Three repetitions (experimental units) were provided for each combination       
#' of isolate and temperature.}      
#'
#' \item{\code{tem}}{factor variable for temperature. Six temperatures were used, from 10 to 35 Celcius degree.}      
#'      
#' \item{\code{day}}{factor variable for number of daily measurements of two perpendicular diameters.}      
#'
#' \item{\code{mm1}}{numeric variable diameter size 1, measured in mm. The NA represent lost data.}       
#'       
#' \item{\code{mm2}}{numeric variable diamenter size 2, measured in mm. The NA represent lost data.}      
#'      
#' }      
#'      
#' @source Lichtemberg,      
#' P. S. F. (\url{https://www.researchgate.net/profile/Paulo_Lichtemberg}), Michailides,      
#' T. J. (\url{https://ucanr.edu/?facultyid=1535}), Zeviani W. M. (\url{http://leg.ufpr.br/~walmes/home/}).      
#' University of California Davis, Department of Plant Pathology,      
#' Universidade Federal do Paraná, Department of Statistics.       
#'      
#' @examples
#' #' NULL
