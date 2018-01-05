# Activity 3
         
## Encode selections from *O Pioneers!*

* Review Oxygen XML Editor
  1. Launch Oxygen XML Editor
       1. Download [opioneers-excerpt](https://app.box.com/s/spka42icx59reonyk15krlu9dmt4xbdt) file
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
  
* Endode metadata from *O Pioneers!* (View [activity3_1913-Cather-OPioneers.pdf](activity 3 packet))
([Download](https://app.box.com/s/9xhg9t4rtxqql1j65tc6xzxqjsgcsc8k) activity 3 packet)

   1. Begin encoding *all together*; Anna/Michelle will walkthrough the encoding with the class
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

* Create a Personography
   1. Open [personography](https://app.box.com/s/wbisqwwzu0fl7r5lthtbvbbef92rsvbq) template file
       1. Save file to desktop or copy and paste into Oxygen XML Editor
   2. Open file in Oxygen XML Editor
       1. File => Open => personography.xml
       2. Begin encoding *all together*; Anna/Michelle will walkthrough the encoding with the class
       3. When finished encoding, copy everything within the person elements and paste into the 
          opioneers-excerpt.xml file within the `<listPerson>` element
   3. Encode `<persName>` within the body
       1. Wrap `<persName>` element around the named reference with the unique ID created in the personography
          `<persName ref="#pers_john_smith">John Smith</persName>`
          
    
***
### Resources 
TEI-C guidelines
* [TEI Header](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html)
* [Text Structure](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/DS.html)
* [Names, Dates, Peopler, and Places](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ND.html)

Fully encoded text (for your review):
* [First edition of *O Pioneers!* from the Willa Cather Archive](http://cather.unl.edu/cat.0017.xml)
