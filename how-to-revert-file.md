# there are three phase the git manage you file
- unmodified
- modified
- staged

## when you do any change to file in your working directory, the file will be
- modified

## when you using command git add in the modified file, git will cached they indiviaully and the file is 
- staged

## That's forward flow of edit files

# And how to travser to three different phase reversely?

## the flow of reverting files 
staged ->(1) modified ->(2) unmodified

## every command you need to
- `(1) git reset HEAD <file>`
- `(2) git checkout <file>`



