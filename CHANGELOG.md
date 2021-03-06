# Version 4.2.2 (2020-02-01)

This is a bug fix release.

We closed a total of 32 issues (enhancements and bug fixes) through 12 pull requests, since our last release on 2020-01-04.

## Issues Closed
  - test_map breakage due to pandas 1.0 deprecation of ufunc.outer (#236)
  - BUG:  ufunc.outer deprecated (#237)
  - raise warning when islands are used in to_adjlist (#230)
  - Some example datasets are missing documentation (#113)
  - DOC: Cleaning up docs and docsr for tutorial (#229)
  - `to_adjlist(remove_symmetric=True)` fails on string-indexed weights.  (#165)
  - AttributeError: 'Queen' object has no attribute 'silent_island_warning' (#204)
  - 4.2.1 (#226)
  - Revert "4.2.1" (#228)
  - 4.2.1 (#227)
  - DOC: images for notebooks (#225)
  - 4.2.1 (#224)
  - 4.2.1 (#223)
  - duplicate pypi package badge (#221)
  - 4.2.1 (#222)
  - REL: 4.2.1 (#220)
  - libpysal 4.2.0 won't import on Windows (#214)
  - libpysal 4.2.0 Windows import issue (#215)
  - Constructing contiguity spatial weights using from_dataframe and from_shapefile could give different results (#212)
  - fix bug 212 (#213)

## Pull Requests
  - BUG:  ufunc.outer deprecated (#237)
  - raise warning when islands are used in to_adjlist (#230)
  - DOC: Cleaning up docs and docsr for tutorial (#229)
  - Revert "4.2.1" (#228)
  - 4.2.1 (#227)
  - DOC: images for notebooks (#225)
  - 4.2.1 (#224)
  - 4.2.1 (#223)
  - 4.2.1 (#222)
  - REL: 4.2.1 (#220)
  - libpysal 4.2.0 Windows import issue (#215)
  - fix bug 212 (#213)

The following individuals contributed to this release:

  - Serge Rey
  - Levi John Wolf

# Version 4.2.1 (2020-01-04)

This is a bug fix release.

We closed a total of 14 issues (enhancements and bug fixes) through 5 pull requests, since our last release on 2019-12-14.

## Issues Closed
  - libpysal 4.2.0 won't import on Windows (#214)
  - libpysal 4.2.0 Windows import issue (#215)
  - Constructing contiguity spatial weights using from_dataframe and from_shapefile could give different results (#212)
  - fix bug 212 (#213)
  - alpha_shapes docs not rendering (#216)
  - corrected docstrings in cg.alpha_shapes.py (#217)
  - Updating requirements (#211)
  - Big tarball (#174)
  - Fetch (#176)

## Pull Requests
  - libpysal 4.2.0 Windows import issue (#215)
  - fix bug 212 (#213)
  - corrected docstrings in cg.alpha_shapes.py (#217)
  - Updating requirements (#211)
  - Fetch (#176)

The following individuals contributed to this release:

  - Serge Rey
  - James Gaboardi
  - Levi John Wolf

# Version 4.2.0 (2019-12-14)

We closed a total of 57 issues (enhancements and bug fixes) through 21 pull requests, since our last release on 2019-09-01.

## Issues Closed
  - Updating requirements (#211)
  - Big tarball (#174)
  - Fetch (#176)
  - metadata for examples  (#125)
  - DOC: math rendering in sphinx, and members included for W (#209)
  - (docs) automatically generate docstrings for class members (#210)
  - (docs) keep file .nojekyll in docs when syncing between docs/ and docsrc/_build/html/ (#207)
  - (bug) replace silent_island_warning with silence_warnings for weights (#206)
  - Documentation does not work (#205)
  - updating cg.standalone.distance_matrix docs (#203)
  - error message in cg.standalone.distance_matrix() (#195)
  - improved docs in io.util.shapefile (#202)
  - [ENH] moving jit import to common.py / improve documentation (#201)
  - rearrange shapely import in cg.alpha_shapes (#199)
  - fix quasi-redundant import of shapely (#200)
  - Remove more relics (from pre-reorg PySAL) (#196)
  - [BUG] alpha_shapes/shapely import error (#197)
  - [BUG] correcting shapely import bug (#198)
  - README.txt refers to pre-reorg PySAL (#194)
  - remove `distribute_setup.py`? (#147)
  - requires() decorator for libpysal.cg.alpha_shapes (#128)
  - decorating functions with requires() (#129)
  - [WIP] removing unused relics (#193)
  - necessity of libpysal.common.iteritems()? (#191)
  - removing iteritems decorator (#192)
  - Voronoi results in weights of different shape than input points (#189)
  - BUG: alpha_shape_auto can fail to contain all points in the set. (#190)
  - WSP(sparse).to_W() has `array`s in weights,neighbors dictionaries, rather than lists.  (#185)
  - Cast arrays as lists (Issue 185)  (#186)
  - BUG: Update for geopandas use of GeometryArray (#188)
  - Updated documentation error (link incorrectly specified) in README.rst  (#187)
  - Docs: badges for pypi (#182)
  - development guidelines link failure (#178)
  - DOCS: moving off rtd (#181)
  - REL 4.1.1 bf release (#180)
  - BUG: Updating manifest for additional requirements files (#179)

## Pull Requests
  - Updating requirements (#211)
  - Fetch (#176)
  - (docs) automatically generate docstrings for class members (#210)
  - (docs) keep file .nojekyll in docs when syncing between docs/ and docsrc/_build/html/ (#207)
  - (bug) replace silent_island_warning with silence_warnings for weights (#206)
  - updating cg.standalone.distance_matrix docs (#203)
  - improved docs in io.util.shapefile (#202)
  - [ENH] moving jit import to common.py / improve documentation (#201)
  - fix quasi-redundant import of shapely (#200)
  - Remove more relics (from pre-reorg PySAL) (#196)
  - decorating functions with requires() (#129)
  - [WIP] removing unused relics (#193)
  - removing iteritems decorator (#192)
  - BUG: alpha_shape_auto can fail to contain all points in the set. (#190)
  - Cast arrays as lists (Issue 185)  (#186)
  - BUG: Update for geopandas use of GeometryArray (#188)
  - Updated documentation error (link incorrectly specified) in README.rst  (#187)
  - Docs: badges for pypi (#182)
  - DOCS: moving off rtd (#181)
  - REL 4.1.1 bf release (#180)
  - BUG: Updating manifest for additional requirements files (#179)

The following individuals contributed to this release:

  - Serge Rey
  - Wei Kang
  - James Gaboardi
  - Levi John Wolf
  - Siddharths8212376
  
#  Version 4.1.1 (2019-09-01)

This is a bug fix release.

We closed a total of 32 issues (enhancements and bug fixes) through 13 pull requests, since our last release on 2019-07-01.

## Issues Closed
  - BUG: Updating manifest for additional requirements files (#179)
  - libpysal 4.1.0 is not released on pypi or conda-forge (#169)
  - addressing DeprecationWarning: fromstring() (#131)
  - ENH: fromstring has been deprecated (#175)
  - addressing DeprecationWarning: fromstring() (#132)
  - Ci (#172)
  - minor change to W's silence_warnings workflow (#171)
  - Automatically voronoi input point dataframes to Queen/Rook (#135)
  - (docs, bug) silence warning for disconnected components and islands (#170)
  - BUG: add zstd as a dependency to work around conda glitch (#168)
  - unable to updata libpysal in Anaconda (#133)
  - Modernize the travis builds (#167)
  - make id_order propagate through symmetrize(inplace=False) (#137)
  - W.symmetrize(inplace=False) resets id order (#136)
  - swap to masking instead of querying in adjlist (#166)
  - REL: 4.1.0 changelog (#160)
  - removing alumni devs from travis notifications  (#161) (#162)
  - remove alumni from travis (#161)
  - update setup.py to accommodate the transition to python3.6 and 3.7 (#163)

## Pull Requests
  - BUG: Updating manifest for additional requirements files (#179)
  - addressing DeprecationWarning: fromstring() (#132)
  - Ci (#172)
  - minor change to W's silence_warnings workflow (#171)
  - Automatically voronoi input point dataframes to Queen/Rook (#135)
  - (docs, bug) silence warning for disconnected components and islands (#170)
  - BUG: add zstd as a dependency to work around conda glitch (#168)
  - Modernize the travis builds (#167)
  - make id_order propagate through symmetrize(inplace=False) (#137)
  - swap to masking instead of querying in adjlist (#166)
  - REL: 4.1.0 changelog (#160)
  - removing alumni devs from travis notifications  (#161) (#162)
  - update setup.py to accommodate the transition to python3.6 and 3.7 (#163)

The following individuals contributed to this release:

  - Serge Rey
  - James Gaboardi
  - Wei Kang
  - Levi John Wolf

# Version 4.1.0 (2019-07-01)

We closed a total of 45 issues (enhancements and bug fixes) through 15 pull requests, since our last release on 2018-10-27.

## Issues Closed
  - Allow for **kwargs any time there's a weights construction (#158)
  - Some functions do not support silence_warnings=True (#134)
  - REL: update changelog (#159)
  - MAINT: bumping version for a release (#157)
  - update interactive examples in inline docstrings (#122)
  - BUG: fix for scipy bump #154 (#156)
  - Revert "bump supported Python versions and correct lat2SW doctest" (#155)
  - bump supported Python versions and correct lat2SW doctest (#154)
  - WIP debugging travis failure (#141)
  - replace deprecated "fromstring" with "frombytes" (#152)
  - doctests on weights are failing across the board (#48)
  - Use Unix line-endings for all files. (#149)
  - Remove unnecessary executable bits. (#148)
  - `import pysal` in libpysal/io/iohandlers/dat.py (#144)
  - enforce strict channel in .travis.yml (#143)
  - continued failing doctests in libpysal.io (#145)
  - sphinxcontrib-napoleon is no longer necessary (#146)
  - pysal --> libpysal docs conv & modernizing .travis.yml (#142)
  - fix README for pypi (#7)
  - build_lattice_shapefile swapped arguments (#138)
  - Accidental create of branch (#124)
  - Travis errors on Python3.6 PYTHON_PLUS=True (#127)
  - [WIP] solution for Travis CI failures (#140)
  - Conda travis (#139)
  - alphashapes & n<4 (#111)
  - [WIP] ensure safe returns for small n alphashapes (#115)
  - swapping ncols <-> nrows in the build_lattice_shapefile function (#130)
  - docstring for min_threshold_dist_from_shapefile is wrong (#120)
  - doc: requirements (#119)
  - REL: version bump for v4.0.1 (#118)

## Pull Requests
  - Allow for **kwargs any time there's a weights construction (#158)
  - REL: update changelog (#159)
  - MAINT: bumping version for a release (#157)
  - update interactive examples in inline docstrings (#122)
  - BUG: fix for scipy bump #154 (#156)
  - bump supported Python versions and correct lat2SW doctest (#154)
  - Use Unix line-endings for all files. (#149)
  - Remove unnecessary executable bits. (#148)
  - pysal --> libpysal docs conv & modernizing .travis.yml (#142)
  - [WIP] solution for Travis CI failures (#140)
  - [WIP] ensure safe returns for small n alphashapes (#115)
  - swapping ncols <-> nrows in the build_lattice_shapefile function (#130)
  - docstring for min_threshold_dist_from_shapefile is wrong (#120)
  - doc: requirements (#119)
  - REL: version bump for v4.0.1 (#118)

The following individuals contributed to this release:

  - Serge Rey
  - Wei Kang
  - Martin Fleischmann
  - James Gaboardi
  - Elliott Sales De Andrade
  - Levi John Wolf
  - Renanxcortes

# Version 4.0.1 (2018-10-27)

We closed a total of 21 issues (enhancements and bug fixes) through 8 pull requests, since our last release on 2018-08-22.

## Issues Closed
  - weights.distance.KNN.from_dataframe ignoring radius  (#116)
  - Always make spherical KDTrees if radius is passed (#117)
  - [ENH] should `weights.util.get_ids()` also accept a geodataframe? (#97)
  - enh: add doctests to travis (#2) (#112)
  - sphinx docs need updating (#49)
  - Add notebooks for subpackage contract (#108)
  - Api docs complete (#110)
  - Doctests and start of documentation for libpysal (#109)
  - Add dependencies to requirements_plus.txt for test_db (#107)
  - Weights/util/get ids gdf (#101)
  - missing adjustments to lower case module names (#106)
  - Rel.4.0.0 (#105)
  - REL: 3.0.8 (#104)

## Pull Requests
  - Always make spherical KDTrees if radius is passed (#117)
  - enh: add doctests to travis (#2) (#112)
  - Api docs complete (#110)
  - Doctests and start of documentation for libpysal (#109)
  - Add dependencies to requirements_plus.txt for test_db (#107)
  - Weights/util/get ids gdf (#101)
  - missing adjustments to lower case module names (#106)

The following individuals contributed to this release:

  - Serge Rey
  - Levi John Wolf
  - Wei Kang


# Version 4.0.0 (2018-08-22)

We closed a total of 52 issues (enhancements and bug fixes) through 18 pull requests, since our last release on 2018-07-15.

## Issues Closed
  - REL: 3.0.8 (#104)
  - error importing v3.0.7 (#100)
  - Lower case module names (#98)
  - remove function regime_weights (#96)
  - depreciating regime_weights in the new release? (#94)
  - inconsistency in api? (#93)
  - Ensure consistency in `from .module import *` in components of libpysal (#95)
  - [WIP] cleanup (#88)
  - docstrings for attributes are defined in properties (#87)
  - docstrings in W class need editing (#64)
  - version name as __version__ (#92)
  - remove `del` statements and modify alphashape __all__ (#89)
  - libpysal/libpysal/cg/__init__.py not importing `rtree` (#90)
  - including rtree in imports (#91)
  - fix hardcoded swm test (#86)
  - BUG:  test_weights_IO.py is using pysal and hard-coded paths (#85)
  - check for spatial index if nonplanar neighbors (#84)
  - nonplanar_neighbors fails when sindex is not constructed.  (#63)
  - increment version number and add bugfixes, api changes (#79)
  - Spherebug (#82)
  - only warn once for islands/disconnected components (#83)
  - only warn on disconnected components if there are no islands (#81)
  - LEP: Stuff/use pysal/network stuff to provide queen weights on linestring dataframes (#59)
  - swm fix not ported forward from pysal.  (#66)
  - import scipy syntax typo in the new issue template (#68)
  - deletion of extra spaces in warning message (#78)
  - Nightli.es build permissions (#77)
  - name of geometry column is hardcoded in nonplanar_neighbors (#75)
  - changed geometry column name from a str to an attribute (#76)
  - Missing example file  (#71)
  - if numba isn't present, libpysal warns every time imported (#73)
  - add check for disconnected components (#65)
  - clean up for release (#74)
  - update for new examples (#72)

## Pull Requests
  - Lower case module names (#98)
  - remove function regime_weights (#96)
  - Ensure consistency in `from .module import *` in components of libpysal (#95)
  - [WIP] cleanup (#88)
  - docstrings for attributes are defined in properties (#87)
  - version name as __version__ (#92)
  - remove `del` statements and modify alphashape __all__ (#89)
  - including rtree in imports (#91)
  - fix hardcoded swm test (#86)
  - check for spatial index if nonplanar neighbors (#84)
  - increment version number and add bugfixes, api changes (#79)
  - Spherebug (#82)
  - only warn once for islands/disconnected components (#83)
  - deletion of extra spaces in warning message (#78)
  - changed geometry column name from a str to an attribute (#76)
  - add check for disconnected components (#65)
  - clean up for release (#74)
  - update for new examples (#72)

The following individuals contributed to this release:

  - Serge Rey
  - Levi John Wolf
  - Wei Kang
  - James Gaboardi
  - Eli Knaap


# v<1.13.0>, 2016-11-24

We closed a total of 38 issues, 7 pull requests and 31 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (7):

* :ghpull:`844`: Geotable plot
* :ghpull:`875`: Spint constant
* :ghpull:`874`: Use standard python facilites for warning
* :ghpull:`873`: updating release schedule
* :ghpull:`871`: Put requirements into setup.py so they are installed if missing
* :ghpull:`870`: Doc/release
* :ghpull:`869`: Dev

Issues (31):

* :ghissue:`844`: Geotable plot
* :ghissue:`877`: documentation links to numpy and scipy are broken
* :ghissue:`875`: Spint constant
* :ghissue:`874`: Use standard python facilites for warning
* :ghissue:`873`: updating release schedule
* :ghissue:`871`: Put requirements into setup.py so they are installed if missing
* :ghissue:`591`: check pysal version and report if a more recent stable version is available
* :ghissue:`410`: prototype LISA cluster map
* :ghissue:`333`: Add k functions
* :ghissue:`274`: Implement LISA in network module
* :ghissue:`746`: Network data structures
* :ghissue:`751`: A method to get a list of example-files by type
* :ghissue:`219`: inconsistent treatment of centroids in arc distance calculations in weights/user.py
* :ghissue:`173`: implement cross sectional and space-time scan statistics
* :ghissue:`170`: centralize all kernel based calculations
* :ghissue:`134`: Complete cg.locators
* :ghissue:`94`: Smoothing: add another module based on model-based smoothing
* :ghissue:`91`: Smoothing: Develop simulations for comparing different smoothers 
* :ghissue:`90`: Overhaul Polygon class
* :ghissue:`89`: Optimize shapefile reader 
* :ghissue:`88`: Optimize Clockwise test
* :ghissue:`86`: Spatial_Dynamics: LISA Time paths
* :ghissue:`85`: Spatial_Dynamics: modified knox statistic
* :ghissue:`84`: Spatial_Dynamics: Optimize Theta
* :ghissue:`652`: Use cKDtree for Arc_KDTree
* :ghissue:`697`: Update Release Management to Support Rolling Releases
* :ghissue:`761`: Object-oriented design for viz module
* :ghissue:`767`: ZeroDivisonError when calculating certain centroids
* :ghissue:`849`: dbf2df can not read dbf files within which there are Chinese characters
* :ghissue:`870`: Doc/release
* :ghissue:`869`: Dev

# v<1.12.0>, 2016-09-21

We closed a total of 100 issues, 33 pull requests and 67 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (33):

* :ghpull:`864`: addressing issue #845 and adding tests
* :ghpull:`862`: Memory efficient Gini and tests
* :ghpull:`865`: fix space/tab inconsistency
* :ghpull:`861`: GSOC -SpInt
* :ghpull:`847`: spatial interaction weights 
* :ghpull:`863`: B859
* :ghpull:`860`: Incoprate updates to db driver and unittests
* :ghpull:`858`: Dev mltest
* :ghpull:`857`: Fix TabErrors, replace tabs with spaces
* :ghpull:`856`: Make the output and build reproducible
* :ghpull:`851`: fixed typo in test_network.py
* :ghpull:`850`: [REBASE] Distance band speed ups
* :ghpull:`843`: update and clean aesthetic of Network_Usage.ipynb
* :ghpull:`842`: typo correction in network.py
* :ghpull:`841`: [REBASE & REDIRECT] Conditional Database Imports & Docos, #692
* :ghpull:`840`: minor bugfix to #816
* :ghpull:`839`: documentation cleanup on network.analysis.py
* :ghpull:`838`: network.util.py documentation cleanup 
* :ghpull:`836`: re: network.py documentation cleanup
* :ghpull:`768`: Modified the way area of a ring is calculated to allow for more precision
* :ghpull:`829`: numba autojit _fisher_jenks_means if numba is available
* :ghpull:`832`: Handling a deprecation warning, and latex errors corrected.
* :ghpull:`834`: Travis testing matrix
* :ghpull:`831`: Refactoring Markov classes for efficiency
* :ghpull:`827`: ESDA Tabular Functions
* :ghpull:`823`: typo and format of docstring of user.py in weights module
* :ghpull:`821`: Pdio
* :ghpull:`817`: D/sur
* :ghpull:`818`: Documentation fix + some PEP8 standardization
* :ghpull:`811`: DistanceBand should correctly handle named weights
* :ghpull:`808`: Dev
* :ghpull:`807`: Updating contrib docs and bumping version for dev
* :ghpull:`797`: working moran plot func

Issues (67):

* :ghissue:`855`: Inefficient Gini Coefficient calculation?
* :ghissue:`864`: addressing issue #845 and adding tests
* :ghissue:`862`: Memory efficient Gini and tests
* :ghissue:`865`: fix space/tab inconsistency
* :ghissue:`861`: GSOC -SpInt
* :ghissue:`847`: spatial interaction weights 
* :ghissue:`859`: Wrong there is one disconnected observation (no neighbors)
* :ghissue:`863`: B859
* :ghissue:`860`: Incoprate updates to db driver and unittests
* :ghissue:`858`: Dev mltest
* :ghissue:`857`: Fix TabErrors, replace tabs with spaces
* :ghissue:`854`: handle verication context for githubstats
* :ghissue:`856`: Make the output and build reproducible
* :ghissue:`851`: fixed typo in test_network.py
* :ghissue:`850`: [REBASE] Distance band speed ups
* :ghissue:`846`: DistanceBand speed ups
* :ghissue:`843`: update and clean aesthetic of Network_Usage.ipynb
* :ghissue:`842`: typo correction in network.py
* :ghissue:`692`: Conditional Database Import / Docos
* :ghissue:`841`: [REBASE & REDIRECT] Conditional Database Imports & Docos, #692
* :ghissue:`769`: Windows 7, 64 bit installation issue with visual C++ for python
* :ghissue:`816`: Exception TypeError in geoda_txt.py
* :ghissue:`840`: minor bugfix to #816
* :ghissue:`839`: documentation cleanup on network.analysis.py
* :ghissue:`397`: integrate optimized contiguity builder
* :ghissue:`531`: add user space function to generate numpy arrays
* :ghissue:`654`: meta update for 2-3 conversion
* :ghissue:`676`: Meta not importable from pysal
* :ghissue:`838`: network.util.py documentation cleanup 
* :ghissue:`753`: Fix the network ring bug
* :ghissue:`836`: re: network.py documentation cleanup
* :ghissue:`768`: Modified the way area of a ring is calculated to allow for more precision
* :ghissue:`837`: re: network.allneighbordistances() diagonal fill
* :ghissue:`822`: two issues about function choropleth_map in viz module
* :ghissue:`835`: fix deprecation warnings noted in #822
* :ghissue:`829`: numba autojit _fisher_jenks_means if numba is available
* :ghissue:`832`: Handling a deprecation warning, and latex errors corrected.
* :ghissue:`834`: Travis testing matrix
* :ghissue:`825`: Headbanging Median Rate ignores edge correction
* :ghissue:`826`: Spatial Filtering grid definition
* :ghissue:`824`: Direct Age Standardization fails for empty regions
* :ghissue:`833`: PySAL+ optional testing matrix
* :ghissue:`830`: [REBASED] PySAL+ optional testing matrix
* :ghissue:`831`: Refactoring Markov classes for efficiency
* :ghissue:`827`: ESDA Tabular Functions
* :ghissue:`815`: rook case not working in ContiguityWeightsPolygons
* :ghissue:`828`: Fisher_Jenks pure python implementation is too slow
* :ghissue:`814`: Explore Classmethods for alternative constructors
* :ghissue:`795`: switch to scipy.linalg instead of numpy.linalg
* :ghissue:`799`: w_subset(weights:W, ids:np.ndarray) constructs faulty weights object
* :ghissue:`823`: typo and format of docstring of user.py in weights module
* :ghissue:`821`: Pdio
* :ghissue:`794`: spreg ML_lag doesn't always set W in __init__
* :ghissue:`754`: Update README
* :ghissue:`819`: add LIMAs
* :ghissue:`817`: D/sur
* :ghissue:`818`: Documentation fix + some PEP8 standardization
* :ghissue:`809`: Fixed documentation
* :ghissue:`813`: w.remap_ids(ids) never sets w.id_order_set
* :ghissue:`775`: Added a prototype for constructing weights from a list of shapely Polygons
* :ghissue:`810`: DistanceBand fails to accept custom ids
* :ghissue:`811`: DistanceBand should correctly handle named weights
* :ghissue:`780`: Doctests failing on travis
* :ghissue:`801`: ImportError: No module named scipy.spatial
* :ghissue:`808`: Dev
* :ghissue:`807`: Updating contrib docs and bumping version for dev
* :ghissue:`797`: working moran plot func

# v<1.11.2>, 2016-05-18

We closed a total of 20 issues, 6 pull requests and 14 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (6):

* :ghpull:`805`: pre Rel1.11.2 and #840
* :ghpull:`802`: fixed issues with model handler failing to correctly discover models
* :ghpull:`798`: fix for css problem on rtd #790
* :ghpull:`793`: Getting weights doctests to pass
* :ghpull:`791`: Doc/rolling
* :ghpull:`792`: Local Moran was using the incorrect moments in z_sim and p_z_sim

Issues (14):

* :ghissue:`805`: pre Rel1.11.2 and #840
* :ghissue:`803`: check_contiguity error.. 
* :ghissue:`802`: fixed issues with model handler failing to correctly discover models
* :ghissue:`800`: `ps.threshold_continuousW_from_shapefile` returning inf along diagonal
* :ghissue:`771`: KDtree type mismatch in knnW
* :ghissue:`798`: fix for css problem on rtd #790
* :ghissue:`796`: working moran plot func
* :ghissue:`787`: Update docs to reflect Python-3 compatibility
* :ghissue:`587`: ML Lag indexing error on optimization result
* :ghissue:`793`: Getting weights doctests to pass
* :ghissue:`791`: Doc/rolling
* :ghissue:`792`: Local Moran was using the incorrect moments in z_sim and p_z_sim
* :ghissue:`674`: Have PySAL included on OSGeo Live 9 
* :ghissue:`779`: DistanceBand include the point itself as neighbor


# v<1.11.1>, 2016-04-01

We closed a total of 62 issues, 20 pull requests and 42 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (20):

* :ghpull:`777`: fix minor issues with using stdlib warnings in mapclassify.py
* :ghpull:`766`: Constant check
* :ghpull:`781`: Dev
* :ghpull:`778`: Wkb
* :ghpull:`776`: Updating & find-bin-as-call for Map_Classifiers
* :ghpull:`770`: adding github chrome to make project contributions easier to handle
* :ghpull:`764`: add folium changes needed for notebook to run
* :ghpull:`760`: Update docs for #697
* :ghpull:`763`: docs fix: incorrect array dimensions listed for spatial interaction SpaceTimeEvents
* :ghpull:`756`: B726
* :ghpull:`749`: remove cruft in git root and add gitter badge to the readme
* :ghpull:`748`: Replace deprecated np.rank with np.ndim
* :ghpull:`745`: Lag Categorical & Find Bins
* :ghpull:`741`: fix for #740
* :ghpull:`739`: Dev
* :ghpull:`738`: fixing master version
* :ghpull:`737`: Bumping dev
* :ghpull:`736`: Merge pull request #734 from sjsrey/master
* :ghpull:`735`: Dev in sync with master for 1.11
* :ghpull:`734`: Release 1.11

Issues (42):

* :ghissue:`773`: add isKDTree typecomparison to handle divergent cKDTree and KDTree types
* :ghissue:`777`: fix minor issues with using stdlib warnings in mapclassify.py
* :ghissue:`766`: Constant check
* :ghissue:`782`: Contrib docs
* :ghissue:`781`: Dev
* :ghissue:`762`: viz: folium_mapping.ipynb AttributeError: 'Map' object has no attribute '_build_map'
* :ghissue:`778`: Wkb
* :ghissue:`776`: Updating & find-bin-as-call for Map_Classifiers
* :ghissue:`770`: adding github chrome to make project contributions easier to handle
* :ghissue:`774`: Added a prototype for constructing weights from a list of shapely Polygons
* :ghissue:`772`: knnW user guide doc error
* :ghissue:`765`: potential constant_check bug
* :ghissue:`759`: Fixed code in ipython notebooks
* :ghissue:`752`: [WIP] Add J function to network submodule
* :ghissue:`764`: add folium changes needed for notebook to run
* :ghissue:`760`: Update docs for #697
* :ghissue:`763`: docs fix: incorrect array dimensions listed for spatial interaction SpaceTimeEvents
* :ghissue:`750`: Add gitter badge to README on master branch
* :ghissue:`758`: Fixed code in ipython notebooks
* :ghissue:`755`: add speedup of conditional randomization
* :ghissue:`726`: Compatibility for Scipy 16.1
* :ghissue:`756`: B726
* :ghissue:`749`: remove cruft in git root and add gitter badge to the readme
* :ghissue:`587`: ML Lag
* :ghissue:`748`: Replace deprecated np.rank with np.ndim
* :ghissue:`747`: Replace deprecated np.rank with np.ndim
* :ghissue:`653`: network is returning NAN's on diagonal of distance matrix
* :ghissue:`660`: insert zeros on symmetric matrix diagonal
* :ghissue:`745`: Lag Categorical & Find Bins
* :ghissue:`744`: [REBASED] Update moran.py with much faster iterations
* :ghissue:`732`: Update moran.py with much faster iterations
* :ghissue:`743`: [REBASED]: Update moran.py with much faster iterations
* :ghissue:`742`: Links not working
* :ghissue:`740`: Moran_Local's EI is returned as an array instead of a float
* :ghissue:`741`: fix for #740
* :ghissue:`739`: Dev
* :ghissue:`738`: fixing master version
* :ghissue:`737`: Bumping dev
* :ghissue:`151`: Port pysal to python3
* :ghissue:`736`: Merge pull request #734 from sjsrey/master
* :ghissue:`735`: Dev in sync with master for 1.11
* :ghissue:`734`: Release 1.11

# v<1.11.0>, 2016-01-27

GitHub stats for 2015/07/29 - 2016/01/27

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 13 authors contributed 216 commits.

* Dani Arribas-Bel
* David Folch
* Levi John Wolf
* Levi Wolf
* Philip Stephens
* Serge Rey
* Sergio Rey
* Wei Kang
* jlaura
* levi.john.wolf@gmail.com
* ljw
* ljwolf
* pedrovma


We closed a total of 86 issues, 33 pull requests and 53 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (33):

* :ghpull:`724`: add synchronization tool
* :ghpull:`733`: Fb/bump
* :ghpull:`731`: Small docfixes
* :ghpull:`730`: Contrib docs
* :ghpull:`728`: B179
* :ghpull:`727`: Geodf io
* :ghpull:`725`: try pinning scipy,numpy
* :ghpull:`723`: make sure to test all moran classes
* :ghpull:`720`: Moving natural breaks to a cleaner kmeans implementation
* :ghpull:`718`: force counts to be same length as bins
* :ghpull:`714`: Dev
* :ghpull:`715`: Heads
* :ghpull:`713`: Enh712
* :ghpull:`710`: Patsy/Pandas wrapper
* :ghpull:`711`: Travis fixes
* :ghpull:`706`: precommit hook
* :ghpull:`707`: Keep dev updated with any bugfixes into master
* :ghpull:`702`: fix for chi2 test 0 denominator and invocation of chi2 test in LISA_Markov
* :ghpull:`704`: Allcloser
* :ghpull:`703`: Swapping to Allclose and RTOL=.00005 in spreg
* :ghpull:`701`: By col array
* :ghpull:`700`: small optimization of bivariate moran motivated by #695
* :ghpull:`696`: Pypi
* :ghpull:`691`: Update doctest for one-off bug that was fixed with #690
* :ghpull:`690`: fix for lisa markov one off for significance indicator
* :ghpull:`689`: Clpy flex w
* :ghpull:`688`: pep 8 edits
* :ghpull:`687`: Change array assertions into allclose
* :ghpull:`686`: Moran local bivariate
* :ghpull:`684`: 591
* :ghpull:`682`: release instructions updated
* :ghpull:`681`: version bump for next dev cycle
* :ghpull:`680`: Rel1.10

Issues (53):

* :ghissue:`705`: spreg check valve
* :ghissue:`344`: Explore new dependency on ogr
* :ghissue:`459`: Problem with bandwidth
* :ghissue:`552`: Viz organization
* :ghissue:`491`: Test np.allclose() for unit tests
* :ghissue:`529`: Clarity needed on proper reference formatting in sphinx docs
* :ghissue:`699`: Trouble importing pysal - ImportError: DLL load failed
* :ghissue:`716`: `min_threshold_dist_from_shapefile` creating an island in some cases
* :ghissue:`724`: add synchronization tool
* :ghissue:`733`: Fb/bump
* :ghissue:`731`: Small docfixes
* :ghissue:`730`: Contrib docs
* :ghissue:`719`: pysal not working with matplotlib v1.5 for plot_lisa_cluster, plot_choropleth, etc.
* :ghissue:`728`: B179
* :ghissue:`727`: Geodf io
* :ghissue:`725`: try pinning scipy,numpy
* :ghissue:`723`: make sure to test all moran classes
* :ghissue:`720`: Moving natural breaks to a cleaner kmeans implementation
* :ghissue:`717`: esda.mapclassify return problematic counts when there is 0 occurrence in the last class
* :ghissue:`718`: force counts to be same length as bins
* :ghissue:`714`: Dev
* :ghissue:`712`: `block_weights` does not take argument `idVariable`
* :ghissue:`715`: Heads
* :ghissue:`713`: Enh712
* :ghissue:`710`: Patsy/Pandas wrapper
* :ghissue:`711`: Travis fixes
* :ghissue:`706`: precommit hook
* :ghissue:`708`: 2-3: is six a dependency or do we ship it?
* :ghissue:`707`: Keep dev updated with any bugfixes into master
* :ghissue:`702`: fix for chi2 test 0 denominator and invocation of chi2 test in LISA_Markov
* :ghissue:`704`: Allcloser
* :ghissue:`703`: Swapping to Allclose and RTOL=.00005 in spreg
* :ghissue:`698`: Py3merge
* :ghissue:`701`: By col array
* :ghissue:`700`: small optimization of bivariate moran motivated by #695
* :ghissue:`695`: Bivariate global moran's I formula
* :ghissue:`683`: Py3 Conversion Project
* :ghissue:`694`: Allclose in SPREG
* :ghissue:`696`: Pypi
* :ghissue:`691`: Update doctest for one-off bug that was fixed with #690
* :ghissue:`693`: Trouble installation: No module named 'shapes'
* :ghissue:`690`: fix for lisa markov one off for significance indicator
* :ghissue:`689`: Clpy flex w
* :ghissue:`688`: pep 8 edits
* :ghissue:`685`: BV Lisa 
* :ghissue:`687`: Change array assertions into allclose
* :ghissue:`686`: Moran local bivariate
* :ghissue:`677`: Make meta importable from base
* :ghissue:`684`: 591
* :ghissue:`682`: release instructions updated
* :ghissue:`679`: pysal.cg.sphere.fast_knn bug
* :ghissue:`681`: version bump for next dev cycle
* :ghissue:`680`: Rel1.10


# v<1.10.0>, 2015-07-29

GitHub stats for 2015/01/31 - 2015/07/29

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 20 authors contributed 334 commits.

* Charlie Schmidt
* Dani Arribas-Bel
* Daniel Arribas-Bel
* David C. Folch
* David Folch
* Jay
* Levi John Wolf
* Marynia
* Philip Stephens
* Serge Rey
* Sergio Rey
* Taylor Oshan
* The Gitter Badger
* Wei Kang
* jay
* jlaura
* ljw
* ljwolf
* luc
* pedrovma


We closed a total of 156 issues, 58 pull requests and 98 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (58):

* :ghpull:`675`: Update README.md
* :ghpull:`673`: Adding init at pdutilities so they are importable
* :ghpull:`672`: ENH: option to locate legend
* :ghpull:`669`: add nonsudo travis
* :ghpull:`666`: Cleaned up conflicts in ref branch
* :ghpull:`664`: Lisa map
* :ghpull:`663`: Examples
* :ghpull:`661`: Reorganization of examples 
* :ghpull:`657`: Assuncao test division errors
* :ghpull:`649`: Add a Gitter chat badge to README.md
* :ghpull:`647`: Addresses 646
* :ghpull:`645`: Update to weights module documentation for PySAL-REST
* :ghpull:`644`: removed test print statements from df2dbf
* :ghpull:`643`: using dtypes.name in df2dbf to avoid gotcha in type
* :ghpull:`642`: Updating copyright year
* :ghpull:`634`: allows non-symmetric distance matrices
* :ghpull:`641`: turning off generatetree
* :ghpull:`592`: adding check for version #591
* :ghpull:`636`: vertical line point simulation
* :ghpull:`639`: Snapping
* :ghpull:`640`: Add users to travis
* :ghpull:`627`: Networkrb
* :ghpull:`631`: Fixing typoes in analysis.py
* :ghpull:`626`: cast arrays over inconsistent kdtree return types
* :ghpull:`620`: adding explicit check for random region contiguity
* :ghpull:`619`: Fixing spreg's warnings
* :ghpull:`618`: initial folder with dbf utilities using pandas
* :ghpull:`616`: Adding isolation and theil indices to inequality._indices.py
* :ghpull:`615`: Network docs
* :ghpull:`614`: cleaning up pr testing
* :ghpull:`613`: test coverage to 98% on network
* :ghpull:`612`: small change for testing PR
* :ghpull:`611`: stubbed in minimal tests
* :ghpull:`607`: B603
* :ghpull:`602`: Documentation Extraction Notebook
* :ghpull:`606`: pct_nonzero was reporting a ratio not a percentage
* :ghpull:`604`: Contribpush
* :ghpull:`601`: Documentation Cleanup
* :ghpull:`599`: Casting bugfix from #598
* :ghpull:`600`: Updates for coveralls
* :ghpull:`598`: IO in Python 3
* :ghpull:`597`: Decoupling bbox from map_XXX_poly
* :ghpull:`595`: Removed testing line in travis.yml and added a .coveragerc file to manag...
* :ghpull:`590`: using numpy sum method
* :ghpull:`589`: Wconstructor
* :ghpull:`588`: Coveralls
* :ghpull:`585`: Fisher Jenks bug in `plot_choropleth`
* :ghpull:`584`: Alpha in plot chor
* :ghpull:`583`: Fixed 576
* :ghpull:`580`: working on #576
* :ghpull:`578`: Fixes #577
* :ghpull:`574`: Handle case where a region has a 0 share.
* :ghpull:`571`: Dict to unique value mapper
* :ghpull:`570`: numpy doc cleanup for weights module
* :ghpull:`569`: folium viz scripts
* :ghpull:`568`: inline with numpy doc spec (spatial_dynamics module)
* :ghpull:`567`: New/masterbump
* :ghpull:`566`: Fix for 1.9.0 missing file in setup.py

Issues (98):

* :ghissue:`675`: Update README.md
* :ghissue:`658`: Travis.CI """Legacy""" architecture
* :ghissue:`667`: Examples Not Found
* :ghissue:`673`: Adding init at pdutilities so they are importable
* :ghissue:`672`: ENH: option to locate legend
* :ghissue:`669`: add nonsudo travis
* :ghissue:`671`: Shapefile Read - PolygonM Attribute Error
* :ghissue:`670`: examples README markdown files reformatting
* :ghissue:`668`: Wconstructor
* :ghissue:`666`: Cleaned up conflicts in ref branch
* :ghissue:`664`: Lisa map
* :ghissue:`662`: Pep8
* :ghissue:`665`: Refs
* :ghissue:`663`: Examples
* :ghissue:`573`: Examples
* :ghissue:`661`: Reorganization of examples 
* :ghissue:`656`: Assuncao rate improper division
* :ghissue:`657`: Assuncao test division errors
* :ghissue:`280`: handle multi-segment links in net_shp_io.py
* :ghissue:`649`: Add a Gitter chat badge to README.md
* :ghissue:`647`: Addresses 646
* :ghissue:`646`: arc distance in knnW
* :ghissue:`645`: Update to weights module documentation for PySAL-REST
* :ghissue:`644`: removed test print statements from df2dbf
* :ghissue:`643`: using dtypes.name in df2dbf to avoid gotcha in type
* :ghissue:`603`: Polygon.contains_point does not correctly process multipart polygons.
* :ghissue:`642`: Updating copyright year
* :ghissue:`623`: reading road shapfiles into network
* :ghissue:`608`: Scipy Sparse Graph
* :ghissue:`621`: network distance speedup
* :ghissue:`632`: network point snapping
* :ghissue:`633`: point to point distances on network
* :ghissue:`635`: simulating points on vertical lines
* :ghissue:`634`: allows non-symmetric distance matrices
* :ghissue:`641`: turning off generatetree
* :ghissue:`637`: speedup distance computations
* :ghissue:`592`: adding check for version #591
* :ghissue:`628`: Re-enable doctests
* :ghissue:`636`: vertical line point simulation
* :ghissue:`639`: Snapping
* :ghissue:`640`: Add users to travis
* :ghissue:`638`: Add users to Travis
* :ghissue:`627`: Networkrb
* :ghissue:`622`: New network branch from clean master
* :ghissue:`630`: NetworkG api is broken
* :ghissue:`631`: Fixing typoes in analysis.py
* :ghissue:`625`: Installation - Binstar and Anaconda
* :ghissue:`624`: Network topology
* :ghissue:`629`: changes to spreg tests for travis
* :ghissue:`166`: pysal.esda.mapclassify.Fisher_Jenks  -   local variable 'best' referenced before assignment
* :ghissue:`626`: cast arrays over inconsistent kdtree return types
* :ghissue:`596`: [question] unsupervised classification
* :ghissue:`620`: adding explicit check for random region contiguity
* :ghissue:`617`: Random_Region not respecting contiguity constraint
* :ghissue:`619`: Fixing spreg's warnings
* :ghissue:`618`: initial folder with dbf utilities using pandas
* :ghissue:`616`: Adding isolation and theil indices to inequality._indices.py
* :ghissue:`615`: Network docs
* :ghissue:`614`: cleaning up pr testing
* :ghissue:`613`: test coverage to 98% on network
* :ghissue:`612`: small change for testing PR
* :ghissue:`611`: stubbed in minimal tests
* :ghissue:`607`: B603
* :ghissue:`602`: Documentation Extraction Notebook
* :ghissue:`606`: pct_nonzero was reporting a ratio not a percentage
* :ghissue:`605`: RTree Weights
* :ghissue:`604`: Contribpush
* :ghissue:`601`: Documentation Cleanup
* :ghissue:`554`: Beginning documentation cleanup
* :ghissue:`599`: Casting bugfix from #598
* :ghissue:`600`: Updates for coveralls
* :ghissue:`598`: IO in Python 3
* :ghissue:`597`: Decoupling bbox from map_XXX_poly
* :ghissue:`595`: Removed testing line in travis.yml and added a .coveragerc file to manag...
* :ghissue:`586`: Look at using Coveralls
* :ghissue:`590`: using numpy sum method
* :ghissue:`589`: Wconstructor
* :ghissue:`588`: Coveralls
* :ghissue:`576`: Predecessor lists inconsistencies
* :ghissue:`585`: Fisher Jenks bug in `plot_choropleth`
* :ghissue:`584`: Alpha in plot chor
* :ghissue:`583`: Fixed 576
* :ghissue:`582`: Fixes #576
* :ghissue:`581`: Network
* :ghissue:`580`: working on #576
* :ghissue:`575`: Network from Lattice
* :ghissue:`578`: Fixes #577
* :ghissue:`577`: bug in FileIO.cast
* :ghissue:`574`: Handle case where a region has a 0 share.
* :ghissue:`343`: Edge Segmentation
* :ghissue:`571`: Dict to unique value mapper
* :ghissue:`570`: numpy doc cleanup for weights module
* :ghissue:`569`: folium viz scripts
* :ghissue:`568`: inline with numpy doc spec (spatial_dynamics module)
* :ghissue:`567`: New/masterbump
* :ghissue:`564`: Bug in setup.py
* :ghissue:`566`: Fix for 1.9.0 missing file in setup.py
* :ghissue:`565`: Bsetup


# v<1.9.1>, 2015-01-31

GitHub stats for 2015/01/30 - 2015/01/31 

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 4 authors contributed 14 commits.

* Dani Arribas-Bel
* Serge Rey
* Sergio Rey
* jlaura


We closed a total of 8 issues, 3 pull requests and 5 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (3):

* :ghpull:`566`: Fix for 1.9.0 missing file in setup.py
* :ghpull:`563`: Updating release instructions
* :ghpull:`561`: Rolling over to 1.10

Issues (5):

* :ghissue:`566`: Fix for 1.9.0 missing file in setup.py
* :ghissue:`565`: Bsetup
* :ghissue:`563`: Updating release instructions
* :ghissue:`562`: adjustments to release management
* :ghissue:`561`: Rolling over to 1.10


# v<1.9.0>, 2015-01-30

GitHub stats for 2014/07/25 - 2015/01/30 

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 12 authors contributed 131 commits.

* Andy Reagan
* Dani Arribas-Bel
* Jay
* Levi John Wolf
* Philip Stephens
* Qunshan
* Serge Rey
* jlaura
* ljwolf
* luc


We closed a total of 113 issues, 44 pull requests and 69 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (44):

* :ghpull:`560`: modifying import scheme for network module
* :ghpull:`559`: Network2
* :ghpull:`558`: Network2
* :ghpull:`557`: Network2
* :ghpull:`556`: Added analytical functions and edge segmentation
* :ghpull:`550`: Network2
* :ghpull:`553`: correction in denominator of spatial tau. 
* :ghpull:`547`: Updates to get network integrated
* :ghpull:`544`: update .gitignore
* :ghpull:`543`: k nearest neighbor gwt example file for baltimore points (with k=4) added to examples directory
* :ghpull:`542`: new format nat_queen.gal file added to examples directory
* :ghpull:`541`: Update tutorial docs for new book
* :ghpull:`540`: doc: updating instructions for anaconda and enthought
* :ghpull:`539`: doc: pysal is now on sagemathcloud
* :ghpull:`538`: Clean up of cg and fixes of other doctests/formats
* :ghpull:`536`: adding entry for getis ord module
* :ghpull:`537`: new opendata module for contrib
* :ghpull:`535`: Add method for extracting data columns as Numpy array rather than list
* :ghpull:`534`: added geogrid to __all__ in sphere.py
* :ghpull:`533`: added geogrid function to create a grid of points on a sphere
* :ghpull:`532`: new functions to deal with spherical geometry: lat-lon conversion, degre...
* :ghpull:`530`: I390
* :ghpull:`528`: Replacing 0 by min value in choropleths
* :ghpull:`526`: B166
* :ghpull:`525`: copyright update
* :ghpull:`524`: New homogeneity tests for general case and spatial markov as a special case
* :ghpull:`523`: pointing to github.io pages
* :ghpull:`520`: Same typo. Toolkit.
* :ghpull:`518`: Update util.py
* :ghpull:`519`: Typo
* :ghpull:`517`: Documentation correction for Prais Conditional Mobility Index
* :ghpull:`516`: ENH for https://github.com/PySAL/PySAL.github.io/issues/17
* :ghpull:`515`: BUG: conditional check for extension of lower bound of colorbar to conta...
* :ghpull:`514`: ENH: adding the user_defined classification
* :ghpull:`513`: rewriting to not use ipython notebook --pylab=line
* :ghpull:`512`: Viz
* :ghpull:`508`: Adding barebones pysal2matplotlib options in viz
* :ghpull:`511`: DOC updating news
* :ghpull:`507`: Sched
* :ghpull:`510`: BUG: fix for #509
* :ghpull:`506`: 1.9dev
* :ghpull:`505`: REL bumping master to 1.9.0dev
* :ghpull:`504`: Release prep 1.8
* :ghpull:`503`: Grid for landing page

Issues (69):

* :ghissue:`560`: modifying import scheme for network module
* :ghissue:`559`: Network2
* :ghissue:`558`: Network2
* :ghissue:`557`: Network2
* :ghissue:`556`: Added analytical functions and edge segmentation
* :ghissue:`555`: Added edge segmentation by distance
* :ghissue:`550`: Network2
* :ghissue:`553`: correction in denominator of spatial tau. 
* :ghissue:`549`: Network2
* :ghissue:`547`: Updates to get network integrated
* :ghissue:`548`: Installation Issues
* :ghissue:`546`: Network2
* :ghissue:`545`: Network
* :ghissue:`544`: update .gitignore
* :ghissue:`543`: k nearest neighbor gwt example file for baltimore points (with k=4) added to examples directory
* :ghissue:`542`: new format nat_queen.gal file added to examples directory
* :ghissue:`541`: Update tutorial docs for new book
* :ghissue:`540`: doc: updating instructions for anaconda and enthought
* :ghissue:`539`: doc: pysal is now on sagemathcloud
* :ghissue:`538`: Clean up of cg and fixes of other doctests/formats
* :ghissue:`536`: adding entry for getis ord module
* :ghissue:`537`: new opendata module for contrib
* :ghissue:`535`: Add method for extracting data columns as Numpy array rather than list
* :ghissue:`534`: added geogrid to __all__ in sphere.py
* :ghissue:`533`: added geogrid function to create a grid of points on a sphere
* :ghissue:`532`: new functions to deal with spherical geometry: lat-lon conversion, degre...
* :ghissue:`390`: add option to have local moran quadrant codes align with geoda
* :ghissue:`530`: I390
* :ghissue:`528`: Replacing 0 by min value in choropleths
* :ghissue:`526`: B166
* :ghissue:`176`: contrib module for proj 4
* :ghissue:`178`: contrib module for gdal/org
* :ghissue:`203`: implement network class in spatialnet
* :ghissue:`204`: pysal-networkx util functions
* :ghissue:`209`: csv reader enhancement
* :ghissue:`215`: Add a tutorial for the spreg module
* :ghissue:`244`: ps.knnW_from_shapefile returns wrong W ids when idVariable specified
* :ghissue:`246`: Only use idVariable in W when writing out to file
* :ghissue:`283`: Create new nodes at intersections of edges
* :ghissue:`291`: Enum links around regions hangs
* :ghissue:`292`: Handle multiple filaments within a region in the Wed construction
* :ghissue:`302`: Handle hole polygons when constructing wed
* :ghissue:`309`: Develop consistent solution for precision induced errors in doctests across platforms
* :ghissue:`350`: reading/writing weights file with spaces in the ids
* :ghissue:`450`: x_name and summary method not consistent in ols
* :ghissue:`521`: Nosetests don't accept setup.cfg
* :ghissue:`509`: ESDA bin type inconsistency
* :ghissue:`525`: copyright update
* :ghissue:`524`: New homogeneity tests for general case and spatial markov as a special case
* :ghissue:`523`: pointing to github.io pages
* :ghissue:`520`: Same typo. Toolkit.
* :ghissue:`522`: Nosetests for python3 porting
* :ghissue:`518`: Update util.py
* :ghissue:`519`: Typo
* :ghissue:`517`: Documentation correction for Prais Conditional Mobility Index
* :ghissue:`516`: ENH for https://github.com/PySAL/PySAL.github.io/issues/17
* :ghissue:`515`: BUG: conditional check for extension of lower bound of colorbar to conta...
* :ghissue:`514`: ENH: adding the user_defined classification
* :ghissue:`513`: rewriting to not use ipython notebook --pylab=line
* :ghissue:`512`: Viz
* :ghissue:`508`: Adding barebones pysal2matplotlib options in viz
* :ghissue:`511`: DOC updating news
* :ghissue:`507`: Sched
* :ghissue:`510`: BUG: fix for #509
* :ghissue:`502`: spreg.ml_lag.ML_Lag is very very very time-consuming?
* :ghissue:`506`: 1.9dev
* :ghissue:`505`: REL bumping master to 1.9.0dev
* :ghissue:`504`: Release prep 1.8
* :ghissue:`503`: Grid for landing page


# v<1.8.0>, 2014-07-25

GitHub stats for 2014/01/29 - 2014/07/25 

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 8 authors contributed 281 commits.

* Dani Arribas-Bel
* Jay
* Philip Stephens
* Serge Rey
* Sergio Rey
* jlaura
* pedrovma
* sjsrey


We closed a total of 160 issues, 60 pull requests and 100 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (60):

* :ghpull:`503`: Grid for landing page
* :ghpull:`501`: Two figs rather than three
* :ghpull:`500`: More efficient higher order operations
* :ghpull:`499`: renamed nat_queen.gal for #452
* :ghpull:`497`: ENH Deprecation warning for regime_weights #486
* :ghpull:`494`: Enables testing against two versions of SciPy shipped with the last two Ubuntu LTS versions.
* :ghpull:`490`: Fix for #487
* :ghpull:`492`: BUG cleaning up temporary files for #398
* :ghpull:`493`: Phil: Skipping several tests that fail due to precision under older scipy
* :ghpull:`489`: test suite fixes
* :ghpull:`488`: More tests to skip if scipy less than 11
* :ghpull:`484`: ENH: cleaning up more test generated files
* :ghpull:`483`: Forwarding Phil's commit: skipping doctests, conditional skip of unit tests
* :ghpull:`482`: DOC cleaning up files after running doctests #398
* :ghpull:`481`: DOC contrib updates and links
* :ghpull:`480`: DOC cleaning up doctests
* :ghpull:`479`: ENH Changing regime_weights to block_weights for #455
* :ghpull:`478`: DOC: link fixes
* :ghpull:`477`: cKDTree for #460
* :ghpull:`476`: redefining w.remap_ids to take only a single arg
* :ghpull:`475`: Adding docstrings and error check to fix #471
* :ghpull:`470`: fixing order of args for api consistency. 
* :ghpull:`469`: Idfix for #449
* :ghpull:`463`: updating gitignore
* :ghpull:`462`: ENH: handle the case of an ergodic distribution where one state has 0 probability
* :ghpull:`458`: ENH: Vagrantfile for PySAL devs and workshops
* :ghpull:`447`: Clusterpy
* :ghpull:`456`: BUG: fix for #451 handling W or WSP in higher_order_sp
* :ghpull:`454`: Foobar
* :ghpull:`443`: Updating spreg: several minor bug and documentation fixes.
* :ghpull:`453`: Resolving conflicts
* :ghpull:`448`: Wsp
* :ghpull:`445`: ENH: unique qualitative color ramp. Also refactoring for future ipython deprecation of --pylab=inline
* :ghpull:`446`: Wmd
* :ghpull:`444`: Scipy dependency
* :ghpull:`442`: Wmd
* :ghpull:`441`: fixed kernel wmd for updated wmd structure
* :ghpull:`440`: ENH: sidebar for Releases and installation doc update
* :ghpull:`439`: - events
* :ghpull:`438`: ENH: pruning to respect flake8
* :ghpull:`437`: BUG: fix for removal of scipy.stat._support #436
* :ghpull:`433`: Rank markov
* :ghpull:`424`: testing
* :ghpull:`431`: FOSS4G
* :ghpull:`430`: Network
* :ghpull:`429`: moving analytics out of wed class and into their own module
* :ghpull:`428`: Network
* :ghpull:`427`: devel docs
* :ghpull:`425`: Viz2contrib
* :ghpull:`423`: Update news.rst
* :ghpull:`422`: ENH: Update doc instructions for napoleon dependency
* :ghpull:`421`: Adding files used in some examples as per Luc's request.
* :ghpull:`419`: Doc fixes 1.7
* :ghpull:`393`: Doc fixes 1.7
* :ghpull:`417`: ENH hex lattice W for #416
* :ghpull:`415`: Temporarily commenting out tests that are blocking Travis.
* :ghpull:`407`: Viz: Moving into contrib/viz in master
* :ghpull:`404`: version change
* :ghpull:`401`: fixes #388
* :ghpull:`402`: release changes

Issues (100):

* :ghissue:`503`: Grid for landing page
* :ghissue:`501`: Two figs rather than three
* :ghissue:`500`: More efficient higher order operations
* :ghissue:`452`: nat_queen.gal example file
* :ghissue:`499`: renamed nat_queen.gal for #452
* :ghissue:`486`: add a deprecation warning on regime_weights
* :ghissue:`497`: ENH Deprecation warning for regime_weights #486
* :ghissue:`449`: Lower order neighbor included in higher order
* :ghissue:`487`: Issue with w.weights when row-standardizing
* :ghissue:`398`: running test suite generates files
* :ghissue:`358`: Graph weights
* :ghissue:`338`: ENH: Move Geary's C calculations to Cython.
* :ghissue:`494`: Enables testing against two versions of SciPy shipped with the last two Ubuntu LTS versions.
* :ghissue:`490`: Fix for #487
* :ghissue:`492`: BUG cleaning up temporary files for #398
* :ghissue:`493`: Phil: Skipping several tests that fail due to precision under older scipy
* :ghissue:`489`: test suite fixes
* :ghissue:`485`: Revert "ENH: cleaning up more test generated files"
* :ghissue:`488`: More tests to skip if scipy less than 11
* :ghissue:`484`: ENH: cleaning up more test generated files
* :ghissue:`483`: Forwarding Phil's commit: skipping doctests, conditional skip of unit tests
* :ghissue:`482`: DOC cleaning up files after running doctests #398
* :ghissue:`481`: DOC contrib updates and links
* :ghissue:`480`: DOC cleaning up doctests
* :ghissue:`455`: regime weights vs block weights
* :ghissue:`479`: ENH Changing regime_weights to block_weights for #455
* :ghissue:`478`: DOC: link fixes
* :ghissue:`460`: Optimize KDTree
* :ghissue:`477`: cKDTree for #460
* :ghissue:`472`: Check for any side effects from new id remapping in w.sparse
* :ghissue:`473`: update all user space functions for new w.remap_ids
* :ghissue:`476`: redefining w.remap_ids to take only a single arg
* :ghissue:`263`: Transition to scipy.spatial.cKDTree from scipy.spatial.KDTree
* :ghissue:`414`: Travis build is killing nosetests
* :ghissue:`335`: Weights transformation docs
* :ghissue:`471`: add docstring example for w.remap_ids
* :ghissue:`475`: Adding docstrings and error check to fix #471
* :ghissue:`405`: ENH: Handling ids in W (Leave open for discussion)
* :ghissue:`470`: fixing order of args for api consistency. 
* :ghissue:`469`: Idfix for #449
* :ghissue:`467`: redirect pysal.org to new dynamic landing page
* :ghissue:`466`: design the grid for the notebooks
* :ghissue:`464`: design new dynamic landing page for github.io
* :ghissue:`465`: move news out of docs and into dynamic landing page
* :ghissue:`468`: Move dynamic items out of sphinx docs and into dynamic landing page
* :ghissue:`463`: updating gitignore
* :ghissue:`451`: docs for higher_order_sp have wrong argument types
* :ghissue:`462`: ENH: handle the case of an ergodic distribution where one state has 0 probability
* :ghissue:`458`: ENH: Vagrantfile for PySAL devs and workshops
* :ghissue:`447`: Clusterpy
* :ghissue:`456`: BUG: fix for #451 handling W or WSP in higher_order_sp
* :ghissue:`457`: This is a test to see if pull request notifications get sent out to the list
* :ghissue:`454`: Foobar
* :ghissue:`443`: Updating spreg: several minor bug and documentation fixes.
* :ghissue:`453`: Resolving conflicts
* :ghissue:`412`: On travis and darwin test_ml_error_regimes.py hangs 
* :ghissue:`448`: Wsp
* :ghissue:`435`: Will spatial durbin model be added in the near future?
* :ghissue:`445`: ENH: unique qualitative color ramp. Also refactoring for future ipython deprecation of --pylab=inline
* :ghissue:`446`: Wmd
* :ghissue:`444`: Scipy dependency
* :ghissue:`442`: Wmd
* :ghissue:`441`: fixed kernel wmd for updated wmd structure
* :ghissue:`440`: ENH: sidebar for Releases and installation doc update
* :ghissue:`439`: - events
* :ghissue:`438`: ENH: pruning to respect flake8
* :ghissue:`436`: Scipy 0.14 induced breakage
* :ghissue:`437`: BUG: fix for removal of scipy.stat._support #436
* :ghissue:`408`: Use of `platform.system()` to determine platform
* :ghissue:`403`: Scipy dependency
* :ghissue:`434`: W Object Metadata Attribute
* :ghissue:`433`: Rank markov
* :ghissue:`424`: testing
* :ghissue:`432`: Implementation of rank Markov classes
* :ghissue:`431`: FOSS4G
* :ghissue:`430`: Network
* :ghissue:`429`: moving analytics out of wed class and into their own module
* :ghissue:`420`: Local Moran's I,  I Attribute Undefined
* :ghissue:`418`: Extended pysal.weights.user.build_lattice_shapefile 
* :ghissue:`428`: Network
* :ghissue:`427`: devel docs
* :ghissue:`426`: dev docs
* :ghissue:`425`: Viz2contrib
* :ghissue:`423`: Update news.rst
* :ghissue:`422`: ENH: Update doc instructions for napoleon dependency
* :ghissue:`421`: Adding files used in some examples as per Luc's request.
* :ghissue:`419`: Doc fixes 1.7
* :ghissue:`393`: Doc fixes 1.7
* :ghissue:`416`: Add hexagonal lattice option for lat2W
* :ghissue:`417`: ENH hex lattice W for #416
* :ghissue:`409`: add wiki page on viz module design
* :ghissue:`413`: Temporary fix for https://github.com/pysal/pysal/issues/412
* :ghissue:`415`: Temporarily commenting out tests that are blocking Travis.
* :ghissue:`407`: Viz: Moving into contrib/viz in master
* :ghissue:`406`: Viz: pruning old code and adding more examples for TAZ paper
* :ghissue:`380`: Pep 8 and Line Length
* :ghissue:`404`: version change
* :ghissue:`401`: fixes #388
* :ghissue:`388`: update testing procedures docs
* :ghissue:`402`: release changes

# v<1.7.0>, 2014-01-29

36d268f Philip Stephens -Merge pull request #400 from sjsrey/mldoc
c2c4741 Serge Rey -Formatting ml docs
685f5e3 Sergio Rey -Merge pull request #399 from sjsrey/master
481ccb4 Serge Rey -correct thanks
4a5cce3 Sergio Rey -Update index.txt
1fe7aeb Philip Stephens -Merge pull request #396 from sjsrey/mldoc
e731278 Serge Rey -EHN: fixing link to bleeding edge docs.
e4e9930 Serge Rey -ENH: adding ml docs to api
9b3c77e Serge Rey -Merge branch 'master' of github.com:pysal/pysal
dda3c01 Philip Stephens -Merge pull request #389 from dfolch/master
74b26d5 Philip Stephens -Merge pull request #392 from pedrovma/spreg17
b47ba84 pedrovma -Bump.
3d8504c Sergio Rey -Merge pull request #386 from pastephens/master
f9b59ea Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
429e19e pedrovma -Upgrading to spreg 1.7.
c698747 David Folch -removing legacy speedup hack that is no longer relevant
88177d0 Sergio Rey -Merge pull request #387 from sjsrey/scipy13
64a4089 Serge Rey -BUG: sorting ijs for asymmetries
5539ef5 Sergio Rey -Merge pull request #1 from sjsrey/scipy13
8a86951 Serge Rey -BUG: fixes for scipy .0.9.0 to 0.13.0 induced errors
fe02796 Philip Stephens -tweaking travis to only run master commits
8c1fbe8 jlaura -Merge pull request #385 from sjsrey/docupdate
b71aedc Serge Rey -ENH: update date
4f237e4 Sergio Rey -Merge pull request #384 from sjsrey/moran
01da3be Serge Rey -ENH: Analytical p-values for Moran are two-tailed by default #337
918fe60 Philip Stephens -further travis tweaks
3920d73 Sergio Rey -Merge pull request #382 from sjsrey/st_docs
d90bc70 Serge Rey -DOC: updating refs for concordance algorithm
0db2790 Philip Stephens -tweaks to travis
063e057 Philip Stephens -upgrading scipy on travis
f90e742 Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
edc9c07 Dani Arribas-Bel -Merge pull request #379 from sjsrey/b244
82479bb Serge Rey -BUG: fix for the comment https://github.com/pysal/pysal/issues/244#issuecomment-30055558
57ba485 jlaura -Update README.md
981ed31 Sergio Rey -Merge pull request #377 from darribas/master
3320c39 darribas -Changing cmap default in plot_choropleth so every type defaults to its own adecuate colormap
e063bee darribas -Fixing ignorance of argument cmap in base_choropleth_unique
1f10906 Dani Arribas-Bel -Merge pull request #375 from sjsrey/viz
94aa3e7 Dani Arribas-Bel -Merge pull request #376 from pedrovma/baltim_data
7568b0b pedrovma -Adding Baltimore example dataset for use with LM models.
5b23f89 Serge Rey -greys for classless map
d4eae1e Dani Arribas-Bel -Merge pull request #374 from sjsrey/viz
652440d Serge Rey -shrinking colorbar
c17bf67 Sergio Rey -Merge pull request #373 from darribas/master
a71c3cb darribas -Fixing minor conflict to merge darribas viz branch into darribas master
ec27e30 Dani Arribas-Bel -Merge pull request #372 from sjsrey/viz
8c03170 Serge Rey -option for resolution of output figs
3fc5bd4 Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
2b5cb23 jlaura -Merge pull request #371 from sjsrey/geopandas
469afa7 Serge Rey -fix for #370
59cdafc jlaura -Merge pull request #369 from pedrovma/south_data
6b88e13 jlaura -Merge pull request #368 from schmidtc/issue367
40fe928 pedrovma -Adding south data to be used in ML doctests.
bcc257e schmidtc -fixes #367
87e057f jlaura -Merge pull request #366 from sjsrey/ml_lag
a64eb27 Serge Rey -queen contiguity for nat.shp
77add5c Sergio Rey -Merge pull request #365 from sjsrey/news
82464ef Serge Rey -narsc workshop
fd79424 Sergio Rey -Merge pull request #364 from sjsrey/news
bc7f25a Serge Rey -Merge branch 'master' of https://github.com/sjsrey/pysal
d669913 David Folch -Merge pull request #363 from sjsrey/maxp
22f9e36 Serge Rey -update example for bug fix #362
fac3b8a Serge Rey -- update tests for bug fix #362
44b4b06 Sergio Rey -Merge pull request #1 from sjsrey/maxp
1e6f1e5 Serge Rey -- fix for #362
68ab3e9 Sergio Rey -Merge pull request #361 from sjsrey/components
aa27c7e Serge Rey -doc test fix
7c08208 Serge Rey -putting Graph class back in for component checking
003b519 Serge Rey -alternative efficient component checker
2080e62 Serge Rey -- fixing doc
4fda442 Serge Rey -Merge branch 'components' of github.com:sjsrey/pysal into components
e9e613b Serge Rey -reverting back to old component check
83d855e Serge Rey -updating example
9defd86 jlaura -Merge pull request #360 from sjsrey/components
6f92335 Serge Rey -more efficient connectivity test
ebde3d1 Dani Arribas-Bel -Adding try/except for ogr since it's only used to reprojection methods but not on the plotting toolkit
5b170eb Sergio Rey -Merge pull request #356 from sjsrey/classification
c9dac41 Serge Rey -- update unit tests for reshaping jenks caspal
d9b06e2 Sergio Rey -Merge pull request #355 from sjsrey/cleanup/moran
dc589e8 darribas -Adding caution note when plotting points to the notebook. Ideally, we wanna be able to build a PathCollection out of the XYs, but for now we rely on plt.scatter, which gets the job done but has some problems.
2224b95 darribas -Including support for points in  base_choropleth_unique and base_choropleth_classless
ac2d08a darribas -Modifying example to show how to do choropleth mapping on points
270786e darribas -Adding support for choropleth plotting on point map objects (this may come from map_point_shp or from a simple matplotlib scatter
e56697c Sergio Rey -Merge pull request #357 from jlaura/newstyle_wed
4c67c2f Jay -errors in segmentation fixed
512cc76 Serge Rey -have Jenks-Caspal bins be a one dimensional array - to be consistent with all other classifiers
5254859 Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
788ecab Serge -pruning
5b6b7b6 Serge -pruning
eb7e9a1 Jay -bug fix and all pointers filled for external edges
e47aa7a Jay -Node insertion, precursor to segmentation.
18a44d1 darribas -*Replacing shp by map_obj in medium layer functionality. *Bringing everything else in line with it *Adding example for line colorig and mixing overlaying of points.
bd041b1 darribas -Replacing shp_link by shp as input for medium and low-level layers. This brings much more flexibility and opens the door to plot formats other than shapefiles (e.g. geojson)
c74a361 darribas -Adding IP notebook to exemplify and keep track of development of mapping module
d23c882 darribas -Minor fixes
4b82a76 darribas -New commit message* Replacing map_poly_shp_lonlat for map_poly_shp in base_choropleth_classif/unique/classless * removed 'projection' from base_choropleth_classif/unique/classless * Allow base_choropleth_classif/unique/classless to plot multi-part polygons properly * changes streamlined to generic plot_choropleth * Added dependency on pandas for rapid reindexing (this is done externally on the method _expand_values to it is easy to drop the dependency when neccesary/time available)
7a0eaec darribas -Merge branch 'viz' of github.com:darribas/pysal into viz
5536424 darribas -Merge branch 'master' of github.com:darribas/pysal
e54ce16 Sergio Rey -Merge pull request #353 from darribas/master
819ee60 darribas -Adding immediate todo on head of the file
946772d darribas -Passing k to base_choropleth_classif from plot_choropleth. This should fix Issue #352
f299b45 darribas -Merge branch 'master' of https://github.com/pysal/pysal
f044f43 Jay -Added W generation
5f48446 jlaura -Merge pull request #348 from sjsrey/master
938a1ae Serge Rey -- adding nn stats to point based methods
a86a051 Philip Stephens -removing dependency tracking service, it was ruby only
1e24fde Philip Stephens -testing dependency tracking service
3aa410c Philip Stephens -Merge pull request #347 from pedrovma/w_silence_island
03990f6 pedrovma -Extending PR #310 (silence island warnings) to include w.transform.
160001a Sergio Rey -Merge pull request #346 from jlaura/newstyle_wed
44989f9 Sergio Rey -Merge pull request #345 from sjsrey/master
2fd99b8 Sergio Rey -Update README.md
bdcc6a8 Jay -NCSR with uniform distribution
769aa03 Jay -Fixed snapping
2561071 Jay -saved notebook and updated readme
3784783 Jay -ReadMe for Changes
019e16b Sergio Rey -Merge pull request #334 from jseabold/fix-build-example-dirs
1889885 Skipper Seabold -BLD: Correctly install package_data dirs.
ff4e355 Serge Rey -- assignments
c5b0cc0 Serge Rey -- reorg
a4f5642 Serge Rey -Merge branch 'network' of github.com:pysal/pysal into network
a95fec8 jlaura -Update README.md
1713145 Serge Rey -Merge branch 'master' of github.com:pysal/pysal into network
ede75c0 Sergio Rey -Merge pull request #329 from jlaura/wed_polar
7399cf2 Jay -Single-source shortest path notebook
9eb3fc1 Philip Stephens -Merge pull request #331 from sjsrey/docfix
ef9c82a Serge Rey -- sphinx doctest markup fix
1e2b6b3 jlaura -Update README.md
e19bffa jlaura -Merge pull request #330 from pysal/b328
6afc30b Serge Rey -- tutorial doc fixes for #328
c7239f1 Serge Rey -- b328 fix
d5fec13 Serge Rey -- fix for #328  making all p-values one-tailed
16b5e6e Jay -enumeration working with filaments
9507bbc jlaura -Update README.md
eef8eec Serge Rey -- stub for design of module
2707d60 Jay -Filaments in polar coordinates
b64f9e2 Serge Rey -Documentation for the development of network module
b90876e Serge Rey -Merge branch 'network' of github.com:pysal/pysal into network
ddad2a5 Philip Stephens -Merge pull request #326 from sjsrey/doc
6b0cd08 Serge Rey -- update release schedule
4cc7bca Jay -bisecting for single point working
79c77d9 jlaura -Merge pull request #324 from pysal/bf_id
9f4c7c9 Serge Rey -id is a keyword
72b1f85 Sergio Rey -Merge pull request #323 from jlaura/network
b5cdae0 Jay -fix to shp2graph
846dce2 Jay -Brute force for point outside network
d6c2ef4 Jay -Added length computation, alter global morans
b7e1465 Jay -Added new pointer to reader/writer
616d62d Jay -LISA and Global Morans on the network
16f84d6 Jay -Added explicit point external to network warning
34f4d8e Jay -update to the ipython notebook
e359e59 Jay -JSON and cPickle Bianry WED Reader/Writer
5373c82 Sergio Rey -Merge pull request #322 from jlaura/network
059d99c Jay -wed into class, tests added
aa5969d Sergio Rey -Merge pull request #320 from pastephens/master
a18000b Philip Stephens -version added info
5b8d490 Philip Stephens -typo
d31a22a Philip Stephens -stubs for cg docs
4dbdfe3 schmidtc -fixes #318
35a0317 Jay -Merge branch 'master' of https://github.com/pysal/pysal into network
77e8387 Jay -Merge branch 'geojson' of https://github.com/pysal/pysal into network
ad670c5 Sergio Rey -Merge pull request #317 from pastephens/master
628f27e Philip Stephens -merging local changes
f9dcb3e Philip Stephens -simplified install instructions
f2fab4c Serge Rey -- notebook on w construction for geojson
830826b Serge Rey -prototyping W from geojson
b10240d Serge Rey -created with "ogr2ogr -lco WRITE_BBOX=YES -f "GeoJSON" columbus.json columbus.shp"
d546926 Philip Stephens -merging with pull
d711011 darribas -Merge branch 'rod'
8bef782 darribas -Merge branch 'rod' of https://github.com/pysal/pysal into rod
03c1003 pedrovma -Merge pull request #315 from sjsrey/rod
950fe8b Serge Rey -Replacing ROD with regular dictionary
b1f009f Philip Stephens -Changes to release docs.
028364a Sergio Rey -Update THANKS.txt
94f5916 Sergio Rey -Update INSTALL.txt

# v<1.6.0>, 2013-07-31

5fa9d09 darribas -silent_island_warning implemented for w_union
6526c62 Sergio Rey -Update README.md
ea826c1 darribas -silent_island_warning implemented for w_intersection
335540a darribas -silent_island_warning implemented for w_difference
0a156cb darribas -silent_island_warning implemented for w_symmetric_difference. Previous commit included support of silent_island_warning for WSP2W as well
34d20d7 darribas -silent_island_warning implemented for w_clip
499815d pedrovma -Test fixing...
8778f75 pedrovma -Test fixing...
a799a13 pedrovma -Test fixing...
6482d81 pedrovma -Test fixing...
2752b1b pedrovma -Test fixing...
0c0a5bf pedrovma -Test fixing...
bbf9dcb pedrovma -Test fixing...
05c34ff pedrovma -Test fixing...
8a3986a Serge Rey -- preparing for release, version updates
9106cfe pedrovma -Matching travis results reg. precision issues.
3cd0ce1 Serge Rey -- updating changelog
74dadd6 pedrovma -Bump.
c7774fb Serge Rey -- update THANKS.txt - testing travis for timing out
cd98057 Serge Rey -- travis fix for multiprocessing permission error
86702f8 Serge Rey -- start of changelog for 1.6
3ee686d pedrovma -Reloading to check new results from Travis.
2de1d21 Serge Rey -- docs
ef72edc Serge Rey -- update docs
0716581 Serge Rey -- deal with multiprocessing on travis
b508c88 Serge Rey -- excluding network from 1.6 release
ff13e31 pedrovma -Matching Travis results. Multiprocessing errors still an issue.
5b916ba pedrovma -Adding Chow test on lambda and updating dynamics of regime_err_sep and regime_lag_sep in combom models.
b6e687f darribas -Patch to include switch for island warning as proposed in #295. The method  is modified as well to include the switch
7ea5f35 pedrovma -Fixing defaults
62ca76b pedrovma -Updating documentation and checking if there are more than 2 regimes when regimes methods are used.
3212249 pedrovma -Fixing documentation on 'name_regimes'
a782d50 pedrovma -Updating tests for integration with pysal 1.6
14f9181 pedrovma -Merging spreg_1.6 with my pysal fork.
817f2c2 Serge Rey -- having build_lattice_shapefile also create the associated dbf file - useful for testing our contiguity builders against geoda since dbf is   required by the latter
41d59a4 Serge Rey -- adding diagonal option to kernel weights in user.py
506d808 Serge Rey -update when added
b2ec3d4 Serge Rey -- updating api docs
9d45496 Serge Rey -- example and doctests for spatial gini
95635bb Serge Rey -updating release docs
bd2f924 darribas -Fixing doctest of towsp method by including isinstance(wsp, ps.weights.weights.WSP)
76183d7 darribas -Fixing doctest of towsp method by including type(wsp)
0c54181 darribas -Adding  method in W that calls WSP class for convenience and elegance. Related to issue #226
f3b23e8 Philip Stephens -adding source build to travis-ci
60930e7 Philip Stephens -adding new url for downloads
9bf7f5b Philip Stephens -modified release docs.
f98d4a9 Philip Stephens -interim ci
aa19028 Philip Stephens -Adding docs about installing in develop mode.
674112f Philip Stephens -starting rewrite of install docs
af0d9b3 Philip Stephens -working on doc tickets
200e77e Serge Rey -handle ties in knnW in doctest
d0d2dd2 Serge Rey -resetting README for pysal/pysal
6afb6ac Serge Rey -- updating docs for new api in interation.py
4c5572f Serge Rey -- updating tests for new api
fabd16a Serge Rey -- refactored signatures to use numpy arrays rather than event class
6367947 Serge Rey -- refactor knox for large samples
5fad3b2 Serge Rey -- updating travis test
06894d8 Serge Rey -- updated README
8b06e63 Serge Rey -- so only i get email when i commit locally
efbb7ff Serge Rey -- removing google pysal-dev circle
9859bda Serge Rey -- turning off gmail circle
51f6d3e Serge Rey -- fixing
46b1084 Serge Rey --docos
4e2c27a Philip Stephens -missing if statement added
d1a83fd Serge Rey -- fixing docs
8275d76 Serge Rey -- fix precision
87ea5cc Philip Stephens -adding to authors and quick test fix for linux
1cfb67f Serge Rey -cant easily remove idVariable, reverting
5933d1e Serge Rey -removing idvariable from Distance - causes too many issues
05f2573 Philip Stephens -removing coverage tests
fcb8c6f Philip Stephens -Knox using KDTree.
2237173 Serge Rey -with tests against previous implementation removed
233e59a Serge Rey -speed comparison for change to query_pairs in kdtree
fb78ea9 Serge Rey -removing test file
4d04575 Philip Stephens -testing
357a184 Serge Rey -second great idea
1fafc2b Serge Rey -on a plane commit 1
fef6eae Philip Stephens -fix
86c17ac Serge Rey -- test file
a619f62 Philip Stephens -interim ci
1a9d881 Serge Rey -- knox test using kdtrees
7459c44 Serge Rey -Fixing reference to missing shapefile Fixing one rounding error induced test
5616b12 Serge Rey -refactored to avoid second loop in explicit queen or rook check
d3d2f71 Philip Stephens -Revert "Changed doctest path calls to account for modified shapefile."
da1d8a1 Philip Stephens -Changed doctest path calls to account for modified shapefile.
f591c99 Philip Stephens -progress on permutations of knox for larger datasets
8d31cde Serge Rey -Testing integration of spatialnet creation and reading into wed
11de6f3 Jay -Fixed wed_modular.py
077658a Serge Rey -adding new test case for wed extraction from a spatialnet shapefile
bbb10b4 Philip Stephens -saving state of development
44076b7 Serge Rey -- update doc test
6fdd94d Serge Rey -- moved regions_from_graph into wed_modular - documented all functions and cleaned up
5bd27c3 Serge Rey -- wrapping in functions
3ad162f Serge Rey -- working version of wed_modular module - starting point for clean up
2380f15 Philip Stephens -Copy of sphinx install docs. Closes #251
5687700 Philip Stephens -tweaks to install instructions
9ffd432 Serge Rey -- updating for switch from svn to git
fdaf521 Philip Stephens -Fixing 250
5ba4fdf Serge Rey -Fixes #249 Closes #249
d89944d Pedro -Adding docs for each regimes estimator
f03bb63 Serge Rey -- updating docs for spatial regimes in spreg
a49d0f7 Philip Stephens -Adding info to setup script.
1f27605 Philip Stephens -mainly docs
04f8a31 Philip Stephens -Adding test coverage with nose, data collected and presented on coveralls.io
6db978b Philip Stephens -last changes
137e088 Philip Stephens -added bigdata parameter
7ca81c2 Philip Stephens -got Knox stat working in alt form
24c1fcc Philip Stephens -workign on refactoring the space-time matrices for the Knox test [ci-skip]
28013f0 Serge Rey -- enumeration of cw edges for faces
baa8f60 Serge Rey -- hole is now included and enumeration of links (cw) around nodes works for all nodes. - isolated nodes also handled in enumeration of links around nodes.
33741c8 Serge Rey -- filaments inserted and pointers updated - have to add hole polygon and isolated nodes, but almost there!!!!!!!!!
416d3db Serge Rey -- pointers updated for edges of connected components
c34e274 Serge Rey -- convex/between edge test as start of testing for insertion of multiple   internal filaments in one region.
78d96b1 Serge Rey -- filament insertion and pointer updates
ced2c5b Serge Rey -- filament insertion (inc)
ba4263f Jay -Logic roughed in for filaments [ci skip]
cf3b0bc Jay -updated wed ipynb [ci skip]
33ce81e Serge Rey -- refactoring of wed construction (incomplete)
0fc16fc Jay -modular WED Pulled Apart 2 funcs in 1 cell
bf73b90 Jay -modular WED
3163377 Serge Rey -- new modular wed construction
e50b31d Jay -added test_wed additions to test_wed2
1cbc941 Serge Rey -- isolated nodes handled
d28b97f Serge Rey -- isolated filament handled
6188fd5 Serge Rey -- hole component handled
a96040b Serge Rey -- getting connected components (current 14,15,16  and 25,26,27 are not   included)
3aa31a5 Jay -Added boolean arg to include or exclude holes [ci skip]
d07876d Jay -Filament identification [ci skip]
0139ea5 Philip Stephens -Slight speed improvement getting rid of append calls in reading shapefile and building x,y lists.
43010b5 Serge Rey -- fixed logic problem with enum for v1, starting on components
8737918 Pedro -Adding more meaningful error message to inverse distance weights
01f52f6 Serge Rey -- replacing code that got deleted previously
7c4c6e1 Philip Stephens -Replacing deleted files.
a8da725 Philip Stephens -added date support to spacetimeevents class, a date column to example dbf.
90c4730 Philip Stephens -logic works, numeric test still failing
b8e43e1 Philip Stephens -saving progress on interaction
81f2408 Serge Rey -- handling external end-node-filament
7de6253 Serge Rey -- adding end node filament handling - edge enumeration around node working
f542b9a Serge -- adding end node filament handling - edge enumeration around node working
d7e3a57 Philip Stephens -[ci skip] disabling nose-progressive so travis output looks best
fe03013 Dani Arribas-Bel -Adding set of diversity indices to inequality module under _indices.py for now. Still lacks doctests, unittests, and a few others will be added
951b6f5 Dani Arribas-Bel -Adding try/except to the import of Basemap to allow the use of the module when there is no Basemap installation
89003eb Serge Rey -- adding wed for eberly example
665ef22 Serge Rey -- fixed 7,2 failure
71fc9ad Serge Rey -start of adding gini and other inequality measures
f7b7bcc Phil Stephens -Adding nose-progressive plugin to test suite. Devs can run test suite with 'make test'.
f5db7bf Serge Rey -- updating copyright
07574b5 Serge Rey -- docs
478d2cb Philip Stephens -Adding requirement. Removing redundancy.
916a6ca Serge Rey -- more island check updates
edd9960 Serge Rey -- more island check doctest changes
ad1a91c Serge Rey -- updating doctests for island check
ce77772 Serge Rey -- fixing doctests to incorporate new island warning
554a30b Serge Rey -- silencing floating point warning
4f76862 Serge Rey -- moving default contiguity builder back to binning from rtree
b99665b Jay -Eberly
d911344 Jay -mp removed, passing nosetests on my machine serial
f005675 Serge Rey -improved binning algorithm for contiguity builder
4a69557 Serge Rey -- double checking threshold in Distance Band - new example to show functionality
7256f13 Serge Rey -- fix handling of idVariable for knnW
31bb36e Jay -bug fixes [ci skip]
a2d2dd4 Jay -WEberly - WED Building [ci skip]
3abc55e Serge Rey -- fixing doctests for new check/reporting for islands
756ac05 Serge Rey -- adding warning if islands exist upon W instantiation
db097a6 Jay -Weberly, bug fix, c and cc link remaining
d5cc6f9 Jay -All but start / end working
033963d Jay -Integration to WEberly error fixed [ci skip]
22b931a Serge Rey -- removing main for doc tests which can be run from nosetests. - updating testing docs
bf753e9 Jay -Integration to WEberly started [ci skip]
6506e07 Serge Rey -- typo
aede375 Serge Rey -- replacing double quotes around multi word ids with strings joined with   underscores
cf029e8 Serge Rey -- changes to wrap string ids in gwt writer - see https://github.com/pysal/pysal/issues/244#issuecomment-16707353
626ac08 Serge Rey -- adding shapefile and variable name to gwt objects created in user space
3c84bb0 Jay -Working version 4.19 [ci skip]
7d77da9 darribas -Include warning in sp_att when rho is outside (-1, 1), ammends #243 although the true problem (pearsonr in diagnostics_tsls) will still raise an error
3719d21 Jay -working WED [ci skip]
b4ce294 Serge Rey -checking edges
f4bb412 Jay -excessive print statements removed. ci skip
9f7dee6 Jay -SUCCESS! ci skip
9077615 Phil Stephens -Note, [ci skip] anywhere in your commit message causes Travis to NOT build a test run.
cb072c4 Jay -getting there
d3b36bc Serge Rey -correcting typo user told me about
19ea051 Jay -trivial working
b9ea577 Jay -eberly cycles - edge issue still
d5153e3 Serge Rey -more refinement of wed from plannar graph
edff44b Philip Stephens -adding git ignore file
8093f21 Serge Rey -wed from minimum cycle basis
b5bcead Serge Rey -handle filaments
9a8927a Serge Rey -face extraction using horton algorithm
10d66c1 Serge Rey -updating readme formatting
59f3750 schmidtc -adding Universal newline support to csvReader, fixes #235
09e813f Serge Rey -- updating notifications
f8b0a26 Serge Rey -- fixing Distance.py and testing travis message
d1ec0f2 Phil Stephens -quieting pip output and fix one doctest
927e799 Phil Stephens -adding networkx, tweaks to travis config
5971bb1 Serge Rey -neighbors from wed
28f0e55 Serge Rey -adding robust segment intersection tests
3bcac73 Serge Rey -adding doubly connected edge list to network module
86f0fea darribas -Adding methods to read line and point shapefiles and improving the method to append different collections to one axes. Still in progress
b61cb55 Serge Rey -- fixing introduced bug in knnW_arc
801e78d Serge Rey -Handle point sets with large percentage of duplicate points
dbafbc4 serge -update pointer to github
427a620 Serge Rey -dealing with filaments
23216ef Serge Rey -Fixed cw enumeration of links incident to a node
0a51a53 Serge Rey -- readme
5f4cab4 sjsrey -cw enumeration not working for all nodes
f2e65d3 Serge Rey -- cw traversal of edges incident with a node
90d150c sjsrey -- version debug for travis
24598a8 sjsrey -- noting move to org
9fb8a17 sjsrey -- fixing tutorial tests
5a14f9e serge -- cleaning up weights tests
6265b3b Serge Rey -- fixing doc tests
7e8c4fe Serge Rey -- testing after move to org
37fc8d4 Serge Rey -- testing post commit emails
bed7f6e Phil Stephens -removed files
eab2895 Phil Stephens -removed virginia_queen files
bcef010 Serge Rey -- adding diagonal argument to Kernel weights - adding doctest evaluation to Distance.py
02d27e9 Phil Stephens -adding libgeos-dev
1126d71 Phil Stephens -pipe build output to null
37dbb35 Phil Stephens -adding -y flag to pip uninstall
06d56e9 Phil Stephens -adding libgeos_c install, pysal from pip
4c53277 Phil Stephens -trying to quiet output, using Makefile
74448e8 Phil Stephens -find setup.py
4634fb1 Phil Stephens -test install in venv and build
5d58723 Phil Stephens -working out travis-ci doctest configuration
5e905d3 Phil Stephens -adding numpydoc
33a5298 Phil Stephens -tweaks travis config
5c85f50 Phil Stephens -tweaking service configs
4ed1201 Josh Kalderimis -use the correct syntax for sysytem_site_packages
954b6d2 Phil Stephens -stop!
311eca8 Phil Stephens -ssp=true
c601bca Phil Stephens -numpy first
54b0afe Phil Stephens -ok, so travis is serious about not using system site packages.
2b912cc Phil Stephens -doh
28994df Phil Stephens -better yaml
ce1d89e Phil Stephens -testing
b535d3e Phil Stephens -testing
440a772 Phil Stephens -tweaking pip requirements file
34a74e2 Phil Stephens -tweaking travis file
33b13aa Serge Rey -- new links
8e09d7b Serge Rey -- setting up travis
d33001e Sergio Rey -Update CHANGELOG.txt
9d4de66 Serge Rey -- added authors
ab672c9 Serge Rey -- modified knnW to speed up dict construction
4edd2ab Serge Rey -- update cr
39e6564 Phil Stephens -syncing install instructions with docs
9e98db9 Phil Stephens -adding website favicon; chrome does not empty cache properly!!

 * migration to github from svn
   svn2git http://pysal.googlecode.com/svn --authors ~/Dropbox/pysal/src/pysal/authors.txt --verbose

# v<1.5.0>, 2013-01-31

2013-01-29 20:36  phil.stphns

	* doc/source/users/installation.txt: updating and simplifying user
	  install instructions.

2013-01-18 16:17  sjsrey

	* Adding regime classes for all GM methods and OLS available in
	  pysal.spreg, i.e. OLS, TSLS, spatial lag models, spatial error models
	  and SARAR models. All tests and heteroskedasticity
	  corrections/estimators currently available in pysal.spreg apply to
	  regime models (e.g. White, HAC and KP-HET). With the regimes, it is
	  possible to estimate models that have:
	  -- Common or regime-specific error variance;
	  -- Common or regime-specific coefficients for all variables or for a
	  selection of variables;
	  -- Common or regime-specific constant term;
	  - Various refactoring to streamline code base and improve long term
	    maintainability
	    - Contributions from Luc Anselin, Pedro Amaral, Daniel Arribas-Bel
	      and David Folch

2013-01-18 14:08  schmidtc

	* pysal/common.py: implemented deepcopy for ROD, see #237

2013-01-08 12:28  dreamessence

	* pysal/contrib/spatialnet/__init__.py: Adding __init__.py to make it importable

2012-12-31 22:53  schmidtc

	* pysal/core/IOHandlers/gwt.py: adding kwt support, see #232

2012-12-21 20:53  sjsrey@gmail.com

	* pysal/__init__.py, pysal/cg/rtree.py,
	  pysal/contrib/weights_viewer/weights_viewer.py,
	  pysal/weights/weights.py: - turning off randomization in rtree

2012-12-06 16:34  dfolch

	* pysal/contrib/shapely_ext.py: adding unary_union() to shapely
	  contrib; note this only works with shapely version 1.2.16 or higher


2012-11-29 13:39  dreamessence 

	* pysal/contrib/viz/mapping.py: Added option in setup_ax to pass
	  pre-existing axes object to append.  It is optional and it enables,
	  for instance, to embed several different maps in one single figure

2012-11-20 00:23  dfolch

	* pysal/contrib/shapely_ext.py: adding shapely's cascaded_union
	  function to contrib

2012-11-12 18:08  dreamessence

	* pysal/contrib/viz/mapping.py: -Adding transCRS method to convert
	  points from one prj to another arbitrary one -Adding map_poly_shp to
	  be able to plot shapefiles in arbitrary projections, not needing to
	  be in lonlat and not depending on Basemap

2012-11-09 15:40  sjsrey@gmail.com

	* pysal/weights/weights.py:
	  - distinguish between intrinsic symmetry and general symmetry
	
2012-11-02 17:48  schmidtc

	* pysal/weights/user.py, pysal/weights/util.py: Adding Minkowski
	  p-norm to min_threshold_dist_from_shapefile, see issue #221

2012-10-19 22:35  sjsrey@gmail.com

	* pysal/weights/weights.py:
	  explicitly prohibit chaining of transformations - all
	  transformations are only applied to the original weights at
	  instantiation

2012-10-19 17:38  sjsrey@gmail.com

	* pysal/spatial_dynamics/markov.py:
	  - fixing bug in permutation matrix to reorder kronecker product in
	    the join test

2012-10-17 17:55  sjsrey@gmail.com

	* pysal/weights/util.py:
	  -
	  higher order contiguity for WSP objects

2012-10-17 15:43  sjsrey@gmail.com

	* pysal/weights/user.py:
	  -
	  id_order attribute was always NONE for wsp created from
	  
	  queen/rook_from_shapefile with sparse=True

2012-10-16 19:25  schmidtc

	* pysal/weights/util.py: improving memory usage of
	  get_points_array_from_shapefile, no need to read entire shapefile
	  into memory.

2012-10-15 00:44  dreamessence

	* pysal/contrib/viz/mapping.py: First attempt to refactor Serge's code
	  for choropleth mapping.  It now offers a more general and flexible
	  architecture.  Still lots of work and extensions left.  The module
	  is explained in a notebook available as a gist at
	  https://gist.github.com/3890284 and viewable at
	  http://nbviewer.ipython.org/3890284/

2012-10-12 18:34  schmidtc

	* pysal/contrib/spatialnet/spatialnet.py: modified SpatialNetwork.snap
	  to calculate and return the snapped point

2012-10-12 17:05  dfolch

	* pysal/contrib/viz/mapping.py: made edits to unique_values_map to
	  allow for unlimited number of categories; I commented out the
	  previous code so these changes can easily be rolled back if it
	  breaks something somewhere else

2012-10-12 15:03  schmidtc

	* pysal/cg/segmentLocator.py: Fixing issue with segmentLocator, when
	  query point is extreamly far from the grid boundary, overflow errors
	  were causing the KDTree to not return any results.  Changed both
	  KDtree's to use Float64 and share the same data.  Previously,
	  cKDTree was using float64 and KDtree was using int32.

2012-10-11 08:12  dreamessence

	* pysal/contrib/viz/__init__.py: Adding __init__.py to viz module to
	  make it importable

2012-08-31 02:57  phil.stphns

	* pysal/spreg/tests/test_diagnostics.py,
	  pysal/spreg/tests/test_diagnostics_sp.py,
	  pysal/spreg/tests/test_diagnostics_tsls.py,
	  pysal/spreg/tests/test_error_sp.py,
	  pysal/spreg/tests/test_error_sp_het.py,
	  pysal/spreg/tests/test_error_sp_het_sparse.py,
	  pysal/spreg/tests/test_error_sp_hom.py,
	  pysal/spreg/tests/test_error_sp_hom_sparse.py,
	  pysal/spreg/tests/test_error_sp_sparse.py,
	  pysal/spreg/tests/test_ols.py,
	  pysal/spreg/tests/test_ols_sparse.py,
	  pysal/spreg/tests/test_probit.py,
	  pysal/spreg/tests/test_twosls.py,
	  pysal/spreg/tests/test_twosls_sp.py,
	  pysal/spreg/tests/test_twosls_sp_sparse.py,
	  pysal/spreg/tests/test_twosls_sparse.py:
	  - autopep8 -iv spreg/tests/*.py - nosetests pysal - no fixes needed

2012-08-31 01:16  phil.stphns

	* pysal/spreg/diagnostics.py,
	  pysal/spreg/diagnostics_sp.py,
	  pysal/spreg/diagnostics_tsls.py,
	  pysal/spreg/error_sp.py,
	  pysal/spreg/error_sp_het.py,
	  pysal/spreg/error_sp_hom.py,
	  pysal/spreg/ols.py,
	  pysal/spreg/probit.py,
	  pysal/spreg/robust.py,
	  pysal/spreg/summary_output.py,
	  pysal/spreg/twosls.py,
	  pysal/spreg/twosls_sp.py,
	  pysal/spreg/user_output.py,
	  pysal/spreg/utils.py:
	  -
	  autopep8 -iv spreg/*.py - fixed autopep8-introduced doctest failures
	  - fixed lingering scientific notation test failures

2012-08-31 00:26  phil.stphns

	* pysal/esda/gamma.py,
	  pysal/esda/join_counts.py,
	  pysal/esda/mapclassify.py,
	  pysal/esda/mixture_smoothing.py,
	  pysal/esda/moran.py,
	  pysal/esda/smoothing.py:
	  -
	  autopep8 fixes - make sure to run unit and doc tests before
	  committing - one autofix breaks long lines, and thus breaks some
	  doctests; must be
	  
	  fixed manually

2012-08-31 00:10  phil.stphns

	* pysal/esda/getisord.py:
	  -
	  using autopep8 module - call: autopep8 -vi getisord.py

2012-08-30 23:18  phil.stphns

	* pysal/esda/geary.py:
	  -
	  pep8 clear - removed wildcard import

2012-08-26 22:53  phil.stphns

	* pysal/spatial_dynamics/directional.py,
	  pysal/spatial_dynamics/ergodic.py,
	  pysal/spatial_dynamics/interaction.py,
	  pysal/spatial_dynamics/markov.py,
	  pysal/spatial_dynamics/rank.py,
	  pysal/spatial_dynamics/util.py:
	  -pep8 and pylint fixes -clean wildcard imports

2012-08-26 21:03  phil.stphns

	* pysal/region/maxp.py,
	  pysal/region/randomregion.py:
	  -
	  cleaning up imports

2012-08-26 18:16  phil.stphns

	* pysal/region/maxp.py:
	  -
	  style fixes with pep8 - cmd line call: pep8 --show-source
	  --ignore=E128,E302,E501,E502,W293,W291
	  
	  region/maxp.py

2012-08-26 17:47  phil.stphns

	* pysal/common.py,
	  pysal/examples/README.txt,
	  pysal/region/components.py,
	  pysal/region/randomregion.py:
	  -
	  using pep8 module

2012-08-24 20:47  schmidtc

	* pysal/network,
	  pysal/network/__init__.py: adding network module

2012-08-21 22:53  phil.stphns

	* doc/source/_templates/ganalytics_layout.html:
	  -
	  updating analytics tracker

2012-08-17 17:11  sjsrey@gmail.com

	* pysal/contrib/spatialnet/util.py:
	  -
	  more utility functions for pysal
	  -
	  networkx interop

2012-08-16 23:44  phil.stphns

	* setup.py:
	  -
	  tweak for build names

2012-08-12 13:15  dreamessence

	* doc/source/index.txt:
	  Adding announcement links to landing page

2012-08-11 17:38  sjsrey

	* LICENSE.txt:
	  -
	  update

2012-08-09 17:19  phil.stphns

	* doc/source/developers/pep/pep-0008.txt:
	  updating
	  spatial
	  db
	  pep

2012-08-08 17:22  schmidtc

	* pysal/weights/Distance.py:
	  Fixing bug in Kernel weights that causes erroneous results when
	  using ArcDistances.  See issue #218.

2012-08-04 21:14  sjsrey

	* doc/source/developers/docs/index.txt:
	  -
	  fixed
	  links

2012-08-04 21:03  sjsrey

	* doc/source/developers/docs/index.txt:
	  -
	  hints
	  on
	  editing
	  docs
	  

2012-08-04 20:14  phil.stphns

	* doc/source/developers/pep/pep-0011.txt:
	  note
	  about
	  travis-ci
	  and
	  github

2012-08-04 16:24  sjsrey

	* doc/source/developers/pep/pep-0011.txt:
	  PEP-0011
	  

2012-08-04 16:22  sjsrey

	* doc/source/developers/pep/index.txt:
	  -
	  PEP 0011 Move from Google Code to Github

2012-08-04 04:42  sjsrey

	* doc/source/index.txt:
	  - broken link

2012-08-04 04:35  sjsrey

	* doc/source/index.txt:
	  - news updates

2012-08-04 04:24  sjsrey

	* doc/source/index.txt:
	  - reorg

2012-08-02 02:32  sjsrey

	* pysal/examples/__init__.py:
	  -
	  moving back to r1049 but leaving r1310 in history for ideas on
	  moving forward - we need to distinguish between using examples in
	  the doctests (which the users see) and for the developers since we
	  are no longer distributing examples with the source

2012-08-02 01:49  sjsrey

	* pysal/examples/__init__.py:
	  -
	  correct conditional this time (i hope)

2012-08-02 01:36  sjsrey

	* pysal/examples/__init__.py:
	  -
	  compromise
	  -
	  returns pth rather than None if file does not exist

2012-08-02 00:58  sjsrey

	* pysal/examples/__init__.py:
	  -
	  link to examples download

2012-08-02 00:42  sjsrey

	* pysal/examples/__init__.py:
	  -
	  explicit check if examples are actually present





# v<1.4.0>, 2012-07-31

2013-01-31 


2012-07-31 21:30  sjsrey@gmail.com

	* pysal/spatial_dynamics/ergodic.py,
	  pysal/spatial_dynamics/rank.py:
	  - docs/example

2012-07-31 20:47  sjsrey@gmail.com

	* pysal/spreg/tests/test_error_sp_hom.py:
	  - rounding/precision issue

2012-07-31 20:27  sjsrey@gmail.com

	* pysal/spatial_dynamics/directional.py,
	  pysal/spatial_dynamics/tests/test_directional.py:
	  - fixing pvalue bug

2012-07-31 20:24  sjsrey@gmail.com

	* doc/source/users/tutorials/dynamics.txt:
	  - fixed rounding problem

2012-07-31 19:58  sjsrey@gmail.com

	* doc/source/index.txt,
	  doc/source/users/tutorials/autocorrelation.txt,
	  doc/source/users/tutorials/dynamics.txt,
	  doc/source/users/tutorials/econometrics.txt,
	  doc/source/users/tutorials/fileio.txt,
	  doc/source/users/tutorials/index.txt,
	  doc/source/users/tutorials/intro.txt,
	  doc/source/users/tutorials/region.txt,
	  doc/source/users/tutorials/smoothing.txt,
	  doc/source/users/tutorials/weights.txt:
	  - adding links to API for more details

2012-07-31 19:05  sjsrey@gmail.com

	* pysal/spatial_dynamics/directional.py:
	  - consistency on pvalues for randomization

2012-07-31 19:02  sjsrey@gmail.com

	* pysal/weights/Distance.py:
	  - docs

2012-07-31 18:58  sjsrey@gmail.com

	* doc/source/users/tutorials/dynamics.txt:
	  - seed issue 

2012-07-31 18:36  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt:
	  - closing issue 214

2012-07-31 18:19  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt:
	  - fixing random.seed issues in doctests

2012-07-31 17:31  schmidtc

	* pysal/cg/shapes.py,
	  pysal/cg/tests/test_shapes.py:
	  Fixing small bugs with VerticleLines and testing

2012-07-31 16:26  sjsrey@gmail.com

	* doc/source/developers/guidelines.txt,
	  doc/source/users/installation.txt:
	  - updating docs 



2012-07-26 15:24  schmidtc

	* pysal/core/FileIO.py,
	  pysal/core/Tables.py:
	 Fixing issue #190

2012-07-24 16:32  schmidtc

	* pysal/cg/sphere.py:
	Allowing linear2arcdist function to maintin 'inf', this allows compatability with Scipy's KDTree and addresses issue 208.  

2012-07-24 16:07  schmidtc

	* pysal/cg/locators.py,
	  pysal/core/FileIO.py,
	  pysal/core/Tables.py:
	  Addressing issue 212, renaming nested and private classes to begin with an underscore.  By default sphinx does not try to document private object, which avoids what appears to be a a bug in Sphinx.

2012-07-17 22:06  sjsrey@gmail.com

	* pysal/spreg/probit.py: pedro doc fixes

2012-07-17 15:07  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/tests/test_segmentLocator.py: Cleaned up fix for Issue 211

2012-07-13 22:50  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: fixing sphinx weirdness in footnotes 

2012-07-13 22:37  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: update for new default parameter values

2012-07-13 22:13  sjsrey@gmail.com

	* pysal/esda/geary.py,
	  pysal/esda/tests/test_geary.py: consistency on transformation and permutation args

2012-07-13 19:59  sjsrey@gmail.com

	* doc/source/users/tutorials/dynamics.txt,
	  pysal/__init__.py,
	  pysal/spatial_dynamics/rank.py: - update user tutorial and __init__

2012-07-13 19:33  sjsrey@gmail.com

	* pysal/spatial_dynamics/rank.py,
	  pysal/spatial_dynamics/tests/test_rank.py: - O(n log n) algorithm for spatial tau (old one was O(n^2)) - closing ticket http://code.google.com/p/pysal/issues/detail?id=83

2012-07-13 17:57  schmidtc

	* pysal/core/IOHandlers/pyDbfIO.py,
	  pysal/core/IOHandlers/tests/test_pyDbfIO.py: Adding better support for writing Null values to DBF.  See issue #193

2012-07-13 15:55  schmidtc

	* pysal/core/util/shapefile.py,
	  pysal/core/util/tests/test_shapefile.py: Cleaning up support for ZM points, polylines and polygons in the shapefile reader. Added unit tests for same.

2012-07-13 15:42  sjsrey@gmail.com

	* doc/source/library/esda/gamma.txt: - update version info 

2012-07-13 15:37  sjsrey@gmail.com

	* doc/source/library/esda/gamma.txt,
	  doc/source/library/esda/index.txt: - adding gamma to api docs

2012-07-13 00:21  sjsrey@gmail.com

	* pysal/esda/gamma.py: optimizations 

2012-07-12 21:28  schmidtc

	* pysal/core/IOHandlers/pyDbfIO.py: Disabling mising value warning for DBF files.  See issue #185

2012-07-12 21:07  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py,
	  pysal/cg/tests/test_segmentLocator.py,
	  pysal/contrib/spatialnet/spatialnet.py: Adding unittests for segmentLocator (including one that fails see #211). Added VerticalLine class to represent verticle LineSegments. Updated __all__ in segmentLocator. Minor comment formatting in spatialnet.

2012-07-12 19:41  lanselin@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: tutorial for gamma index

2012-07-12 19:40  lanselin@gmail.com

	* pysal/esda/gamma.py,
	  pysal/esda/tests/test_gamma.py: gamma with generic function

2012-07-12 14:17  sjsrey@gmail.com

	* pysal/__init__.py: - gamma index added

2012-07-12 03:14  lanselin@gmail.com

	* pysal/esda/tests/test_gamma.py: tests for gamma

2012-07-12 03:13  lanselin@gmail.com

	* pysal/esda/gamma.py: gamma index of spatial autocorrelation

2012-07-12 03:11  lanselin@gmail.com

	* pysal/esda/__init__.py: gamma index 

2012-07-11 21:32  lanselin@gmail.com

	* pysal/esda/join_counts.py,
	  pysal/esda/tests/test_join_counts.py: join counts without analytical results, new permutation 

2012-07-11 21:32  lanselin@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: updated docs for join counts

2012-07-10 21:13  lanselin@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: docs for join count in autocorrelation

2012-07-10 21:12  lanselin@gmail.com

	* pysal/esda/join_counts.py,
	  pysal/esda/tests/test_join_counts.py: additional test in join counts, docs added

2012-07-10 19:24  lanselin@gmail.com

	* pysal/esda/join_counts.py,
	  pysal/esda/tests/test_join_counts.py: join counts with permutations for BB, updated tests to include permutations

2012-07-09 04:22  sjsrey

	* pysal/weights/weights.py:
	  - fixing bug luc identified with regard to mean_neighbor property.  wrong key name was used in cache dictionary.  

2012-07-07 17:00  sjsrey

	* pysal/__init__.py: update for spreg and contrib inclusion


2012-07-07 16:51  sjsrey

	* pysal/spatial_dynamics/markov.py: - updating doc strings

2012-07-07 16:17  sjsrey

	* pysal/spreg/probit.py:
	  - fixing doc string and refs 

2012-07-06 21:58  dfolch

	* doc/source/library/spreg/probit.txt: txt file to include probit in the HTML docs

2012-07-06 21:11  dfolch

	* pysal/spreg/tests/test_ols_sparse.py: fixing unittest error; still no solution to scientific notation formatting in doctests

2012-07-06 20:24  dfolch

	* pysal/spreg/__init__.py,
	  pysal/spreg/diagnostics.py,
	  pysal/spreg/diagnostics_sp.py,
	  pysal/spreg/diagnostics_tsls.py,
	  pysal/spreg/error_sp.py,
	  pysal/spreg/error_sp_het.py,
	  pysal/spreg/error_sp_hom.py,
	  pysal/spreg/ols.py,
	  pysal/spreg/probit.py,
	  pysal/spreg/robust.py,
	  pysal/spreg/summary_output.py,
	  pysal/spreg/tests/test_diagnostics.py,
	  pysal/spreg/tests/test_diagnostics_sp.py,
	  pysal/spreg/tests/test_diagnostics_tsls.py,
	  pysal/spreg/tests/test_error_sp.py,
	  pysal/spreg/tests/test_error_sp_het.py,
	  pysal/spreg/tests/test_error_sp_het_sparse.py,
	  pysal/spreg/tests/test_error_sp_hom.py,
	  pysal/spreg/tests/test_error_sp_hom_sparse.py,
	  pysal/spreg/tests/test_error_sp_sparse.py,
	  pysal/spreg/tests/test_ols.py,
	  pysal/spreg/tests/test_ols_sparse.py,
	  pysal/spreg/tests/test_probit.py,
	  pysal/spreg/tests/test_twosls.py,
	  pysal/spreg/tests/test_twosls_sp.py,
	  pysal/spreg/tests/test_twosls_sp_sparse.py,
	  pysal/spreg/tests/test_twosls_sparse.py,
	  pysal/spreg/twosls.py,
	  pysal/spreg/twosls_sp.py,
	  pysal/spreg/user_output.py,
	  pysal/spreg/utils.py: -Adding classic probit regression class -Adding spatial diagnostics for probit -Allowing x parameter to be either a numpy array or scipy sparse matrix in all regression classes -Adding additional unit tests -Various refactoring to streamline code base and improve long term maintainability -Contributions from Luc Anselin, Pedro Amaral, Daniel Arribas-Bel, David Folch and Nicholas Malizia

2012-07-03 18:59  sjsrey

	* pysal/spatial_dynamics/markov.py,
	  pysal/spatial_dynamics/tests/test_markov.py: - refactor significant move_types for clarity and fixing a logic bug


2012-06-20 04:50  sjsrey@gmail.com

	* doc/source/developers/docs/index.txt:
	  - added section for how to write a tutorial for new modules 
2012-06-20 02:45  sjsrey

	* doc/source/developers/docs/index.txt:
	  - updating doc building instructions

2012-06-06 18:58  phil.stphns

	* .build-osx10.6-py26.sh,
	  .build-osx10.6-py27.sh:
	  - local modifications for Frameworks builds

2012-06-05 20:56  phil.stphns

	* .build-osx10.6-py26.sh,
	  .build-osx10.6-py27.sh,
	  .build-osx10.7-py27.sh, .runTests.sh:
	  - adding experimental build and test scripts.

2012-06-05 16:43  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py,
	  pysal/contrib/spatialnet/spatialnet.py:
	  initial snap function for spatialnet

2012-06-05 16:38  schmidtc

	* pysal/core/IOHandlers/pyShpIO.py,
	  pysal/core/util/shapefile.py,
	  pysal/core/util/tests/test_shapefile.py: Adding PolygonZ support to Shapefile IO

2012-05-24 21:57  sjsrey

	* pysal/esda/mapclassify.py: - truncate option for fisher_jenks sampling

2012-05-15 20:08  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py: Added query to SegmentLocator

2012-05-11 22:17  sjsrey

	* pysal/esda/mapclassify.py: - added Fisher_Jenks_Sampled

2012-05-11 00:45  mhwang4

	* pysal/contrib/network/distances.csv,
	  pysal/contrib/network/simulator.py,
	  pysal/contrib/network/test_lincs.py,
	  pysal/contrib/network/test_weights.py,
	  pysal/contrib/network/weights.py: adding test code for distance-file-based weight generator; updates on simulator 

2012-05-10 22:37  mhwang4

	* pysal/contrib/network/klincs.py,
	  pysal/contrib/network/lincs.py,
	  pysal/contrib/network/test_klincs.py,
	  pysal/contrib/network/test_lincs.py: adding test code for network-constrained lisa

2012-05-10 21:11  mhwang4

	* pysal/contrib/network/crimes.dbf,
	  pysal/contrib/network/crimes.shp,
	  pysal/contrib/network/crimes.shx,
	  pysal/contrib/network/test_klincs.py: test code for local K function

2012-05-08 18:05  mhwang4

	* pysal/contrib/network/streets.dbf,
	  pysal/contrib/network/streets.shp,
	  pysal/contrib/network/streets.shx,
	  pysal/contrib/network/test_network.py: adding a test data set

2012-05-08 16:34  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py,
	  pysal/core/FileIO.py: Adding start of segmentLocator, adding minimal slicing support to FileIO


2012-05-03 17:03  schmidtc

	* pysal/cg/shapes.py,
	  pysal/cg/tests/test_shapes.py: Adding solve for x support to Line. Cleaning up LineSegment's Line method.

2012-04-20 17:48  schmidtc

	* pysal/cg/shapes.py: adding arclen method to Chain object.

2012-04-19 16:37  dfolch

	* pysal/weights/Distance.py: reducing number of distance queries in Kernel from n^2 to n

2012-04-17 21:20  schmidtc

	* pysal/contrib/spatialnet/spatialnet.py: adding distance

2012-04-17 19:46  schmidtc

	* pysal/contrib/spatialnet/cleanNetShp.py,
	  pysal/contrib/spatialnet/spatialnet.py: Adding FNODE/TNODE to dbf when cleaning shapefiles. Added util function createSpatialNetworkShapefile Added SpatialNetwork class

2012-04-17 15:32  schmidtc

	* pysal/contrib/weights_viewer/weights_viewer.py: "revert back to the background when the point is outside of any unit" - request from serge

2012-04-11 02:50  schmidtc

	* pysal/cg/kdtree.py: Fixing user submitted bug,issue #206.

2012-04-10 22:00  dreamessence

	* pysal/weights/Wsets.py: Including w_clip in __all__

2012-04-10 21:58  dreamessence

	* pysal/weights/Wsets.py: Adding w_clip method to clip W matrices (sparse and/or pysal.W) with a second (binary) matrix

2012-04-10 21:57  schmidtc

	* pysal/contrib/spatialnet/beth_roads.shp,
	  pysal/contrib/spatialnet/beth_roads.shx,
	  pysal/contrib/spatialnet/cleanNetShp.py: Adding network shapefile cleaning tools and temporary sample data.  

2012-04-10 21:48  sjsrey

	* pysal/contrib/spatialnet/util.py: - more stubs for util mod

2012-04-10 19:58  sjsrey

	* pysal/contrib/spatialnet/util.py: - start of util module

2012-04-03 20:43  sjsrey

	* pysal/contrib/spatialnet: - new contrib module - integrate geodanet functional (move over from network) - wrap networkx

2012-04-03 01:21  schmidtc

	* pysal/cg/rtree.py: Adding pickle support to RTree


2012-03-28 23:27  mhwang4 
	* pysal/contrib/network/kernel.py,
	  pysal/contrib/network/kfuncs.py,
	  pysal/contrib/network/test_access.py,
	  pysal/contrib/network/test_kernel.py,
	  pysal/contrib/network/test_kfuncs.py,
	  pysal/contrib/network/test_network.py: adding examples for network-related modules

2012-03-19 15:33  schmidtc

	* pysal/core/IOHandlers/pyDbfIO.py: Adding support for writing Null dates

2012-03-14 21:04  phil.stphns

	* doc/source/developers/testing.txt,
	  doc/source/users/installation.txt: Small changes to user install instructions to highlight the ease with which pysal can be installed ;-> And, developer instructions for running the test suite from within a session if desired.

2012-03-03 00:00  phil.stphns

	* pysal/spatial_dynamics/markov.py: Potential source of dev docs pngmath latex fail.

2012-02-24 23:29  mhwang4

	* pysal/contrib/network/network.py: fixing bug in network.py

2012-02-20 19:50  phil.stphns

	* doc/source/developers/py3k.txt: Developer doc to explain setting up PySAL for Python3.

2012-02-20 16:18  schmidtc

	* pysal/esda/__init__.py: removing invalid __all__ from esda's init.  See #194

2012-02-16 23:15  phil.stphns

	* pysal/__init__.py,
	  pysal/core/util/shapefile.py: Minor changes to imports that cause py3tool to stumble.

2012-02-15 23:16  phil.stphns

	* doc/source/developers/py3k.txt,
	  doc/source/users/installation.txt: Modified links in user installation instructions.  Added more steps for developers setting up Python3 dev environments on OSX.

2012-02-14 21:55  schmidtc

	* pysal/esda/getisord.py: fixing side effect caused when changing the shape of y, creating a new view with reshape instead.

2012-02-14 21:21  schmidtc

	* pysal/esda/getisord.py: optimizing G_Local

2012-02-14 20:37  schmidtc

	* pysal/esda/getisord.py: optimizing G

2012-02-14 00:21  phil.stphns

	* doc/source/developers/index.txt,
	  doc/source/developers/py3k.txt,
	  doc/source/developers/release.txt: Adding early docs on Python 3 support. Modifying release instructions.

# v<1.3.0>, 2012-01-31

    * core/IOHandlers/pyDbfIO.py: Addressing issue #186

    * cg/shapes.py: fixing small bug in polygon constructor that causes
      an exception when an empty list is passed in for the holes.

    * cg/standalone.py: removing standalone centroid method. see issue
      #138.

    * esda/mapclassify.py, esda/tests/test_mapclassify.py: - new
      implementation of fisher jenks

    * spreg/__init__.py, spreg/diagnostics_sp.py,
      spreg/diagnostics_tsls.py, spreg/error_sp.py,
      spreg/error_sp_het.py, spreg/error_sp_hom.py, spreg/ols.py,
      spreg/robust.py, spreg/tests, spreg/twosls.py,
      spreg/twosls_sp.py, spreg/user_output.py, spreg/utils.py: Adding
      the following non-spatial/spatial regression modules:
      * Two Stage Least Squares
      * Spatial Two Stage Least Squares
      * GM Error (KP 98-99)
      * GM Error Homoskedasticity (Drukker et. al, 2010)
      * GM Error Heteroskedasticity (Arraiz et. al, 2010)
      * Anselin-Kelejian test for residual spatial autocorrelation of
      residuals from IV regression
      
      Adding also utility functions and other helper classes.
      
    * cg/standalone.py: slight improvment to get_shared_segments, in
      part to make it more readable.

    * cg/shapes.py, cg/tests/test_standalone.py: adding <,<=,>,>= tests
      to Point, this fixes a bug in the get_shared_segments function
      that was causing some LineSegments to be incorectly ordered
      because the default memory address was being used instead of the
      points location.

    * core/IOHandlers/tests/test_wkt.py, core/IOHandlers/wkt.py,
      core/util/tests/test_wkt.py, core/util/wkt.py,
      weights/tests/test_Distance.py, weights/tests/test_user.py,
      weights/user.py: Fixing small numerical errors n testing that
      resulted from changing the centroid algorithm.

    * esda/moran.py: another optimization for __crand see issue #188

    * weights/util.py: Added option for row-standardized SW in lat2SW.
      Implementing suggestion from Charlie in Issue 181 from
      StackOverflow

    * esda/moran.py: another optimization to __crand, see issue #188
      for details.

    * esda/moran.py: Optimized __crand in Local_Moran

    * cg/shapes.py, cg/standalone.py, contrib/shapely_ext.py:
      Adddressing issue #138, centroids for polygons with holes
      Fixing some issues with the shapely wrapper and out implemenation
      of __geo_interface__

    * weights/Distance.py: previous 'fix' to uniform kernel did not
      have correct dimensions

    * core/IOHandlers/arcgis_txt.py, core/IOHandlers/dat.py,
      weights/user.py: fixing rounding errors with docstrings

    * contrib/README, contrib/shared_perimeter_weights.py: Adding
      shared perimeter weights, see Issue #46

    * contrib/README, contrib/shapely_ext.py: moving shapely_ext into
      contrib

    * core/IOHandlers/pyDbfIO.py: Fixing issue with scientific notation
      is DBF files. #182

    * core/IOHandlers/pyShpIO.py: clockwise testing should only be
      performed on Polygons. #183

    * spreg/diagnostics_sp.py: Switching ints to floats in variance of
      Morans I for residuals to get correct results

    * core/util/shapefile.py, examples/__init__.py: Add a "get_path"
      function to examples module.
      pysal.examples.get_path('stl_hom.shp') will always return the
      correct system path to stl_hom.shp, no matter where it's run
      from. This is useful for testing.
      Modified shapefile tests to use the new function.

    * spreg/diagnostics.py: Adding check on condition_index to pick OLS
      (xtx) or IV (hth) model

    * core/IOHandlers/template.py: Updating template to pass unit
      testing.

    * core/util/shapefile.py: Fixing issue #180. Making shapefile
      opener case insensitive.

    * spatial_dynamics/interaction.py,
      spatial_dynamics/tests/test_interaction.py: Adding modified Knox
      and changes to existing tests in spatial_dynamics.

    * core/IOHandlers/arcgis_txt.py,
      core/IOHandlers/tests/test_arcgis_txt.py: fixing arcgis_txt.py so
      that it ignores self-neighbors with zero weights

    * core/FileIO.py: Updating library README.
      Removing docstrings from FileIO module.

    * contrib/README: adding contrib to installer and adding initial
      README

    * core/IOHandlers/gwt.py: rewrote GWT reader to avoid list appends.
      resulted in speed up of about 12x.

    * core/IOHandlers/pyDbfIO.py: implementing _get_col for dbf files.

    * core/IOHandlers/gwt.py: Adding a small fix to gwt reader, if the
      ids cannot be found in the associated DBF, they will be read in
      order from the GWT file.

    * contrib/weights_viewer/weights_viewer.py: Small change to
      identify polygons that are their own neighbor.

    * weights/Distance.py: removing incorrect kernel functions and
      fixing bug in uniform kernel

    * weights/util.py: refactoring insert_diagonal so that it can add
      or overwrite the diagonal weights

    * contrib, contrib/README, contrib/__init__.py,
      contrib/weights_viewer, contrib/weights_viewer/__init__.py,
      contrib/weights_viewer/transforms.py,
      contrib/weights_viewer/weights_viewer.py: Adding 1st contrib, a
      wxPython based Weights file viewer.


    * spatial_dynamics/markov.py: - handle case of zero transitions in
      spatial markov, consistent with treatment
      in classic markov

    * core/FileIO.py, core/IOHandlers/pyShpIO.py: Changes to allow
      reading of null polygons.

    * core/util/shapefile.py, core/util/tests/test_shapefile.py:
      refactoring shapefile reader, see issue #89

    * core/FileIO.py: small change to FileIO to allow FileFormat
      argument to be passed through

    * esda/getisord.py: fixing bug in local Z values for integer data

    * cg/__init__.py, weights/user.py, weights/util.py: adding radius
      option to user weights methods

    * cg/kdtree.py, common.py, weights/Distance.py,
      weights/tests/test_Distance.py: Distance weights can not be
      passed an instnace of KDTree instead of an array. If the KDTree
      is of type ArcKDTree, the weights returns will be based on
      ArcDistances. Adding tests for Arc cases off KNN and
      DistanceBand.

    * weights/util.py: - added function for local clustering
      coefficient - summary for W as a graph

    * cg/kdtree.py, cg/sphere.py: finishing up Arc_KDTree

    * weights/Distance.py: More doctest fixes.

    * region/maxp.py, spreg/diagnostics.py, weights/Distance.py,
      weights/user.py: Fixing the doctests for dusty python setup.

    * cg/kdtree.py, cg/sphere.py: adding spherical wrapper around scipy
      kdtree

    * cg/__init__.py, cg/sphere.py: Adding spherical distance tools to
      cg. Related to issue #168

    * core/IOHandlers/gwt.py, core/IOHandlers/tests/test_gwt.py:
      re-enabled gwt writing.
      'o' transform is used on all GWTs for writing (w is returned to
      existing transform on exit)
      Also, setting '_shpName' and '_varName' attributes on W's which
      are read in through gwt.
      the writer will check if these vars exist and use them for the
      header, this prevents metadata loss on simple copies

    * esda/join_counts.py: - fix for handling int array type

    * spreg/diagnostics.py: Adding more efficient constant check for
      spreg.

    * cg/shapes.py: adding __geo_interface__ and asShape adapter for
      Point, LineString and Polygon

    * spreg/diagnostics.py: minor change to t-stat function to
      accommodate future regression models

    * esda/mapclassify.py: - more general fix for #166


# v<1.2.0>, 2011-07-31

    * pysal/spreg/user_output.py: Fix for bug 162

    * pysal/spatial_dynamics/markov.py: Added markov mobility measures; addresses issue 137

    * pysal/weights/weights.py: Partially addressed issue 160 by removing the shimbel, order, and higher_order methods from W. 

    * doc/source/users/installation.txt: Adding known issue regarding GNU/Linux testing and random seeds; see ticket 52.

    * pysal/esda/geary.py: Adding sparse implementation of Geary's C; substantial gains on larger datasets. 

    * pysal/core/IOHandlers/mtx.py: Adding WSP2W function for fast conversion of sparse weights object (WSP) to pysal W.

    * pysal/esda/getisord.py: Adding Getis-Ord G test module

    * pysal/weights/util.py: Added function that inserts values along the main diagonal of a weights object

    * doc/source/users/tutorials: Fixed issue 76.

    * pysal/core/IOHandlers/mtx.py: Added an IOHandler for MatrixMarket MTX files

    * pysal/esda/moran.py: Optimized conditional randomization

    * pysal/weights/util.py: Re-adding full2W() method to convert full arrays into W objects; related to issue #136. 

    * pysal/core/IOHandlers/gal.py: Added sparse WSP (thin W); gal reader can return W or WSP

    * pysal/core/IOHandlers/pyDbfIO.py: Bug Fix, DBF files are not properly closed when opened in 'r' mode. See issue #155.

    * pysal/core/IOHandlers/stata_txt.py: Adding FileIO handlers for STATA text files

    * pysal/weights/user.py: Fixed issue #154, adding k option to User Kernel weights functions.

    * pysal/core/IOHandlers/mat.py: Adding an IOHandler for MATLAB mat file

    * pysal/core/IOHandlers/wk1.py: Adding an IO handler for wk1 file

    * pysal/core/IOHandlers/geobugs_txt.py: Adding an IO handler for geobugs text file.

    * pysal/core/IOHandlers/arcgis_swm.py: Added ArcGIS SWM file handler

    * pysal/core/IOHandlers/arcgis_dbf.py: Adding a spatial weights file in the (ArcGIS-style) DBF format. 

    * pysal/core/IOHandlers/arcgis_txt.py: Added ArcGIS ASCII file IO handler. 

    * pysal/core/IOHandlers/dat.py: Added DAT file handler.

    * pysal/cg/locators.py: Added point in polygon method for Polygon and PolygonLocator

    * pysal/weights/Distance.py: Optimized Kernel() method to run much faster for the case of adaptive bandwidths

    * pysal/weights/user.py: Added helper function in user.py to create scipy sparse matrix from a gal file

    * pysal/common.py: Added shallow copy method to Read-Only Dict to support multiprocessing.

    * pysal/spatial_dynamics/rank.py: More efficient regime weights

    * pysal/weights/Distance.py: Adding epanechnikov and bisquare kernel funtions

    * pysal/core/IOHandlers/pyDbfIO.py: Adding NULL support to numerical DBF fields; modifying PointLocator API to match PolygonLocator API 

    * pysal/cg/locators.py: Handles case when query rectangle is completely inside a polygon

    * pysal/cg/locators.py: Explicit polygon overlap hit test

    * pysal/cg/standalone.py: Adding point-polygon intersection support for polygons with holes.

    * pysal/spatial_dynamics/markov.py: Added homogeneity test.

    * pysal/spatial_dynamics/markov.py: Added spillover test in LISA_Markov.

    * pysal/cg/locators.py: Added Rtree based spatial index for polygonlocator.

    * pysal/cg/rtree.py: Added pure python Rtree module.

    * doc/source/developers/pep/pep-0010.txt: Added PEP 0010: Rtree module in pure python.

    * pysal/esda/geary.py: Fixed bug 144.

    * pysal/spatial_dynamics/markov.py: Added significance filtering of LISA markov.

    * doc/source/developers/pep/pep-0009.txt: Added new PEP, "PEP 0009: Add Python 3.x Support."

    * doc/source/developers/guidelines.txt: New release cycle schedules for 1.2 and 1.3.

    * doc/source/developers/release.txt: Updated pypi instructions; PySAL available on the Python Package Index via download, easy_install, and pip. 

# v<1.1.0>, 2011-01-31

    * pysal/core/FileIO.py, pysal/core/IOHandlers/pyDbfIO.py: Added missing value support to FileIO. Warnings will be issued when missing values are found and the value will be set to pysal.MISSINGVALUE, currently None, but the user can change it as needed.

    * pysal/spreg/: Added Spatial Regression module, spreg, and tests.  Added non-spatial diagnostic tests for OLS regression. 

    * pysal/core/IOHandlers/gwt.py: Fixing bottle neck in gwt reader, adding support for GeoDa Style ID's and DBF id_order.

    * pysal/cg/standalone.py: adding, distance_matrix, full distance matrix calculation using sparse matrices

    * pysal/core/util: Moved "converters" into core.util, allows them to be used independently of FileIO.

    * pysal/weights/Distance.py: Adding work around for bug in scipy spatial, see pysal issue #126

    * pysal/weights/user.py: Added build_lattice_shapefile in weights.user, which writes an ncol by nrow grid to a shapefile.

    * pysal/weights/Distance.py: fixed coincident point problem in knnW and made sure it returns k neighbors 
    * pysal/spatial_dynamics/interaction.py: Added a suite of spatio-temporal interaction tests including the Knox, Mantel, and Jacquez tests. 

    * pysal/weights/util.py: Added lat2SW, allows to create a sparse W matrix for a regular lattice.

    * pysal/tests/tests.py: - new 1.1 integration testing scheme.

    * pysal/esda/interaction.py: added standardized Mantel test and improved readability.

    * pysal/spatial_dynamics/directional.py: - adding directional LISA analytics

    * pysal/esda/mapclassify.py: Natural_Breaks will lower k for data with fewer than k unique values, prints warning.

    * pysal/region/randomregion.py: improvements to spatially constrained random region algorithm

    * pysal/esda/smoothing.py: Adding choynowski probabilities and SMR to smoothing.py

    * doc/source/developers/release.txt: - updating release cycle - release management

# v<1.0.0>, 2010-07-31 -- Initial release.

The following 13 authors contributed 216 commits.

* Dani Arribas-Bel
* David Folch
* Levi John Wolf
* Levi Wolf
* Philip Stephens
* Serge Rey
* Sergio Rey
* Wei Kang
* jlaura
* levi.john.wolf@gmail.com
* ljw
* ljwolf
* pedrovma


We closed a total of 86 issues, 33 pull requests and 53 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (33):

* :ghpull:`724`: add synchronization tool
* :ghpull:`733`: Fb/bump
* :ghpull:`731`: Small docfixes
* :ghpull:`730`: Contrib docs
* :ghpull:`728`: B179
* :ghpull:`727`: Geodf io
* :ghpull:`725`: try pinning scipy,numpy
* :ghpull:`723`: make sure to test all moran classes
* :ghpull:`720`: Moving natural breaks to a cleaner kmeans implementation
* :ghpull:`718`: force counts to be same length as bins
* :ghpull:`714`: Dev
* :ghpull:`715`: Heads
* :ghpull:`713`: Enh712
* :ghpull:`710`: Patsy/Pandas wrapper
* :ghpull:`711`: Travis fixes
* :ghpull:`706`: precommit hook
* :ghpull:`707`: Keep dev updated with any bugfixes into master
* :ghpull:`702`: fix for chi2 test 0 denominator and invocation of chi2 test in LISA_Markov
* :ghpull:`704`: Allcloser
* :ghpull:`703`: Swapping to Allclose and RTOL=.00005 in spreg
* :ghpull:`701`: By col array
* :ghpull:`700`: small optimization of bivariate moran motivated by #695
* :ghpull:`696`: Pypi
* :ghpull:`691`: Update doctest for one-off bug that was fixed with #690
* :ghpull:`690`: fix for lisa markov one off for significance indicator
* :ghpull:`689`: Clpy flex w
* :ghpull:`688`: pep 8 edits
* :ghpull:`687`: Change array assertions into allclose
* :ghpull:`686`: Moran local bivariate
* :ghpull:`684`: 591
* :ghpull:`682`: release instructions updated
* :ghpull:`681`: version bump for next dev cycle
* :ghpull:`680`: Rel1.10

Issues (53):

* :ghissue:`705`: spreg check valve
* :ghissue:`344`: Explore new dependency on ogr
* :ghissue:`459`: Problem with bandwidth
* :ghissue:`552`: Viz organization
* :ghissue:`491`: Test np.allclose() for unit tests
* :ghissue:`529`: Clarity needed on proper reference formatting in sphinx docs
* :ghissue:`699`: Trouble importing pysal - ImportError: DLL load failed
* :ghissue:`716`: `min_threshold_dist_from_shapefile` creating an island in some cases
* :ghissue:`724`: add synchronization tool
* :ghissue:`733`: Fb/bump
* :ghissue:`731`: Small docfixes
* :ghissue:`730`: Contrib docs
* :ghissue:`719`: pysal not working with matplotlib v1.5 for plot_lisa_cluster, plot_choropleth, etc.
* :ghissue:`728`: B179
* :ghissue:`727`: Geodf io
* :ghissue:`725`: try pinning scipy,numpy
* :ghissue:`723`: make sure to test all moran classes
* :ghissue:`720`: Moving natural breaks to a cleaner kmeans implementation
* :ghissue:`717`: esda.mapclassify return problematic counts when there is 0 occurrence in the last class
* :ghissue:`718`: force counts to be same length as bins
* :ghissue:`714`: Dev
* :ghissue:`712`: `block_weights` does not take argument `idVariable`
* :ghissue:`715`: Heads
* :ghissue:`713`: Enh712
* :ghissue:`710`: Patsy/Pandas wrapper
* :ghissue:`711`: Travis fixes
* :ghissue:`706`: precommit hook
* :ghissue:`708`: 2-3: is six a dependency or do we ship it?
* :ghissue:`707`: Keep dev updated with any bugfixes into master
* :ghissue:`702`: fix for chi2 test 0 denominator and invocation of chi2 test in LISA_Markov
* :ghissue:`704`: Allcloser
* :ghissue:`703`: Swapping to Allclose and RTOL=.00005 in spreg
* :ghissue:`698`: Py3merge
* :ghissue:`701`: By col array
* :ghissue:`700`: small optimization of bivariate moran motivated by #695
* :ghissue:`695`: Bivariate global moran's I formula
* :ghissue:`683`: Py3 Conversion Project
* :ghissue:`694`: Allclose in SPREG
* :ghissue:`696`: Pypi
* :ghissue:`691`: Update doctest for one-off bug that was fixed with #690
* :ghissue:`693`: Trouble installation: No module named 'shapes'
* :ghissue:`690`: fix for lisa markov one off for significance indicator
* :ghissue:`689`: Clpy flex w
* :ghissue:`688`: pep 8 edits
* :ghissue:`685`: BV Lisa 
* :ghissue:`687`: Change array assertions into allclose
* :ghissue:`686`: Moran local bivariate
* :ghissue:`677`: Make meta importable from base
* :ghissue:`684`: 591
* :ghissue:`682`: release instructions updated
* :ghissue:`679`: pysal.cg.sphere.fast_knn bug
* :ghissue:`681`: version bump for next dev cycle
* :ghissue:`680`: Rel1.10

# v<1.10.0>, 2015-07-29

GitHub stats for 2015/01/31 - 2015/07/29

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 20 authors contributed 334 commits.

* Charlie Schmidt
* Dani Arribas-Bel
* Daniel Arribas-Bel
* David C. Folch
* David Folch
* Jay
* Levi John Wolf
* Marynia
* Philip Stephens
* Serge Rey
* Sergio Rey
* Taylor Oshan
* The Gitter Badger
* Wei Kang
* jay
* jlaura
* ljw
* ljwolf
* luc
* pedrovma


We closed a total of 156 issues, 58 pull requests and 98 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (58):

* :ghpull:`675`: Update README.md
* :ghpull:`673`: Adding init at pdutilities so they are importable
* :ghpull:`672`: ENH: option to locate legend
* :ghpull:`669`: add nonsudo travis
* :ghpull:`666`: Cleaned up conflicts in ref branch
* :ghpull:`664`: Lisa map
* :ghpull:`663`: Examples
* :ghpull:`661`: Reorganization of examples 
* :ghpull:`657`: Assuncao test division errors
* :ghpull:`649`: Add a Gitter chat badge to README.md
* :ghpull:`647`: Addresses 646
* :ghpull:`645`: Update to weights module documentation for PySAL-REST
* :ghpull:`644`: removed test print statements from df2dbf
* :ghpull:`643`: using dtypes.name in df2dbf to avoid gotcha in type
* :ghpull:`642`: Updating copyright year
* :ghpull:`634`: allows non-symmetric distance matrices
* :ghpull:`641`: turning off generatetree
* :ghpull:`592`: adding check for version #591
* :ghpull:`636`: vertical line point simulation
* :ghpull:`639`: Snapping
* :ghpull:`640`: Add users to travis
* :ghpull:`627`: Networkrb
* :ghpull:`631`: Fixing typoes in analysis.py
* :ghpull:`626`: cast arrays over inconsistent kdtree return types
* :ghpull:`620`: adding explicit check for random region contiguity
* :ghpull:`619`: Fixing spreg's warnings
* :ghpull:`618`: initial folder with dbf utilities using pandas
* :ghpull:`616`: Adding isolation and theil indices to inequality._indices.py
* :ghpull:`615`: Network docs
* :ghpull:`614`: cleaning up pr testing
* :ghpull:`613`: test coverage to 98% on network
* :ghpull:`612`: small change for testing PR
* :ghpull:`611`: stubbed in minimal tests
* :ghpull:`607`: B603
* :ghpull:`602`: Documentation Extraction Notebook
* :ghpull:`606`: pct_nonzero was reporting a ratio not a percentage
* :ghpull:`604`: Contribpush
* :ghpull:`601`: Documentation Cleanup
* :ghpull:`599`: Casting bugfix from #598
* :ghpull:`600`: Updates for coveralls
* :ghpull:`598`: IO in Python 3
* :ghpull:`597`: Decoupling bbox from map_XXX_poly
* :ghpull:`595`: Removed testing line in travis.yml and added a .coveragerc file to manag...
* :ghpull:`590`: using numpy sum method
* :ghpull:`589`: Wconstructor
* :ghpull:`588`: Coveralls
* :ghpull:`585`: Fisher Jenks bug in `plot_choropleth`
* :ghpull:`584`: Alpha in plot chor
* :ghpull:`583`: Fixed 576
* :ghpull:`580`: working on #576
* :ghpull:`578`: Fixes #577
* :ghpull:`574`: Handle case where a region has a 0 share.
* :ghpull:`571`: Dict to unique value mapper
* :ghpull:`570`: numpy doc cleanup for weights module
* :ghpull:`569`: folium viz scripts
* :ghpull:`568`: inline with numpy doc spec (spatial_dynamics module)
* :ghpull:`567`: New/masterbump
* :ghpull:`566`: Fix for 1.9.0 missing file in setup.py

Issues (98):

* :ghissue:`675`: Update README.md
* :ghissue:`658`: Travis.CI """Legacy""" architecture
* :ghissue:`667`: Examples Not Found
* :ghissue:`673`: Adding init at pdutilities so they are importable
* :ghissue:`672`: ENH: option to locate legend
* :ghissue:`669`: add nonsudo travis
* :ghissue:`671`: Shapefile Read - PolygonM Attribute Error
* :ghissue:`670`: examples README markdown files reformatting
* :ghissue:`668`: Wconstructor
* :ghissue:`666`: Cleaned up conflicts in ref branch
* :ghissue:`664`: Lisa map
* :ghissue:`662`: Pep8
* :ghissue:`665`: Refs
* :ghissue:`663`: Examples
* :ghissue:`573`: Examples
* :ghissue:`661`: Reorganization of examples 
* :ghissue:`656`: Assuncao rate improper division
* :ghissue:`657`: Assuncao test division errors
* :ghissue:`280`: handle multi-segment links in net_shp_io.py
* :ghissue:`649`: Add a Gitter chat badge to README.md
* :ghissue:`647`: Addresses 646
* :ghissue:`646`: arc distance in knnW
* :ghissue:`645`: Update to weights module documentation for PySAL-REST
* :ghissue:`644`: removed test print statements from df2dbf
* :ghissue:`643`: using dtypes.name in df2dbf to avoid gotcha in type
* :ghissue:`603`: Polygon.contains_point does not correctly process multipart polygons.
* :ghissue:`642`: Updating copyright year
* :ghissue:`623`: reading road shapfiles into network
* :ghissue:`608`: Scipy Sparse Graph
* :ghissue:`621`: network distance speedup
* :ghissue:`632`: network point snapping
* :ghissue:`633`: point to point distances on network
* :ghissue:`635`: simulating points on vertical lines
* :ghissue:`634`: allows non-symmetric distance matrices
* :ghissue:`641`: turning off generatetree
* :ghissue:`637`: speedup distance computations
* :ghissue:`592`: adding check for version #591
* :ghissue:`628`: Re-enable doctests
* :ghissue:`636`: vertical line point simulation
* :ghissue:`639`: Snapping
* :ghissue:`640`: Add users to travis
* :ghissue:`638`: Add users to Travis
* :ghissue:`627`: Networkrb
* :ghissue:`622`: New network branch from clean master
* :ghissue:`630`: NetworkG api is broken
* :ghissue:`631`: Fixing typoes in analysis.py
* :ghissue:`625`: Installation - Binstar and Anaconda
* :ghissue:`624`: Network topology
* :ghissue:`629`: changes to spreg tests for travis
* :ghissue:`166`: pysal.esda.mapclassify.Fisher_Jenks  -   local variable 'best' referenced before assignment
* :ghissue:`626`: cast arrays over inconsistent kdtree return types
* :ghissue:`596`: [question] unsupervised classification
* :ghissue:`620`: adding explicit check for random region contiguity
* :ghissue:`617`: Random_Region not respecting contiguity constraint
* :ghissue:`619`: Fixing spreg's warnings
* :ghissue:`618`: initial folder with dbf utilities using pandas
* :ghissue:`616`: Adding isolation and theil indices to inequality._indices.py
* :ghissue:`615`: Network docs
* :ghissue:`614`: cleaning up pr testing
* :ghissue:`613`: test coverage to 98% on network
* :ghissue:`612`: small change for testing PR
* :ghissue:`611`: stubbed in minimal tests
* :ghissue:`607`: B603
* :ghissue:`602`: Documentation Extraction Notebook
* :ghissue:`606`: pct_nonzero was reporting a ratio not a percentage
* :ghissue:`605`: RTree Weights
* :ghissue:`604`: Contribpush
* :ghissue:`601`: Documentation Cleanup
* :ghissue:`554`: Beginning documentation cleanup
* :ghissue:`599`: Casting bugfix from #598
* :ghissue:`600`: Updates for coveralls
* :ghissue:`598`: IO in Python 3
* :ghissue:`597`: Decoupling bbox from map_XXX_poly
* :ghissue:`595`: Removed testing line in travis.yml and added a .coveragerc file to manag...
* :ghissue:`586`: Look at using Coveralls
* :ghissue:`590`: using numpy sum method
* :ghissue:`589`: Wconstructor
* :ghissue:`588`: Coveralls
* :ghissue:`576`: Predecessor lists inconsistencies
* :ghissue:`585`: Fisher Jenks bug in `plot_choropleth`
* :ghissue:`584`: Alpha in plot chor
* :ghissue:`583`: Fixed 576
* :ghissue:`582`: Fixes #576
* :ghissue:`581`: Network
* :ghissue:`580`: working on #576
* :ghissue:`575`: Network from Lattice
* :ghissue:`578`: Fixes #577
* :ghissue:`577`: bug in FileIO.cast
* :ghissue:`574`: Handle case where a region has a 0 share.
* :ghissue:`343`: Edge Segmentation
* :ghissue:`571`: Dict to unique value mapper
* :ghissue:`570`: numpy doc cleanup for weights module
* :ghissue:`569`: folium viz scripts
* :ghissue:`568`: inline with numpy doc spec (spatial_dynamics module)
* :ghissue:`567`: New/masterbump
* :ghissue:`564`: Bug in setup.py
* :ghissue:`566`: Fix for 1.9.0 missing file in setup.py
* :ghissue:`565`: Bsetup


# v<1.9.1>, 2015-01-31

GitHub stats for 2015/01/30 - 2015/01/31 

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 4 authors contributed 14 commits.

* Dani Arribas-Bel
* Serge Rey
* Sergio Rey
* jlaura


We closed a total of 8 issues, 3 pull requests and 5 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (3):

* :ghpull:`566`: Fix for 1.9.0 missing file in setup.py
* :ghpull:`563`: Updating release instructions
* :ghpull:`561`: Rolling over to 1.10

Issues (5):

* :ghissue:`566`: Fix for 1.9.0 missing file in setup.py
* :ghissue:`565`: Bsetup
* :ghissue:`563`: Updating release instructions
* :ghissue:`562`: adjustments to release management
* :ghissue:`561`: Rolling over to 1.10


# v<1.9.0>, 2015-01-30

GitHub stats for 2014/07/25 - 2015/01/30 

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 12 authors contributed 131 commits.

* Andy Reagan
* Dani Arribas-Bel
* Jay
* Levi John Wolf
* Philip Stephens
* Qunshan
* Serge Rey
* jlaura
* ljwolf
* luc


We closed a total of 113 issues, 44 pull requests and 69 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (44):

* :ghpull:`560`: modifying import scheme for network module
* :ghpull:`559`: Network2
* :ghpull:`558`: Network2
* :ghpull:`557`: Network2
* :ghpull:`556`: Added analytical functions and edge segmentation
* :ghpull:`550`: Network2
* :ghpull:`553`: correction in denominator of spatial tau. 
* :ghpull:`547`: Updates to get network integrated
* :ghpull:`544`: update .gitignore
* :ghpull:`543`: k nearest neighbor gwt example file for baltimore points (with k=4) added to examples directory
* :ghpull:`542`: new format nat_queen.gal file added to examples directory
* :ghpull:`541`: Update tutorial docs for new book
* :ghpull:`540`: doc: updating instructions for anaconda and enthought
* :ghpull:`539`: doc: pysal is now on sagemathcloud
* :ghpull:`538`: Clean up of cg and fixes of other doctests/formats
* :ghpull:`536`: adding entry for getis ord module
* :ghpull:`537`: new opendata module for contrib
* :ghpull:`535`: Add method for extracting data columns as Numpy array rather than list
* :ghpull:`534`: added geogrid to __all__ in sphere.py
* :ghpull:`533`: added geogrid function to create a grid of points on a sphere
* :ghpull:`532`: new functions to deal with spherical geometry: lat-lon conversion, degre...
* :ghpull:`530`: I390
* :ghpull:`528`: Replacing 0 by min value in choropleths
* :ghpull:`526`: B166
* :ghpull:`525`: copyright update
* :ghpull:`524`: New homogeneity tests for general case and spatial markov as a special case
* :ghpull:`523`: pointing to github.io pages
* :ghpull:`520`: Same typo. Toolkit.
* :ghpull:`518`: Update util.py
* :ghpull:`519`: Typo
* :ghpull:`517`: Documentation correction for Prais Conditional Mobility Index
* :ghpull:`516`: ENH for https://github.com/PySAL/PySAL.github.io/issues/17
* :ghpull:`515`: BUG: conditional check for extension of lower bound of colorbar to conta...
* :ghpull:`514`: ENH: adding the user_defined classification
* :ghpull:`513`: rewriting to not use ipython notebook --pylab=line
* :ghpull:`512`: Viz
* :ghpull:`508`: Adding barebones pysal2matplotlib options in viz
* :ghpull:`511`: DOC updating news
* :ghpull:`507`: Sched
* :ghpull:`510`: BUG: fix for #509
* :ghpull:`506`: 1.9dev
* :ghpull:`505`: REL bumping master to 1.9.0dev
* :ghpull:`504`: Release prep 1.8
* :ghpull:`503`: Grid for landing page

Issues (69):

* :ghissue:`560`: modifying import scheme for network module
* :ghissue:`559`: Network2
* :ghissue:`558`: Network2
* :ghissue:`557`: Network2
* :ghissue:`556`: Added analytical functions and edge segmentation
* :ghissue:`555`: Added edge segmentation by distance
* :ghissue:`550`: Network2
* :ghissue:`553`: correction in denominator of spatial tau. 
* :ghissue:`549`: Network2
* :ghissue:`547`: Updates to get network integrated
* :ghissue:`548`: Installation Issues
* :ghissue:`546`: Network2
* :ghissue:`545`: Network
* :ghissue:`544`: update .gitignore
* :ghissue:`543`: k nearest neighbor gwt example file for baltimore points (with k=4) added to examples directory
* :ghissue:`542`: new format nat_queen.gal file added to examples directory
* :ghissue:`541`: Update tutorial docs for new book
* :ghissue:`540`: doc: updating instructions for anaconda and enthought
* :ghissue:`539`: doc: pysal is now on sagemathcloud
* :ghissue:`538`: Clean up of cg and fixes of other doctests/formats
* :ghissue:`536`: adding entry for getis ord module
* :ghissue:`537`: new opendata module for contrib
* :ghissue:`535`: Add method for extracting data columns as Numpy array rather than list
* :ghissue:`534`: added geogrid to __all__ in sphere.py
* :ghissue:`533`: added geogrid function to create a grid of points on a sphere
* :ghissue:`532`: new functions to deal with spherical geometry: lat-lon conversion, degre...
* :ghissue:`390`: add option to have local moran quadrant codes align with geoda
* :ghissue:`530`: I390
* :ghissue:`528`: Replacing 0 by min value in choropleths
* :ghissue:`526`: B166
* :ghissue:`176`: contrib module for proj 4
* :ghissue:`178`: contrib module for gdal/org
* :ghissue:`203`: implement network class in spatialnet
* :ghissue:`204`: pysal-networkx util functions
* :ghissue:`209`: csv reader enhancement
* :ghissue:`215`: Add a tutorial for the spreg module
* :ghissue:`244`: ps.knnW_from_shapefile returns wrong W ids when idVariable specified
* :ghissue:`246`: Only use idVariable in W when writing out to file
* :ghissue:`283`: Create new nodes at intersections of edges
* :ghissue:`291`: Enum links around regions hangs
* :ghissue:`292`: Handle multiple filaments within a region in the Wed construction
* :ghissue:`302`: Handle hole polygons when constructing wed
* :ghissue:`309`: Develop consistent solution for precision induced errors in doctests across platforms
* :ghissue:`350`: reading/writing weights file with spaces in the ids
* :ghissue:`450`: x_name and summary method not consistent in ols
* :ghissue:`521`: Nosetests don't accept setup.cfg
* :ghissue:`509`: ESDA bin type inconsistency
* :ghissue:`525`: copyright update
* :ghissue:`524`: New homogeneity tests for general case and spatial markov as a special case
* :ghissue:`523`: pointing to github.io pages
* :ghissue:`520`: Same typo. Toolkit.
* :ghissue:`522`: Nosetests for python3 porting
* :ghissue:`518`: Update util.py
* :ghissue:`519`: Typo
* :ghissue:`517`: Documentation correction for Prais Conditional Mobility Index
* :ghissue:`516`: ENH for https://github.com/PySAL/PySAL.github.io/issues/17
* :ghissue:`515`: BUG: conditional check for extension of lower bound of colorbar to conta...
* :ghissue:`514`: ENH: adding the user_defined classification
* :ghissue:`513`: rewriting to not use ipython notebook --pylab=line
* :ghissue:`512`: Viz
* :ghissue:`508`: Adding barebones pysal2matplotlib options in viz
* :ghissue:`511`: DOC updating news
* :ghissue:`507`: Sched
* :ghissue:`510`: BUG: fix for #509
* :ghissue:`502`: spreg.ml_lag.ML_Lag is very very very time-consuming?
* :ghissue:`506`: 1.9dev
* :ghissue:`505`: REL bumping master to 1.9.0dev
* :ghissue:`504`: Release prep 1.8
* :ghissue:`503`: Grid for landing page


# v<1.8.0>, 2014-07-25

GitHub stats for 2014/01/29 - 2014/07/25 

These lists are automatically generated, and may be incomplete or contain duplicates.

The following 8 authors contributed 281 commits.

* Dani Arribas-Bel
* Jay
* Philip Stephens
* Serge Rey
* Sergio Rey
* jlaura
* pedrovma
* sjsrey


We closed a total of 160 issues, 60 pull requests and 100 regular issues;
this is the full list (generated with the script 
:file:`tools/github_stats.py`):

Pull Requests (60):

* :ghpull:`503`: Grid for landing page
* :ghpull:`501`: Two figs rather than three
* :ghpull:`500`: More efficient higher order operations
* :ghpull:`499`: renamed nat_queen.gal for #452
* :ghpull:`497`: ENH Deprecation warning for regime_weights #486
* :ghpull:`494`: Enables testing against two versions of SciPy shipped with the last two Ubuntu LTS versions.
* :ghpull:`490`: Fix for #487
* :ghpull:`492`: BUG cleaning up temporary files for #398
* :ghpull:`493`: Phil: Skipping several tests that fail due to precision under older scipy
* :ghpull:`489`: test suite fixes
* :ghpull:`488`: More tests to skip if scipy less than 11
* :ghpull:`484`: ENH: cleaning up more test generated files
* :ghpull:`483`: Forwarding Phil's commit: skipping doctests, conditional skip of unit tests
* :ghpull:`482`: DOC cleaning up files after running doctests #398
* :ghpull:`481`: DOC contrib updates and links
* :ghpull:`480`: DOC cleaning up doctests
* :ghpull:`479`: ENH Changing regime_weights to block_weights for #455
* :ghpull:`478`: DOC: link fixes
* :ghpull:`477`: cKDTree for #460
* :ghpull:`476`: redefining w.remap_ids to take only a single arg
* :ghpull:`475`: Adding docstrings and error check to fix #471
* :ghpull:`470`: fixing order of args for api consistency. 
* :ghpull:`469`: Idfix for #449
* :ghpull:`463`: updating gitignore
* :ghpull:`462`: ENH: handle the case of an ergodic distribution where one state has 0 probability
* :ghpull:`458`: ENH: Vagrantfile for PySAL devs and workshops
* :ghpull:`447`: Clusterpy
* :ghpull:`456`: BUG: fix for #451 handling W or WSP in higher_order_sp
* :ghpull:`454`: Foobar
* :ghpull:`443`: Updating spreg: several minor bug and documentation fixes.
* :ghpull:`453`: Resolving conflicts
* :ghpull:`448`: Wsp
* :ghpull:`445`: ENH: unique qualitative color ramp. Also refactoring for future ipython deprecation of --pylab=inline
* :ghpull:`446`: Wmd
* :ghpull:`444`: Scipy dependency
* :ghpull:`442`: Wmd
* :ghpull:`441`: fixed kernel wmd for updated wmd structure
* :ghpull:`440`: ENH: sidebar for Releases and installation doc update
* :ghpull:`439`: - events
* :ghpull:`438`: ENH: pruning to respect flake8
* :ghpull:`437`: BUG: fix for removal of scipy.stat._support #436
* :ghpull:`433`: Rank markov
* :ghpull:`424`: testing
* :ghpull:`431`: FOSS4G
* :ghpull:`430`: Network
* :ghpull:`429`: moving analytics out of wed class and into their own module
* :ghpull:`428`: Network
* :ghpull:`427`: devel docs
* :ghpull:`425`: Viz2contrib
* :ghpull:`423`: Update news.rst
* :ghpull:`422`: ENH: Update doc instructions for napoleon dependency
* :ghpull:`421`: Adding files used in some examples as per Luc's request.
* :ghpull:`419`: Doc fixes 1.7
* :ghpull:`393`: Doc fixes 1.7
* :ghpull:`417`: ENH hex lattice W for #416
* :ghpull:`415`: Temporarily commenting out tests that are blocking Travis.
* :ghpull:`407`: Viz: Moving into contrib/viz in master
* :ghpull:`404`: version change
* :ghpull:`401`: fixes #388
* :ghpull:`402`: release changes

Issues (100):

* :ghissue:`503`: Grid for landing page
* :ghissue:`501`: Two figs rather than three
* :ghissue:`500`: More efficient higher order operations
* :ghissue:`452`: nat_queen.gal example file
* :ghissue:`499`: renamed nat_queen.gal for #452
* :ghissue:`486`: add a deprecation warning on regime_weights
* :ghissue:`497`: ENH Deprecation warning for regime_weights #486
* :ghissue:`449`: Lower order neighbor included in higher order
* :ghissue:`487`: Issue with w.weights when row-standardizing
* :ghissue:`398`: running test suite generates files
* :ghissue:`358`: Graph weights
* :ghissue:`338`: ENH: Move Geary's C calculations to Cython.
* :ghissue:`494`: Enables testing against two versions of SciPy shipped with the last two Ubuntu LTS versions.
* :ghissue:`490`: Fix for #487
* :ghissue:`492`: BUG cleaning up temporary files for #398
* :ghissue:`493`: Phil: Skipping several tests that fail due to precision under older scipy
* :ghissue:`489`: test suite fixes
* :ghissue:`485`: Revert "ENH: cleaning up more test generated files"
* :ghissue:`488`: More tests to skip if scipy less than 11
* :ghissue:`484`: ENH: cleaning up more test generated files
* :ghissue:`483`: Forwarding Phil's commit: skipping doctests, conditional skip of unit tests
* :ghissue:`482`: DOC cleaning up files after running doctests #398
* :ghissue:`481`: DOC contrib updates and links
* :ghissue:`480`: DOC cleaning up doctests
* :ghissue:`455`: regime weights vs block weights
* :ghissue:`479`: ENH Changing regime_weights to block_weights for #455
* :ghissue:`478`: DOC: link fixes
* :ghissue:`460`: Optimize KDTree
* :ghissue:`477`: cKDTree for #460
* :ghissue:`472`: Check for any side effects from new id remapping in w.sparse
* :ghissue:`473`: update all user space functions for new w.remap_ids
* :ghissue:`476`: redefining w.remap_ids to take only a single arg
* :ghissue:`263`: Transition to scipy.spatial.cKDTree from scipy.spatial.KDTree
* :ghissue:`414`: Travis build is killing nosetests
* :ghissue:`335`: Weights transformation docs
* :ghissue:`471`: add docstring example for w.remap_ids
* :ghissue:`475`: Adding docstrings and error check to fix #471
* :ghissue:`405`: ENH: Handling ids in W (Leave open for discussion)
* :ghissue:`470`: fixing order of args for api consistency. 
* :ghissue:`469`: Idfix for #449
* :ghissue:`467`: redirect pysal.org to new dynamic landing page
* :ghissue:`466`: design the grid for the notebooks
* :ghissue:`464`: design new dynamic landing page for github.io
* :ghissue:`465`: move news out of docs and into dynamic landing page
* :ghissue:`468`: Move dynamic items out of sphinx docs and into dynamic landing page
* :ghissue:`463`: updating gitignore
* :ghissue:`451`: docs for higher_order_sp have wrong argument types
* :ghissue:`462`: ENH: handle the case of an ergodic distribution where one state has 0 probability
* :ghissue:`458`: ENH: Vagrantfile for PySAL devs and workshops
* :ghissue:`447`: Clusterpy
* :ghissue:`456`: BUG: fix for #451 handling W or WSP in higher_order_sp
* :ghissue:`457`: This is a test to see if pull request notifications get sent out to the list
* :ghissue:`454`: Foobar
* :ghissue:`443`: Updating spreg: several minor bug and documentation fixes.
* :ghissue:`453`: Resolving conflicts
* :ghissue:`412`: On travis and darwin test_ml_error_regimes.py hangs 
* :ghissue:`448`: Wsp
* :ghissue:`435`: Will spatial durbin model be added in the near future?
* :ghissue:`445`: ENH: unique qualitative color ramp. Also refactoring for future ipython deprecation of --pylab=inline
* :ghissue:`446`: Wmd
* :ghissue:`444`: Scipy dependency
* :ghissue:`442`: Wmd
* :ghissue:`441`: fixed kernel wmd for updated wmd structure
* :ghissue:`440`: ENH: sidebar for Releases and installation doc update
* :ghissue:`439`: - events
* :ghissue:`438`: ENH: pruning to respect flake8
* :ghissue:`436`: Scipy 0.14 induced breakage
* :ghissue:`437`: BUG: fix for removal of scipy.stat._support #436
* :ghissue:`408`: Use of `platform.system()` to determine platform
* :ghissue:`403`: Scipy dependency
* :ghissue:`434`: W Object Metadata Attribute
* :ghissue:`433`: Rank markov
* :ghissue:`424`: testing
* :ghissue:`432`: Implementation of rank Markov classes
* :ghissue:`431`: FOSS4G
* :ghissue:`430`: Network
* :ghissue:`429`: moving analytics out of wed class and into their own module
* :ghissue:`420`: Local Moran's I,  I Attribute Undefined
* :ghissue:`418`: Extended pysal.weights.user.build_lattice_shapefile 
* :ghissue:`428`: Network
* :ghissue:`427`: devel docs
* :ghissue:`426`: dev docs
* :ghissue:`425`: Viz2contrib
* :ghissue:`423`: Update news.rst
* :ghissue:`422`: ENH: Update doc instructions for napoleon dependency
* :ghissue:`421`: Adding files used in some examples as per Luc's request.
* :ghissue:`419`: Doc fixes 1.7
* :ghissue:`393`: Doc fixes 1.7
* :ghissue:`416`: Add hexagonal lattice option for lat2W
* :ghissue:`417`: ENH hex lattice W for #416
* :ghissue:`409`: add wiki page on viz module design
* :ghissue:`413`: Temporary fix for https://github.com/pysal/pysal/issues/412
* :ghissue:`415`: Temporarily commenting out tests that are blocking Travis.
* :ghissue:`407`: Viz: Moving into contrib/viz in master
* :ghissue:`406`: Viz: pruning old code and adding more examples for TAZ paper
* :ghissue:`380`: Pep 8 and Line Length
* :ghissue:`404`: version change
* :ghissue:`401`: fixes #388
* :ghissue:`388`: update testing procedures docs
* :ghissue:`402`: release changes

# v<1.7.0>, 2014-01-29

36d268f Philip Stephens -Merge pull request #400 from sjsrey/mldoc
c2c4741 Serge Rey -Formatting ml docs
685f5e3 Sergio Rey -Merge pull request #399 from sjsrey/master
481ccb4 Serge Rey -correct thanks
4a5cce3 Sergio Rey -Update index.txt
1fe7aeb Philip Stephens -Merge pull request #396 from sjsrey/mldoc
e731278 Serge Rey -EHN: fixing link to bleeding edge docs.
e4e9930 Serge Rey -ENH: adding ml docs to api
9b3c77e Serge Rey -Merge branch 'master' of github.com:pysal/pysal
dda3c01 Philip Stephens -Merge pull request #389 from dfolch/master
74b26d5 Philip Stephens -Merge pull request #392 from pedrovma/spreg17
b47ba84 pedrovma -Bump.
3d8504c Sergio Rey -Merge pull request #386 from pastephens/master
f9b59ea Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
429e19e pedrovma -Upgrading to spreg 1.7.
c698747 David Folch -removing legacy speedup hack that is no longer relevant
88177d0 Sergio Rey -Merge pull request #387 from sjsrey/scipy13
64a4089 Serge Rey -BUG: sorting ijs for asymmetries
5539ef5 Sergio Rey -Merge pull request #1 from sjsrey/scipy13
8a86951 Serge Rey -BUG: fixes for scipy .0.9.0 to 0.13.0 induced errors
fe02796 Philip Stephens -tweaking travis to only run master commits
8c1fbe8 jlaura -Merge pull request #385 from sjsrey/docupdate
b71aedc Serge Rey -ENH: update date
4f237e4 Sergio Rey -Merge pull request #384 from sjsrey/moran
01da3be Serge Rey -ENH: Analytical p-values for Moran are two-tailed by default #337
918fe60 Philip Stephens -further travis tweaks
3920d73 Sergio Rey -Merge pull request #382 from sjsrey/st_docs
d90bc70 Serge Rey -DOC: updating refs for concordance algorithm
0db2790 Philip Stephens -tweaks to travis
063e057 Philip Stephens -upgrading scipy on travis
f90e742 Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
edc9c07 Dani Arribas-Bel -Merge pull request #379 from sjsrey/b244
82479bb Serge Rey -BUG: fix for the comment https://github.com/pysal/pysal/issues/244#issuecomment-30055558
57ba485 jlaura -Update README.md
981ed31 Sergio Rey -Merge pull request #377 from darribas/master
3320c39 darribas -Changing cmap default in plot_choropleth so every type defaults to its own adecuate colormap
e063bee darribas -Fixing ignorance of argument cmap in base_choropleth_unique
1f10906 Dani Arribas-Bel -Merge pull request #375 from sjsrey/viz
94aa3e7 Dani Arribas-Bel -Merge pull request #376 from pedrovma/baltim_data
7568b0b pedrovma -Adding Baltimore example dataset for use with LM models.
5b23f89 Serge Rey -greys for classless map
d4eae1e Dani Arribas-Bel -Merge pull request #374 from sjsrey/viz
652440d Serge Rey -shrinking colorbar
c17bf67 Sergio Rey -Merge pull request #373 from darribas/master
a71c3cb darribas -Fixing minor conflict to merge darribas viz branch into darribas master
ec27e30 Dani Arribas-Bel -Merge pull request #372 from sjsrey/viz
8c03170 Serge Rey -option for resolution of output figs
3fc5bd4 Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
2b5cb23 jlaura -Merge pull request #371 from sjsrey/geopandas
469afa7 Serge Rey -fix for #370
59cdafc jlaura -Merge pull request #369 from pedrovma/south_data
6b88e13 jlaura -Merge pull request #368 from schmidtc/issue367
40fe928 pedrovma -Adding south data to be used in ML doctests.
bcc257e schmidtc -fixes #367
87e057f jlaura -Merge pull request #366 from sjsrey/ml_lag
a64eb27 Serge Rey -queen contiguity for nat.shp
77add5c Sergio Rey -Merge pull request #365 from sjsrey/news
82464ef Serge Rey -narsc workshop
fd79424 Sergio Rey -Merge pull request #364 from sjsrey/news
bc7f25a Serge Rey -Merge branch 'master' of https://github.com/sjsrey/pysal
d669913 David Folch -Merge pull request #363 from sjsrey/maxp
22f9e36 Serge Rey -update example for bug fix #362
fac3b8a Serge Rey -- update tests for bug fix #362
44b4b06 Sergio Rey -Merge pull request #1 from sjsrey/maxp
1e6f1e5 Serge Rey -- fix for #362
68ab3e9 Sergio Rey -Merge pull request #361 from sjsrey/components
aa27c7e Serge Rey -doc test fix
7c08208 Serge Rey -putting Graph class back in for component checking
003b519 Serge Rey -alternative efficient component checker
2080e62 Serge Rey -- fixing doc
4fda442 Serge Rey -Merge branch 'components' of github.com:sjsrey/pysal into components
e9e613b Serge Rey -reverting back to old component check
83d855e Serge Rey -updating example
9defd86 jlaura -Merge pull request #360 from sjsrey/components
6f92335 Serge Rey -more efficient connectivity test
ebde3d1 Dani Arribas-Bel -Adding try/except for ogr since it's only used to reprojection methods but not on the plotting toolkit
5b170eb Sergio Rey -Merge pull request #356 from sjsrey/classification
c9dac41 Serge Rey -- update unit tests for reshaping jenks caspal
d9b06e2 Sergio Rey -Merge pull request #355 from sjsrey/cleanup/moran
dc589e8 darribas -Adding caution note when plotting points to the notebook. Ideally, we wanna be able to build a PathCollection out of the XYs, but for now we rely on plt.scatter, which gets the job done but has some problems.
2224b95 darribas -Including support for points in  base_choropleth_unique and base_choropleth_classless
ac2d08a darribas -Modifying example to show how to do choropleth mapping on points
270786e darribas -Adding support for choropleth plotting on point map objects (this may come from map_point_shp or from a simple matplotlib scatter
e56697c Sergio Rey -Merge pull request #357 from jlaura/newstyle_wed
4c67c2f Jay -errors in segmentation fixed
512cc76 Serge Rey -have Jenks-Caspal bins be a one dimensional array - to be consistent with all other classifiers
5254859 Philip Stephens -Merge branch 'master' of https://github.com/pysal/pysal
788ecab Serge -pruning
5b6b7b6 Serge -pruning
eb7e9a1 Jay -bug fix and all pointers filled for external edges
e47aa7a Jay -Node insertion, precursor to segmentation.
18a44d1 darribas -*Replacing shp by map_obj in medium layer functionality. *Bringing everything else in line with it *Adding example for line colorig and mixing overlaying of points.
bd041b1 darribas -Replacing shp_link by shp as input for medium and low-level layers. This brings much more flexibility and opens the door to plot formats other than shapefiles (e.g. geojson)
c74a361 darribas -Adding IP notebook to exemplify and keep track of development of mapping module
d23c882 darribas -Minor fixes
4b82a76 darribas -New commit message* Replacing map_poly_shp_lonlat for map_poly_shp in base_choropleth_classif/unique/classless * removed 'projection' from base_choropleth_classif/unique/classless * Allow base_choropleth_classif/unique/classless to plot multi-part polygons properly * changes streamlined to generic plot_choropleth * Added dependency on pandas for rapid reindexing (this is done externally on the method _expand_values to it is easy to drop the dependency when neccesary/time available)
7a0eaec darribas -Merge branch 'viz' of github.com:darribas/pysal into viz
5536424 darribas -Merge branch 'master' of github.com:darribas/pysal
e54ce16 Sergio Rey -Merge pull request #353 from darribas/master
819ee60 darribas -Adding immediate todo on head of the file
946772d darribas -Passing k to base_choropleth_classif from plot_choropleth. This should fix Issue #352
f299b45 darribas -Merge branch 'master' of https://github.com/pysal/pysal
f044f43 Jay -Added W generation
5f48446 jlaura -Merge pull request #348 from sjsrey/master
938a1ae Serge Rey -- adding nn stats to point based methods
a86a051 Philip Stephens -removing dependency tracking service, it was ruby only
1e24fde Philip Stephens -testing dependency tracking service
3aa410c Philip Stephens -Merge pull request #347 from pedrovma/w_silence_island
03990f6 pedrovma -Extending PR #310 (silence island warnings) to include w.transform.
160001a Sergio Rey -Merge pull request #346 from jlaura/newstyle_wed
44989f9 Sergio Rey -Merge pull request #345 from sjsrey/master
2fd99b8 Sergio Rey -Update README.md
bdcc6a8 Jay -NCSR with uniform distribution
769aa03 Jay -Fixed snapping
2561071 Jay -saved notebook and updated readme
3784783 Jay -ReadMe for Changes
019e16b Sergio Rey -Merge pull request #334 from jseabold/fix-build-example-dirs
1889885 Skipper Seabold -BLD: Correctly install package_data dirs.
ff4e355 Serge Rey -- assignments
c5b0cc0 Serge Rey -- reorg
a4f5642 Serge Rey -Merge branch 'network' of github.com:pysal/pysal into network
a95fec8 jlaura -Update README.md
1713145 Serge Rey -Merge branch 'master' of github.com:pysal/pysal into network
ede75c0 Sergio Rey -Merge pull request #329 from jlaura/wed_polar
7399cf2 Jay -Single-source shortest path notebook
9eb3fc1 Philip Stephens -Merge pull request #331 from sjsrey/docfix
ef9c82a Serge Rey -- sphinx doctest markup fix
1e2b6b3 jlaura -Update README.md
e19bffa jlaura -Merge pull request #330 from pysal/b328
6afc30b Serge Rey -- tutorial doc fixes for #328
c7239f1 Serge Rey -- b328 fix
d5fec13 Serge Rey -- fix for #328  making all p-values one-tailed
16b5e6e Jay -enumeration working with filaments
9507bbc jlaura -Update README.md
eef8eec Serge Rey -- stub for design of module
2707d60 Jay -Filaments in polar coordinates
b64f9e2 Serge Rey -Documentation for the development of network module
b90876e Serge Rey -Merge branch 'network' of github.com:pysal/pysal into network
ddad2a5 Philip Stephens -Merge pull request #326 from sjsrey/doc
6b0cd08 Serge Rey -- update release schedule
4cc7bca Jay -bisecting for single point working
79c77d9 jlaura -Merge pull request #324 from pysal/bf_id
9f4c7c9 Serge Rey -id is a keyword
72b1f85 Sergio Rey -Merge pull request #323 from jlaura/network
b5cdae0 Jay -fix to shp2graph
846dce2 Jay -Brute force for point outside network
d6c2ef4 Jay -Added length computation, alter global morans
b7e1465 Jay -Added new pointer to reader/writer
616d62d Jay -LISA and Global Morans on the network
16f84d6 Jay -Added explicit point external to network warning
34f4d8e Jay -update to the ipython notebook
e359e59 Jay -JSON and cPickle Bianry WED Reader/Writer
5373c82 Sergio Rey -Merge pull request #322 from jlaura/network
059d99c Jay -wed into class, tests added
aa5969d Sergio Rey -Merge pull request #320 from pastephens/master
a18000b Philip Stephens -version added info
5b8d490 Philip Stephens -typo
d31a22a Philip Stephens -stubs for cg docs
4dbdfe3 schmidtc -fixes #318
35a0317 Jay -Merge branch 'master' of https://github.com/pysal/pysal into network
77e8387 Jay -Merge branch 'geojson' of https://github.com/pysal/pysal into network
ad670c5 Sergio Rey -Merge pull request #317 from pastephens/master
628f27e Philip Stephens -merging local changes
f9dcb3e Philip Stephens -simplified install instructions
f2fab4c Serge Rey -- notebook on w construction for geojson
830826b Serge Rey -prototyping W from geojson
b10240d Serge Rey -created with "ogr2ogr -lco WRITE_BBOX=YES -f "GeoJSON" columbus.json columbus.shp"
d546926 Philip Stephens -merging with pull
d711011 darribas -Merge branch 'rod'
8bef782 darribas -Merge branch 'rod' of https://github.com/pysal/pysal into rod
03c1003 pedrovma -Merge pull request #315 from sjsrey/rod
950fe8b Serge Rey -Replacing ROD with regular dictionary
b1f009f Philip Stephens -Changes to release docs.
028364a Sergio Rey -Update THANKS.txt
94f5916 Sergio Rey -Update INSTALL.txt

# v<1.6.0>, 2013-07-31

5fa9d09 darribas -silent_island_warning implemented for w_union
6526c62 Sergio Rey -Update README.md
ea826c1 darribas -silent_island_warning implemented for w_intersection
335540a darribas -silent_island_warning implemented for w_difference
0a156cb darribas -silent_island_warning implemented for w_symmetric_difference. Previous commit included support of silent_island_warning for WSP2W as well
34d20d7 darribas -silent_island_warning implemented for w_clip
499815d pedrovma -Test fixing...
8778f75 pedrovma -Test fixing...
a799a13 pedrovma -Test fixing...
6482d81 pedrovma -Test fixing...
2752b1b pedrovma -Test fixing...
0c0a5bf pedrovma -Test fixing...
bbf9dcb pedrovma -Test fixing...
05c34ff pedrovma -Test fixing...
8a3986a Serge Rey -- preparing for release, version updates
9106cfe pedrovma -Matching travis results reg. precision issues.
3cd0ce1 Serge Rey -- updating changelog
74dadd6 pedrovma -Bump.
c7774fb Serge Rey -- update THANKS.txt - testing travis for timing out
cd98057 Serge Rey -- travis fix for multiprocessing permission error
86702f8 Serge Rey -- start of changelog for 1.6
3ee686d pedrovma -Reloading to check new results from Travis.
2de1d21 Serge Rey -- docs
ef72edc Serge Rey -- update docs
0716581 Serge Rey -- deal with multiprocessing on travis
b508c88 Serge Rey -- excluding network from 1.6 release
ff13e31 pedrovma -Matching Travis results. Multiprocessing errors still an issue.
5b916ba pedrovma -Adding Chow test on lambda and updating dynamics of regime_err_sep and regime_lag_sep in combom models.
b6e687f darribas -Patch to include switch for island warning as proposed in #295. The method  is modified as well to include the switch
7ea5f35 pedrovma -Fixing defaults
62ca76b pedrovma -Updating documentation and checking if there are more than 2 regimes when regimes methods are used.
3212249 pedrovma -Fixing documentation on 'name_regimes'
a782d50 pedrovma -Updating tests for integration with pysal 1.6
14f9181 pedrovma -Merging spreg_1.6 with my pysal fork.
817f2c2 Serge Rey -- having build_lattice_shapefile also create the associated dbf file - useful for testing our contiguity builders against geoda since dbf is   required by the latter
41d59a4 Serge Rey -- adding diagonal option to kernel weights in user.py
506d808 Serge Rey -update when added
b2ec3d4 Serge Rey -- updating api docs
9d45496 Serge Rey -- example and doctests for spatial gini
95635bb Serge Rey -updating release docs
bd2f924 darribas -Fixing doctest of towsp method by including isinstance(wsp, ps.weights.weights.WSP)
76183d7 darribas -Fixing doctest of towsp method by including type(wsp)
0c54181 darribas -Adding  method in W that calls WSP class for convenience and elegance. Related to issue #226
f3b23e8 Philip Stephens -adding source build to travis-ci
60930e7 Philip Stephens -adding new url for downloads
9bf7f5b Philip Stephens -modified release docs.
f98d4a9 Philip Stephens -interim ci
aa19028 Philip Stephens -Adding docs about installing in develop mode.
674112f Philip Stephens -starting rewrite of install docs
af0d9b3 Philip Stephens -working on doc tickets
200e77e Serge Rey -handle ties in knnW in doctest
d0d2dd2 Serge Rey -resetting README for pysal/pysal
6afb6ac Serge Rey -- updating docs for new api in interation.py
4c5572f Serge Rey -- updating tests for new api
fabd16a Serge Rey -- refactored signatures to use numpy arrays rather than event class
6367947 Serge Rey -- refactor knox for large samples
5fad3b2 Serge Rey -- updating travis test
06894d8 Serge Rey -- updated README
8b06e63 Serge Rey -- so only i get email when i commit locally
efbb7ff Serge Rey -- removing google pysal-dev circle
9859bda Serge Rey -- turning off gmail circle
51f6d3e Serge Rey -- fixing
46b1084 Serge Rey --docos
4e2c27a Philip Stephens -missing if statement added
d1a83fd Serge Rey -- fixing docs
8275d76 Serge Rey -- fix precision
87ea5cc Philip Stephens -adding to authors and quick test fix for linux
1cfb67f Serge Rey -cant easily remove idVariable, reverting
5933d1e Serge Rey -removing idvariable from Distance - causes too many issues
05f2573 Philip Stephens -removing coverage tests
fcb8c6f Philip Stephens -Knox using KDTree.
2237173 Serge Rey -with tests against previous implementation removed
233e59a Serge Rey -speed comparison for change to query_pairs in kdtree
fb78ea9 Serge Rey -removing test file
4d04575 Philip Stephens -testing
357a184 Serge Rey -second great idea
1fafc2b Serge Rey -on a plane commit 1
fef6eae Philip Stephens -fix
86c17ac Serge Rey -- test file
a619f62 Philip Stephens -interim ci
1a9d881 Serge Rey -- knox test using kdtrees
7459c44 Serge Rey -Fixing reference to missing shapefile Fixing one rounding error induced test
5616b12 Serge Rey -refactored to avoid second loop in explicit queen or rook check
d3d2f71 Philip Stephens -Revert "Changed doctest path calls to account for modified shapefile."
da1d8a1 Philip Stephens -Changed doctest path calls to account for modified shapefile.
f591c99 Philip Stephens -progress on permutations of knox for larger datasets
8d31cde Serge Rey -Testing integration of spatialnet creation and reading into wed
11de6f3 Jay -Fixed wed_modular.py
077658a Serge Rey -adding new test case for wed extraction from a spatialnet shapefile
bbb10b4 Philip Stephens -saving state of development
44076b7 Serge Rey -- update doc test
6fdd94d Serge Rey -- moved regions_from_graph into wed_modular - documented all functions and cleaned up
5bd27c3 Serge Rey -- wrapping in functions
3ad162f Serge Rey -- working version of wed_modular module - starting point for clean up
2380f15 Philip Stephens -Copy of sphinx install docs. Closes #251
5687700 Philip Stephens -tweaks to install instructions
9ffd432 Serge Rey -- updating for switch from svn to git
fdaf521 Philip Stephens -Fixing 250
5ba4fdf Serge Rey -Fixes #249 Closes #249
d89944d Pedro -Adding docs for each regimes estimator
f03bb63 Serge Rey -- updating docs for spatial regimes in spreg
a49d0f7 Philip Stephens -Adding info to setup script.
1f27605 Philip Stephens -mainly docs
04f8a31 Philip Stephens -Adding test coverage with nose, data collected and presented on coveralls.io
6db978b Philip Stephens -last changes
137e088 Philip Stephens -added bigdata parameter
7ca81c2 Philip Stephens -got Knox stat working in alt form
24c1fcc Philip Stephens -workign on refactoring the space-time matrices for the Knox test [ci-skip]
28013f0 Serge Rey -- enumeration of cw edges for faces
baa8f60 Serge Rey -- hole is now included and enumeration of links (cw) around nodes works for all nodes. - isolated nodes also handled in enumeration of links around nodes.
33741c8 Serge Rey -- filaments inserted and pointers updated - have to add hole polygon and isolated nodes, but almost there!!!!!!!!!
416d3db Serge Rey -- pointers updated for edges of connected components
c34e274 Serge Rey -- convex/between edge test as start of testing for insertion of multiple   internal filaments in one region.
78d96b1 Serge Rey -- filament insertion and pointer updates
ced2c5b Serge Rey -- filament insertion (inc)
ba4263f Jay -Logic roughed in for filaments [ci skip]
cf3b0bc Jay -updated wed ipynb [ci skip]
33ce81e Serge Rey -- refactoring of wed construction (incomplete)
0fc16fc Jay -modular WED Pulled Apart 2 funcs in 1 cell
bf73b90 Jay -modular WED
3163377 Serge Rey -- new modular wed construction
e50b31d Jay -added test_wed additions to test_wed2
1cbc941 Serge Rey -- isolated nodes handled
d28b97f Serge Rey -- isolated filament handled
6188fd5 Serge Rey -- hole component handled
a96040b Serge Rey -- getting connected components (current 14,15,16  and 25,26,27 are not   included)
3aa31a5 Jay -Added boolean arg to include or exclude holes [ci skip]
d07876d Jay -Filament identification [ci skip]
0139ea5 Philip Stephens -Slight speed improvement getting rid of append calls in reading shapefile and building x,y lists.
43010b5 Serge Rey -- fixed logic problem with enum for v1, starting on components
8737918 Pedro -Adding more meaningful error message to inverse distance weights
01f52f6 Serge Rey -- replacing code that got deleted previously
7c4c6e1 Philip Stephens -Replacing deleted files.
a8da725 Philip Stephens -added date support to spacetimeevents class, a date column to example dbf.
90c4730 Philip Stephens -logic works, numeric test still failing
b8e43e1 Philip Stephens -saving progress on interaction
81f2408 Serge Rey -- handling external end-node-filament
7de6253 Serge Rey -- adding end node filament handling - edge enumeration around node working
f542b9a Serge -- adding end node filament handling - edge enumeration around node working
d7e3a57 Philip Stephens -[ci skip] disabling nose-progressive so travis output looks best
fe03013 Dani Arribas-Bel -Adding set of diversity indices to inequality module under _indices.py for now. Still lacks doctests, unittests, and a few others will be added
951b6f5 Dani Arribas-Bel -Adding try/except to the import of Basemap to allow the use of the module when there is no Basemap installation
89003eb Serge Rey -- adding wed for eberly example
665ef22 Serge Rey -- fixed 7,2 failure
71fc9ad Serge Rey -start of adding gini and other inequality measures
f7b7bcc Phil Stephens -Adding nose-progressive plugin to test suite. Devs can run test suite with 'make test'.
f5db7bf Serge Rey -- updating copyright
07574b5 Serge Rey -- docs
478d2cb Philip Stephens -Adding requirement. Removing redundancy.
916a6ca Serge Rey -- more island check updates
edd9960 Serge Rey -- more island check doctest changes
ad1a91c Serge Rey -- updating doctests for island check
ce77772 Serge Rey -- fixing doctests to incorporate new island warning
554a30b Serge Rey -- silencing floating point warning
4f76862 Serge Rey -- moving default contiguity builder back to binning from rtree
b99665b Jay -Eberly
d911344 Jay -mp removed, passing nosetests on my machine serial
f005675 Serge Rey -improved binning algorithm for contiguity builder
4a69557 Serge Rey -- double checking threshold in Distance Band - new example to show functionality
7256f13 Serge Rey -- fix handling of idVariable for knnW
31bb36e Jay -bug fixes [ci skip]
a2d2dd4 Jay -WEberly - WED Building [ci skip]
3abc55e Serge Rey -- fixing doctests for new check/reporting for islands
756ac05 Serge Rey -- adding warning if islands exist upon W instantiation
db097a6 Jay -Weberly, bug fix, c and cc link remaining
d5cc6f9 Jay -All but start / end working
033963d Jay -Integration to WEberly error fixed [ci skip]
22b931a Serge Rey -- removing main for doc tests which can be run from nosetests. - updating testing docs
bf753e9 Jay -Integration to WEberly started [ci skip]
6506e07 Serge Rey -- typo
aede375 Serge Rey -- replacing double quotes around multi word ids with strings joined with   underscores
cf029e8 Serge Rey -- changes to wrap string ids in gwt writer - see https://github.com/pysal/pysal/issues/244#issuecomment-16707353
626ac08 Serge Rey -- adding shapefile and variable name to gwt objects created in user space
3c84bb0 Jay -Working version 4.19 [ci skip]
7d77da9 darribas -Include warning in sp_att when rho is outside (-1, 1), ammends #243 although the true problem (pearsonr in diagnostics_tsls) will still raise an error
3719d21 Jay -working WED [ci skip]
b4ce294 Serge Rey -checking edges
f4bb412 Jay -excessive print statements removed. ci skip
9f7dee6 Jay -SUCCESS! ci skip
9077615 Phil Stephens -Note, [ci skip] anywhere in your commit message causes Travis to NOT build a test run.
cb072c4 Jay -getting there
d3b36bc Serge Rey -correcting typo user told me about
19ea051 Jay -trivial working
b9ea577 Jay -eberly cycles - edge issue still
d5153e3 Serge Rey -more refinement of wed from plannar graph
edff44b Philip Stephens -adding git ignore file
8093f21 Serge Rey -wed from minimum cycle basis
b5bcead Serge Rey -handle filaments
9a8927a Serge Rey -face extraction using horton algorithm
10d66c1 Serge Rey -updating readme formatting
59f3750 schmidtc -adding Universal newline support to csvReader, fixes #235
09e813f Serge Rey -- updating notifications
f8b0a26 Serge Rey -- fixing Distance.py and testing travis message
d1ec0f2 Phil Stephens -quieting pip output and fix one doctest
927e799 Phil Stephens -adding networkx, tweaks to travis config
5971bb1 Serge Rey -neighbors from wed
28f0e55 Serge Rey -adding robust segment intersection tests
3bcac73 Serge Rey -adding doubly connected edge list to network module
86f0fea darribas -Adding methods to read line and point shapefiles and improving the method to append different collections to one axes. Still in progress
b61cb55 Serge Rey -- fixing introduced bug in knnW_arc
801e78d Serge Rey -Handle point sets with large percentage of duplicate points
dbafbc4 serge -update pointer to github
427a620 Serge Rey -dealing with filaments
23216ef Serge Rey -Fixed cw enumeration of links incident to a node
0a51a53 Serge Rey -- readme
5f4cab4 sjsrey -cw enumeration not working for all nodes
f2e65d3 Serge Rey -- cw traversal of edges incident with a node
90d150c sjsrey -- version debug for travis
24598a8 sjsrey -- noting move to org
9fb8a17 sjsrey -- fixing tutorial tests
5a14f9e serge -- cleaning up weights tests
6265b3b Serge Rey -- fixing doc tests
7e8c4fe Serge Rey -- testing after move to org
37fc8d4 Serge Rey -- testing post commit emails
bed7f6e Phil Stephens -removed files
eab2895 Phil Stephens -removed virginia_queen files
bcef010 Serge Rey -- adding diagonal argument to Kernel weights - adding doctest evaluation to Distance.py
02d27e9 Phil Stephens -adding libgeos-dev
1126d71 Phil Stephens -pipe build output to null
37dbb35 Phil Stephens -adding -y flag to pip uninstall
06d56e9 Phil Stephens -adding libgeos_c install, pysal from pip
4c53277 Phil Stephens -trying to quiet output, using Makefile
74448e8 Phil Stephens -find setup.py
4634fb1 Phil Stephens -test install in venv and build
5d58723 Phil Stephens -working out travis-ci doctest configuration
5e905d3 Phil Stephens -adding numpydoc
33a5298 Phil Stephens -tweaks travis config
5c85f50 Phil Stephens -tweaking service configs
4ed1201 Josh Kalderimis -use the correct syntax for sysytem_site_packages
954b6d2 Phil Stephens -stop!
311eca8 Phil Stephens -ssp=true
c601bca Phil Stephens -numpy first
54b0afe Phil Stephens -ok, so travis is serious about not using system site packages.
2b912cc Phil Stephens -doh
28994df Phil Stephens -better yaml
ce1d89e Phil Stephens -testing
b535d3e Phil Stephens -testing
440a772 Phil Stephens -tweaking pip requirements file
34a74e2 Phil Stephens -tweaking travis file
33b13aa Serge Rey -- new links
8e09d7b Serge Rey -- setting up travis
d33001e Sergio Rey -Update CHANGELOG.txt
9d4de66 Serge Rey -- added authors
ab672c9 Serge Rey -- modified knnW to speed up dict construction
4edd2ab Serge Rey -- update cr
39e6564 Phil Stephens -syncing install instructions with docs
9e98db9 Phil Stephens -adding website favicon; chrome does not empty cache properly!!

 * migration to github from svn
   svn2git http://pysal.googlecode.com/svn --authors ~/Dropbox/pysal/src/pysal/authors.txt --verbose

# v<1.5.0>, 2013-01-31

2013-01-29 20:36  phil.stphns

	* doc/source/users/installation.txt: updating and simplifying user
	  install instructions.

2013-01-18 16:17  sjsrey

	* Adding regime classes for all GM methods and OLS available in
	  pysal.spreg, i.e. OLS, TSLS, spatial lag models, spatial error models
	  and SARAR models. All tests and heteroskedasticity
	  corrections/estimators currently available in pysal.spreg apply to
	  regime models (e.g. White, HAC and KP-HET). With the regimes, it is
	  possible to estimate models that have:
	  -- Common or regime-specific error variance;
	  -- Common or regime-specific coefficients for all variables or for a
	  selection of variables;
	  -- Common or regime-specific constant term;
	  - Various refactoring to streamline code base and improve long term
	    maintainability
	    - Contributions from Luc Anselin, Pedro Amaral, Daniel Arribas-Bel
	      and David Folch

2013-01-18 14:08  schmidtc

	* pysal/common.py: implemented deepcopy for ROD, see #237

2013-01-08 12:28  dreamessence

	* pysal/contrib/spatialnet/__init__.py: Adding __init__.py to make it importable

2012-12-31 22:53  schmidtc

	* pysal/core/IOHandlers/gwt.py: adding kwt support, see #232

2012-12-21 20:53  sjsrey@gmail.com

	* pysal/__init__.py, pysal/cg/rtree.py,
	  pysal/contrib/weights_viewer/weights_viewer.py,
	  pysal/weights/weights.py: - turning off randomization in rtree

2012-12-06 16:34  dfolch

	* pysal/contrib/shapely_ext.py: adding unary_union() to shapely
	  contrib; note this only works with shapely version 1.2.16 or higher


2012-11-29 13:39  dreamessence 

	* pysal/contrib/viz/mapping.py: Added option in setup_ax to pass
	  pre-existing axes object to append.  It is optional and it enables,
	  for instance, to embed several different maps in one single figure

2012-11-20 00:23  dfolch

	* pysal/contrib/shapely_ext.py: adding shapely's cascaded_union
	  function to contrib

2012-11-12 18:08  dreamessence

	* pysal/contrib/viz/mapping.py: -Adding transCRS method to convert
	  points from one prj to another arbitrary one -Adding map_poly_shp to
	  be able to plot shapefiles in arbitrary projections, not needing to
	  be in lonlat and not depending on Basemap

2012-11-09 15:40  sjsrey@gmail.com

	* pysal/weights/weights.py:
	  - distinguish between intrinsic symmetry and general symmetry
	
2012-11-02 17:48  schmidtc

	* pysal/weights/user.py, pysal/weights/util.py: Adding Minkowski
	  p-norm to min_threshold_dist_from_shapefile, see issue #221

2012-10-19 22:35  sjsrey@gmail.com

	* pysal/weights/weights.py:
	  explicitly prohibit chaining of transformations - all
	  transformations are only applied to the original weights at
	  instantiation

2012-10-19 17:38  sjsrey@gmail.com

	* pysal/spatial_dynamics/markov.py:
	  - fixing bug in permutation matrix to reorder kronecker product in
	    the join test

2012-10-17 17:55  sjsrey@gmail.com

	* pysal/weights/util.py:
	  -
	  higher order contiguity for WSP objects

2012-10-17 15:43  sjsrey@gmail.com

	* pysal/weights/user.py:
	  -
	  id_order attribute was always NONE for wsp created from
	  
	  queen/rook_from_shapefile with sparse=True

2012-10-16 19:25  schmidtc

	* pysal/weights/util.py: improving memory usage of
	  get_points_array_from_shapefile, no need to read entire shapefile
	  into memory.

2012-10-15 00:44  dreamessence

	* pysal/contrib/viz/mapping.py: First attempt to refactor Serge's code
	  for choropleth mapping.  It now offers a more general and flexible
	  architecture.  Still lots of work and extensions left.  The module
	  is explained in a notebook available as a gist at
	  https://gist.github.com/3890284 and viewable at
	  http://nbviewer.ipython.org/3890284/

2012-10-12 18:34  schmidtc

	* pysal/contrib/spatialnet/spatialnet.py: modified SpatialNetwork.snap
	  to calculate and return the snapped point

2012-10-12 17:05  dfolch

	* pysal/contrib/viz/mapping.py: made edits to unique_values_map to
	  allow for unlimited number of categories; I commented out the
	  previous code so these changes can easily be rolled back if it
	  breaks something somewhere else

2012-10-12 15:03  schmidtc

	* pysal/cg/segmentLocator.py: Fixing issue with segmentLocator, when
	  query point is extreamly far from the grid boundary, overflow errors
	  were causing the KDTree to not return any results.  Changed both
	  KDtree's to use Float64 and share the same data.  Previously,
	  cKDTree was using float64 and KDtree was using int32.

2012-10-11 08:12  dreamessence

	* pysal/contrib/viz/__init__.py: Adding __init__.py to viz module to
	  make it importable

2012-08-31 02:57  phil.stphns

	* pysal/spreg/tests/test_diagnostics.py,
	  pysal/spreg/tests/test_diagnostics_sp.py,
	  pysal/spreg/tests/test_diagnostics_tsls.py,
	  pysal/spreg/tests/test_error_sp.py,
	  pysal/spreg/tests/test_error_sp_het.py,
	  pysal/spreg/tests/test_error_sp_het_sparse.py,
	  pysal/spreg/tests/test_error_sp_hom.py,
	  pysal/spreg/tests/test_error_sp_hom_sparse.py,
	  pysal/spreg/tests/test_error_sp_sparse.py,
	  pysal/spreg/tests/test_ols.py,
	  pysal/spreg/tests/test_ols_sparse.py,
	  pysal/spreg/tests/test_probit.py,
	  pysal/spreg/tests/test_twosls.py,
	  pysal/spreg/tests/test_twosls_sp.py,
	  pysal/spreg/tests/test_twosls_sp_sparse.py,
	  pysal/spreg/tests/test_twosls_sparse.py:
	  - autopep8 -iv spreg/tests/*.py - nosetests pysal - no fixes needed

2012-08-31 01:16  phil.stphns

	* pysal/spreg/diagnostics.py,
	  pysal/spreg/diagnostics_sp.py,
	  pysal/spreg/diagnostics_tsls.py,
	  pysal/spreg/error_sp.py,
	  pysal/spreg/error_sp_het.py,
	  pysal/spreg/error_sp_hom.py,
	  pysal/spreg/ols.py,
	  pysal/spreg/probit.py,
	  pysal/spreg/robust.py,
	  pysal/spreg/summary_output.py,
	  pysal/spreg/twosls.py,
	  pysal/spreg/twosls_sp.py,
	  pysal/spreg/user_output.py,
	  pysal/spreg/utils.py:
	  -
	  autopep8 -iv spreg/*.py - fixed autopep8-introduced doctest failures
	  - fixed lingering scientific notation test failures

2012-08-31 00:26  phil.stphns

	* pysal/esda/gamma.py,
	  pysal/esda/join_counts.py,
	  pysal/esda/mapclassify.py,
	  pysal/esda/mixture_smoothing.py,
	  pysal/esda/moran.py,
	  pysal/esda/smoothing.py:
	  -
	  autopep8 fixes - make sure to run unit and doc tests before
	  committing - one autofix breaks long lines, and thus breaks some
	  doctests; must be
	  
	  fixed manually

2012-08-31 00:10  phil.stphns

	* pysal/esda/getisord.py:
	  -
	  using autopep8 module - call: autopep8 -vi getisord.py

2012-08-30 23:18  phil.stphns

	* pysal/esda/geary.py:
	  -
	  pep8 clear - removed wildcard import

2012-08-26 22:53  phil.stphns

	* pysal/spatial_dynamics/directional.py,
	  pysal/spatial_dynamics/ergodic.py,
	  pysal/spatial_dynamics/interaction.py,
	  pysal/spatial_dynamics/markov.py,
	  pysal/spatial_dynamics/rank.py,
	  pysal/spatial_dynamics/util.py:
	  -pep8 and pylint fixes -clean wildcard imports

2012-08-26 21:03  phil.stphns

	* pysal/region/maxp.py,
	  pysal/region/randomregion.py:
	  -
	  cleaning up imports

2012-08-26 18:16  phil.stphns

	* pysal/region/maxp.py:
	  -
	  style fixes with pep8 - cmd line call: pep8 --show-source
	  --ignore=E128,E302,E501,E502,W293,W291
	  
	  region/maxp.py

2012-08-26 17:47  phil.stphns

	* pysal/common.py,
	  pysal/examples/README.txt,
	  pysal/region/components.py,
	  pysal/region/randomregion.py:
	  -
	  using pep8 module

2012-08-24 20:47  schmidtc

	* pysal/network,
	  pysal/network/__init__.py: adding network module

2012-08-21 22:53  phil.stphns

	* doc/source/_templates/ganalytics_layout.html:
	  -
	  updating analytics tracker

2012-08-17 17:11  sjsrey@gmail.com

	* pysal/contrib/spatialnet/util.py:
	  -
	  more utility functions for pysal
	  -
	  networkx interop

2012-08-16 23:44  phil.stphns

	* setup.py:
	  -
	  tweak for build names

2012-08-12 13:15  dreamessence

	* doc/source/index.txt:
	  Adding announcement links to landing page

2012-08-11 17:38  sjsrey

	* LICENSE.txt:
	  -
	  update

2012-08-09 17:19  phil.stphns

	* doc/source/developers/pep/pep-0008.txt:
	  updating
	  spatial
	  db
	  pep

2012-08-08 17:22  schmidtc

	* pysal/weights/Distance.py:
	  Fixing bug in Kernel weights that causes erroneous results when
	  using ArcDistances.  See issue #218.

2012-08-04 21:14  sjsrey

	* doc/source/developers/docs/index.txt:
	  -
	  fixed
	  links

2012-08-04 21:03  sjsrey

	* doc/source/developers/docs/index.txt:
	  -
	  hints
	  on
	  editing
	  docs
	  

2012-08-04 20:14  phil.stphns

	* doc/source/developers/pep/pep-0011.txt:
	  note
	  about
	  travis-ci
	  and
	  github

2012-08-04 16:24  sjsrey

	* doc/source/developers/pep/pep-0011.txt:
	  PEP-0011
	  

2012-08-04 16:22  sjsrey

	* doc/source/developers/pep/index.txt:
	  -
	  PEP 0011 Move from Google Code to Github

2012-08-04 04:42  sjsrey

	* doc/source/index.txt:
	  - broken link

2012-08-04 04:35  sjsrey

	* doc/source/index.txt:
	  - news updates

2012-08-04 04:24  sjsrey

	* doc/source/index.txt:
	  - reorg

2012-08-02 02:32  sjsrey

	* pysal/examples/__init__.py:
	  -
	  moving back to r1049 but leaving r1310 in history for ideas on
	  moving forward - we need to distinguish between using examples in
	  the doctests (which the users see) and for the developers since we
	  are no longer distributing examples with the source

2012-08-02 01:49  sjsrey

	* pysal/examples/__init__.py:
	  -
	  correct conditional this time (i hope)

2012-08-02 01:36  sjsrey

	* pysal/examples/__init__.py:
	  -
	  compromise
	  -
	  returns pth rather than None if file does not exist

2012-08-02 00:58  sjsrey

	* pysal/examples/__init__.py:
	  -
	  link to examples download

2012-08-02 00:42  sjsrey

	* pysal/examples/__init__.py:
	  -
	  explicit check if examples are actually present





# v<1.4.0>, 2012-07-31

2013-01-31 


2012-07-31 21:30  sjsrey@gmail.com

	* pysal/spatial_dynamics/ergodic.py,
	  pysal/spatial_dynamics/rank.py:
	  - docs/example

2012-07-31 20:47  sjsrey@gmail.com

	* pysal/spreg/tests/test_error_sp_hom.py:
	  - rounding/precision issue

2012-07-31 20:27  sjsrey@gmail.com

	* pysal/spatial_dynamics/directional.py,
	  pysal/spatial_dynamics/tests/test_directional.py:
	  - fixing pvalue bug

2012-07-31 20:24  sjsrey@gmail.com

	* doc/source/users/tutorials/dynamics.txt:
	  - fixed rounding problem

2012-07-31 19:58  sjsrey@gmail.com

	* doc/source/index.txt,
	  doc/source/users/tutorials/autocorrelation.txt,
	  doc/source/users/tutorials/dynamics.txt,
	  doc/source/users/tutorials/econometrics.txt,
	  doc/source/users/tutorials/fileio.txt,
	  doc/source/users/tutorials/index.txt,
	  doc/source/users/tutorials/intro.txt,
	  doc/source/users/tutorials/region.txt,
	  doc/source/users/tutorials/smoothing.txt,
	  doc/source/users/tutorials/weights.txt:
	  - adding links to API for more details

2012-07-31 19:05  sjsrey@gmail.com

	* pysal/spatial_dynamics/directional.py:
	  - consistency on pvalues for randomization

2012-07-31 19:02  sjsrey@gmail.com

	* pysal/weights/Distance.py:
	  - docs

2012-07-31 18:58  sjsrey@gmail.com

	* doc/source/users/tutorials/dynamics.txt:
	  - seed issue 

2012-07-31 18:36  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt:
	  - closing issue 214

2012-07-31 18:19  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt:
	  - fixing random.seed issues in doctests

2012-07-31 17:31  schmidtc

	* pysal/cg/shapes.py,
	  pysal/cg/tests/test_shapes.py:
	  Fixing small bugs with VerticleLines and testing

2012-07-31 16:26  sjsrey@gmail.com

	* doc/source/developers/guidelines.txt,
	  doc/source/users/installation.txt:
	  - updating docs 



2012-07-26 15:24  schmidtc

	* pysal/core/FileIO.py,
	  pysal/core/Tables.py:
	 Fixing issue #190

2012-07-24 16:32  schmidtc

	* pysal/cg/sphere.py:
	Allowing linear2arcdist function to maintin 'inf', this allows compatability with Scipy's KDTree and addresses issue 208.  

2012-07-24 16:07  schmidtc

	* pysal/cg/locators.py,
	  pysal/core/FileIO.py,
	  pysal/core/Tables.py:
	  Addressing issue 212, renaming nested and private classes to begin with an underscore.  By default sphinx does not try to document private object, which avoids what appears to be a a bug in Sphinx.

2012-07-17 22:06  sjsrey@gmail.com

	* pysal/spreg/probit.py: pedro doc fixes

2012-07-17 15:07  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/tests/test_segmentLocator.py: Cleaned up fix for Issue 211

2012-07-13 22:50  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: fixing sphinx weirdness in footnotes 

2012-07-13 22:37  sjsrey@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: update for new default parameter values

2012-07-13 22:13  sjsrey@gmail.com

	* pysal/esda/geary.py,
	  pysal/esda/tests/test_geary.py: consistency on transformation and permutation args

2012-07-13 19:59  sjsrey@gmail.com

	* doc/source/users/tutorials/dynamics.txt,
	  pysal/__init__.py,
	  pysal/spatial_dynamics/rank.py: - update user tutorial and __init__

2012-07-13 19:33  sjsrey@gmail.com

	* pysal/spatial_dynamics/rank.py,
	  pysal/spatial_dynamics/tests/test_rank.py: - O(n log n) algorithm for spatial tau (old one was O(n^2)) - closing ticket http://code.google.com/p/pysal/issues/detail?id=83

2012-07-13 17:57  schmidtc

	* pysal/core/IOHandlers/pyDbfIO.py,
	  pysal/core/IOHandlers/tests/test_pyDbfIO.py: Adding better support for writing Null values to DBF.  See issue #193

2012-07-13 15:55  schmidtc

	* pysal/core/util/shapefile.py,
	  pysal/core/util/tests/test_shapefile.py: Cleaning up support for ZM points, polylines and polygons in the shapefile reader. Added unit tests for same.

2012-07-13 15:42  sjsrey@gmail.com

	* doc/source/library/esda/gamma.txt: - update version info 

2012-07-13 15:37  sjsrey@gmail.com

	* doc/source/library/esda/gamma.txt,
	  doc/source/library/esda/index.txt: - adding gamma to api docs

2012-07-13 00:21  sjsrey@gmail.com

	* pysal/esda/gamma.py: optimizations 

2012-07-12 21:28  schmidtc

	* pysal/core/IOHandlers/pyDbfIO.py: Disabling mising value warning for DBF files.  See issue #185

2012-07-12 21:07  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py,
	  pysal/cg/tests/test_segmentLocator.py,
	  pysal/contrib/spatialnet/spatialnet.py: Adding unittests for segmentLocator (including one that fails see #211). Added VerticalLine class to represent verticle LineSegments. Updated __all__ in segmentLocator. Minor comment formatting in spatialnet.

2012-07-12 19:41  lanselin@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: tutorial for gamma index

2012-07-12 19:40  lanselin@gmail.com

	* pysal/esda/gamma.py,
	  pysal/esda/tests/test_gamma.py: gamma with generic function

2012-07-12 14:17  sjsrey@gmail.com

	* pysal/__init__.py: - gamma index added

2012-07-12 03:14  lanselin@gmail.com

	* pysal/esda/tests/test_gamma.py: tests for gamma

2012-07-12 03:13  lanselin@gmail.com

	* pysal/esda/gamma.py: gamma index of spatial autocorrelation

2012-07-12 03:11  lanselin@gmail.com

	* pysal/esda/__init__.py: gamma index 

2012-07-11 21:32  lanselin@gmail.com

	* pysal/esda/join_counts.py,
	  pysal/esda/tests/test_join_counts.py: join counts without analytical results, new permutation 

2012-07-11 21:32  lanselin@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: updated docs for join counts

2012-07-10 21:13  lanselin@gmail.com

	* doc/source/users/tutorials/autocorrelation.txt: docs for join count in autocorrelation

2012-07-10 21:12  lanselin@gmail.com

	* pysal/esda/join_counts.py,
	  pysal/esda/tests/test_join_counts.py: additional test in join counts, docs added

2012-07-10 19:24  lanselin@gmail.com

	* pysal/esda/join_counts.py,
	  pysal/esda/tests/test_join_counts.py: join counts with permutations for BB, updated tests to include permutations

2012-07-09 04:22  sjsrey

	* pysal/weights/weights.py:
	  - fixing bug luc identified with regard to mean_neighbor property.  wrong key name was used in cache dictionary.  

2012-07-07 17:00  sjsrey

	* pysal/__init__.py: update for spreg and contrib inclusion


2012-07-07 16:51  sjsrey

	* pysal/spatial_dynamics/markov.py: - updating doc strings

2012-07-07 16:17  sjsrey

	* pysal/spreg/probit.py:
	  - fixing doc string and refs 

2012-07-06 21:58  dfolch

	* doc/source/library/spreg/probit.txt: txt file to include probit in the HTML docs

2012-07-06 21:11  dfolch

	* pysal/spreg/tests/test_ols_sparse.py: fixing unittest error; still no solution to scientific notation formatting in doctests

2012-07-06 20:24  dfolch

	* pysal/spreg/__init__.py,
	  pysal/spreg/diagnostics.py,
	  pysal/spreg/diagnostics_sp.py,
	  pysal/spreg/diagnostics_tsls.py,
	  pysal/spreg/error_sp.py,
	  pysal/spreg/error_sp_het.py,
	  pysal/spreg/error_sp_hom.py,
	  pysal/spreg/ols.py,
	  pysal/spreg/probit.py,
	  pysal/spreg/robust.py,
	  pysal/spreg/summary_output.py,
	  pysal/spreg/tests/test_diagnostics.py,
	  pysal/spreg/tests/test_diagnostics_sp.py,
	  pysal/spreg/tests/test_diagnostics_tsls.py,
	  pysal/spreg/tests/test_error_sp.py,
	  pysal/spreg/tests/test_error_sp_het.py,
	  pysal/spreg/tests/test_error_sp_het_sparse.py,
	  pysal/spreg/tests/test_error_sp_hom.py,
	  pysal/spreg/tests/test_error_sp_hom_sparse.py,
	  pysal/spreg/tests/test_error_sp_sparse.py,
	  pysal/spreg/tests/test_ols.py,
	  pysal/spreg/tests/test_ols_sparse.py,
	  pysal/spreg/tests/test_probit.py,
	  pysal/spreg/tests/test_twosls.py,
	  pysal/spreg/tests/test_twosls_sp.py,
	  pysal/spreg/tests/test_twosls_sp_sparse.py,
	  pysal/spreg/tests/test_twosls_sparse.py,
	  pysal/spreg/twosls.py,
	  pysal/spreg/twosls_sp.py,
	  pysal/spreg/user_output.py,
	  pysal/spreg/utils.py: -Adding classic probit regression class -Adding spatial diagnostics for probit -Allowing x parameter to be either a numpy array or scipy sparse matrix in all regression classes -Adding additional unit tests -Various refactoring to streamline code base and improve long term maintainability -Contributions from Luc Anselin, Pedro Amaral, Daniel Arribas-Bel, David Folch and Nicholas Malizia

2012-07-03 18:59  sjsrey

	* pysal/spatial_dynamics/markov.py,
	  pysal/spatial_dynamics/tests/test_markov.py: - refactor significant move_types for clarity and fixing a logic bug


2012-06-20 04:50  sjsrey@gmail.com

	* doc/source/developers/docs/index.txt:
	  - added section for how to write a tutorial for new modules 
2012-06-20 02:45  sjsrey

	* doc/source/developers/docs/index.txt:
	  - updating doc building instructions

2012-06-06 18:58  phil.stphns

	* .build-osx10.6-py26.sh,
	  .build-osx10.6-py27.sh:
	  - local modifications for Frameworks builds

2012-06-05 20:56  phil.stphns

	* .build-osx10.6-py26.sh,
	  .build-osx10.6-py27.sh,
	  .build-osx10.7-py27.sh, .runTests.sh:
	  - adding experimental build and test scripts.

2012-06-05 16:43  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py,
	  pysal/contrib/spatialnet/spatialnet.py:
	  initial snap function for spatialnet

2012-06-05 16:38  schmidtc

	* pysal/core/IOHandlers/pyShpIO.py,
	  pysal/core/util/shapefile.py,
	  pysal/core/util/tests/test_shapefile.py: Adding PolygonZ support to Shapefile IO

2012-05-24 21:57  sjsrey

	* pysal/esda/mapclassify.py: - truncate option for fisher_jenks sampling

2012-05-15 20:08  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py: Added query to SegmentLocator

2012-05-11 22:17  sjsrey

	* pysal/esda/mapclassify.py: - added Fisher_Jenks_Sampled

2012-05-11 00:45  mhwang4

	* pysal/contrib/network/distances.csv,
	  pysal/contrib/network/simulator.py,
	  pysal/contrib/network/test_lincs.py,
	  pysal/contrib/network/test_weights.py,
	  pysal/contrib/network/weights.py: adding test code for distance-file-based weight generator; updates on simulator 

2012-05-10 22:37  mhwang4

	* pysal/contrib/network/klincs.py,
	  pysal/contrib/network/lincs.py,
	  pysal/contrib/network/test_klincs.py,
	  pysal/contrib/network/test_lincs.py: adding test code for network-constrained lisa

2012-05-10 21:11  mhwang4

	* pysal/contrib/network/crimes.dbf,
	  pysal/contrib/network/crimes.shp,
	  pysal/contrib/network/crimes.shx,
	  pysal/contrib/network/test_klincs.py: test code for local K function

2012-05-08 18:05  mhwang4

	* pysal/contrib/network/streets.dbf,
	  pysal/contrib/network/streets.shp,
	  pysal/contrib/network/streets.shx,
	  pysal/contrib/network/test_network.py: adding a test data set

2012-05-08 16:34  schmidtc

	* pysal/cg/segmentLocator.py,
	  pysal/cg/shapes.py,
	  pysal/core/FileIO.py: Adding start of segmentLocator, adding minimal slicing support to FileIO


2012-05-03 17:03  schmidtc

	* pysal/cg/shapes.py,
	  pysal/cg/tests/test_shapes.py: Adding solve for x support to Line. Cleaning up LineSegment's Line method.

2012-04-20 17:48  schmidtc

	* pysal/cg/shapes.py: adding arclen method to Chain object.

2012-04-19 16:37  dfolch

	* pysal/weights/Distance.py: reducing number of distance queries in Kernel from n^2 to n

2012-04-17 21:20  schmidtc

	* pysal/contrib/spatialnet/spatialnet.py: adding distance

2012-04-17 19:46  schmidtc

	* pysal/contrib/spatialnet/cleanNetShp.py,
	  pysal/contrib/spatialnet/spatialnet.py: Adding FNODE/TNODE to dbf when cleaning shapefiles. Added util function createSpatialNetworkShapefile Added SpatialNetwork class

2012-04-17 15:32  schmidtc

	* pysal/contrib/weights_viewer/weights_viewer.py: "revert back to the background when the point is outside of any unit" - request from serge

2012-04-11 02:50  schmidtc

	* pysal/cg/kdtree.py: Fixing user submitted bug,issue #206.

2012-04-10 22:00  dreamessence

	* pysal/weights/Wsets.py: Including w_clip in __all__

2012-04-10 21:58  dreamessence

	* pysal/weights/Wsets.py: Adding w_clip method to clip W matrices (sparse and/or pysal.W) with a second (binary) matrix

2012-04-10 21:57  schmidtc

	* pysal/contrib/spatialnet/beth_roads.shp,
	  pysal/contrib/spatialnet/beth_roads.shx,
	  pysal/contrib/spatialnet/cleanNetShp.py: Adding network shapefile cleaning tools and temporary sample data.  

2012-04-10 21:48  sjsrey

	* pysal/contrib/spatialnet/util.py: - more stubs for util mod

2012-04-10 19:58  sjsrey

	* pysal/contrib/spatialnet/util.py: - start of util module

2012-04-03 20:43  sjsrey

	* pysal/contrib/spatialnet: - new contrib module - integrate geodanet functional (move over from network) - wrap networkx

2012-04-03 01:21  schmidtc

	* pysal/cg/rtree.py: Adding pickle support to RTree


2012-03-28 23:27  mhwang4 
	* pysal/contrib/network/kernel.py,
	  pysal/contrib/network/kfuncs.py,
	  pysal/contrib/network/test_access.py,
	  pysal/contrib/network/test_kernel.py,
	  pysal/contrib/network/test_kfuncs.py,
	  pysal/contrib/network/test_network.py: adding examples for network-related modules

2012-03-19 15:33  schmidtc

	* pysal/core/IOHandlers/pyDbfIO.py: Adding support for writing Null dates

2012-03-14 21:04  phil.stphns

	* doc/source/developers/testing.txt,
	  doc/source/users/installation.txt: Small changes to user install instructions to highlight the ease with which pysal can be installed ;-> And, developer instructions for running the test suite from within a session if desired.

2012-03-03 00:00  phil.stphns

	* pysal/spatial_dynamics/markov.py: Potential source of dev docs pngmath latex fail.

2012-02-24 23:29  mhwang4

	* pysal/contrib/network/network.py: fixing bug in network.py

2012-02-20 19:50  phil.stphns

	* doc/source/developers/py3k.txt: Developer doc to explain setting up PySAL for Python3.

2012-02-20 16:18  schmidtc

	* pysal/esda/__init__.py: removing invalid __all__ from esda's init.  See #194

2012-02-16 23:15  phil.stphns

	* pysal/__init__.py,
	  pysal/core/util/shapefile.py: Minor changes to imports that cause py3tool to stumble.

2012-02-15 23:16  phil.stphns

	* doc/source/developers/py3k.txt,
	  doc/source/users/installation.txt: Modified links in user installation instructions.  Added more steps for developers setting up Python3 dev environments on OSX.

2012-02-14 21:55  schmidtc

	* pysal/esda/getisord.py: fixing side effect caused when changing the shape of y, creating a new view with reshape instead.

2012-02-14 21:21  schmidtc

	* pysal/esda/getisord.py: optimizing G_Local

2012-02-14 20:37  schmidtc

	* pysal/esda/getisord.py: optimizing G

2012-02-14 00:21  phil.stphns

	* doc/source/developers/index.txt,
	  doc/source/developers/py3k.txt,
	  doc/source/developers/release.txt: Adding early docs on Python 3 support. Modifying release instructions.

# v<1.3.0>, 2012-01-31

    * core/IOHandlers/pyDbfIO.py: Addressing issue #186

    * cg/shapes.py: fixing small bug in polygon constructor that causes
      an exception when an empty list is passed in for the holes.

    * cg/standalone.py: removing standalone centroid method. see issue
      #138.

    * esda/mapclassify.py, esda/tests/test_mapclassify.py: - new
      implementation of fisher jenks

    * spreg/__init__.py, spreg/diagnostics_sp.py,
      spreg/diagnostics_tsls.py, spreg/error_sp.py,
      spreg/error_sp_het.py, spreg/error_sp_hom.py, spreg/ols.py,
      spreg/robust.py, spreg/tests, spreg/twosls.py,
      spreg/twosls_sp.py, spreg/user_output.py, spreg/utils.py: Adding
      the following non-spatial/spatial regression modules:
      * Two Stage Least Squares
      * Spatial Two Stage Least Squares
      * GM Error (KP 98-99)
      * GM Error Homoskedasticity (Drukker et. al, 2010)
      * GM Error Heteroskedasticity (Arraiz et. al, 2010)
      * Anselin-Kelejian test for residual spatial autocorrelation of
      residuals from IV regression
      
      Adding also utility functions and other helper classes.
      
    * cg/standalone.py: slight improvment to get_shared_segments, in
      part to make it more readable.

    * cg/shapes.py, cg/tests/test_standalone.py: adding <,<=,>,>= tests
      to Point, this fixes a bug in the get_shared_segments function
      that was causing some LineSegments to be incorectly ordered
      because the default memory address was being used instead of the
      points location.

    * core/IOHandlers/tests/test_wkt.py, core/IOHandlers/wkt.py,
      core/util/tests/test_wkt.py, core/util/wkt.py,
      weights/tests/test_Distance.py, weights/tests/test_user.py,
      weights/user.py: Fixing small numerical errors n testing that
      resulted from changing the centroid algorithm.

    * esda/moran.py: another optimization for __crand see issue #188

    * weights/util.py: Added option for row-standardized SW in lat2SW.
      Implementing suggestion from Charlie in Issue 181 from
      StackOverflow

    * esda/moran.py: another optimization to __crand, see issue #188
      for details.

    * esda/moran.py: Optimized __crand in Local_Moran

    * cg/shapes.py, cg/standalone.py, contrib/shapely_ext.py:
      Adddressing issue #138, centroids for polygons with holes
      Fixing some issues with the shapely wrapper and out implemenation
      of __geo_interface__

    * weights/Distance.py: previous 'fix' to uniform kernel did not
      have correct dimensions

    * core/IOHandlers/arcgis_txt.py, core/IOHandlers/dat.py,
      weights/user.py: fixing rounding errors with docstrings

    * contrib/README, contrib/shared_perimeter_weights.py: Adding
      shared perimeter weights, see Issue #46

    * contrib/README, contrib/shapely_ext.py: moving shapely_ext into
      contrib

    * core/IOHandlers/pyDbfIO.py: Fixing issue with scientific notation
      is DBF files. #182

    * core/IOHandlers/pyShpIO.py: clockwise testing should only be
      performed on Polygons. #183

    * spreg/diagnostics_sp.py: Switching ints to floats in variance of
      Morans I for residuals to get correct results

    * core/util/shapefile.py, examples/__init__.py: Add a "get_path"
      function to examples module.
      pysal.examples.get_path('stl_hom.shp') will always return the
      correct system path to stl_hom.shp, no matter where it's run
      from. This is useful for testing.
      Modified shapefile tests to use the new function.

    * spreg/diagnostics.py: Adding check on condition_index to pick OLS
      (xtx) or IV (hth) model

    * core/IOHandlers/template.py: Updating template to pass unit
      testing.

    * core/util/shapefile.py: Fixing issue #180. Making shapefile
      opener case insensitive.

    * spatial_dynamics/interaction.py,
      spatial_dynamics/tests/test_interaction.py: Adding modified Knox
      and changes to existing tests in spatial_dynamics.

    * core/IOHandlers/arcgis_txt.py,
      core/IOHandlers/tests/test_arcgis_txt.py: fixing arcgis_txt.py so
      that it ignores self-neighbors with zero weights

    * core/FileIO.py: Updating library README.
      Removing docstrings from FileIO module.

    * contrib/README: adding contrib to installer and adding initial
      README

    * core/IOHandlers/gwt.py: rewrote GWT reader to avoid list appends.
      resulted in speed up of about 12x.

    * core/IOHandlers/pyDbfIO.py: implementing _get_col for dbf files.

    * core/IOHandlers/gwt.py: Adding a small fix to gwt reader, if the
      ids cannot be found in the associated DBF, they will be read in
      order from the GWT file.

    * contrib/weights_viewer/weights_viewer.py: Small change to
      identify polygons that are their own neighbor.

    * weights/Distance.py: removing incorrect kernel functions and
      fixing bug in uniform kernel

    * weights/util.py: refactoring insert_diagonal so that it can add
      or overwrite the diagonal weights

    * contrib, contrib/README, contrib/__init__.py,
      contrib/weights_viewer, contrib/weights_viewer/__init__.py,
      contrib/weights_viewer/transforms.py,
      contrib/weights_viewer/weights_viewer.py: Adding 1st contrib, a
      wxPython based Weights file viewer.


    * spatial_dynamics/markov.py: - handle case of zero transitions in
      spatial markov, consistent with treatment
      in classic markov

    * core/FileIO.py, core/IOHandlers/pyShpIO.py: Changes to allow
      reading of null polygons.

    * core/util/shapefile.py, core/util/tests/test_shapefile.py:
      refactoring shapefile reader, see issue #89

    * core/FileIO.py: small change to FileIO to allow FileFormat
      argument to be passed through

    * esda/getisord.py: fixing bug in local Z values for integer data

    * cg/__init__.py, weights/user.py, weights/util.py: adding radius
      option to user weights methods

    * cg/kdtree.py, common.py, weights/Distance.py,
      weights/tests/test_Distance.py: Distance weights can not be
      passed an instnace of KDTree instead of an array. If the KDTree
      is of type ArcKDTree, the weights returns will be based on
      ArcDistances. Adding tests for Arc cases off KNN and
      DistanceBand.

    * weights/util.py: - added function for local clustering
      coefficient - summary for W as a graph

    * cg/kdtree.py, cg/sphere.py: finishing up Arc_KDTree

    * weights/Distance.py: More doctest fixes.

    * region/maxp.py, spreg/diagnostics.py, weights/Distance.py,
      weights/user.py: Fixing the doctests for dusty python setup.

    * cg/kdtree.py, cg/sphere.py: adding spherical wrapper around scipy
      kdtree

    * cg/__init__.py, cg/sphere.py: Adding spherical distance tools to
      cg. Related to issue #168

    * core/IOHandlers/gwt.py, core/IOHandlers/tests/test_gwt.py:
      re-enabled gwt writing.
      'o' transform is used on all GWTs for writing (w is returned to
      existing transform on exit)
      Also, setting '_shpName' and '_varName' attributes on W's which
      are read in through gwt.
      the writer will check if these vars exist and use them for the
      header, this prevents metadata loss on simple copies

    * esda/join_counts.py: - fix for handling int array type

    * spreg/diagnostics.py: Adding more efficient constant check for
      spreg.

    * cg/shapes.py: adding __geo_interface__ and asShape adapter for
      Point, LineString and Polygon

    * spreg/diagnostics.py: minor change to t-stat function to
      accommodate future regression models

    * esda/mapclassify.py: - more general fix for #166


# v<1.2.0>, 2011-07-31

    * pysal/spreg/user_output.py: Fix for bug 162

    * pysal/spatial_dynamics/markov.py: Added markov mobility measures; addresses issue 137

    * pysal/weights/weights.py: Partially addressed issue 160 by removing the shimbel, order, and higher_order methods from W. 

    * doc/source/users/installation.txt: Adding known issue regarding GNU/Linux testing and random seeds; see ticket 52.

    * pysal/esda/geary.py: Adding sparse implementation of Geary's C; substantial gains on larger datasets. 

    * pysal/core/IOHandlers/mtx.py: Adding WSP2W function for fast conversion of sparse weights object (WSP) to pysal W.

    * pysal/esda/getisord.py: Adding Getis-Ord G test module

    * pysal/weights/util.py: Added function that inserts values along the main diagonal of a weights object

    * doc/source/users/tutorials: Fixed issue 76.

    * pysal/core/IOHandlers/mtx.py: Added an IOHandler for MatrixMarket MTX files

    * pysal/esda/moran.py: Optimized conditional randomization

    * pysal/weights/util.py: Re-adding full2W() method to convert full arrays into W objects; related to issue #136. 

    * pysal/core/IOHandlers/gal.py: Added sparse WSP (thin W); gal reader can return W or WSP

    * pysal/core/IOHandlers/pyDbfIO.py: Bug Fix, DBF files are not properly closed when opened in 'r' mode. See issue #155.

    * pysal/core/IOHandlers/stata_txt.py: Adding FileIO handlers for STATA text files

    * pysal/weights/user.py: Fixed issue #154, adding k option to User Kernel weights functions.

    * pysal/core/IOHandlers/mat.py: Adding an IOHandler for MATLAB mat file

    * pysal/core/IOHandlers/wk1.py: Adding an IO handler for wk1 file

    * pysal/core/IOHandlers/geobugs_txt.py: Adding an IO handler for geobugs text file.

    * pysal/core/IOHandlers/arcgis_swm.py: Added ArcGIS SWM file handler

    * pysal/core/IOHandlers/arcgis_dbf.py: Adding a spatial weights file in the (ArcGIS-style) DBF format. 

    * pysal/core/IOHandlers/arcgis_txt.py: Added ArcGIS ASCII file IO handler. 

    * pysal/core/IOHandlers/dat.py: Added DAT file handler.

    * pysal/cg/locators.py: Added point in polygon method for Polygon and PolygonLocator

    * pysal/weights/Distance.py: Optimized Kernel() method to run much faster for the case of adaptive bandwidths

    * pysal/weights/user.py: Added helper function in user.py to create scipy sparse matrix from a gal file

    * pysal/common.py: Added shallow copy method to Read-Only Dict to support multiprocessing.

    * pysal/spatial_dynamics/rank.py: More efficient regime weights

    * pysal/weights/Distance.py: Adding epanechnikov and bisquare kernel funtions

    * pysal/core/IOHandlers/pyDbfIO.py: Adding NULL support to numerical DBF fields; modifying PointLocator API to match PolygonLocator API 

    * pysal/cg/locators.py: Handles case when query rectangle is completely inside a polygon

    * pysal/cg/locators.py: Explicit polygon overlap hit test

    * pysal/cg/standalone.py: Adding point-polygon intersection support for polygons with holes.

    * pysal/spatial_dynamics/markov.py: Added homogeneity test.

    * pysal/spatial_dynamics/markov.py: Added spillover test in LISA_Markov.

    * pysal/cg/locators.py: Added Rtree based spatial index for polygonlocator.

    * pysal/cg/rtree.py: Added pure python Rtree module.

    * doc/source/developers/pep/pep-0010.txt: Added PEP 0010: Rtree module in pure python.

    * pysal/esda/geary.py: Fixed bug 144.

    * pysal/spatial_dynamics/markov.py: Added significance filtering of LISA markov.

    * doc/source/developers/pep/pep-0009.txt: Added new PEP, "PEP 0009: Add Python 3.x Support."

    * doc/source/developers/guidelines.txt: New release cycle schedules for 1.2 and 1.3.

    * doc/source/developers/release.txt: Updated pypi instructions; PySAL available on the Python Package Index via download, easy_install, and pip. 

# v<1.1.0>, 2011-01-31

    * pysal/core/FileIO.py, pysal/core/IOHandlers/pyDbfIO.py: Added missing value support to FileIO. Warnings will be issued when missing values are found and the value will be set to pysal.MISSINGVALUE, currently None, but the user can change it as needed.

    * pysal/spreg/: Added Spatial Regression module, spreg, and tests.  Added non-spatial diagnostic tests for OLS regression. 

    * pysal/core/IOHandlers/gwt.py: Fixing bottle neck in gwt reader, adding support for GeoDa Style ID's and DBF id_order.

    * pysal/cg/standalone.py: adding, distance_matrix, full distance matrix calculation using sparse matrices

    * pysal/core/util: Moved "converters" into core.util, allows them to be used independently of FileIO.

    * pysal/weights/Distance.py: Adding work around for bug in scipy spatial, see pysal issue #126

    * pysal/weights/user.py: Added build_lattice_shapefile in weights.user, which writes an ncol by nrow grid to a shapefile.

    * pysal/weights/Distance.py: fixed coincident point problem in knnW and made sure it returns k neighbors 
    * pysal/spatial_dynamics/interaction.py: Added a suite of spatio-temporal interaction tests including the Knox, Mantel, and Jacquez tests. 

    * pysal/weights/util.py: Added lat2SW, allows to create a sparse W matrix for a regular lattice.

    * pysal/tests/tests.py: - new 1.1 integration testing scheme.

    * pysal/esda/interaction.py: added standardized Mantel test and improved readability.

    * pysal/spatial_dynamics/directional.py: - adding directional LISA analytics

    * pysal/esda/mapclassify.py: Natural_Breaks will lower k for data with fewer than k unique values, prints warning.

    * pysal/region/randomregion.py: improvements to spatially constrained random region algorithm

    * pysal/esda/smoothing.py: Adding choynowski probabilities and SMR to smoothing.py

    * doc/source/developers/release.txt: - updating release cycle - release management

# v<1.0.0>, 2010-07-31 -- Initial release.
