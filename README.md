# shopee

# Syntax

python Shopee -o "outputFileName.csv" -p "2000" -s "indonesia" -k "Nike shoes"

Argument's details


"--output", "-o", help="set output file name") -> must be in csv formate
# default is output.csv
"--numberOfProducts", "-p", help="Set Number of Scraped Products") 
# default is 200
"--site", "-s", help="Set Domain of Shopee")=> valid inputs are  "indonesia | co.id | vietnam|vn |singapore|sg" 
# default is singapore

"--keyword", "-k", help="Search keyword")
# required*
