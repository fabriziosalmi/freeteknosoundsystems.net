# freeteknosoundsystems.net

The aim of this project is to create and mantain a **free tekno sound system open database**.

## Contribute to the project

[Mail me](mailto:fabrizio.salmi@gmail.com) some missing data or controbute to the project with a GitHub account:

1. Clone the repo to your local device:

- `git clone https://github.com/fabriziosalmi/freeteknosoundsystems.net.git`

2. Update sources.list by adding the source where you find the missing data:

- `cd freeteknosoundsystems.net && echo "your-email@domain.com" >> sources.list`

3. Update artists.list by adding the missing data:

- `echo "SOUND SYSTEM NAME" >> artists.list`

4. Commit and push your updates

- `git add * && git commit -m "Source your-email@domain.com and SOUND SYSTEM NAME added." && git push`

5. I will merge your update after a quick review, if multiple contributors will join the project master write access will be granted.


### File formats

- artist.list: one sound system or artist per line
- sources.list: one source per line, valid sources are e-mail, url or 3rd party database
- master branch updates will be performed after some formatting filters: update date time (sources.list), alphabetical order and capitalization (artists.list)

-=FREE TEKNO=- iS ALiVE!!
