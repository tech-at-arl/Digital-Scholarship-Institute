# Activity 3

## Review Oxygen XML Editor
* Launch Oxygen XML Editor
  1. Open new TEI template
      1. Close unnecessary windows
      3. Review basics 
         * validation/schema
         * tree structure
         * formatting and indentation
         * shortcuts: CTRL/CMD + E
         * preferences
         * editor
         * content completion
         
## Encode selections from *O Pioneers!*

* Encode TEI Header
  1. Encode the metadata for *O Pioneers!*
       1. Open TEI template file
          * Click "download" (top-right) to download opioneers-excerpt.xml file 
       2. Launch Oxygen XML Editor
          * File => Open => opioneers-excerpt.xml
       3. Begin encoding *all together*; Anna/Michelle will walkthrough the encoding with the class
          * Subdivisions of TEI header and elements:
              * fileDesc (mandatory)
                * titleStmt
                * publicationStmt
                * sourceDesc
              * encodingDesc
                * projectDesc
              * profileDesc
              * revisionDesc

* Encode text and body
       1. In the same file, move down to the text section and encode the front matter
       2. Move down to the body section and begin encoding the paragraph structure and page breaks

* Create a Personography
   1. Open Personography template file
       1. Click "download" (top-right) to download personography.xml file
   2. Open file in Oxygen XML Editor
       1. File => Open => personography.xml
       2. Begin encoding *all together*; Anna/Michelle will walkthrough the encoding with the class
       3. When finished encoding, copy everything within the person elements and paste into the 
          opioneers-excerpt.xml file within the listPerson element
   3. Encode persNames within the body
       1. Wrap `<persName>` element around the named reference with the unique ID created in the personography
          `<persName ref="#pers_john_smith">John Smith</persName>`
        
          
    
***
### Resources 
TEI-C guidelines
* [TEI Header](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html)
* [Text Structure](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/DS.html)
* [Names, Dates, Peopler, and Places](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ND.html)

Fully encoded text (for your review):
* [http://cather.unl.edu/cat.0017.xml] (First edition of *O Pioneers!* from the Willa Cather Archive)
