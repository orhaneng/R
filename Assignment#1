DBDA.X404.(8) - Assignment#1
Omer Orhan
5 Ekim 2018
#QUESTION1;
#What are the different steps of data analysis
#and what is done during each step

#answer;
#The steps of data analysis are Design, Obtain Data, Data Prep, Analyze, Fine Tune,present.

# Design: Gather requirements
# Obtain Data: Data collection
# Data Prep: Data exploration, preview, and selection, preprocessing, cleaning and preparation.
# Analyze: Data normalization and transformation
# Fine Tune: Gather and analyze results
# Present: present the results
#QUESTION2. What are the different ways to create a vector in R?
x <- 1:7; x
## [1] 1 2 3 4 5 6 7
x <- seq(1, 3, by=0.2); x
##  [1] 1.0 1.2 1.4 1.6 1.8 2.0 2.2 2.4 2.6 2.8 3.0
x <- c(1, 5.4, TRUE, "hello"); x
## [1] "1"     "5.4"   "TRUE"  "hello"
#QUESTION3:Create the following vector and check the class (‘x’,’x’, ‘x’, 1,3,5,7,9,2,4,6,8,10)
Q3 <- c(rep(c('x'), times = 3),1:10)
Q3
##  [1] "x"  "x"  "x"  "1"  "2"  "3"  "4"  "5"  "6"  "7"  "8"  "9"  "10"
class(Q3)
## [1] "character"
#QUESTION4:Create a vector of positive odd integers less than 100
x<-seq(1,100, by =2); x
##  [1]  1  3  5  7  9 11 13 15 17 19 21 23 25 27 29 31 33 35 37 39 41 43 45
## [24] 47 49 51 53 55 57 59 61 63 65 67 69 71 73 75 77 79 81 83 85 87 89 91
## [47] 93 95 97 99
#QUESTION5:Remove the values greater than 60 and less than 80
x2 <- x[!x %in% 60:80]; x2
##  [1]  1  3  5  7  9 11 13 15 17 19 21 23 25 27 29 31 33 35 37 39 41 43 45
## [24] 47 49 51 53 55 57 59 81 83 85 87 89 91 93 95 97 99
#QUESTION6:Write a function to return standard deviation, mean, and median of the vector. Verify with example.
 Q6 <-function(input) {
     
     sd= sd(input)
     med = median(input)
     mea = mean(input)
     output<-list("standart deviation:"=sd,"mean="=med,"median="=mea)
     return(output) }
 
 x<-seq(1,100, by =2); 
 x2 <- x[!x %in% 60:80]
 res <- Q6(x2)
 res
## $`standart deviation:`
## [1] 30.51691
## 
## $`mean=`
## [1] 40
## 
## $`median=`
## [1] 45
#QUESTION7:Create two matrices of the from the given set of numbers} in two ways X1 = {2,3,7,1,6,2,3,5,1} and x2 ={3,2,9,0,7,8,5,8,2}

mat1 = matrix(c(2,3,7,1,6,2,3,5,1), nrow=3, ncol=3, byrow = TRUE) 
mat1
##      [,1] [,2] [,3]
## [1,]    2    3    7
## [2,]    1    6    2
## [3,]    3    5    1
mat2 = matrix(c(3,2,9,0,7,8,5,8,2), nrow=3, ncol=3) 
mat2
##      [,1] [,2] [,3]
## [1,]    3    0    5
## [2,]    2    7    8
## [3,]    9    8    2
#QUESTION8:Find the matrix product
 matProduct <- mat1 %*% mat2
 matProduct
##      [,1] [,2] [,3]
## [1,]   75   77   48
## [2,]   33   58   57
## [3,]   28   43   57
#QUESTION9: Find the class of ‘iris’ dataframe, find the class of all the columns of ‘iris’ get the summary. Get rownames, column names. Get the number of rows and number of columns.

class(iris)
## [1] "data.frame"
summary(iris)
##   Sepal.Length    Sepal.Width     Petal.Length    Petal.Width   
##  Min.   :4.300   Min.   :2.000   Min.   :1.000   Min.   :0.100  
##  1st Qu.:5.100   1st Qu.:2.800   1st Qu.:1.600   1st Qu.:0.300  
##  Median :5.800   Median :3.000   Median :4.350   Median :1.300  
##  Mean   :5.843   Mean   :3.057   Mean   :3.758   Mean   :1.199  
##  3rd Qu.:6.400   3rd Qu.:3.300   3rd Qu.:5.100   3rd Qu.:1.800  
##  Max.   :7.900   Max.   :4.400   Max.   :6.900   Max.   :2.500  
##        Species  
##  setosa    :50  
##  versicolor:50  
##  virginica :50  
##                 
##                 
## 
colnames(iris)
## [1] "Sepal.Length" "Sepal.Width"  "Petal.Length" "Petal.Width" 
## [5] "Species"
rownames(iris)
##   [1] "1"   "2"   "3"   "4"   "5"   "6"   "7"   "8"   "9"   "10"  "11" 
##  [12] "12"  "13"  "14"  "15"  "16"  "17"  "18"  "19"  "20"  "21"  "22" 
##  [23] "23"  "24"  "25"  "26"  "27"  "28"  "29"  "30"  "31"  "32"  "33" 
##  [34] "34"  "35"  "36"  "37"  "38"  "39"  "40"  "41"  "42"  "43"  "44" 
##  [45] "45"  "46"  "47"  "48"  "49"  "50"  "51"  "52"  "53"  "54"  "55" 
##  [56] "56"  "57"  "58"  "59"  "60"  "61"  "62"  "63"  "64"  "65"  "66" 
##  [67] "67"  "68"  "69"  "70"  "71"  "72"  "73"  "74"  "75"  "76"  "77" 
##  [78] "78"  "79"  "80"  "81"  "82"  "83"  "84"  "85"  "86"  "87"  "88" 
##  [89] "89"  "90"  "91"  "92"  "93"  "94"  "95"  "96"  "97"  "98"  "99" 
## [100] "100" "101" "102" "103" "104" "105" "106" "107" "108" "109" "110"
## [111] "111" "112" "113" "114" "115" "116" "117" "118" "119" "120" "121"
## [122] "122" "123" "124" "125" "126" "127" "128" "129" "130" "131" "132"
## [133] "133" "134" "135" "136" "137" "138" "139" "140" "141" "142" "143"
## [144] "144" "145" "146" "147" "148" "149" "150"
nrow(iris)
## [1] 150
ncol(iris)
## [1] 5
#QUESTION10: Get the last two rows in the last 2 columns from iris dataset.
iris[nrow(iris):(nrow(iris)-1),ncol(iris):(ncol(iris)-1)]
##       Species Petal.Width
## 150 virginica         1.8
## 149 virginica         2.3
