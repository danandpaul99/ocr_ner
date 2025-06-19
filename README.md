# This task demonstrates a combined approach using Optical Character Recognition (OCR) with EasyOCR and OpenCV, along with Named Entity Recognition (NER) using spaCy. 
# The workflow involves extracting text from images and overlaying bounding boxes around detected text regions.
# Since OCR can sometimes produce inaccurate or noisy text—especially from scanned or low-quality documents—TextBlob is used for basic text correction before applying NER. 
# This helps improve the accuracy of entity recognition by normalizing misspelled or distorted words.
# After correction, the cleaned text is processed through NER to identify and classify entities such as names, dates, organizations, locations, and numerical values.

# Model Used for NER - Spcay NER
# Text Detection and Recognition - EasyOCR
# Text correction - Text Correction
