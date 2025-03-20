# dotfiles

This repository contains configuration files for various tools used in my development environment, including Yabai, SKHD, Komorebi, WKHD, and Neovim. The purpose of this repository is to facilitate easy setup and synchronization of my development environment across multiple computers.

## Description

This repository holds all necessary configuration files that customize and optimize my workflow. The configurations are designed to provide an efficient, user-friendly environment tailored to my preferences. Whether you're setting up a new machine or want to replicate my setup, these configuration files serve as a simple starting point.

## Tools Included

- **Yabai**: A window management tool for macOS that allows for efficient tiling and organization of application windows.
- **skhd**: A simple hotkey daemon for macOS that lets you define keyboard shortcuts to trigger various commands.
- **Komorebi**: A window management tool for Windows that allows for efficient tiling and organization of application windows.
- **whkd**: A simple hotkey daemon for Windows that lets you define keyboard shortcuts to trigger various commands.
- **Neovim**: An extensible text editor designed for developer usability.

## Getting Started

### Prerequisites

Before setting up, ensure you have the following installed on your system:

- Git
- Homebrew (for installing macOS applications)
- The respective applications (Yabai, SKHD, Komorebi, WKHD, Neovim)

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/config-files-repo.git
```

2. Navigate into the project directory:

```bash
cd config-files-repo
```

3. Copy the configuration files to their respective locations. For example:

```bash
cp -r yabai/. ~/.config/yabai/
cp -r skhd/. ~/.config/skhd/
cp -r komorebi/. ~/.config/komorebi/
cp -r wkhd/. ~/.config/wkhd/
cp -r nvim/. ~/.config/nvim/
```

4. Restart any necessary services or applications to load the new configurations.

## Usage
After installing the configurations, you may need to restart your system or specific applications to see the changes take effect. Customize the configurations further as per your requirements.

### Contributing
If you would like to contribute to this repository, please follow these steps:
1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [MIT License](https://github.com/jgdemois/dotfiles?tab=MIT-1-ov-file#) file for details.

## Acknowledgments
Thanks to the creators and maintainers of [Yabai](https://github.com/koekeishiya/yabai), [skhd](https://github.com/koekeishiya/skhd), [Komorebi](https://github.com/LGUG2Z/komorebi), [whkd](https://github.com/LGUG2Z/whkd), and Neovim for their amazing tools that enhance my productivity.

