
### **Basic functionality**

1. Converte all type of resumes to  (doc,docx,pdf,rtf etc) to HTML .
2. Apply Masking of data using regex ( like masking email, phone nos in Resume).
3. Add Client Specific Content to Start of HTML Body/First page of Resume.
4. Convert HTML to PDF 

Steps to use DocumentConverter

### Dependency List :
1.**unoconv** : unoconv converts between any document format that OpenOffice understands. It uses OpenOffice's UNO bindings for non-interactive conversion of documents. unoconv is written in python. It needs a recent LibreOffice or OpenOffice with UNO bindings.
2.**pdf2tmlEX** : pdf2htmlEX renders PDF files in HTML, utilizing modern Web technologies, aims to provide an accuracy rendering, while keeping optimized for Web display. Text, fonts and formats are natively preserved in HTML, math formulas, figures and images are also supported.pdf2htmlEX is also a publishing tool, almost 50 options make it flexible for many different use cases: PDF preview, book/magazine publishing, personal resume.... pdf2htmlEX was first designed especially for scientific papers, which contain different fonts and complicated formulas and figures.
3.**wkhtmltopdf** : wkhtmltopdf and wkhtmltoimage are open source (LGPLv3) command line tools to render HTML into PDF and various image formats using the QT Webkit rendering engine. These run entirely "headless" and do not require a display or display service.


All three tools are very effective in document cnversion and all three are complete open source.We can run these tools as stand alone commands or as backend listeners/deamon.

### User Inputs:
1. Content of file (binary) or File Path
2. File Extension
3. Masing details.
4 Header HTML


**Instalation Steps are written in executable shell files.**

To do List :
1. Provide support for file extension identification in side library.
2. Providing exceptions with message and error codes.
3. Bench Marking with large set of data.


