### Overview
The `integration_test` data product allows for customer to test their ability to integrate into the sonar customer data processing system. This is done by providing a very simple schema for the input data. The customer can then generate input data on their end (or use the included sample data file) which matches this schema, upload the data, and verify that an output file was produced. 

### Input
A csv file, delimited via commas, is expected to be provided as input. The file should contain columns matching the described columns in the `schema.json` file.

### Output
A csv file is produced which contains each record from the provided input file, but with each records `rpm` value multiplied by two. 
