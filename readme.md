


# lib_Weglot

This is the Weglot plugin for Convertigo platform for building automatic multi-lingual applications with a language selector.

To use this library you will neet to set up a Weglot account  on [https://dashboard.weglot.com/login](https://dashboard.weglot.com/login)

## Symbols

To use this library you will have to configure the following symbols in the Admin console.

| Symbol | Usage |
|----------|---------|
|lib_weglot.weglotkey.secret  | The Weglot API key you will find in the Weglot dashboard for your project |




For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Library](#mobile-library)
    - [Shared Actions](#shared-actions)
        - [InstallWeglot](#installweglot)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_Weglot=https://github.com/convertigo/c8oprj-lib-weglot.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Weglot=https://github.com/convertigo/c8oprj-lib-weglot/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Weglot__ project


## Mobile Library

Describes the mobile application global properties

### Shared Actions

#### InstallWeglot

This Shared Action must be invoked in your app to initilize Weglot



