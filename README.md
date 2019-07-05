#' @name pistachio-anthracnose
#' @title Characterization studies of \emph{Colletotrichum karstii} and \emph{C. fioriniae} causing the pistachio anthracnose in 
#' California
#' @description Optimal Germination Temperature (\% of germinated conidia of \emph{Colletotrichum karstii} (Ck, n=1) and \emph{C.
#' fioriniae} (Cf, n=6) after 6 and 12 hours, incubated at six different temperatures (10, 15, 20, 25, 30 and 35 Celsius degree). For
#' each combination of isolate (n=6) and temperature (n=6), 50 ul of conidial suspension at concentration of 10^5 were transferred to
#' three water agar plates (2% WA). plates were identified and incubated. Six and twelve hours after assay preparation the number of
#' germinated conidia was counted out of 50 conidias. Experiment was replicated three times).      
#'
#' @format Um \code{data.frame} with 756 lines and 8 collunms, where
#'
#' \describe{
#'
#' \item{\code{exp}}{factor variable for experiment replication. Experiment was performed three times.}
#'
#' \item{\code{spp}}{factor variable for pathogen species. In total two \emph{Colletotrichum} species were used, Ck (n=1) and Cf (n=6).}
#'
#' \item{\code{tim}}{factor variable for time of incubation prior evaluations. The first evaluation was made 6 hours after incubation.
#' When the evaluation was finished, plates were re-incubated until reach 12 hours. At the 12^th hour, plates were again evaluated under
#' mycroscopy.}
#'
#' \item{\code{iso}}{factor variable for isolate code. As previously mentioned Cf included six isolates: 11J23, 11K11, 11K17, 12D46,
#' 12J05 and 12J41, while Ck included only the isolate 3G23.}
#'
#' \item{\code{tem}}{Integer variable for temperature of incubation. In total, six temperatures were used, from 10 to 35 Celcius degre.}
#' 
#' \item{\code{rep}}{Integer variable for experimental unit repetition. In total, three plates were prepared per combination of isolate
#'and temperature.}
#' 
#' \item{\code{ger}}{numeric variable for the number of germinated conidia. the number of germinated conidia (germinative tube =< than
#'conidia size) was counted our of 50 conidia. Lost values are reported as \code{NA}}
#' 
#' \item{\code{of}}{numeric variable for the total number conidia counted. Total number of conidia counted from where germination
#'frequency was made.}
#'
#' }
#'
#' @source Lichtemberg,
#'     P. S. F. (\url{https://www.researchgate.net/profile/Paulo_Lichtemberg}), Michailides,
#'     T. J. (\url{https://ucanr.edu/?facultyid=1535}), Zeviani W. M. (\url{http://leg.ufpr.br/~walmes/home/}).
#' University of California Davis, Department of Plant Pathology,
#' Universidade Federal do Paraná, Department of Statistics.
#'
#' @examples
#'
#'
NULL
