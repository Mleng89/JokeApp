# C# Web application

Attempt at creating a web application using ASP.NET core (MVC)

## Notes:

1. Creation of application using `dotnet new mvc -au Individual` for a MVC web application & individual authentication
2. To run application `dotnet run`

- Will show in terminal what port to go on.
  Currently `https://localhost:7007/` or `http://localhost:5107/`

3. Installed Entity Framework to allow for migrations on existing dbs. `dotnet tool install --global dotnet-ef`
   3a. Updated `.zshrc` file with `export PATH="$PATH:/Users/<username>/.dotnet/tools"` to allow for usage of ef in session.
   3b. `zsh -l` to load configs for coloring

### Issues:

- Visual Studio on macOS compatability is not great (no terminal to migrate data)
- Attempting application with VSC.
