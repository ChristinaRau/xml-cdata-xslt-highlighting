# XML CDATA XSLT Highlighting

**XML CDATA XSLT Highlighting** is a Visual Studio Code extension that enables XSLT syntax highlighting within CDATA sections of XML files. 

---

## Features

- Automatically detects CDATA sections in XML files.
- Applies XSLT syntax highlighting within the CDATA blocks.
- Improves readability and debugging of XSLT code embedded in XML.

### Example

With this extension, the following XML code will render the XSLT code inside the <![CDATA[]]> block with proper syntax highlighting:


```xml
<root>
  <data>
    <![CDATA[
    <xsl:stylesheet xmlns:xsl="http://www.w3.org/1999/XSL/Transform" version="1.0">
        <xsl:template match="/">
            <html>
                <body>
                    <h1>XSLT Inside CDATA</h1>
                </body>
            </html>
        </xsl:template>
    </xsl:stylesheet>
    ]]>
  </data>
</root>
```

## Usage

Open any XML file with CDATA sections containing XSLT code.
The extension will automatically highlight XSLT code inside CDATA sections.

## License

This extension is licensed under the MIT License.