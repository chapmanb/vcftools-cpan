## cpanm ready distribution of VCFtools Perl libraries

A number of Perl tools make use of the VCF Perl libraries in VCFtools
(http://vcftools.sourceforge.net/). These are not present in an existing
CPAN-compatible package and require external installation of vcftools and manual
adjustment of a user's `PERL5LIB`.

This provides an installable distribution of just the Perl modules from VCFtools.
This is `r953` from the latest vcftools release (0.1.12b) converted into a CPAN
friendly version number (0.953). You can install with cpan minus
(http://search.cpan.org/perldoc?App::cpanminus):

    cpanm -i https://github.com/chapmanb/vcftools-cpan/archive/v0.953.tar.gz

The code is all written by Petr Danecek and the VCFtools authors and released
under the GNU Lesser General Public License version 3.0 (LGPLv3).
