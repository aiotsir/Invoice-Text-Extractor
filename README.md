This Jupyter Notebook code was done to create a script to extract text data from invoices of Pharma industry. The script was incorporated to Web App.

Region based and layout based text extraction with Paddle OCR.
Converted the invoice pdf file to image and chose the ROI coordinates from the layout and did text detection and recognition with PaddleOCR, draw_ocr and then reconstructed using non max suppression methods of tensorflow. 
Saved the text to csv file and did data manipulation using Pandas.
