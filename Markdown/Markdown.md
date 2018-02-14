The recommended way to use Markdown is to type the document on Madoko.

Website: https://www.madoko.net/.

Here is its document: http://madoko.org/reference.html.


Translating a markdown document is done simply as:

madoko -v mydoc.mdk
which generates mydoc.html. The -v flag gives more verbose output. To also generate a PDF file, use:

madoko --pdf -vv --odir=out mydoc
where --odir puts all output files in the out directory. To generate a PDF, you need to have LaTeX installed on your system, which is also required for mathematics and bibliographies. We recommend the full TeXLive LaTeX system as it is available for Windows, Linux and MacOSX, and is used on the Madoko.net server as well.

For PDF output, we added an extra verbose flag in order to see any warnings LaTeX produces. A full description of all command line options can be found in Appendix A.1.





















