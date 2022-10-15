# Obsidian OpenPublish

## TODO

### short-term

- [ ] Process notes before feeding into `hugo-obsidian`
    - [ ] Add `title` key to notes that don't have them
    
### long(er)-term

- [ ] Make wiki-links appear in search
- [ ] `hugo-obsidian`
    - [ ] Make `title` value the name of the file if it doesn't have that key
    - [ ] Fix hard-coded `./content` directory
        - When serving the default Quartz notes, all is normal if you have the content dir at the root
        - However, if you move the dir to somewhere else (say, `assets/content`) the output is different (7 notes, instead of 32)
- [ ] Note list on left side
