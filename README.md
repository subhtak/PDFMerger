PDFMerger
=========

Wrapper for fpdf and fpdi to help merge pdf files together.

Original sources: http://pdfmerger.codeplex.com

Changes made in this repo:

* added composer.json
* added PSR-0 support, use the class like so: `$p = new \pdfmerger\PDFMerger`
* removed fpdf and fpdi, uses newer versions through composer
