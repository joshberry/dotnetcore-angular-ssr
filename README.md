The goal of this project was to create and configure a minimal spa setup with the following attributes:
- Latest version of ASP.NET Core (2.2)
- Latest version of Angular (7)
- SSR using Angular Universal
- No need to deploy node_modules folder for SSR

The project was created in 3 steps. See the commit history for specific file changes.

1. Create a base ASP.NET Core web application
```
dotnet new web
```

2. Create a base client app using Angular CLI
```
ng new ClientApp
```

3. Configure ASP.NET to host client app and perform server side prerendering. See commit https://github.com/joshberry/dotnetcore-angular-ssr/commit/952f37cfde11c8fa80e36d6982887133e6c3fd55.
