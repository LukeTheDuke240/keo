# keo
Krunker editor offline: a fully functional offline version of the krunker editor.
For this to work you need to download this file: https://assets.krunker.io/mod.zip?v=3.3.7 and extract the folders "models" and "textures" into the directory. If you want to save space, you can delete textures\weapons, which is 400MB of weapon textures

TODO: 
  - redirect the file requests from assets.krunker.io to the local folder... somehow
  - when running offline, getting the textures is blocked by CORS >:(
  - either need to modify the script to grab local files, or "fake" the files being on assets.krunker.io with http server and hosts?
