# @WCYS-Co/--font-template

[![][Fontbakery]](https://wcys-co.github.io/--font-template/fontbakery/fontbakery-report.html)
[![][Universal]](https://wcys-co.github.io/--font-template/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://wcys-co.github.io/--font-template/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://wcys-co.github.io/--font-template/fontbakery/fontbakery-report.html)
[![][Shaping]](https://wcys-co.github.io/--font-template/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwcys-co%2F--font-template%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwcys-co%2F--font-template%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwcys-co%2F--font-template%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwcys-co%2F--font-template%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fwcys-co%2F--font-template%2Fgh-pages%2Fbadges%2FUniversal.json

> ⚡️ Starter template for Glyphs / UFO font projects ⚡️
<!-- REMOVE ANY QUOTED TEXT -->

Snazzy description of your font here. 

Origin of the project, idea of usage, concept of creation… but also number of masters, axes, character sets, et al.

![Sample Image](documentation/hero-light.svg#gh-light-mode-only)
![Sample Image](documentation/hero-dark.svg#gh-dark-mode-only)

> ## Setting up your font // REMOVE THIS SECTION FROM README
>
> This template is based on [Google Fonts' Project Template](https://github.com/googlefonts/googlefonts-project-template)
> 
> * **New repositories.** Hit the green button above ("Use this template") to create your own repository. Please note that a GitHub Action job will be executed once you've created the repository which will populate the readme. This may take a few minutes. Please wait for this job to complete before pulling the repo to your local system.*
> 
> * **Updating a repository.** To update your font repository to bring in the latest best-practices from Google Fonts, run `make update-ufr` from the command line.
> 
> * Replace the font sources in the `sources` directory with your own font sources. These sources may be either in Glyphs or UFO/Designspace formats.
> 
> * Read up on [Google Fonts Specifications](https://github.com/googlefonts/gf-docs/tree/main/Spec) for best practices. Note, following the spec is a prerequisite if submitting to Google Fonts. 
> 
> * Then reference the sources in the file `sources/config.yaml`, as well as making any other changes you would like to make based on the instructions in the [Google Fonts Builder documentation](https://github.com/googlefonts/gftools/blob/main/Lib/gftools/builder/__init__.py).
> 
> * Add yourself to the `AUTHORS.txt` and `CONTRIBUTORS.txt` files.
> 
> * Update the first line of the OFL.txt (year and project name). Update also the Copyright string in the sources, it has to be the same as the OFL.txt. The `.glyphs` file in this repo gives you required base charset and font info.
> 
> * Finally, add and commit any files you have modified (i.e. `README.md`, `AUTHORS.txt`, `CONTRIBUTORS.txt`, the font sources, and `sources/config.yaml`) to git, then push to GitHub. Please be aware that GitHub Actions may take a few minutes to build your font family. It is worthwhile inspecting the progress in the "Actions" tab.
> 
> * If GitHub Actions has successfully built the family, you will find the font binaries in the Actions tab. The official GitHub Actions documentation provides further [information](https://docs.github.com/en/actions/managing-workflow-runs/downloading-workflow-artifacts).
> 
> * If you feel your font project has hit a milestone, create a new release for it. Go to the releases page and hit the "Draft a new release button". Provide a tag number and title with only a decimal number e.g 0.100, 1.000 etc. For the body text, mention what has changed since the last release. Once you are done, hit the "Publish release" button. Here is an example: https://github.com/m4rc1e/test-ufr-family/releases/tag/2.019. For more info regarding GitHub release, please see the official GitHub Release [documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). **Please note that GitHub Actions must be able to build the fonts before you can make a release. Once you have made a release, the fonts and tests assets will be attached to the release automatically. This may take a while since the fonts and tests will be built from scratch.**

## Building

Fonts are built automatically by GitHub Actions -- take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions -- look at `https://{{yourGitHubUsername}}.github.io/{{yourFontRepositoryName}}`.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**2021-05-26 Version 2.130**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Stylistic sets added.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
