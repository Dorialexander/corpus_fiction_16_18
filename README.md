# corpus_roman_16_18
A corpus containing all digitized French novels from the beginning of print (the first entry is from 1473) to the 18th century.

French novels of the period have been identified using the Y2 quote of the French National Library Catalog that has served to classify past and present collections of novels in France from 1730 to 1996. Combined use of digitized sources from Gallica, Google Books, Archive.org and other digital library made it possible to attain a high representativeness: 78% of the novels of the 1450-1600 and 68% of the novels of the 1600-1700 have been retrieved.

The corpus is part of a planned collection of French Fiction (1050-1920) that will also integrate Geste (a medieval corpus curated by Jean-Baptiste Camps) and Fictions littéraires de Gallica (a 1600-1950 corpus extracted from Gallica with Pierre-Carl Langlais, with a strong focus on the 19th century). While it aims to bridge the two pre-existing part of the collection, it is also a more ambitious experiment of systematic collection of existing digital sources.

The project remains very much a work-in-progress at this stage. Occasional errors in the metadata and the identification of the unique work are still possible. Besides, the identification of multi-volumes remain challenging in digital sources beyond Gallica.

The repository includes the following files:
-The metadata of available and unavailable file for all novels identified in the 16th century (corpus_roman_metadata_16.tsv) and the 17th century (corpus_roman_metadata_17.tsv). All the editions have been temptatively assigned to a unique work (work_id) based on theo title, the author and additional metadata. This dataset includes both information on a specific digitized volume (volume_file, volume_title, volume_date, volume_edition_id) and on the earliest edition of the work recorded by the French national library (first_edition, first_edition_titre, first_edition_date), as well as the identification of the author (prenom_auteur, nom_auteur) and the complete list of all available edition (list_edition_bnf). When digitized files are not available for a given work, the information on the volume is replaced with a missing data mark (NA).

Due to limitations by Github, the PDF corpus is downloadable in two large zip files in an external corpus:

