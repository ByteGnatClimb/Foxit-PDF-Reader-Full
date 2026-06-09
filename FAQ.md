# Foxit PDF Reader — FAQ

**Q: Is Foxit PDF Reader completely free?**  
A: The core reader with annotation, form filling, digital signatures, text editing, OCR, and PDF export is free. Foxit offers a paid PDF Editor suite with advanced features (bulk processing, PDF/A conversion, Bates numbering), but the free reader covers everything most users need.

**Q: How do I remove the Foxit toolbar from my browser?**  
A: During installation, uncheck "Install browser extensions." If already installed: Chrome → Settings → Extensions → find Foxit → Remove. The reader itself is unaffected.

**Q: Can Foxit open password-protected PDFs?**  
A: Yes — Foxit opens any PDF you have the password for. It doesn't bypass PDF encryption.

**Q: How do I convert a PDF to Word?**  
A: File → Export to → Microsoft Word (.docx). OCR is applied automatically if the PDF is a scanned image. The free version supports this — no paid subscription needed.

**Q: My digital signature isn't being validated by recipients.**  
A: Certificate-based signatures require the certificate chain to be trusted by the recipient's viewer. If you're using a self-signed certificate, they need to add your certificate to their trusted certificates list. For legally recognized signatures, use a qualified certificate from a trusted authority (DigiCert, GlobalSign, etc.).

**Q: Foxit is slow on a PDF with hundreds of pages.**  
A: Enable lazy loading: Preferences → Documents → Enable Fast Web View. This loads only visible pages instead of the entire document. For very large documents, also close unused tabs — each tab keeps its document in memory.

**Q: Does Foxit have a portable version?**  
A: Foxit can be run without installation by extracting the portable ZIP from the download page. Settings and annotations are stored relative to the executable folder.
