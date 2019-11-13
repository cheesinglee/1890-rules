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

OCR and machine translation is finished with the exception of the
example game at the end of book. That section appears to use lots of
colloquialisms that cause the maching translation output to be barely
intelligible. OCR output is stored [here](./ocr_output.txt).

The machine translation output has been rewritten into legible prose,
but as this rulebook contains some extra details and repetitions
compared to typical English language 18xx rulebooks, it could be
streamlined substantially.

## Contributing

Collaboration is welcome through pull requests.

## License

Unless license issues arise due to use of the Japanese rules:

This work is licensed under the Creative Commons Attribution 4.0
International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by/4.0/ or send a letter to
Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
