# XamarinFormsTemplate

This is source code of newest Xamarin.Forms with PCL Xamarin.Forms core project Template made by Japan Xamarin User Group.

## Specification

- Xamarin.Forms 3.1.0.637273
- PackageReference (can use only Visual Studio 2017)
- PCL core project (profile 44)

# How to get

### Option 1: Clone the Repository (Recommended)

Clone the project on the following location directly:

```%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#```

That is, on a command prompt, you can install the template by the following commands:

```
cd "%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#"
git clone https://github.com/ytabuchi/XamarinFormsPCLTemplate.git
```

After the first installation, you can update your copy by ```git pull``` in ```XamarinFormsPCLTemplate``` directory, and you feel it's easier to update the templates than the other option.

### Option 2: Download the ZIP

- Download XamarinFormsTemplate-master.zip file from [GitHub](https://github.com/ytabuchi/XamarinFormsPCLTemplate/archive/master.zip)
- Extract the zip file
- Move the extracted ```XamarinFormsTemplate-master``` folder to the following location:
```%USERPROFILE%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#```

Please see [blog page (in Japanese)](http://ytabuchi.hatenablog.com/entry/vs-xf-template) for how to use.

# How to maintenance

`MyTemplate.vstemplate` located in Root folder is a Master file that is specify each child projects.
In each projects folder, there are `MyTemplate.vstemplate` files. They are the template setting files for each projects.

If Xamarin.Forms will be updated, you can just change the version numbers of each `MyTemplate.vstemplate` files

There are some macros such as `WizardExtension` in the template files. Please see [MSDN document](https://docs.microsoft.com/en-us/visualstudio/extensibility/visual-studio-template-schema-reference) for each meaning.
