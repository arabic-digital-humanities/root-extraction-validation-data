# Dataset for evaluating root extraction

This dataset contains data to evaluate the roots extracted by Arabic
stemmers and morphological analyzers.

The dataset was created in the context of the [Bridging the Gap project](https://www.esciencecenter.nl/project/bridging-the-gap).

The `txt` directory contains the text files for which roots were extracted,
and `gs` contains csv files with columns `word` and `root`, containing the words
from the text and the manually corrected roots. If multiple roots apply, they
have been separated using a backslash (`\`). If the word is a letter, the root is `#`.

## License

[![License: CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

The data in this repository is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

* The text fragments have been taken from the [OpenITI project](https://alraqmiyyat.github.io/OpenITI/).
* The stopword list was created by Maksim Abdul Latif.
