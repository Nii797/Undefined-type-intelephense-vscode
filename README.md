# Undefined-type-intelephense-vscode
problem Undefined type intelephense in vscode 
==============================================

Troubleshooting Undefined type intelephense (1009). In the latest update from PHP Intelephense, intelephense keeps showing errors for undefined symbols for routes (and other classes too), there has been no error like this before and it is annoying.

I'm one of those people who don't really like to see the error red color everywhere, it's itchy and uncomfortable because i'm 
perfectionist hahahah.

![alt text](https://github.com/Nii797/Undefined-type-intelephense-vscode/blob/main/image/image-1.png?raw=true)

at the check this problem message like this and make me uncomfortable in eyes hahaha.

![alt text](https://github.com/Nii797/Undefined-type-intelephense-vscode/blob/main/image/image-2.png?raw=true)

after check that causes is extension intelephense didn't definition my code used 

Undefined type intelephense(1009)

intelephense have option configuration for make active or non activate every category symbol which is determined for adjusted with code style.

This option is :

1. intelephense.diagnostics.undefinedTypes
2. intelephense.diagnostics.undefinedFunctions
3. intelephense.diagnostics.undefinedConstants
4. intelephense.diagnostics.undefinedClassConstants
5. intelephense.diagnostics.undefinedMethods
6. intelephense.diagnostics.undefinedProperties
7. intelephense.diagnostics.undefinedVariables

so that is code not like have problem, settings option above becomes false, **exepct intelephense.diagnostics.undefinedVariables.**

This step for install
Click File > Prfences > Settings

![alt text](https://github.com/Nii797/Undefined-type-intelephense-vscode/blob/main/image/image-3.png?raw=true)

Input option varable which will changed value becomes false

1. intelephense.diagnostics.undefinedTypes
2. intelephense.diagnostics.undefinedFunctions
3. intelephense.diagnostics.undefinedConstants
4. intelephense.diagnostics.undefinedClassConstants
5. intelephense.diagnostics.undefinedMethods
6. intelephense.diagnostics.undefinedProperties

![alt text](https://github.com/Nii797/Undefined-type-intelephense-vscode/blob/main/image/image-4.png?raw=true)

Click and changes checkbox becomes false

![alt text](https://github.com/Nii797/Undefined-type-intelephense-vscode/blob/main/image/image-5.png?raw=true)

do it for option else

last close Visual Studio Code this is for refresh yours Visual Studio Code. and not will show error undefined type intelephense again.

This is done no problem again

good luck

![alt text](https://github.com/Nii797/Undefined-type-intelephense-vscode/blob/main/image/image-6.png?raw=true)


**reference** : https://www.pintarkoding.com/mengatasi-masalah-undefined-type-intelephense1009/ and
            https://stackoverflow.com/questions/59149877/visual-studio-code-php-intelephense-keep-showing-not-necessary-error
