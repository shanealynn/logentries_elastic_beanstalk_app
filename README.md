# logentries_elastic_beanstalk_app

Amazon AWS lambda script to upload rotated elastic beanstalk logs from S3 to the Logentries service.

The S3 ingestion script for Amazon applications provided by Logentries will not work for the gzip compressed log files produced by the Elastic Beanstalk log rotation system. This edited script will allow AWS rotated logs to be uploaded successfully.

A blog post describing the problem and the installation of this script is at: www.shanelynn.ie
