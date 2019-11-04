# pulumi-examples
Pulumi examples

## Installing Pulumi
I'm suposing that you are using macOS if not please use the official documentation [Pulumi Docs](https://www.pulumi.com/).

Installation: 
```
$ brew install pulumi
```

To upgrade if necessary:

```
$ brew upgrade pulumi
```

## Configure AWS
Copy from AWS Web UI to past in the terminal:

```
$ export AWS_ACCESS_KEY_ID="YOUR-ACCESS-KEY-ID"
$ export AWS_SECRET_ACCESS_KEY="YOUR-SECRET-ACCESS-KEY"
$ export AWS_SESSION_TOKEN="YOUR-SESSION-TOKEN"
```

## Pulumi Login
To make the login without app.pulumi.com into the root path of the project:

```
$ pulumi login --local
```

## Create a new Project
Prepare to create a project:

```
$ mkdir quickstart && cd quickstart
$ pulumi new aws-python
```