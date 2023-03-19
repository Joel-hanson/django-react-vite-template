# Django React Vite Template

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/Joel-hanson/django-react-vite-template)

This is a template for a Django project with React. This project can also be run using the devcontainer in VSCode.

The devcontainer library files are taken from the [vscode-dev-containers](https://github.com/microsoft/vscode-dev-containers) repository. More about devcontainers can be found [here](https://containers.dev/) and [here](https://github.com/devcontainers).

## Setting up the development container

### GitHub Codespaces

Follow these steps to open this sample in a Codespace:

1. Click the **Code** drop-down menu.
2. Click on the **Codespaces** tab.
3. Click **Create codespace on main** .

For more information on creating your codespace, visit the [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces/creating-a-codespace#creating-a-codespace).

### VS Code Dev Containers

If you already have VS Code and Docker installed, you can click the badge above or [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/Joel-hanson/django-react-vite-template) to get started. Clicking these links will cause VS Code to automatically install the Dev Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.

Follow these steps to open this sample in a container using the VS Code Dev Containers extension:

1. If this is your first time using a development container, please ensure your system meets the prerequisites (i.e. have Docker installed) in the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can either open the repository in an isolated Docker volume:

   - Press <kbd>F1</kbd> and select the **Dev Containers: Try a Sample...** command.
   - Choose the "Python" sample, wait for the container to start, and try things out!
     > **Note:** Under the hood, this will use the **Dev Containers: Clone Repository in Container Volume...** command to clone the source code in a Docker volume instead of the local filesystem. [Volumes](https://docs.docker.com/storage/volumes/) are the preferred mechanism for persisting container data.

   Or open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Dev Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

## Get started

### Running the project

1. Open the project in VSCode
1. Open the terminal in VSCode
1. Run `docker-compose up` to start the project
1. Run `docker-compose exec web python manage.py migrate` to run migrations
1. Run `docker-compose exec web python manage.py createsuperuser` to create a superuser
1. visit `localhost:8000` to view the project with both the frontend and backend

### Running the frontend

1. Open the project in VSCode
1. Open the terminal in VSCode
1. Run `cd frontend` to navigate to the frontend directory
1. Run `npm install` to install the dependencies
1. Run `npm run dev` to start the frontend
1. visit `localhost:3000` to view the frontend only

### Running the backend

1. Open the project in VSCode
1. Open the terminal in VSCode
1. Run `cd backend` to navigate to the backend directory
1. Run `python manage.py migrate` to run migrations
1. Run `python manage.py createsuperuser` to create a superuser
1. Run `python manage.py runserver` to start the backend
1. visit `localhost:8000` to view the backend only

## Features

- [x] Django
- [x] React
- [x] Vite
- [x] Devcontainer
- [x] GitHub Codespaces

## Acknowledgements

- [vscode-dev-containers](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/)
- [Django](https://www.djangoproject.com/)
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
