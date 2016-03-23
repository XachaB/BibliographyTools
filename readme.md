python3 script that takes a bib file and outputs a new bibfile with the DOIs it finds. I'm not using bibtool or taking any aux files.
The requirements are bibtexparser and unidecode.
This is based on : http://tex.stackexchange.com/questions/6810/automatically-adding-doi-fields-to-a-hand-made-bibliography/300474#300474

You can use it as such :

    python3 searchdoi.py test.bib

And it will look like this :
  
    Reading Bibliography...
    Looking for Dois...
    161/162 entries processed, please wait...
    We added 49 DOIs !
    Before: 42/162 entries had DOI
    Now: 91/162 entries have DOI
    Writing result to  test.bib_doi.bib

You can now just check test.bib_doi.bib.
