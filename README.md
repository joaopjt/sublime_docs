# Sublime Docs
Open the README docs from npm packages with the command pallet of sublime text.

## Why
If you work as web developer, for sure you know how boring and the waste of time everytime you want to get that library docs.
You need to go to your navigator, search and find it in the github, so you can read the library docs (**GENERALLY IN README.md**).

## How it works
This plugin will search for the ``package.json`` in the root of the opened folder at sublime,
but you can change that by creating a file named ``.docsconfig``. The file should follow the format below:

```json
{
  "base_path": "/web/app/themes/projectName/"
}
```

## How to use
Open the sublime command pallet (``ctrl+shift+p``), and search for **Docs**

![Exemple](https://github.com/joaopjt/sublime_docs/blob/master/docs/exemple_01.jpg)

Select it, and a list of your packages should appear. You can filter for them.
After, selected the desired one, and the magic happens!

**Notes:**
- The ``.docsconfig`` should be created at the root of project folder.
- The **base_path** value should start and end with a bar (`/`).
