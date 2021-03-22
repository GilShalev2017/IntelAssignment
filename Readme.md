## Fd19ControllersApi
by Maxim Tsarenko & Gil Shalev

## Publish

```
    dotnet lambda deploy-serverless --name Fd19ControllerApi --region eu-central-1 --s3-bucket fd19-controller-api-2
```

## Environment variables

```
    "DYNAMO_DB_PROGRAMS": "fd-controller-programs",
    "DYNAMO_DB_FLOWS": "fd-controller-flows",
    "DYNAMO_DB_TASKS": "fd-controller-tasks",
    "AWS_REGION": "eu-west-1",
    "PROGRAMS_BUCKET": "fd-controller-application-bucket",
    "PROGRAMS_BUCKET_REGION": "eu-west-1"
```

## Link to skeleton readme

https://github.com/aws-samples/aws-codepipeline-dotnet-lambda/blob/master/DotnetCliSample/Dotnetlambda4/src/Dotnetlambda4/Readme.md

## Here are some steps to follow to get started from the command line:

Install Amazon.Lambda.Tools Global Tools if not already installed.
```
    dotnet tool install -g Amazon.Lambda.Tools
```

If already installed check if new version is available.
```
    dotnet tool update -g Amazon.Lambda.Tools
```

Execute unit tests
```
    cd "Fd19ControllerApi/test/Fd19ControllerApi.Tests"
    dotnet test
```

Deploy application
```
    cd "Fd19ControllerApi/src/Fd19ControllerApi"
    dotnet lambda deploy-serverless
```
"# IntelAssignment" 
