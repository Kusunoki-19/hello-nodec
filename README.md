# hello-nodec

![](./gallery/screenshot.png)

## Quick Start

1. Clone this repository.
   ```sh
   git clone --recursive https://github.com/ContentsViewer/hello-nodec.git
   ```

   If you have already clone it without submodule clones, clone submodule recursively.

   ```sh
   git submodule update --init --recursive
   ```

2. Build dependencies.
   * assimp
     * `nodec/modules/assimp`
  
   * DirectXTex
     * `nodec/platforms/sdks/DirectXTex/`
     

3. Open the project according to the desired platform.
   * Windows
     * Environment
       * Visual Studio 2022
    
     1. Open the project file `project.sln`.


   * macOS
     * Not supported yet.

4. Add your editor config file.
   * Windows
     * location: [`windows/apps__hello_nodec`](windows/apps__hello_nodec/)

   <b>`editor-config.json`</b>

   ```json
   {
       "config": {
           "font": {
               "path": "{path to the font path}",
               "pixel_size": 18.0
           },
           "resource_path": "{path to the resource folder}"
       }
   }
   ```
   
   * <b>resource_path</b>
  
     The path to the `nodec/apps/hello-nodec/resources`.

     for example: `C:/Users/{your-name}/{path-to-project}/hello-nodec/nodec/apps/hello-nodec/resources`

5. Enjoy
   ![](./gallery/screenshot.png)

