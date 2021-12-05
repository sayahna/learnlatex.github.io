---
layout: "page"
lang: "en"
title: "Using the learnlatex.org site"
description: "This page explains the learnlatex.org website itself and how to best make use of it."
permalink: /en/help
---
<script>
  function acesettings() {
      editors['pre0'].execCommand("showSettingsMenu");
  }
</script>


# സഹായം


## ഈ സൈറ്റിലൂടെയുള്ള സഞ്ചാരം

 [ആദ്യ പേജിലെ](./) [ഉള്ളടക്കത്തിൽ]({{ "/" | absolute_url | append: page.lang | append: "/#toc" }}) നിന്നു് എത്തിച്ചേരാവുന്ന
 16 മുഖ്യ പാഠങ്ങളാണു് ഈ പാഠ്യപദ്ധതിയിലുള്ളതു്.

 ഓരോ പാഠത്തിനും ആ വിഷയത്തിൽ കൂടുതലാഴത്തിലുള്ള മറ്റൊരു അനുബന്ധപാഠത്തിലേക്കുള്ള കണ്ണിയുണ്ട്.
 പതിനാറു പാഠങ്ങളും ഈ അനുബന്ധപാഠങ്ങൾ _വായിക്കാതെ_ തന്നെ പൂര്‍ത്തിയാക്കുക സാദ്ധ്യമാണ്.

പാഠങ്ങള്‍ക്കുപയോഗിച്ച ഭാഷയിലുള്ള ഒന്നോ അതിലധികമോ പാഠങ്ങളും, ഇവിടെ പ്രതിപാദിച്ചിട്ടില്ലാത്ത
ലാറ്റെൿ പാക്കേജുകളുടെ ഉദാഹരണ സഞ്ചയവും പാഠ്യപദ്ധതിക്കവസാനം ലഭ്യമാണ്.

---

## ഉദാഹരണങ്ങൾ

### ഉദാഹരണങ്ങളുടെ പ്രവര്‍ത്തനം

താളിലുള്‍പ്പെടുത്തിയിട്ടുള്ള ഓരോ ഉദാഹരണത്തിലും ഇതുപോലൊരു ഒരു സമ്പൂര്‍ണ്ണ ലാറ്റെൿ പ്രമാണം കാണും:

```latex
\documentclass{article}
\usepackage[T1]{fontenc}

\begin{document}
Example text.
\end{document}
```

ഓരോ ഉദാഹരണവും ഒരു പൂര്‍ണ പ്രമാണമാണ്. എങ്കിലും പാഠത്തിനവസാനം അഭ്യാസത്തിന്റെ ഭാഗമായും മറ്റും
നിങ്ങള്‍ക്ക് അവയിൽ മാറ്റങ്ങൾ വരുത്താവുന്നതാണു്.

