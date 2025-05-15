solutions in Julia to the exercises in David Hogg’s 2010 tutorial paper “Data analysis recipes: Fitting a model to data” https://arxiv.org/pdf/1008.4686

use quarto to render pdf & html

to use local fonts, they must be installed at system level, e.g. `C:\Windows\Fonts` or `/usr/local/share/fonts/`

to show plot in pdf, need rsvg-convert
- in linux: install `librsvg` or the like
- in windows to show plot: download `rsvg-convert.exe` into `<quarto path>\bin\tools`
  - https://github.com/miyako/console-rsvg-convert/releases or
  - https://sourceforge.net/projects/tumagcc/files/rsvg-convert-2.40.20.7z/download
