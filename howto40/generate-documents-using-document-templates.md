---
title: "Generate documents using document templates"
category: "howto40"
space: "Mendix 4 How-to's"
---
## Description

This section describes how to generate a document with a microflow using a previously designed document template. The related reference guide article can be found [here](https://world.mendix.com/pages/releaseview.action?pageId=10420579).

## Instructions

![](attachments/819203/917932.png) **Create the document template you intend to use. If you do not know how to do this, please refer to** **[this](https://world.mendix.com/display/howto25/Create+and+build+a+document+template)** **article.**

![](attachments/2621586/2752884.png)

![](attachments/819203/917932.png) **Open the microflow, or if necessary create a new one. If you do not know how to add documents to your project, please refer to** **[this](https://world.mendix.com/display/howto25/Add+documents+to+a+module)** **article.**

![](attachments/2621586/2752880.png)

Make sure that the object which is connected to the document template you intend to use is passed to the microflow.

![](attachments/819203/917932.png) **Use a 'Create object' activity to create a new object of the System.FileDocument entity or a specialization of it. If you do not know how to use the 'Create object' activity, please refer to** **[this](https://world.mendix.com/display/howto25/Create+and+change+an+object)** **article.**

![](attachments/2621586/2752879.png)

This object will be used to store the document in.

![](attachments/819203/917932.png) **Add a 'Generate document' activity to the microflow and double-click on it.**

![](attachments/2621586/2752886.png)

![](attachments/819203/917932.png) **Use the drop-down menu at 'File' to select the file object which is created in the microflow.**

![](attachments/2621586/2752881.png)

![](attachments/819203/917932.png) **At 'Language' you can use the radio buttons to select the language the form should be generated in.**

You can choose either the language of the current user, the default project language, or a language stored in a variable.

![](attachments/819203/917932.png) **Use the drop-down at 'Document type' to select which of the available formats should be used for the generated document.**

![](attachments/2621586/2752882.png)

![](attachments/819203/917932.png) **Press the 'Select' button next to 'Template' to bring up a new menu allowing you to choose the document template you want to use.**

![](attachments/2621586/2752883.png)

![](attachments/819203/917932.png) **The parameter area will now be filled with the parameters needed for the document template. Select one of these parameters and click on the 'Edit parameter value'.**

![](attachments/2621586/2752874.png)

![](attachments/819203/917932.png) **In the new window you can specify the variable you want to pass to the document template with the use of a microflow expression.**

![](attachments/2621586/2752873.png)

![](attachments/819203/917932.png) **The microflow should now be fully configured to generate a document when it is executed.**

![](attachments/2621586/2752885.png)

![](attachments/819203/917932.png) **To enable viewing of the generated document, add a download form with file manager, or add a 'Download' activity to the microflow that generated the document.**

If the document is not intended to be kept after the initial download, you can add a 'Change' activity to the microflow that generated the document to set the 'DeleteAfterDownload' flag of the document to 'true'.

[![](attachments/819203/917564.png)](generate-documents-using-document-templates)[(Back to Top)](generate-documents-using-document-templates)