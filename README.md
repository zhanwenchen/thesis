# Important

Run `biber thesis` first in order to update the generated/stored bibliography. Then run the compilation command is `xelatex thesis` (instead of `xelatex thesis.tex`, Otherwise the bibliography won't be found correctly). So the most convenient command would be

```sh
biber thesis && xelatex thesis
```
