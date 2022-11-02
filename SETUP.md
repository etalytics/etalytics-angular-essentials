## Setup for publishing the extension

Make sure you have Node.js installed. Then run:

`npm install -g vsce`

Login as publisher
`vsce login <publisher name>`

In the console run

```
$ vsce package
# myExtension.vsix generated
$ vsce publish
# <publisherID>.myExtension published to VS Code Marketplace
```

Alternatively, you can package the extension (vsce package) and manually upload it to the Visual Studio Marketplace publisher management page:
https://marketplace.visualstudio.com/manage

# References

- https://code.visualstudio.com/api/get-started/your-first-extension
- https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup
- https://code.visualstudio.com/api/working-with-extensions/publishing-extension
