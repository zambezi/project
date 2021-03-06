Zambezi Project
===============

Whenever you're starting a project, there are about a million questions that need to be answered – some of them inevitable end up having to be answered for every project. This template attempts to answer the most common ones, providing a solid foundation for you to build on.

Usage
-----

There are three ways to generate a project using this template:

- Interactively using the initialization guide
- Automatically by initializing with default values
- Downloading the latest release and editing files manually

### Interactive project generation

Run the following in a bash terminal, substituting `<directory>` with the directory you wish to create your project in:

```bash
git clone https://github.com/zambezi/project.git <directory> && <directory>/init
```

This will run the guide, which will take you through the process. Once it's done, cd in to `<directory>` and behold your glorious new project!

### Automatic project generation

This is similar to interactively generating a project, but you also add the `--default` flag with the script, like so:

```bash
git clone https://github.com/zambezi/project.git <directory> && <directory>/init --default
```

This will use default values when generating files, and is good for when you plan to add more information later.

### Manually creating a project

1. [Download the latest release](../../releases/latest)
2. Extract the downloaded archive
3. Run `./init` in the extracted directory – or – follow the checklist below

#### New project checklist

*NOTE: The easiest way to get started is to simply run the included initialization script. Just run `./init` in the directory where you extracted the release archive.*

The steps in this list should be considered mandatory, and the following section includes some information on additional files to keep an eye on.

- [ ] Remove init script

      The file `init` in the extracted directory is a script that guides you through this process, and is by far the easiest way to get started. If you do not wish to run this script, you should remove it altogether. If you *do* run the script, it will remove itself when it's done.

- [ ] Name

      You may pick any name for your project, but as a guideline make sure it's concise and reasonably descriptive.

      Some specific Zambezi tooling uses the `ez` prefix for fun and profit. This is usually done for CLI tooling, but may be used for other kinds of projects as well.

- [ ] README (i.e. this file)

      The README should answer the following questions:

      - **What is this project anyway?** Make the introductory paragraph a short summary of your project. It'll probably be the summary of your [rationale](RATIONALE.md) – the file that justifies the project's existance.

      - **How do I consume this project?** Any instructions on how to use your project, keep them front and center. If there is more than can fit in a simple step-by-step list, then summarize and link to further documentation.

      - **How do I contribute to this project?**
      For developers and those just looking to discuss, provide some [contribution instructions](CONTRIBUTING.md). Make sure that you include some short instructions on how to get started for developers. Again, keep it to a step-by-step list, and any further documentation separately.

      - **What is the license?** For legal reasons, *all* open source projects *must* have a [license and copyright information](LICENSE.md). This template chose MIT because it's short and permissive, and a very popular open source license. You can choose another, but [make sure you've done your homework](https://opensource.org/licenses)!

- [ ] RATIONALE
      
      When you create a project, think about why you're creating it. The [RATIONALE](RATIONALE.md) is your project's justification – its reason for being. You can make this how long and involved as you'd like, but should really discuss the goals and ambitions of the project. The big picture, as it were. Try to avoid sweating the small things like implementation details, so this document stands the test of time. This should be the document you hold up your work against and say: does this fit the bill?

Files to keep updated
---------------------

- [SUMMARY](SUMMARY.md): This file is the summary of your project's documentation. Keep it concise. The default contents is a list of links – keep this, and add to it with sections relevant to your project. This effectively turns your summary into the sitemap of your documentation.

- [AUTHORS](AUTHORS.md): This file should list and thank the authors of your project, in whatever form is appropriate. By default it's a simple thank you notice, followed by a link to the full list of contributors as determined by the repository history. Expand this any way you see fit.

- [LICENSE](LICENSE.md): By default, all Zambezi open source projects use the MIT license. Unless you're switching to an altogether different license, the only thing you should ever consider modifying in this file is the copyright notice – everything else should stay as it is.

Found an issue, or want to contribute?
--------------------------------------

If you find an issue, want to start a discussion on something related to this project, or have suggestions on how to improve it? Please [create an issue](../../issues/new)!

See an error and want to fix it? Want to add a file or otherwise make some changes? All contributions are welcome! Please refer to the [contribution guidelines](CONTRIBUTING.md) for more information.

License
-------

Please refer to the [license](LICENSE.md) for more information on licensing and copyright information.
