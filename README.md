# phpunit-stubs
PHPUnit Stubs file for PHP Intelephense for VS Code

# To Use

1. Download the phpunit-stub.php file
2. Update the settings.json file of your VSCode

## settings.json file changes

```
    "intelephense.stubs": [
        ...
        "/your/folder/location/vscode-stubs/"
        ...
    ],
```

Make sure that where `vscode-stubs` is in the example, you place the folder name that contains the PHPUnit Stubs file. Ignore the warning that this value does not exist in the PHP Intelephense valid array. At least as of version 1.5.4 of Intelephense this still works.
