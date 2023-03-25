# docker-image-flutter

Flutter docker image for Github Codespaces

## Dev container

This repository aims to give public example of a completlly configured dev container for Flutter developpment usage in Gihub Codespaces

## Vscode settings

This repository also contains a vscode settings values to configure the Flutter extension for vscode

Predefined settings:

- color theme: Community Material Theme
- icon theme: Material Icon Theme
- dart: format on save
- autoSave: onFocusChange

See [devcontainer.json](.devcontainer/devcontainer.json) for details.

## Vscode extensions

This repository also contains a vscode extensions list to configure the Flutter extension for vscode

Used extensions:

- bloc
- community material theme
- material theme icons
- material theme
- material icon theme
- dart code
- flutter
- github copilot
- rapid api
- git lens
- error lens
- version lens
- makdown lint

See [devcontainer.json](.devcontainer/devcontainer.json) for details.

## Links

[devcontainer documentation](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/setting-up-your-project-for-codespaces)

Thanks to Cirrus CI and Codemagic for examples and documentations

- [Cirrus CI docker-image-flutter](https://github.com/cirruslabs/docker-images-flutter)
- [Codemagic Flutter Dockerfile blog post](https://blog.codemagic.io/how-to-dockerize-flutter-apps/)
- [Publishing Docker to github packages](https://docs.github.com/en/actions/publishing-packages/publishing-docker-images#publishing-images-to-github-packages)
- [Pulling Docker from private registry](https://linuxhint.com/pull-docker-image-from-private-registry/)
- [Wokring with the Container registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry)
