# Apt

## Ajuda do Apt

'''
apt 2.6.1 (amd64)
Usage: apt [options] command

apt is a commandline package manager and provides commands for
searching and managing as well as querying information about packages.
It provides the same functionality as the specialized APT tools,
like apt-get and apt-cache, but enables options more suitable for
interactive use by default.

Most used commands:
  list - list packages based on package names
  search - search in package descriptions
  show - show package details
  install - install packages
  reinstall - reinstall packages
  remove - remove packages
  autoremove - automatically remove all unused packages
  update - update list of available packages
  upgrade - upgrade the system by installing/upgrading packages
  full-upgrade - upgrade the system by removing/installing/upgrading packages
  edit-sources - edit the source information file
  satisfy - satisfy dependency strings

See apt(8) for more information about the available commands.
Configuration options and syntax is detailed in apt.conf(5).
Information about how to configure sources can be found in sources.list(5).
Package and version choices can be expressed via apt_preferences(5).
Security details are available in apt-secure(8).
                                   Este APT tem Poderes de Super Vaca.
'''

## Exemplos

- 'sudo apt update'
- 'sudo apt install -y nano'


## tlrd

'''

tldr - Simplified and community-driven man pages

Usage: tldr [-v|--version] 
            ((-u|--update) | [-p|--platform PLATFORM] [-L|--language LOCALE]
              COMMAND |
              (-a|--about)) [--auto-update-interval DAYS] [--color | --no-color]
  tldr Client program

Available options:
  -h,--help                Show this help text
  -v,--version             Show version
  -u,--update              Update offline cache of tldr pages
  -p,--platform PLATFORM   Prioritize a specific platform while searching. Valid
                           values include linux, osx, windows, sunos
  -L,--language LOCALE     Preferred language for the page returned
  COMMAND                  name of the command
  -a,--about               About this program
  --auto-update-interval DAYS
                           Perform an automatic update if the cache is older
                           than DAYS
  --color                  Force colored output, overriding the NO_COLOR
                           environment variable
  --no-color               Disable colored output
'''

## Exemplos de tlrd

- 'tlrd apt'
- 'tlrd cat'

Mostra o que o comando faz de forma resumida
