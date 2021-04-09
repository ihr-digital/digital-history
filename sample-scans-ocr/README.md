# Sample scans

*OCR and Double Rekeying as the digitisation process*

The sample pages in this directory (the `.tif` and `.pdf` files) have been run through several different OCR applications and the output from each saved to the files in this repository.


### Adobe Acrobat Pro DC

This has to be the professional and paid-for version of Adobe Acrobat DC. The free Acrobat reader will not perform OCR on your pdf files.

First the tiff files were manually converted to individual PDF files, then the feature to recognise text was applied (this feature is available as part of the 'Enhance scans' application functionality). The 'language English (UK)' was used, and the image was downsampled to 600dpi. Then we selected all the text (Ctrl-A) and copyied and pasted this into the text file. Both the PDF and the text files are availalbe for you to view in this repository.

Adobe Acrobat does give you a user interface to correct the recognised text, as well as a way to view the text as an overlay ontop of the scanned page. This can be quite useful. A few screenshots have been included in this repository to give you an idea of what this looks like.


### Free Online OCR Websites

The next option we trialled several an free online OCR websites (which we just googled):

http://www.free-online-ocr.com
https://onlineocr.net

These services are all slightly different, but you need to upload your image (some don't accept TIFF so you might need to convert your images first), and then they convert and send you the text in various formats. We chose to download/copy the plain text.

There are several converns with using free online services like this. First, you have no control over what they do with the files you upload, and your content might have copyright restrictions, so be careful when you think about using free services like this. Second, if you honly have a few pages to OCR this can be useful, but to OCR an entire book would be quite cumbersome.


### Tesseract OCR

The final tool we have used is an open source utility called Tesseract OCR: https://github.com/tesseract-ocr/tesseract. This is predominantly a command line program but there are GUI layers available, or Tesseract can be invoked from programming languages such as Python.

There are installation instructions on the link above. Tessearct has a number of dependencies which need to be installed. Note that once Tesseract is installed you still need to download the training data for the language you are interested. Once everything is ready, the command to run an image through the OCR with the default settings (English) is: `tesseract 0000.tif 0000-tesseract.txt`

### Double Rekeying

This automated OCR techniques above are often not accurate enough for digitisation of historical printed sources and so the [double rekeying](https://www.british-history.ac.uk/about#technical) technique was used to digitise the Post Office directory page scans.

The resulting XML files are available in the `./data/XML` directory of this repository, and it is these files which were used as the data for all the methodoligical explanations used throughout the book.

The 'Post Office directory keying instructions.docx' Microsoft Word document contains the detailed instructions for the keying company to observe during the manual double rekeying process. Keying instructions are a balance between pragmatic markup (becaue rekeying costs per character) of typographical features and information about how to resolve common print or formatting anomolies present in the source material being digitised. Keying instructions generally should not require the keying company to make decisions based on the content itself. This is to mitigate and reduce the probabiliy of the introduction of any interpretation or source modification biases as a result of the rekeying procedure, and to ensure high quality minimally- structured data files.


### 