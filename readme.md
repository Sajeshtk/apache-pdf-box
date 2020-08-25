keytool -genkeypair -storepass 123456 -storetype pkcs12 -alias test -validity 365 -v -keyalg RSA -keystore keystore.p12

Usage
-----
Pass the below as program arguments
Example: keystore.p12 123456 sample.pdf

java poc.pdf.CreateSignature <pkcs12_keystore> <password> <pdf_to_sign>

Refer
https://pdfbox.apache.org/2.0/examples.html
