# Asp.Net Core 6.0 Simple Register Login App From Docker

## Usage

### Usage in Docker

#### Building

```
$ docker build -t exampleapp -f Dockerfile .
```

#### Run

```
$ docker run exampleapp
```

if you want it to run in the background

```
$ docker run -d exampleapp
```

### Usage Normal

#### Building

```
$ dotnet publish "AspNetCoreDockerExample.csproj" -c Release -o /app/publish
```

#### Run

```
$ cd /publish
$ dotnet AspNetCoreDockerExample.dll
```

### Contact

- Contact Email: omerasafkarasu06@gmail.com

Please report bugs or errors
