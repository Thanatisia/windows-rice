# Windows Guides & Scripts - Rice

Repository created for all Windows Guides and Scripts related to Ricing on Windows

## Table of Contents
- Background
- File Structure
- Obtaining
- Usage

## Background

## File Structure
- Root
    > [Fonts](Fonts)
	- Hack-v2.1.0
    > [registry-scripts](registry-scripts)

## Obtaining

- Git Repository Cloning
	```
	Syntax: git clone [repository_url]
	```
	git clone https://github.com/Thanatisia/windows-rice

- File-Only
	```
	- Download via curl
		Syntax: curl -L -O [file_raw_url] [filename (optional)]
	```
	curl -L -O "https://raw.githubusercontent.com/Thanatisia/windows-rice/main/[filename]"

## Usage

- Fonts
    - To change fonts
    	- Copy your fonts from your folder and paste into 'C:/Windows/Fonts'
    	- Edit Registry Editor Script 'change-to-personal-font.reg'
		- Change "[your-font_name-here]" into your target font name
			> Examples:
				- Hack Nerd Font
				- Hack Nerd Font Mono
	- Restart Computer for font change to take effect

    - To change your fonts back to system default
	- Run Registry Editor Script 'restore-system-font.reg'
	- Restart Computer for font change to take effect

