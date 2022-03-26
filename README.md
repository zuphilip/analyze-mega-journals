# Analyze Mega Journals

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zuphilip/analyze-mega-journals/HEAD?labpath=analyze.ipynb)

This repository contains a Jupyter Notebook to analyze mega journals and their articles together with the current results.


## Usage

To try it out, you can simple click on the binder link above, which opens the Jupyter Notebook directly in your browser. This may takes some minutes to set up everything, but you can then run the analysis without any further set-up.

Alternatively, you can also download the [analyze.ipynb](analyze.ipynb) and open it in your local Jupyter Notebook instance. You need a Python 3 kernel and some additional packages, see [requirements.txt](requirements.txt).


## Data and results

The data for each journal were saved in CSV files. You can either do the analysis with these CSV files directly or call the data from Crossref's API again.

Some results are saved direclty as images here.
The following mega journals are anyalzed:
- Academia Letters (<https://portal.issn.org/resource/ISSN/2771-9359>)
- F1000 Research (<https://doaj.org/toc/2046-1402>)
- Open Research Europe (<https://doaj.org/toc/2732-5121>)
- PeerJ (<https://doaj.org/toc/2167-8359>)
- PeerJ Computer Science (PeerJ CS <https://doaj.org/toc/2376-5992>)
- PLOS One (<https://doaj.org/toc/1932-6203>)
- SAGE Open (<https://doaj.org/toc/2158-2440>)

The following analyses have been done:
- number of articles which received the same amount of citations
- number of publications per weekday
- number of publications per month
- word cloud from the title words

You can also simply open [analyze.ipynb](analyze.ipynb) here on GitHub to see the different steps and results.
For an interactive examination click on the binder link above.


## Link and reference

This repository was created especially to analyze the publication data of Academic Letters as part of an article in Libreas [^1].
The data for the other mega journals were useful for comparison, but are not discussed further in this article.

However, I prefer direct software citations, if you reuse any of the scripts here for your own article.


## License

This is Open Source software. You may use this software under the terms of the MIT License. See [LICENSE](LICENSE) for details.

The data in the CSV files come from the Crossref API and are therefore a [mixture of facts without copyright restrictions and things waived under CC0](https://www.crossref.org/documentation/retrieve-metadata/rest-api/rest-api-metadata-license-information/), i.e. no rights reserved at all on the data.


[^1]: (this info needs to be added later)
