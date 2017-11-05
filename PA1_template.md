# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
fileUrl <- "https://d396qusza40orc.cloudfront.net/repdata/data/activity.zip"
download.file(fileUrl, destfile="./RepResActivity.zip")
unzip("RepResActivity.zip")
activity <- read.csv("activity.csv")
```



## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
