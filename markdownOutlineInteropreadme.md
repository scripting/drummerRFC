# Markdown as an outliner interop format

As I implement the file format used by LogSeq and Obsidian to interop, in Drummer, I'm taking notes here. If there is any documentation on this format, I don't know where it is. 

### Background and agenda

So I'm going to document the assumptions Drummer makes, and hope that the current implementors will participate in either validating the assumptions, or saying what the actual format is. 

Each developer must decide for themselves what formats to support, this is not a place to debate which format is better.

### The format needs a name

I don't know what to call it. Just calling it "markdown" is too vague, markdown is used for many other purposes. The goal here is not to read all markdown files, but a subset of them that follow strict rules. 

### Is .md the right extnesion to use?

That's what LogSeq seems to use. I think this question should be asked. It may be too late to change it. 

### File-level attributes

In OPML these are called head-level attributes. 

There does not appear to be the equivalent concept in this format. 

We can't make this work two-ways if file-level attributes are not supported.

### How to create attributes in LogSeq?

I am a newbie. I do not know how to do this, so it's impossible to test. I will figure it out, but it would be helpful if someone explained it in a 1. 2. 3. kind of way. I don't care what the attributes are. Make it as simple as possible please. :smile:

