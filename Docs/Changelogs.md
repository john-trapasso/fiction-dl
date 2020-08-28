# 1.4.0

**Extractors**:

- Added a text file extractor: you can now put the HTML-formatted story in a raw text file and use **fiction-dl** to auto-format it as ODT, PDF etc.

**Processing:**

- Improved chapter title processing.

**Bugfixes:**

- Fixed a bug in the sanitizer.
- Fixed a typo in Xen Foro extractors' authentication screen.

**Stuff:**

- Removed one unneeded dependency (the *fitz* package).
- Updated the readme: mentioned some libraries that might need to be installed on Linux systems.
- Fixed some typos.

# 1.3.0

**Processing:**

- Improved chapter title processing.

**Bugfixes:**

- Fixed a bug in the ODT formatter.
- Fixed a bug in the FF.net extractor.

# 1.2.0

**General:**

- Links (anchors) are now preserved in output files.

**Extractors**:

- Added an extractor for [AdultFanFiction](http://www.adult-fanfiction.org/html-index.php).

**Processing:**

- Improved horizontal line recognition.
- Improved story title processing.

**Stuff:**

- Reformatted *Style Guidelines* as Markdown.
- Reformatted changelogs as Markdown.

# 1.1.1

**Stuff:**

- Fixed a mistake in the readme.

# 1.1.0

**General**:

- Reworked the way authentication works in all extractors.

**Extractors**:

- Added support for Reddit authentication.
- Expanded exception handling in the Reddit extractor.
- The Reddit extractor now handles extracting posts made by deleted users and suspended users.

**Processing**:

- Added some more processing for story titles.