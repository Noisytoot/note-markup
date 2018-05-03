# note-markup
A repository for Note Markup
## Instructions:
1. Create a folder for the files
2. Download `note.dtd` for the DTD version or `note.xsd` for the XSD version
3. Put the the file in the folder you made for it
4. Create a XML file in the folder
5. Put `<?xml version="1.0"?>` at the top of the file
6. Put `<!DOCTYPE note SYSTEM "note.xsd">` if you are using XSD or `<!DOCTYPE note SYSTEM "note.dtd">` if you are using DTD below `<?xml version="1.0"?>`
## Specification
On the top of the page there must be `<?xml version="1.0"?>` and below that the doctype declaration.
One file may contain multiple notes inside the root `<notes>` tag.
Below the `notes` tag there is the `<note>` tag for a single note.
The `<note>` tag may have the attribute `name` in which the name of the note is put, `date` in which the date is put and `time` in which the time is put.
Below the `note` tag there is the `to` tag for who the note is to, the `from` tag in which who the note is from is put and the `body` tag in which the note body is put.
