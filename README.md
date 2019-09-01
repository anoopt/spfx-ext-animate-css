## SPFx Animate.css extension

This is a simple SPFx extension (application customiser) to add a CSS file.

### Instructions

- Download and upload [animate.min.css](https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css) to a library in your SharePoint site.
- Update the cssurl property in [elements.xml](./sharepoint/assets/elements.xml) to point to the uploaded file.
- Package the solution and upload it the app catalog.
- Add the app to the required site.
- Follow the instructions in [this article](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/extensions/get-started/serving-your-extension-from-sharepoint) for deployment. 