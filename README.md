

This webpage was created using [Quarto](https://quarto.org/) and is hosted using Github Pages.  Quarto is an open source scientific writing package that helps you write articles, create presentations, and publish websites.  It supports integration with Python and R, and can render .pdf, .docx, .html, .pptx files and multiple other types of documents.

If you want to make your own, the first step is to [download and install Quarto](https://quarto.org/docs/get-started/).  It can be run in RStudio or VSCode (along with other apps).  To learn more about Quarto websites visit <https://quarto.org/docs/websites>.

To host a personal website you need to create a github repository using this format:

* User-Name.github.io

* This isn't necessary to host a regular webpage with github, only if you want to make a "homepage" for yourself. i.e., the repo for this site is: [https://github.com/June-Skeeter/june-skeeter.github.io](https://github.com/June-Skeeter/june-skeeter.github.io), so when the page is rendered it shows up as [https://june-skeeter.github.io/](https://june-skeeter.github.io/)

* You can use other naming conventions if you don't need this.  i.e., the here is a repo hosted on the micromet github: [https://github.com/ubc-micromet/FieldSiteMaps](https://github.com/ubc-micromet/FieldSiteMaps), and the corresponding github page address is [https://ubc-micromet.github.io/FieldSiteMaps/](https://ubc-micromet.github.io/FieldSiteMaps/)



This should mostly work as is, provided you install [Quarto](https://quarto.org/docs/get-started/).  To render the .pdf version of the CV template you will also need LaTeX installed.  I use the XeTeX engine which I you can find [here](https://miktex.org/download); you can also try installing "TinyTex" instead directly through Quarto by typing this command in the termina:

'''console
quarto install tinytex
'''

This template also uses the quarto package [Section Bibliographies Filter](https://github.com/pandoc-ext/section-bibliographies) - I've included it in this repo (under _extensions) because I've altered it slightly from its orignal format.  It should work as is?  But you may need to install it with first then replace with the updated version.

Don't hesitate to reach out if you have any questions.

