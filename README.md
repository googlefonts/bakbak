# Bakbak One
![Bakbak](/images/Bakbak.jpg)
Designed by Saumya Kishore and Sanchit Sawaria

Bakbak One is a custom brand typeface for All India Bakchod. Owing to its usage, it is a heavyweight display typeface for headings, video titles and posters. It consists of 1 weight and 692 glyphs and borrows from humanist ‘Johnston’ like arches. Bakbak is loud and present but also neutral enough to render anything from a warning to a mockery.

[Specimen](https://www.sawariasanchit.com/bakbak)

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you particularly want to build fonts manually on your own computer, you will need to install the [`yq` utility](https://github.com/mikefarah/yq). On OS X with Homebrew, type `brew install yq`; on Linux, try `snap install yq`; if all else fails, try the instructions on the linked page.

Then:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at
http://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