ഇവിടെ ഉപയോഗിക്കുന്നത് [ACE](https://ace.c9.io/) എഡിറ്റർ ആണ്.

എഡിറ്ററിന്റെ കെട്ടും മട്ടും  (ഉദാ: ഇരുണ്ട പശ്ചാത്തലത്തിൽ വെളുത്ത അക്ഷരങ്ങൾ) വേണമെങ്കിൽ [സൈറ്റ് സജ്ജീകരണങ്ങൾ](settings) എന്ന താളിൽ മാറ്റാവുന്നതാണ്.
കെട്ടിലും മട്ടിലും പരീക്ഷണത്തിനുള്ള എളുപ്പവഴിയായി ഇവിടെയുള്ള ഏത് ഉദാഹരണത്തിൽ നിന്നും <kbd>Ctrl</kbd>+<kbd>,</kbd> (മാൿ ആണെങ്കിൽ <kbd>⌘</kbd>+<kbd>,</kbd>)
കീബോഡ് കട്ടകൾ ഉപയോഗിക്കാവുന്നതാണ്.
എല്ലാ ACE സജ്ജീകരണങ്ങളും മാറ്റാൻ [ഈ പാളി](javascript:acesettings()) വഴി സാധിക്കും.

[കീബോഡ് സൂത്രക്കട്ടകളുടെ ഉപകാരപ്രദമായ ഒരു താൾ](https://github.com/ajaxorg/ace/wiki/Default-Keyboard-Shortcuts) ACE ഉറവയിലുണ്ട്.



#### ഉദാഹരണങ്ങൾ പ്രവര്‍ത്തിപ്പിക്കാനുള്ള മൂന്നു വഴികൾ

* ഓവർലീഫ് സേവനം ഉപയോഗിച്ച്
* ടെൿലൈവ്.നെറ്റ്  സേവനം ഉപയോഗിച്ച്
* സ്വയം ഇന്‍സ്റ്റാൾ ചെയ്ത ടെൿ സംവിധാനം ഉപയോഗിച്ച്

##### ഓവർലീഫ് സേവനം ഉപയോഗിക്കുന്നത്

വളരെ ജനപ്രിയമായ ഒരു ഓണ്‍ലൈൻ ലാറ്റെൿ പ്രസിദ്ധീകരണ സേവനമാണ് ഓവര്‍ലീഫ്. ഉദാഹരണങ്ങള്‍ക്കു താഴെയുള്ള,
<button>ഓവര്‍ലീഫിൽ തുറക്കുക</button> എന്ന ബട്ടൺ, കോഡ് [ഓവര്‍ലീഫിനു](https://www.overleaf.com/about) കൈമാറും.

നിങ്ങള്‍ക്ക് ഓവര്‍ലീഫ് അക്കൗണ്ട് ഇല്ലെങ്കിലോ വെബ് ബ്രൗസറിൽ ലോഗിൻ ചെയ്തിട്ടില്ലെങ്കിലോ, ലോഗിൻ ചെയ്യാനോ അക്കൗണ്ട് തുറക്കാനോ സാധിക്കുന്ന താളിലേയ്ക്ക് വഴികാട്ടും. ഇതൊരു സൗജന്യ സേവനമാണ്, പക്ഷേ കുറച്ചു വിവരങ്ങൾ നല്കി നിബന്ധനകൾ സമ്മതിക്കേണ്ടതുണ്ട്.

ലോഗിൻ ചെയ്തിട്ടുണ്ടെങ്കിൽ ഓവര്‍ലീഫ് ഒരു പുതിയ താളിൽ തുറന്ന് കോഡ് തിരുത്താനും ലാറ്റെൿ പ്രവര്‍ത്തിപ്പിച്ച് പ്രമാണം (അല്ലെങ്കിൽ എറർ ലോഗ് - പ്രശ്നങ്ങൾ) കാണുവാനും സാധിക്കും.

ഈ പ്രൊജക്റ്റ് ഓവര്‍ലീഫിൽ സൂക്ഷിക്കാനും പിന്നീട് തുറന്നു നോക്കാനും സാധിക്കും, ടെൿലൈവ്.നെറ്റിൽ പ്രവര്‍ത്തിപ്പിക്കുന്ന പ്രമാണങ്ങൾ
ഈ വിധം സൂക്ഷിക്കുവാൻ സാധിക്കില്ല.


##### ടെൿലൈവ്.നെറ്റ് സേവനം ഉപയോഗിക്കുന്നത്

ഉദാഹരണങ്ങള്‍ക്കു താഴെയുള്ള,
<button>ടെൿലൈവ്.നെറ്റിൽ തുറക്കുക</button> എന്ന ബട്ടൺ, കോഡ് [ടെൿലൈവ്.നെറ്റിനു](https://texlive.net) കൈമാറും [^1].

ടെൿലൈവ്.നെറ്റ് സേവനം വികസിപ്പിച്ചതു് പ്രധാനമായും ഈ വെബ്‌‍സൈറ്റിനു വേണ്ടിയാണ്. ഇതിൽ [PDF.js](https://mozilla.github.io/pdf.js/) ഉപയോഗിച്ച് മൊബൈലിലും അവശ്യ സോഫ്റ്റ്‌വെയറുകളില്ലാത്ത മറ്റു ബ്രൗസറുകളിലും പിഡിഎഫ് നന്നായി കാണിക്കും.

പരിണിതമായി ലഭിക്കുന്ന പിഡിഎഫ് പ്രമാണം (അല്ലെങ്കിൽ എറർ ലോഗ്) ഉദാഹരണത്തിനു ചുവടെ ഉടനടി പ്രദര്‍ശിപ്പിക്കും.
ആവശ്യമെങ്കിൽ <button>പ്രമാണം നീക്കുക</button> എന്ന ബട്ടൺ ഉപയോഗിച്ച് ഇതു നീക്കം ചെയ്യാം (അല്ലെങ്കിൽ അവിടെത്തന്നെ നിലനിര്‍ത്തി അടുത്ത പാഠഭാഗത്തിലേയ്ക്കു നീങ്ങാം).

ശ്രദ്ധിക്കേണ്ട കാര്യം, **ടെൿലൈവ്.നെറ്റ്** പ്രവര്‍ത്തിപ്പിക്കാൻ ലോഗിൻ, അക്കൗണ്ട് തുറക്കൽ മുതലായ യാതൊരു നടപടിക്രമങ്ങളും
ആവശ്യമില്ല; ആയതിനാൽ തന്നെ നിങ്ങളുണ്ടാക്കുന്ന പ്രമാണങ്ങൾ സൂക്ഷിച്ചു വയ്ക്കുകയുമില്ല. അതായത്, ഉദാഹരണങ്ങളിൽ വരുത്തുന്ന മാറ്റങ്ങൾ
മറ്റൊരു താളിലേയ്ക്കു നീങ്ങുമ്പോൾ നഷ്ടപ്പെടും.


##### സ്വയം ഇന്‍സ്റ്റാൾ ചെയ്ത ടെൿ സംവിധാനം

നിങ്ങളുടെ കംപ്യൂട്ടറിൽ ടെൿ ഇന്‍സ്റ്റാൾ ചെയ്തിട്ടുണ്ടെങ്കിൽ, ഉദാഹരണത്തിന്റെ കോഡ് പകര്‍ത്തിയെടുത്ത് (ഇതിനായി <kbd>Ctrl</kbd>+<kbd>A</kbd> <kbd>Ctrl</kbd>+<kbd>C</kbd>
കീബോഡ് സൂത്രക്കട്ടകൾ ഉപയോഗിക്കാവുന്നതാണ്) കംപ്യൂട്ടറിലെ ടെക്സ്റ്റ് എഡിറ്റർ തുറന്ന് അതിൽ പതിപ്പിച്ച്; ടെൿ പ്രവര്‍ത്തിപ്പിച്ച് ഫലം കാണാം.

### പ്രശ്നനിര്‍ദ്ധാരണം

ഞങ്ങളുടെ എല്ലാ ഉദാഹരണങ്ങളും ആധുനികമായ ലാറ്റെൿ പതിപ്പിനെ അടിസ്ഥാനമാക്കിയുള്ളതാണ്. എല്ലാം തന്നെ മുകളിൽ സൂചിപ്പിച്ച
രണ്ടു് ഓണ്‍ലൈൻ സേവനങ്ങളിലും ശരിയായി പ്രവര്‍ത്തിക്കും. നിങ്ങളൂടെ കംപ്യൂട്ടറിൽ ഈ ഉദാഹരണങ്ങൾ പ്രവര്‍ത്തിപ്പിക്കുമ്പോൾ പിശകു വരുന്നെങ്കിൽ ലാറ്റെൿ പതിപ്പ് പുതുക്കിയിട്ടുണ്ടോ എന്നു പരിശോധിക്കുക.

---

## ടെൿ എന്‍ജിൻ തിരഞ്ഞെടുക്കുന്നത്

മാതൃകാപ്രമണങ്ങൾ സമര്‍പ്പിക്കുമ്പോൾ സാധാരണഗതിയിൽ `pdflatex` എന്‍ജിനാണ് ഉപയോഗിക്കുക.

`latex`, `pdflatex`, `xelatex`, `lualatex`,
`platex` അഥവാ `uplatex` എന്നിവ പകരം ഉപയോഗിക്കുവാൻ താഴെ കൊടുത്തിരിക്കുന്നതു പോലെ ഒരു കമന്റ് ചേര്‍ക്കുക:

`% !TEX ` _എന്തെങ്കിലും പാഠം_ `lualatex`

ഇതിൽ  തുടക്കത്തിലുള്ള ഒഴിഞ്ഞ സ്ഥലം കൊടുക്കണമെന്നും വലിയ അക്ഷരങ്ങളിൽ കൊടുക്കണമെന്നും നിര്‍ബന്ധമില്ല, _എന്തെങ്കിലും പാഠം_  എന്നത്
അവഗണിക്കപ്പെടുകയും ചെയ്യും.

ചില ടെൿ എഡിറ്ററുകൾ ഉപയോഗിക്കുന്ന `% !TEX program=pdflatex` എന്ന രൂപവും ഇതിനാൽ പിന്തുണയുണ്ട്, പക്ഷേ
`program=` എന്നതു നിര്‍ബന്ധമല്ല. ഇങ്ങനെ കൊടുക്കുന്നതിൽ മുമ്പു പ്രസ്താവിച്ച ഓണ്‍ലൈൻ സേവനങ്ങൾ പിന്തുണയ്ക്കുന്ന എന്‍ജിനുകൾ മാത്രമേ നിലവിൽ ഉപയോഗിക്കുവാൻ സാധിക്കൂ.

ലുവാലാറ്റെൿ ഉപയോഗിക്കാനുള്ള ഒരു കമന്റിന്റെ മാതൃക [ഈ വെബ്‌സൈറ്റിലെ ചില ഉദാഹരണങ്ങളിൽ](more-14) കാണാം.

`platex` അല്ലെങ്കിൽ  `uplatex` ആണു നിര്‍ദ്ദേശിച്ചതെങ്കിൽ `dvipdfmx` പ്രവര്‍ത്തനം ഉപയോഗിച്ചാവും DVI പ്രമാണത്തിൽ നിന്നും പിഡിഎഫ് പ്രമാണമുണ്ടാക്കുന്നത്.
അതുപോലെ, `latex`ആണു നിര്‍ദ്ദേശിച്ചതെങ്കിൽ  `dvips`, `ps2pdf` എന്നിവയായിരിക്കും ഉപയോഗിക്കുക.

`% !TeX` കമന്റിനകത്ത് എന്‍ജിൻ പറയാതിരിക്കുകയും, സാധാരണ ഉപയോഗിക്കാനുള്ള ടെൿ എന്‍ജിൻ [സൈറ്റ് സജ്ജീകരണങ്ങളിൽ](settings) മുന്‍കൂട്ടി പറഞ്ഞിട്ടുമില്ലെങ്കിൽ, `pdflatex`ആയിരിക്കും ഉപയോഗിക്കുക.

---

## Choosing how to display the output

If you use the TeXLive.net system, then the PDF
output from running an example is shown using
[PDF.js](https://mozilla.github.io/pdf.js/) by default. This provides
consistent behavior over the widest range of browsers.

If you would prefer to use your browser's default PDF reader (either
its built in one, or an external application that you have configured)
then add a comment of the form:

`% !TEX ` _any text_ `pdf`

The default behavior can be explicitly specified by using `pdfjs` as
the final token. For debugging you may sometimes want the log file
returned, even if the document produces a PDF with
no errors. This can be specified by using `log` as the final token in
the comment.

As an alternative to using a `% !TeX` comment, you may specify the
site default return parameter on the [Site Settings](settings)
page. The Settings are specific to each browser, so for example you
may choose to use the default `pdfjs` setting on your mobile device,
but use `pdf` on your desktop browser to use its default PDF rendering.


---

## HTML output (make4ht, LaTeXML, lwarp)

If using the TeXLive.net system, then additional return options,
`make4ht`, `LaTeXML` or `lwarp` may be specified. These return one or more HTML pages
in the frame within the page. It may be specified at the same time
as `xelatex` or `lualatex` as well as the default `pdflatex` processing.

To enable this output, add a comment of the form:


```
% !TeX make4ht
```
{: .noedit :}


Replacing `make4ht` by `LaTeXML` or `lwarp` to specify those systems.



Alternatively you may specify `make4ht`, `LaTeXML` or `lwarp` as the default return option
on the [Site Settings](settings) page.


If using a locally installed TeX system, the same output as the `make4ht` option may be obtained
by executing

```
make4ht  document.tex "learnlatex4ht,2,mathml,mathjax,svg"
```
{: .noedit :}

with the addional option `-x` or `-l` if XeLaTeX or LuaLaTeX are specified.

When running locally, other configurations would be possible. See the [make4ht
manual](https://texdoc.org/pkg/make4ht).


For `LaTeXML` to run locally, you would need to install LaTeXML (it is not part of TeX Live or MiKTeX)
and use

```
latexml document.tex > document.xml
latexmlpost --format=html5 \
   --javascript='https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js' \
   --destination=document.html" document.tex
```
{: .noedit :}

Many other LaTeXML configurations are possible,
[as described in the manual](https://dlmf.nist.gov/LaTeXML/manual/).


The `lwarp` configuration is not documented here, it is somewhat experimental and subject to change.
The current version can be seen at the
[source repository](https://github.com/davidcarlisle/latexcgi/blob/main/lwarp/latexcgilwarp).


---

[^1]: Note that during development of the site we have also used 
      [LaTeX.Online](https://latexonline.cc/) and
      [LaTeX-on-HTTP](https://github.com/YtoTech/latex-on-http)
      and we thank the developers of those services for making updates to enable
      the examples on this site to be available at an early stage.


