# Note Markup
A repository for Note Markup
## Instructions:
1. Create a folder for the files;
2. Download `note.css`;
3. Optional: Download `note.dtd` for the DTD version or `note.xsd` for the XSD version;
4. Put the the file(s) in the folder you made for it;
5. Create a XML file in the folder or download `note.xml`;
6. Put the the `note.xml` in the folder you made for it if you downloaded it, if you downloaded `note.xml` you do not need to do the following steps;
7. Put `<?xml version="1.0"?>` at the top of the file;
8. Optional: Put `<!DOCTYPE note SYSTEM "note.xsd">` if you are using XSD or `<!DOCTYPE note SYSTEM "note.dtd">` if you are using DTD below `<?xml version="1.0"?>`;
9. Add `<?xml-stylesheet href="note.css" type="text/css"?>` below `<?xml version="1.0"?>` or the doctype.
## Specification
On the top of the page there can be `<?xml version="1.0"?>`, below that the doctype declaration then the link to the stylesheet.
One file may contain multiple notes inside the root `<notes>` tag.
Below the `notes` tag there is the `<note>` tag for a single note.
The `<note>` tag may have the attribute `name` in which the name of the note is put, `date` in which the date is put and `time` in which the time is put.
Below the `note` tag there is the `to` tag for who the note is to, the `from` tag in which who the note is from is put and the `body` tag in which the note body is put.
There are also a lot of styling tags that are in the `note.xml` file.
