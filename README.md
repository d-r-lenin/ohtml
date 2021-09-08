># On Live HTML \(ohtml\)
<hr>

>## <i> Discription </i>
<div style="
    margin-left:2em;
    margin-bottom:2rem;
    font-size:1.3rem
">Live preview for html</div>

>## <i>Instalation</i>
* To install first you need nodejs installed. [click here to downloat node](https://nodejs.org/en/download/)

* Type following command to install
```
    npm i -g ohtml
```
* Or run npx command directly (not recomended)
```
    npx run ohtml
```
>## usage
* Got to any directory that includes a html file.
* If the directory have only one html file , Simply run " ``` ohtml ``` "
* If you have multiple files, Then specify the filename. Like " ``` ohtml <file_name.html> ``` "
* If the default PORT is not available, Specify the port like " ``` ohtml index.html --port 5000 ``` "

>## Argument List

<hr>

 * ## ```--help```  <sub style="font-size:.5em">optional</sub>
    ###  To Show help
    ```
        ohtml --help
    ```
<hr>

* ## ``` --port ``` <sub style="font-size:.5em">optional</sub>
    ### To specify the PORT
    ```
    ohtml --port 3000
    ```
    default:: 4040

<hr>

* ## ``` --path ```  <sub style="font-size:.5em">optional</sub>

    ### To specify the path to watch
    ```
    ohtml --path "E://my_app/"
    ```
    default:: '.' (current path)

<hr>

* ## ```--file``` <sub style="font-size:.5em">optional</sub>

    ### To specify the file name
    ```
    ohtml --file mysite.html
    ```
    default:: <first file in the path\>

># Example
```
    ohtml index.html
```
```
    ohtml --path C://Github/myApp --file example.html --port 3000
```