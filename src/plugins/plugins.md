# Plugins

## General architecture
The server accepts plugins in the `plugins` folder. The so called plugin loader will scan the `plugins`folder for subfolders and try to include the `index.ts` file. 

![plugin architecture](https://raw.githubusercontent.com/wzr1337/rsiServer/develop/src/plugins/rsiServer_architecture.png "Plugin Architecture 1")
