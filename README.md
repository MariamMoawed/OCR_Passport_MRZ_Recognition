# OCR_Passport_MRZ_Recognition
 
OCR Passports with OpenCV and Tesseract


Finding Text in Images with Image Processing

In the first part of this tutorial, we’ll briefly review what a passport MRZ is. From there, I’ll show you how to implement a Python script to detect and extract the MRZ from an input image. Once the MRZ is extracted, we can use Tesseract to OCR the MRZ.

What Is a Machine-Readable Zone?
A passport is a travel document that looks like a small notebook. This document is issued by your country’s government and includes information that identifies you personally, including your name, address, etc.

You typically use your passport when traveling internationally. Once you arrive in your destination country, an immigration official checks your passport, validates your identity, and stamps your passport with your arrival date.

Inside your passport, you’ll find your personal identifying information. If you look at the bottom of the passport, you’ll see 2-3 lines of fixed-width characters.

The MRZ encodes your personal identifying information, including:

Name
Passport number
Nationality
Date of birth/age
Sex
Passport expiration date
Before computers and MRZs, TSA agents and immigration officials had to review your passport and tediously validate your identity. It was a time-consuming task that was monotonous for the officials and frustrating for travelers who patiently waited for their turn in long immigration lines.

MRZs allow TSA agents to quickly scan your information, validate who you are, and enable you to pass through the queue more quickly, thereby reducing queue length (and reducing the stress on travelers and officials alike).


