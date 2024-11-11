Annotation works
- in mirador, Theseus, Clover and Annona
- none show the HTML annotation. Theseus is in a loading loop

Image transformation tools from inside tropy don't reflect

Before exporting in Tropiiify
- give identifiers to all the items and selections
  - this means select image, sidebar - add a number in the identifier field (or add new field>identifier)
- in the plugin settings change the base ID to the github pages url till 1 level above the index.json
- To the viewers pass the URL manifest.json that is usually in the first subfolder of a collection

https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json

View in 
- [Theseus Viewer](https://theseusviewer.org/?iiif-content=https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json)
- [Universal Viewer](https://uv-v4.netlify.app/#?iiifManifestId=https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json)
- [Mirador Viewer](https://projectmirador.org/embed/?iiif-content=https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json)
- [Annona Viewer](https://ncsu-libraries.github.io/annona/tools/#/display?url=https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json&viewtype=iiif-storyboard&manifesturl=&settings={"fullpage"%3Atrue)
- [Clover Viewer](https://samvera-labs.github.io/clover-iiif/docs/viewer/demo?iiif-content=https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json)
- [DELFT Viewer](https://delft-viewer.netlify.app/#manifest=https://micahchoo.github.io/Tropiiify-test/iiif/455/manifest.json)
