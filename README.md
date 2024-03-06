# Assignment
*Iterate through each row in the input file.
*store each row in the form of a date as a key and values as compensation, review, and engagement.
*sort the map by the date, Now again iterate through each key in the map.
*The first row values are fixed by Employee Code, Manager Employee Code, Compensation, and Effective Date as joining date.
*Through iterating in the map when we encounter a review, engagement, and compensation by their values, we start updating these values reviews, engagement, and compensation by keeping other values as previous row values.
*The new row is appended to data(the output file).
*At last, the end date values are taken from the Effective Date, By taking the next row of Effective Date date minus one day.
