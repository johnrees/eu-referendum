# EU Referendum Datasets

Data from the 23rd June EU Referendum on whether the United Kingdom should remain in or leave the European Union.

## guardian-results.json

Voting counts and results per constituency in the UK.

Taken directly from http://www.theguardian.com/politics/ng-interactive/2016/jun/23/eu-referendum-live-results-and-analysis

## petition-counts.json

Totals of all signature counts on a petition calling for a second referendum. Grouped by country and UK constituency. Pulled from https://petition.parliament.uk/petitions/131215 and updated once a minute

Please note that after commit https://github.com/johnrees/eu-referendum/commit/5da7bd55316079d259697bf1fff981e7daf18861 the format changed to pretty-printed rather than the default compact style. This is so that the file is split into multiple lines and can have multiple diffs, rather than the entire file contents being a diff (like a binary blob) each time it is pushed.

## newspapers/

Front pages of newspapers from the days surrounding the referendum.

## transcriptions/

Subtitle files from various broadcasts related to the referendum.

## exchange-rates/

Global currency exchange rates from the days surrounding the referendum.

### More data sources to be added soon

I'll remove any data if requested, but I feel this is too important not to be shared.
