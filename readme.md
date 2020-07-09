# Default Template index for [short🩳](https://github.com/vincent-herlemont/short) 

This index allow to share templates with the community.

## Display with cli

List available templates with **[short cli](https://github.com/vincent-herlemont/short)**.
```
$> sht generate -l
```
## Add template and share with the community.

1. Create an **short** and **git** project. You can inspire you with existing templates like 
[test](https://github.com/vincent-herlemont/test-short-template) and
[aws-sam](https://github.com/vincent-herlemont/aws-sam-short-template.git).
2. Assure you that your repository is accessible publicly. 
You can use [github](https://github.com/), [gitlabs](https://gitlab.com/), [bitbucket](https://bitbucket.org/product) etc ...
3. Create an new file json file `<file name>.json` in the index repository **[add file](https://github.com/vincent-herlemont/short-template-index/new/master)**
with the following data : 
    ```json
    { "url" : "https://.... or git@.... your git url" }
    ```
4. Create pull request on this repository.

