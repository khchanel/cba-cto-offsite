CBA CTO Offsite test
=======
[![Build Status](https://travis-ci.org/khchanel/cba-cto-offsite.svg?branch=master)](https://travis-ci.org/khchanel/cba-cto-offsite)

[Specification Here](spec.pdf)

The solution is implemented as a C# .NET core 2.1 console app

## Development setup
You will need .net core >=2.1
You may use Visual Studio or dotnet command:


### Build

```
dotnet restore
dotnet build
```

### Test
To run unit tests

```
dotnet test
```

### Run
Launch app using dotnet command

```
dotnet run --project=CbaOffsite
```
The app will execute once and generate result, and then watch on rules.xml config file for changes.  
If it detect a change, the app will re-run with the new rules.  

Note that you will need to have Rules.xml and TestInput.txt file in current directory to work
alternatively just run in Visual Studio :)
