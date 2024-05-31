# ENVS 193DS Homework 3 repository
## Spring 2024

# General information

**Description**: Repo for Homework 03 that answers questions 1-3 

**Homework Overview **: examining effects of specific leaf area (mm^2^/g), water treatment (well-watered or drought-stressed), and species on plant mass for Questions 1a-1e, designed affective data visualizations for personal data for questions 2a-2d, and wrote up a statistical critique for problems 3a-3d

**Data sources** Valliere, Justin; Zhang, Jacqueline; Sharifi, M.; Rundel, Philip (2019). Data from: Can we condition native plants to increase drought tolerance and improve restoration success? [Dataset]. Dryad. https://doi.org/10.5061/dryad.v0861f7 

**Data sources for Statistical Critique**
# Data and file overview

```
.
├── ENVS193DS_homework-08.Rproj
├── README.md
├── code
│   ├── CopyOfhomework-03.pdf
│   ├── CopyOfhomework-03.qmd
│   ├── homework-03.html
│   ├── homework-03.qmd
│   ├── homework-03_files
│   │   ├── figure-html
│   │   │   ├── correlations-with-ggpairs-1.png
│   │   │   ├── mass-as-a-function-of-sla-1.png
│   │   │   ├── mass-as-a-function-of-species-1.png
│   │   │   ├── mass-as-a-function-of-water-treatment-1.png
│   │   │   ├── model-predictions-with-ggeffects-1.png
│   │   │   ├── model-predictions-with-ggplot-1.png
│   │   │   ├── model-predictions-with-ggplot-2.png
│   │   │   ├── saturated-model1-1.png
│   │   │   ├── simpler-model2-1.png
│   │   │   ├── simpler-model3-1.png
│   │   │   └── unnamed-chunk-1-1.png
│   │   └── libs
│   │       ├── bootstrap
│   │       │   ├── bootstrap-icons.css
│   │       │   ├── bootstrap-icons.woff
│   │       │   ├── bootstrap.min.css
│   │       │   └── bootstrap.min.js
│   │       ├── clipboard
│   │       │   └── clipboard.min.js
│   │       ├── quarto-html
│   │       │   ├── anchor.min.js
│   │       │   ├── popper.min.js
│   │       │   ├── quarto-syntax-highlighting.css
│   │       │   ├── quarto.js
│   │       │   ├── tippy.css
│   │       │   └── tippy.umd.min.js
│   │       └── tabwid-1.1.3
│   │           ├── tabwid.css
│   │           └── tabwid.js
│   ├── homework-starter-doc_KEY.html
│   ├── homework-starter-doc_KEY.qmd
│   ├── homework-starter-doc_KEY_files
│   │   ├── figure-html
│   │   │   ├── correlations-with-ggpairs-1.png
│   │   │   ├── mass-as-a-function-of-sla-1.png
│   │   │   ├── mass-as-a-function-of-species-1.png
│   │   │   ├── mass-as-a-function-of-water-treatment-1.png
│   │   │   ├── model-predictions-with-ggeffects-1.png
│   │   │   ├── model-predictions-with-ggplot-1.png
│   │   │   ├── saturated-model1-1.png
│   │   │   ├── simpler-model2-1.png
│   │   │   ├── simpler-model3-1.png
│   │   │   └── unnamed-chunk-1-1.png
│   │   └── libs
│   │       ├── bootstrap
│   │       │   ├── bootstrap-icons.css
│   │       │   ├── bootstrap-icons.woff
│   │       │   ├── bootstrap.min.css
│   │       │   └── bootstrap.min.js
│   │       ├── clipboard
│   │       │   └── clipboard.min.js
│   │       ├── quarto-html
│   │       │   ├── anchor.min.js
│   │       │   ├── popper.min.js
│   │       │   ├── quarto-syntax-highlighting.css
│   │       │   ├── quarto.js
│   │       │   ├── tippy.css
│   │       │   └── tippy.umd.min.js
│   │       └── tabwid-1.1.3
│   │           ├── tabwid.css
│   │           └── tabwid.js
│   ├── homework-starter-doc_TEMPLATE.html
│   ├── homework-starter-doc_TEMPLATE.qmd
│   ├── homework-starter-doc_TEMPLATE_files
│   │   ├── figure-html
│   │   │   ├── unnamed-chunk-10-1.png
│   │   │   ├── unnamed-chunk-10-2.png
│   │   │   ├── unna├── fink-upstream
│   ├── 10.9-libcxx
│   │   ├── base-files.info
│   │   ├── bzip2.info
│   │   ├── bzip2.patch
│   │   ├── class-inspector-pm.info
│   │   ├── cvs-snprintf.patch
│   │   ├── cvs.info
│   │   ├── cvs.patch
│   │   ├── debianutils.info
│   │   ├── dpkg-base-files.info
│   │   ├── dpkg-bootstrap.info
│   │   ├── dpkg.info
│   │   ├── dpkg.patch
│   │   ├── expat1.info
│   │   ├── file-sharedir-pm.info
│   │   ├── fink-mirrors.info
│   │   ├── gettext-tools-tests.patch
│   │   ├── gettext-tools.info
│   │   ├── gperf.info
│   E.html
│   ├── Usage.md
│   ├── VERSION
│   ├── bootstrap
│   ├── bootstrap-phase2.pl
│   ├── compiler_wrapper-10.6.in
│   ├── compiler_wrapper-10.7.in
│   ├── compiler_wrapper-10.9.in
│   ├── dpkg-checkall.sh
│   ├── fink-dpkg-status-cleanup.in
│   ├── fink-instscripts.in
│   ├── fink-scanpackages.in
│   ├── fink-virtual-pkgs.in
│   ├── fink.8.in
│   ├── fink.conf.5.in
│   ├── fink.csh
│   ├── fink.in
│   ├── fink.info.in
│   ├── fink.sh
│   ├── fink.shlibs
│   ├── g++-wrapper.in
│   ├── images
│   │   ├── finkDoneFailed.png
│   │   ├──│   ├── perlmod
│   │   ├── Fink
│   │   │   ├── Base.pm
│   │   │   ├── Bootstrap.pm
│   │   │   ├── CLI.pm
│   │   │   ├── Checksum
│   │   │   │   ├── MD5.pm
│   │   │   │   ├── SHA1.pm
│   │   │   │   └── SHA256.pm
│   │   │   ├── Checksum.pm
│   │   │   ├── Command.pm
│   │   │   ├── Config.pm
│   │   │   ├── Configure.pm
│   │   │   ├── Engine.pm
│   │   │   ├── Finally
│   │   │   │   ├── BuildConflicts.pm
│   │   │   │   └── Buildlock.pm
│   │   │   ├── Finally.pm
│   │   │   ├── FinkVersion.pm.in
│   │   │   ├── Mirror.pm
│   │   │   ├── NetAccess.pm
│   │   │   ├── Notify
│   │   │   │   ├── Growl.pm
│   │   │   │   ├── QuickSilver.pm
│   │   │   │   ├── Say.pm
│   │   │   │   ├── Syslog.pm
│   │   │   │   └── XTerm.pm
│   │   │   ├── Notify.pm
│   │   │   ├── Package.pm
│   │   │   ├── PkgVersion.pm
│   │   │   ├── Scanpackages.pm
│   │   ├── CLI
│   │   │   └── capture.t
│   │   ├── Command
│   │   │   ├── cat.t
│   │   │   ├── chowname.t
│   │   │   ├── commands.t
│   │   │   ├── du_sk.t
│   │   │   ├── exports.t
│   │   │   ├── failure.t
│   │   │   └── touch.t
│   │   ├── Config
│   │   │   ├── exports.t
│   │   │   ├── failure.t
│   │   │   ├── flag.t
│   │   │   ├── load_save.t
│   │   │   ├── options.t
│   │   │   ├── param.t
│   │   │   └── verbosity_level.t
│   │   ├── Engine
│   │   │   ├── fetch.t
│   │   │   ├── p0.info
│   │   │   ├── p1.info
│   │   │   ├── p2.info
│   │   │   ├── p3.info
│   │   │   └── p4.info
│   │   ├── Finally
│   │   │   ├── buildlocks.t
│   │   │   └── finally.t
│   │   ├── FinkVersion
│   │   │   ├── exports.t
│   │   │   └── version.t
│   │   ├── Mirror
│   │   │   └── exports.t
│   │   ├── Notify
│   │   │   └── exports.t
│   │   ├── Package
│   │   │   ├── duplicate_fullname_trees
│   │   │   │   ├── epoch1
│   │   │   │   │   └── finkinfo
│   │   │   │   │       └── duplicate-fullname.info
│   │   │   │   ├── epoch1again
│   │   │   │   │   └── finkinfo
│   │   │   │   │       └── duplicate-fullname.info
│   │   │   │   └── epoch2
│   │   │   │       └── finkinfo
│   │   │   │           └── duplicate-fullname.info
│   │   │   └── duplicate_fullnames.t
│   │   ├── PkgVersion
│   │   │   ├── get_perl.t
│   │   │   ├── get_ruby.t
│   │   ├── Tie
│   │   │   └── IxHash
│   │   │       ├── each-delete.t
│   │   │       └── ixhash.t
│   │   ├── Validation
│   │   │   ├── _filename_versioning_cmp.t
│   │   │   └── exports.t
│   │   ├── basepath
│   │   │   └── etc
│   │   │       └── fink.conf
│   │   └── testmore.pl
│   ├── update
│   │   ├── Makefile.in.in
│   │   ├── config.guess
│   │   ├── config.sub
│   │   ├── ltconfig
│   │   └── ltmain.sh
│   └── update-packages
│       └── README
└── model_dt.csv```

# Rendered output

The rendered .html for this repo is [here](https://an-bui.github.io/ENVS193DS_workshop-08/code/homework-starter-doc_KEY.html).

