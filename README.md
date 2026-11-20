# Syncfusion® Blazor DOCX Editor – Signature using signature pad

## Introduction

This sample demonstrates how to add signatures using the Syncfusion® Blazor DOCX Editor integrated with the Signature Pad component. Users can draw their signatures, add relevant details such as name and title, and insert the signature directly into the document.

## Project Features

- Draw signatures using the Signature Pad component
- Add signer details such as name and title
- Insert the signature into the document
- Signature will be preserved as image
 
## How to Run the Sample
 
This sample includes a Blazor application that must be running to enable the complete signature creation and insertion workflow within the DOCX Editor.

### 1. Navigate to the project directory:

```bash
cd signature-using-signature-pad-in-blazor-docx-editor
```

### 2. Build and run the application:

```bash
dotnet build
dotnet run
```
 
## APIs Used
 
| API / Endpoint | HTTP Method | Purpose |
| --- | --- | --- |
| `/api/ContentReview/GetSignatureAsync` | POST | Returns the signature as a base 64 encoded string. |
| `/api/ContentReview/FindAllAsync` | GET | Finds all occurrence of specified text in the document. |
| `/api/ContentReview/InsertImageAsync` | POST | Inserts an image at the cursor position in the document. |
 
## Resources
 
- **Product page:** [Syncfusion Blazor DOCX Editor](https://www.syncfusion.com/docx-editor-sdk/blazor-docx-editor?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples)
- **Documentation:** [Syncfusion Blazor DOCX Editor - Documentation](https://help.syncfusion.com/document-processing/word/word-processor/blazor/overview?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples)
- **Online demo:** [Syncfusion Blazor DOCX Editor - Online demo](https://document.syncfusion.com/demos/docx-editor/blazor-server/document-editor/default-functionalities?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples)
 
## Support and feedback
 
For any other queries, reach our [Syncfusion support team](https://support.syncfusion.com/?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples) or post the queries through the [community forums](https://www.syncfusion.com/forums?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). 

Request new feature through [Syncfusion feedback portal](https://www.syncfusion.com/feedback?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples).
 
## License
 
This is a commercial product and requires a paid license for possession or use. Syncfusion's licensed software, including this component, is subject to the terms and conditions of [Syncfusion's EULA](https://www.syncfusion.com/license/studio/35.1.37/syncfusion_essential_studio_eula.pdf?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). You can purchase a license [here](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples) or start a free 30-day trial [here](https://www.syncfusion.com/account/manage-trials/start-trials?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples).
