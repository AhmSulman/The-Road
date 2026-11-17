# The Road

A to-do list app built with **.NET MAUI** using the **MVVM** pattern, with tasks stored locally in SQLite.

![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## Features

- Create, view and edit to-do items
- Persists tasks locally with SQLite
- MVVM structure: ViewModels injected into views and bound through `BindingContext`

## Structure

```
The Road/
  Models/TheRoadItem.cs   to-do item model
  Views/                  MainView (list), ItemView (detail / edit)
  MauiProgram.cs          DI registration
```

## Build

Open `The Road.sln` in Visual Studio 2022 with the .NET MAUI workload installed, then run on Android or Windows.

## License

Boost Software License 1.0
