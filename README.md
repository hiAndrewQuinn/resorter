# `resorter`: CLI program for noisy pairwise rankings

This repo simplifies installing and running Gwern's [Resorter](https://www.gwern.net/Resorter).

# Quickstart

```powershell
cd $WhereverYouWant
git clone https://github.com/AndrewQuinn2020/resorter.git
```

_Install this another way? Fork this repo and edit `README.md` to let me know how you did it._

## ... on Windows

### ... using [Scoop](https://scoop.sh)

You can install Scoop in PowerShell easily using

```powershell
# as admin - Win-X,A,Alt-Y to open admin PoSH window
Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')
```

```powershell
# as admin ~> Win-X,A to open admin PowerShell session
scoop install r
cd resorter\
rscript.exe resorter.r
```

# Demo

# Licensing

Gwern's entire website is in the [public domain](https://www.gwern.net/About#license), including it appears the code, and I've opted to keep my copy of this code the same way, instead of switching to a [poison dart license](https://www.gwern.net/Evolutionary-Licenses#the-analogy) (even though [almost nobody actually sues on GPL-based grounds](https://www.greaterwrong.com/posts/gziZACDg6EBpGZbJe/almost-everyone-should-be-less-afraid-of-lawsuits#Most_lawsuit_types_are_rare) anyway).