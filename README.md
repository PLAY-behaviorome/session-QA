# session-QA
Code for semi-automated quality assurance (QA) tests on LEGO and PLAY data.

## Contents

- `LEGO-spreadsheet.Rmd` is an RMarkdown document that downloads the session spreadsheet from Databrary for the LEGO project <https://nyu.databrary.org/volume/563#panel-data>.
It then runs various tests on those data. An HTML format summary of the results can be viewed here: <http://PLAY-behaviorome.github.io/session-QA/LEGO-spreadsheet.html>. To re-render the report, download the repo and run `rmarkdown::render('LEGO-spreadsheet.Rmd', params=list(db_account="youremail@yourdomain.com"))` from the project root directory. You will need to substitute your own valid Databrary account ID for the `db_account` variable.
