# EU Referendum Datasets

Data from the 23rd June EU Referendum on whether the United Kingdom should remain in or leave the European Union.

## campaign-materials/

Various media published and commissioned by both sides.

## economic-data/

Global currency exchange rates and share prices from the days surrounding the referendum.

## newspapers/

Front pages of newspapers from the days surrounding the referendum.

## Petitions

## article50-petition-counts.json

Totals of all signature counts on a petition calling for Article 50 of the Lisbon Treaty to be invoked immediately. Doing so would begin the irreversible process of withdrawing the United Kingdom from the European Union. Pulled from https://petition.parliament.uk/petitions/133618 and updated once a minute

## petition-counts.json

Totals of all signature counts on a petition calling for a second referendum. Grouped by country and UK constituency. Pulled from https://petition.parliament.uk/petitions/131215 and updated once a minute

Please note that after commit https://github.com/johnrees/eu-referendum/commit/5da7bd55316079d259697bf1fff981e7daf18861 the format changed to pretty-printed rather than the default compact style. This is so that the file is split into multiple lines and can have multiple diffs, rather than the entire file contents being a diff (like a binary blob) each time it is pushed.

## Poll Results

### guardian-results.json

Voting counts and results per constituency in the UK.

Taken directly from http://www.theguardian.com/politics/ng-interactive/2016/jun/23/eu-referendum-live-results-and-analysis

## transcriptions/

Subtitle files from various broadcasts related to the referendum.

## websites/

Local mirrors of official websites used during the campaign.

#### More data sources to be added soon

I'm currently collecting all the information and media I can, including hundreds of GBs of videos. It won't be possible to publish everything here immediately but it will appear in time.

Please open issues and submit pull requests if you want to help to grow the dataset. Thanks.
