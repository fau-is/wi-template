# WI-Template

## About
The provided template is based on the LNCS template from Springer and adapted for usage for the proceedings of the International Conference on Wirtschaftsinformatik (WI).

## Usage
### Authors
Author names are specified by `\author{}`. If there are multiple authors, use `\and` to separate them, e.g.:

```latex
\author{First Author \and
Second Author \and
Third Author}
```

### Affiliations
Institutions are specified by `\institute{}`. Use `\and` to separate multiple institutions (see Authors).
You can use `\email{}` and `\url{}` within `\institute{}` to specify e-mail addresses and links to the respective institutions.

```latex
\institute{Institution, Department, City, Country\\
\email{\{first.author,second.author,third.author\}@example.com} \and
Other Institution, Other Department, Other City, Other Country\\
\email{\{third.author,fourth.author}@anotherexample.com\}}
```

To map the institutions to the authors, use `\inst{<number>}` after the corresponding author names. 
`<number>` refers to the "rank" of the elements, which are listed within `\institute{}`.

```latex
\author{First Author\inst{1} \and
Second Author\inst{1} \and
Third Author\inst{1,2} \and
Fourth Author\inst{2}
```

## Contribute
As with many LaTeX documents, you will probably run into problems and errors. While we cannot provide you with any support, we welcome contributions of any kind. 
Feel free to submit your pull requests and bug reports.
