# `quicksstart_identityserver`

learn identityserver 4

![Version dotnet](https://img.shields.io/badge/Version-dotnet--5.0-blue)
![Build Status](https://img.shields.io/badge/build-Pass-green)


## Usage

dev and prod configurations assume this instance is available on the
localhost. Without a database builds will not be stored.

## Install

```
git clone git@github.com/mmousa8189/quicksstart_identityserver.git
```

#### IdentityServer project first

```bash
cd .\src\IdentityServer\ 
dotnet restore
```

#### Api project

```bash
cd .\src\Api\ 
dotnet restore
```

#### MvcClient project

```bash
cd .\src\MvcClient\ 
dotnet restore
```

#### Console Client project

```bash
cd .\src\Client\ 
dotnet restore
```

### dev (run on dev environment)

#### IdentityServer project first

```bash
cd .\src\IdentityServer\ 
dotnet run
```

#### Api project

```bash
cd .\src\Api\ 
dotnet run
```

#### MvcClient project

```bash
cd .\src\MvcClient\ 
dotnet run
```

#### Console Client project

```bash
cd .\src\Client\ 
dotnet run
```
