# Bild windows GUI App with VS code

## Setup

1. Install Visual Studio Code <https://code.visualstudio.com/download>
2. Download and install .NET 5.0 <https://dotnet.microsoft.com/download>

## Build exe

```
cd Simple
dotnet publish -c Release -r win-x64
```

`bin\Release\net5.0-windows\win-x64\publish\Simple.exe` will be created.

copy publish directory to run Simple.exe. 

----
Takashi Masuyama < mamewotoko@gmail.com >  
https://mamewo.ddo.jp/
