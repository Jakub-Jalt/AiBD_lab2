README

Orginal data name: billboard.csv
Orginal data location: '../Orginal_data/billboard.csv'

*Artists with tracks list*
Modified data: artists_tracks.csv
Modified data location: '../Analysis_data/artists_tracks.csv'

*Ranking*
Modified data: ranking.csv
Modified data location: '../Analysis_data/ranking.csv'

To get modified data run file Command_file.ipynb.
Command_file.ipynb in catalogue Command_files.

Command_file.ipynb in steps description:
1. Importing required packeges: pandas.
2. Reading orginal data.
3. Change type of date columns.
4. Create new Dataframe from columns in orginal data.
5. Modife data:
	- 'artists_tracks.csv':
		* Sort data by track name,
		* Create new Dataframe,
		* Rename colums.
	- 'ranking.csv':
		* Drop columns with Nan values,
		* Subtract enter date from peak date,
		* Raneme colums,
		* Sort data by ranking position.
6. Save new Dataframes in new csv files: 'artists_tracks.csv', 'ranking.csv'

Directory and files structure:

AiBD_lab2
	Analysis_data
		- artist_tracks.csv
		- ranking.csv
	Command_files
		- Command_file.ipynb
	Documents
		- Readme.txt
		- The Data Appendix.txt
		- The Final Paper.txt
	Orginal_data
		- billboard.csv
		Metadata
			-The Metadata Guide.txt