# ASP.NET Core with React + TypeScript Template

![banner](banner.png)

This template provides a seamless integration of ASP.NET Core with React and TypeScript, enabling a robust full-stack development environment.

**It's essentially the standard ASP.NET Core with React template, restructured and enhanced with TypeScript integration for a more robust and type-safe development experience.**

Follow the steps below to get started:

## Installation

1. Clone the repository:

```bash
git clone https://github.com/LucasMiserez/dotnet-react-ts-template.git
cd dotnet-react-ts-template
```

2. Install the template:

```bash
dotnet new install ./
```

## Creating a New Project

1. Navigate to the desired folder:

```bash
cd [desired_folder]
```

2. Create a new project using the template:

```
dotnet new reactts --name [project_name]
```

## Setting Up the Project

1. Navigate to the client app folder:

```bash
cd [project_name]/ClientApp
```

2. Install dependencies:

```
npm i
```

## Running the Project

1. Navigate back to the root folder of the project:

```
cd ..
```

2. Run the project:

```bash
dotnet run
```

## Note

This template is based on .NET 6. If you prefer to use a newer version, feel free to update as needed.

## Why This Template?

This template was created to provide a streamlined development environment for ASP.NET Core with React and TypeScript. It was born out of a desire to cater to developers who felt that Microsoft's support for ASP.NET Core with React and TypeScript in this specific context might be lacking [(Right now it is only available in Visual Studio 2022 Preview)](https://devblogs.microsoft.com/visualstudio/new-react-typescript-spa-templates-and-more/). By offering a structured and integrated template, the aim is to empower developers seeking a smoother, more efficient workflow without the limitations they might have encountered.
