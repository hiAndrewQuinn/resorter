# resorter
Simpler to install fork of https://www.gwern.net/Resorter#source-code .

For people who have never worked with R scripts before but want to try it out painlessly.

1. [resorter](#resorter)
2. [Usage](#usage)
3. [Installation + Quickstart](#installation--quickstart)
   1. [Debian / Ubuntu](#debian--ubuntu)


# Usage

```bash
$ Rscript resorter.r --output out.csv --input in.csv

Comparison commands: 1=yes, 2=tied, 3=second is better, p=print estimates, s=skip, q=quit
Is 'Blinky' greater than 'Clyde'? 1
Is 'Clyde' greater than 'Inky'? 3
Is 'Inky' greater than 'Pinky'? 1
Is 'Pinky' greater than 'Inky'? 3
Is 'Inky' greater than 'Blinky'? 4
Is 'Inky' greater than 'Blinky'? 3
Is 'Clyde' greater than 'Pinky'? 1

Resorting complete
# see out.csv for example results
```

# Installation

_PR friendly! If you have instructions for your OS, consider submitting a PR._

## Debian / Ubuntu
```bash
git clone https://github.com/hiAndrewQuinn/resorter.git
cd ./resorter

# sudo needed the first time to download + compile BradleyTerry package.
sudo apt install r-base cmake
```

## macOS
Install R with [Homebrew](https://brew.sh) if needed.
```bash
git clone https://github.com/hiAndrewQuinn/resorter.git
cd ./resorter

brew install r
```

# Quickstart

```bash
# Capitalization matters.
# This will take a while the first time.
Rscript resorter.r --output out.csv --input in.csv
```