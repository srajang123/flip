# FLIPKART GRID
## Electronic Invoicing using Image Processing
### Tools and technologies used:
* Tessaract API`(for Optical Character Recognition)`
* Django `(for Server)`
* ReactJS `(for User Interaction)`
### Using the product:
* Open the website
* Select the file to upload `(Selected file must be PDF file)`
* Click Upload
* The file will be uploaded to the servers and after complex processing the spreadsheet file will be generated.
* Then the server will return the file to your system which can be downloaded.
### further improvements
* Improving the Accuracy upto 100%.
* Finding and removing the errors.
* Building a complete working project.
### OCR
Optical Character Recognition (OCR) is the conversion of images of typed, handwritten or printed text into machine-encoded text, whether from a scanned document, a photo of a document, a photo from a scene (billboards in a landscape photo) or from a text superimposed on an image (subtitles on a television broadcast).
### Tessaract OCR
Tesseract OCR is an open-source project, started by Hewlett-Packard. Later Google took over development. It can be used directly, or (for programmers) using an API to extract printed text from images. It supports a wide variety of languages. Tesseract doesn’t have a built-in GUI, but there are several available from the 3rdParty page. Tesseract is compatible with many programming languages and frameworks through wrappers. t can be used with the existing layout analysis to recognize text within a large document, or it can be used in conjunction with an external text detector to recognize text from an image of a single text line.

We need to make sure the image is appropriately pre-processed. to ensure a certain level of accuracy. This includes rescaling, binarization, noise removal, deskewing, etc.

![Tesseract 3 OCR process from paper](https://miro.medium.com/max/700/1*koItF8Mhlbg5W2ep662C5A.png)

Tesseract OCR is quite powerful but does have some limitations.
* The OCR is not as accurate as some available commercial solutions .
* Doesn’t do well with images affected by artifacts including partial occlusion, distorted perspective, and complex background.
* It is not capable of recognizing handwriting.
* It may find gibberish and report this as OCR output.
* If a document contains languages outside of those given in the -l LANG arguments, results may be poor.
* It is not always good at analyzing the natural reading order of documents. For example, it may fail to recognize that a document contains two columns, and may try to join text across columns.
* Poor quality scans may produce poor quality OCR.
* It does not expose information about what font family text belongs to.