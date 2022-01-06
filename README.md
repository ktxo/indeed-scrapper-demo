# Indeed Scrapper and Data Analysis (DEMO)

Application to extract and process jobs offers from Indeed (https://www.indeed.com)

----

# Features:
- Extraction of jobs offers based on provided url
- Generate .csv and .xlsx 
- Extract job details for each offer
- Configure  number of pages to extract

Script provides 3 operations:
- **extraction1:** Get a list of jobs offers from url (e.g: https://www.indeed.com/jobs?q=django&vjk=df1cce3cc988f374)
- **extraction2:** For each job from extraction1 get the details  (e.g.: https://www.indeed.com/rc/clk?jk=df1cce3cc988f374&fccid=dd616958bd9ddc12&vjs=3)
- **join_extraction1:** Build a csv/xlsx file combining data from previous **extraction1** and **extration2**
    
    This file can be processed later
 

## Requirements:
- Python 3.x

## Screenshots

### Command Line ![Command line](indeed-cmd.gif)

### Data extraction 1![Data](indeed-x1.gif)

### Data extraction 2![Data](indeed-x2.gif)

### Data join![Data](indeed-j.gif)

### Sample data

See files included in [TEST2.zip](data/TEST2.zip)


