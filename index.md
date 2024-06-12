# Hi GMF!
## I like you

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

``` python
import pandas as pd
def browse_words_file():
    global words_file_path
    words_file_path = filedialog.askopenfilename(initialdir="/",
                                                 title="Selecione o Arquivo de Palavras:",
                                                 filetypes=(("Excel Files",
                                                             "*.xlsx*"),
                                                            ("all files",
                                                             "*.*")))

    words_file_label['text'] = "Arquivo de palavras: " + words_file_path
    print(words_file_path)

```

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
