# aws-cheatsheet
Cheatsheet for Amazon AWS Services

## Sample Lambda Function
- create Lambda function in AWS Management Console
- install .NET 
- install Amazon Lambda templates
```dotnet new -i Amazon.Lambda.Templates::*```
- install Amazon.Lambda.Tools dotnet tool
```dotnet tool install --global Amazon.Lambda.Tools```
- create new Lambda project from template
```dotnet new lambda.EmptyFunction```
- implement stuff + build
- deploy function to AWS
```dotnet-lambda deploy-function FUNCTION_NAME```
- (optional) invoke function
```dotnet-lambda invoke-function FUNCTION_NAME --payload```
