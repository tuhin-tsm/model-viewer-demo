# Model Viewer Demo

Easily display interactive 3D models on the web & in AR.

This project uses [model-viewer](https://modelviewer.dev/) component by Google

#### Note:
Only `glTF/GLB` models are supported,

### Running app locally

1. Install [Node.JS](https://nodejs.org/en)
2. `cd` into your directory and install dependencies by:
     
     `D:\Project\model-viewer-demo> npm install`
3. Start development server by running:

     `D:\Project\model-viewer-demo> npm start`
     
     Note: If required allow access in windows defender.
4. Open the http://127.0.0.1:8000/ URL in browser to access the page.

     Note: You can access the  app from other devices such as mobile devices from same network by opening the other URL shown in the command line.
     
     Something like: `192.168.XXX.XXXX:8000`
     
### Convert FBX to Gltf/GLB using [Facebook's FBX2glTF](https://github.com/facebookincubator/FBX2glTF)

1. Put the required `fbx` file in the `bin` folder
2. Open a command window in the `bin` directory and run the following command:

`D:\Project\model-viewer-demo\bin> .\FBX2glTF.exe .\3DView-3D.fbx`

Note: This may take couple of minutes to complete depending upon the size of the `fbx` file.
