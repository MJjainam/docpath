obj is generated from running `godocfx cloud.google.com/go/notebooks`
Create obj-gen dir and run the below steps
    1. Run `docfx init` inside obj-gen
    2. Edit generated docfx.json by adding path
    3. Then run `docfx build` command. This creates _site folder.
    4. You can serve the _site folder `cd obj-gen/_site && python3 -m http.server 8080`
