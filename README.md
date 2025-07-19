# BengaliToHindiRefiner

A project combining OCR (Optical Character Recognition), handwritten text recognition, and natural language translation with refinement. Here's a high-level plan of the end-to-end system:
Input: Handwritten Bengali text or an image.
Step 1 - OCR: Recognize handwritten Bengali text from the image.
Step 2 - Bengali to Hindi Translation: Translate extracted Bengali text to Hindi.
Step 3 - Text Refinement: Improve clarity/understandability in Hindi.
Output: Display refined Hindi translation.
Models and libraries used:
pyteserract-> To extract the text from the image
Facebook m2m100-> To translate the Bengali text into Hindi
Google flan/t5-> For the refinement of the extracted text
