## APP and API Description

The APP allows the user to write notes as an agenda.

The APP sends two XML.

The API validates them (XSD) and store the data.

## XML description

The app can send two XML:

  One  with the note.
  
  <?xml version="1.0" encoding="UTF-8"?>


<accounts xmlns="https://www.alberto.com/accounts"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="https://www.alberto.com/accounts accounts.xsd">
    <account>
        <messages>
            <message>
                <image>https://firebasestorage.googleapis.com/</image>
                <text>Prueba</text>
            </message>
        </messages>
    </account>
</accounts>
  
  The other with the registration details.
  
  <?xml version="1.0" encoding="UTF-8"?>

<accounts xmlns="https://www.alberto.com/accounts"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="https://www.alberto.com/accounts accounts.xsd">
    <account>
        <details>
            <detail>
                <age>19</age>
                <country>Spain</country>
                <image>https://firebasestorage.googleapis.com/</image>
                <nickname>Test</nickname>
                <sex>Woman</sex>
            </detail>
        </details>
    </account>
</accounts>
  
## Screenshots

XML of notes

https://github.com/koncana/xml-xsd-Readme.md-/blob/master/img/XML%20messages.JPG

XML of registration details

https://github.com/koncana/xml-xsd-Readme.md-/blob/master/img/XML%20details.JPG



## Acknowledgments

https://netbeans.org/. The framework I used. 

https://www.w3schools.com/xml/default.asp. A great place to learn about xml.

https://www.w3schools.com/xml/xml_schema.asp. A great place to learn about xsd.

https://github.com/tcrurav/D3EnIonic. An example of Readme.md

https://github.com/tcrurav/XmlRESTfulNodeJSfromJS. An example of xml and Readme.md

### Extensible Markup Language

### Does It comply with the basis sixtaxis of Extensible Markup Language?

It doesn´t because Markdown doesn´t use labels.
