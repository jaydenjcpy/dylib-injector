## dylib-injector
A tool that injects .dylib files into decrypted .ipa files througha Github actions script

## How to use

1. Fork this repo
2. Go to actions and enable workflows
3. Click on the workflow that has the title "Inject Dylib into IPA"
4. Click on "Run Workflow" and fill in the boxes with the *DIRECT LINKS* of the decrypted .ipa and .dylib files
5. Click "Run workflow"
6. Wait for the process to finish and go to the section that says "Upload Artifacts" that appears during the workflow run
7. Click on the link to download the zip file, then unzip it to get your injected ipa file

## Credits
[Azule](https://github.com/mpelteshki/Azule) is the tool used in this repo to inject .dylibs into ipa files
