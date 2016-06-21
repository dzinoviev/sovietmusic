# Sharing of performers between Soviet/Russian non-academic music groups

This dataset contains information about 4565 non-academic music groups performing in the USSR and post-Soviet countries in 1960–2015 in 275 [coded] genres, and 17,000 performers (of whom at least 3,600 were shared). Some performers who were never shared, are not in the dataset.

The dataset consists of three CSV files. Each file's first row contains column headers.

## Data dictionary

* genres.csv – original and coded genres
  * genre – original genre designation (possibly in the original language)
  * code – genre designation in English

* groups.csv
  * name – group name (possibly in the original language)
  * genres – original genre(s), semicolon-separated (possibly in the original language)
  * year – group formation year
  * url – Wikipedia page for the group
  * genres_coded – coded genre(s), semicolon-separated

* musicians.csv
  * group – group name (possibly in the original language)
  * person – name of the performer (possibly in the original language)
  * url – Wikipedia page for the performer; if the performer is mentioned more than once, the URL is mentioned only once
