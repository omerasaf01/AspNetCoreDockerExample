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

- Software Community: https://discord.gg/dehETrV8HT
- Contact Email: omerconsept999@gmail.com

Please report bugs or errors