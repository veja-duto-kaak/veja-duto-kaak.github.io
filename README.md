# National Math Camp Archival Site

To see instructions on how to build this site locally, see [the original template repository.](https://github.com/mmistakes/minimal-mistakes)

### Contributing

#### To old years

Just make a PR with the change.

##### Adding a new year
 
1. Create a folder named `<year>` and add an `index.md`.
2. In `_data/navigation.yml`, in the `main` block, add the following-

	```yaml
	  - title: "NMC <year>"
    	url: /<year>/
	```
	This will add the year to the site navbar.
3. Update the top level `index.md` accordingly