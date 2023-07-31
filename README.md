# Pulling RealBundle from WebFlow

Be sure to install `wget` via HomeBrew.

1. Open a temporary directory in console.
2. Run `wget --recursive --page-requisites --span-hosts --html-extension --domains="realbundle.com,uploads-ssl.webflow.com" realbundle.com`
3. Move the files in `www.realbundle.com` to the `realbundle.com` folder.
4. Open the `uploads-ssl.webflow.com` folder and rename the `64475dc938d5f0a9a3db70a4` folder to  `assets`, then move it into the `realbundle.com` folder.
5. Open the `realbundle.com` folder in VS Code.
6. Search and bulk replace `https://uploads-ssl.webflow.com/64475dc938d5f0a9a3db70a4` to `/assets`
7. Copy/paste all the folders into the root of this project.