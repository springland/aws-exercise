
##1. Create input and output s3 buckets

###input bucket
springland365-940483669721-codebuilddemo-input

###output bucket
springland365-940483669721-codebuilddemo-output


##2. Upload code
zip the project to codebuildemo.zip , upload it to the input bucket
cd codebuilddemo
zip -r  codebuilddemo.zip *
upload it to springland365-940483669721-codebuilddemo-input

##3. Create build project from console
Select springland365-940483669721-codebuilddemo-input as input bucket
and the file

Use springland365-940483669721-codebuilddemo-output for the output bucket

## Build
The jar file will be placed in the output bucket

