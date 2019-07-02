# Activity 4

## Encode selections from *O Pioneers!*

* Review Oxygen XML Editor
  1. Launch Oxygen XML Editor
       1. Download [opioneers-excerpt]() file
          * Save file to desktop or copy and paste into Oxygen XML Editor
          * File => Open => opioneers-excerpt.xml
       2. Close unnecessary windows
       3. Review basics
          * validation/schema
          * tree structure
          * formatting and indentation
          * shortcuts: CTRL/CMD + E
          * preferences
          * editor
          * content completion

* Endode metadata from *O Pioneers!* ([View or download activity 4 packet](/activity4_1913-Cather-OPioneers.pdf))

   1. Begin encoding *all together*; Anna/Leigh will walkthrough the encoding with the class
         1. Subdivisions of TEI header and elements:
              * `<fileDesc>` (mandatory)
                * `<titleStmt>`
                * `<publicationStmt>`
                * `<sourceDesc>`
              * `<encodingDesc>`
                * `<projectDesc>`
              * `<profileDesc>`
              * `<revisionDesc>`

* Encode text and body (through page 10)
   1. In the same file, move down to the text section and encode the front matter
      1. `<front>`, `<titlePage>`, illustration, dedication, epigraph, contents
      2. Move down to the `<body>` section and begin encoding the paragraph structure `<p>` and page breaks `<pb n="#"/>`
              
***
### Resources
TEI-C guidelines
* [TEI Header](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html)
* [Text Structure](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/DS.html)
* [Names, Dates, People, and Places](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ND.html)

Fully encoded text (for your review):
* [First edition of *O Pioneers!* from the Willa Cather Archive](http://cather.unl.edu/cat.0017.xml)
