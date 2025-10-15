📄 The goal was to simulate real-world document automation — converting messy mortgage PDFs into machine-readable information.

I applied three OCR models on the same dataset:

1️⃣ Tesseract OCR – Classic and open-source, quick to set up but often struggles with layout alignment and faint text.
2️⃣ EasyOCR – Lightweight and intuitive; gave smoother bounding boxes and decent accuracy, though it merged some columns.
3️⃣ PaddleOCR – The most layout-aware engine among the three; produced cleaner segmentation and reliable bounding polygons — ideal for financial or tabular documents.

Each model produced its own JSON outputs, revealing how text detection, bounding boxes, and field extraction vary across architectures.


Key takeaway: OCR accuracy isn’t just about reading characters — it’s about preserving structure, hierarchy, and context.
