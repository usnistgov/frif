Friction Ridge Image and Features Technology Evaluations <img src="doc/doxygen/assets/nist_itl_two_color.svg" align="right" alt="NIST Information Technology Laboratory" style="width:150px" />
=================================

Friction Ridge Image and Features (FRIF) Technology Evaluations (TEs) are a
series of public tests of automated friction ridge algorithms. Algorithms tested
in FRIF TEs are usually part of a larger Automated Biometric Identification
System (ABIS). Tests of automated friction ridge algorithms have taken place at
the National Institute of Standards and Technology (NIST) since 2004.

Tests
-----
FRIF defines common concepts within an application programming interface (API)
that apply to many different types of automated friction ridge algorithms that
make up core components (but not the entirety) of an ABIS. TEs under the FRIF
umbrella define an additional, more specific API for each type of friction ridge
algorithm tested by NIST. These APIs allow NIST a common interface to perform
testing among a width breadth of participants.

The various types of algorithms currently under test by NIST include:

### Exemplar 1:N Search
*Note: this TE was previously called "[Fingerprint Vendor Technology Evaluation
(FpVTE)]."*

Search one or more exemplar fingerprint image against a participant-defined
database of millions of other subjects.

### Mark 1:N Search
_Note: This TE was previously called both "[Evaluation of Latent Fingerprint
Technologies (ELFT)]" and "[Evaluation of Latent Friction Ridge Technology],"
and has **not** yet been converted to the FRIF TE umbrella._

Search one or more friction ridge mark (colloquially, "latent") image and/or
sets of friction ridge features (e.g., minutia) against a participant-defined
database of millions of friction ridge exemplar and/or mark data.

### 1:1 Comparison
_Note: This TE was previously called "[Proprietary Fingerprint Template
(PFT)]" and has **not** yet been converted to the FRIF umbrella._

Produce a similarity score given two exemplar fingerprint images.

### PIV 1:1 Comparison
_Note: This TE was previously called "[Minutiae Interoperability Exchange
(MINEX)]" and has **not** yet been converted to the FRIF umbrella._

Produce a similarity score given two exemplar fingerprint images, where the
fingerprint feature representations (i.e., "templates") were not necessarily
generated by the algorithm under test. This test supports the comparison
operations performed under the US Government's FIPS 201 Evaluation Program.

### Slap Fingerprint Segmentation (SlapSeg)
_Note: [SlapSeg] has **not** yet been converted to the FRIF umbrella._

Automatically draw bounding boxes around the distal phalanges present in a
multi-finger impression image.

Communication
-------------
If you found a bug and can provide steps to reliably reproduce it, or if you
have a feature request, please [open an issue]. Other questions may be addressed
to the [NIST FRIF TE team].

The FRIF TE team sends updates about the FRIF TEs to their mailing list. Enter
your e-mail address on the [mailing list site], or send a blank e-mail to
FRIFTE+subscribe@list.nist.gov to be automatically subscribed.

License
-------
The items in this repository are released in the public domain. See the
[LICENSE] for details.

[open an issue]: https://github.com/usnistgov/frifte/issues
[mailing list site]: https://groups.google.com/a/list.nist.gov/forum/#!forum/frifte/join
[LICENSE]: https://github.com/usnistgov/frifte/blob/main/LICENSE.md
[NIST FRIF TE team]: mailto:frifte@nist.gov
[Minutiae Interoperability Exchange (MINEX)]: https://www.nist.gov/programs-projects/minutiae-interoperability-exchange-minex-overview
[Proprietary Fingerprint Template (PFT)]: https://www.nist.gov/programs-projects/proprietary-fingerprint-template-evaluations-pft-overview
[SlapSeg]: https://www.nist.gov/programs-projects/slap-fingerprint-segmentation-evaluation-slapseg-overview
[Fingerprint Vendor Technology Evaluation (FpVTE)]: https://www.nist.gov/programs-projects/fingerprint-vendor-technology-evaluation-fpvte
[Evaluation of Latent Fingerprint Technologies (ELFT)]: https://www.nist.gov/programs-projects/nist-evaluation-latent-fingerprint-technologies-elft
[Evaluation of Latent Friction Ridge Technology]: https://www.nist.gov/itl/iad/image-group/evaluation-latent-friction-ridge-technology
