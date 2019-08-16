# 1890-rules
Rulebook translation for 1890 from the original Japanese to English.

Besides being quasi-literate in kanji, I have no language skills that
would aid this endeavor, so this project is based on OCR of the
Japanese rules coupled with machine translation.

## Tools

OCR was performed with
[gImageReader](https://github.com/manisandro/gImageReader) (based on
the tesseract library), and machine translation was done with [Google
Translate](https://translate.google.com).

The English translation is being authored in
[LaTeX](https://www.latex-project.org/).

## Compiling

Run the following command to generate a PDF of the rules:

`pdflatex -interaction=nonstopmode 1890rules-en-translation.tex`

## Status

OCR and machine translation is finished through Appendix C of the
rules. Appendix D (1890 simplified scenario) and the Designer Notes
remain to be OCR'd and machine translated. OCR output is stored as
comments in the .tex source file.

The machine translation output has been rewritten into legible prose
up through Chapter 6.

As this rulebook contains some extra details and repetitions compared
to typical English language 18xx rulebooks, there may be an extra
stage of editing for conciseness.

## Contributing

Collaboration is welcome through pull requests.

## License

Unless license issues arise due to use of the Japanese rules:

This work is licensed under the Creative Commons Attribution 4.0
International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by/4.0/ or send a letter to
Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
