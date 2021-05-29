# Texeech--Text-to-Speech
# A programme to read aloud the contents of a pdf 
Here I have written a code where the programme reads aloud the contents of a pdf word by word. The programme in written using Python language. 
The approach of the programme is like this.
1) I first import the python library PyPDF2. PyPDF2 acts as a pdf toolkit. The function of this is to extract the document information and encrypt and decrypt the pdf file. From this library the class PdfFileReader is imported. 
2) The second library imported is pytttsx3. This library is used for text to speech conversion. Using pyttsx3
An application invokes the pyttsx3.init() factory function to get a reference to a pyttsx3.Engine instance. During construction, the engine initializes a pyttsx3.driver.DriverProxy object responsible for loading a speech engine driver implementation from the pyttsx3.drivers module. After construction, an application uses the engine object to register and unregister event callbacks; produce and stop speech; get and set speech engine properties; and start and stop event loops.

3) At the end a loop is run to extract information of each page and read it aloud in a specific volume of our choice and also the male or female voice of our choice.

