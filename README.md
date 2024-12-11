# EB-PyMadDic2024
This repository includes the slides of the public presentation 'Cómo usar Python para curar enfermedades genéticas' of the PyLadies Madrid, Python Madrid and PyData Madrid December 2024 Meetup and both the code and files used for the practical case (slide 26 onwards).

## Installation
You simply have to download the .py and fasta files (or get your own fasta files from a database as [NCBI](https://www.ncbi.nlm.nih.gov/)).

## Usage
First you'll have to select the file of your diseased gene of interest, then you'll have to introduce the position of the mutation (as a positive integer) and the letter that should be in that position. When finished, you'll have three .txt files saved in the same folder of the .py file with the RNA guide, the DNA mold and the corrected sequence.
If you want to recreate the example of the slides just use the provided fasta file diseased_COL7A1 with this Epidermolysis Bullosa's mutation:
- Mutation position: 6.527
- Corrected base: T

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
