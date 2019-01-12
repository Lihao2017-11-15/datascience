# Data Science [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

#### Core
[pandas](https://pandas.pydata.org/) | Data structures and data analysis tools for Python built on top of [numpy](https://www.numpy.org/).  
[scikit-learn](https://scikit-learn.org/stable/) | Core ML library.  
[matplotlib](https://matplotlib.org/) | Plotting library.  
[seaborn](https://seaborn.pydata.org/) | Python data visualization library based on matplotlib.  
[pandas_summary](https://github.com/mouradmourafiq/pandas-summary) | Basic statistics using `DataFrameSummary(df).summary()`.   
[pandas_profiling](https://github.com/pandas-profiling/pandas-profiling) | Descriptive statistics using `ProfileReport`.  
[sklearn_pandas](https://github.com/scikit-learn-contrib/sklearn-pandas) | Helpful `DataFrameMapper` class.   
[janitor](https://pyjanitor.readthedocs.io/) | Clean messy column names.   
[missingno](https://github.com/ResidentMario/missingno) | Missing data visualization.   

#### Pandas and Jupyter
General ticks: [link](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)  
[modin](https://github.com/modin-project/modin) | Parallelization library for faster pandas `DataFrame`.   
[xarray](https://github.com/pydata/xarray/) | Extends pandas to n-dimensional arrays.  
[blackcellmagic](https://github.com/csurfer/blackcellmagic) | Code formatting for jupyter notebooks.  
[pivottablejs](https://github.com/nicolaskruchten/jupyter_pivottablejs) | Drag n drop Pivot Tables and Charts for jupyter notebooks.  
[qgrid](https://github.com/quantopian/qgrid) | Pandas `DataFrame` sorting.     
[nbdime](https://github.com/jupyter/nbdime) | Diff two notebook files, Alternative Github App: [ReviewNB](https://www.reviewnb.com/).   

#### Extraction
[textract](https://github.com/deanmalmgren/textract) | Extract text from any document.   

#### Big Data
[spark](https://docs.databricks.com/spark/latest/dataframes-datasets/introduction-to-dataframes-python.html#work-with-dataframes) | `DataFrame` for big data.
[spark cheatsheet](https://gist.github.com/crawles/b47e23da8218af0b9bd9d47f5242d189)
[dask](https://github.com/dask/dask) | Pandas `DataFrame` for big data.  
[dask-ml](http://ml.dask.org/) | Scalable machine learning.  
[turicreate](https://github.com/apple/turicreate) | Helpful `SFrame` class for out-of-memory dataframes.  
[h2o](https://github.com/h2oai/h2o-3) | Helpful `H2OFrame` class for out-of-memory dataframes.  
[ray](https://github.com/ray-project/ray/) | Flexible, high-performance distributed execution framework.  
[sparkit-learn](https://github.com/lensacom/sparkit-learn) | PySpark + Scikit-learn

##### Command line tools
[ni](https://github.com/spencertipping/ni) | Command line tool for big data.  
[xsv](https://github.com/BurntSushi/xsv) | Command line tool for indexing, slicing, analyzing, splitting and joining CSV files.  
[csvkit](https://csvkit.readthedocs.io/en/1.0.3/) | Another command line tool for CSV files.  
[csvsort](https://pypi.org/project/csvsort/) | Sort large csv files.  

#### Exploration and Cleaning
[fancyimpute](https://github.com/iskandr/fancyimpute) | Matrix completion and imputation algorithms.  
[imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) | Resampling for imbalanced datasets.  
[tspreprocess](https://github.com/MaxBenChrist/tspreprocess) | Time series preprocessing: Denoising, Compression, Resampling.   

#### Feature Engineering
[sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html) | Pipeline, [examples](https://github.com/jem1031/pandas-pipelines-custom-transformers).  
[skoot](https://github.com/tgsmith61591/skoot) | Pipeline helper functions.  
[categorical-encoding](https://github.com/scikit-learn-contrib/categorical-encoding) | Categorical encoding of variables.  
[patsy](https://github.com/pydata/patsy/) | R-like syntax for statistical models.   
[mlxtend](https://rasbt.github.io/mlxtend/user_guide/feature_extraction/LinearDiscriminantAnalysis/) | LDA.  
[featuretools](https://github.com/Featuretools/featuretools) | Automated feature engineering, [example](https://github.com/WillKoehrsen/automated-feature-engineering/blob/master/walk_through/Automated_Feature_Engineering.ipynb).   
[tsfresh](https://github.com/blue-yonder/tsfresh) | Time series feature engineering.  

#### Feature Selection
[Tutorial](https://machinelearningmastery.com/feature-selection-machine-learning-python/), [Talk](https://www.youtube.com/watch?v=JsArBz46_3s)  
[scikit-feature](https://github.com/jundongl/scikit-feature) | Feature selection algorithms.  
[stability-selection](https://github.com/scikit-learn-contrib/stability-selection) | Stability selection.  
[scikit-rebate](https://github.com/EpistasisLab/scikit-rebate) | Relief-based feature selection algorithms.  
[boruta_py](https://github.com/scikit-learn-contrib/boruta_py) | Feature selection, [explaination](https://stats.stackexchange.com/questions/264360/boruta-all-relevant-feature-selection-vs-random-forest-variables-of-importanc/264467), [example](https://www.kaggle.com/tilii7/boruta-feature-elimination).  
[linselect](https://github.com/efavdb/linselect) | Feature selection package.   


#### Dimensionality Reduction
[prince](https://github.com/MaxHalford/prince) | Dimensionality reduction, factor analysis (PCA, MCA, CA, FAMD).  
[sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.MDS.html) | Multidimensional scaling.  
[sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html) | t-distributed Stochastic Neighbor Embedding. Faster implementations: [lvdmaaten](https://lvdmaaten.github.io/tsne/), [MulticoreTSNE](https://github.com/DmitryUlyanov/Multicore-TSNE).  
[sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html) | Truncated SVD (aka LSA).   
[mdr](https://github.com/EpistasisLab/scikit-mdr) | Dimensionality reduction, multifactor dimensionality reduction (MDR).  
[umap](https://github.com/lmcinnes/umap) | Uniform Manifold Approximation and Projection.  

#### Visualization
[All charts](https://datavizproject.com/), [Austrian monuments](https://github.com/njanakiev/austrian-monuments-visualization).  
[physt](https://github.com/janpipek/physt) | Better histograms, [talk](https://www.youtube.com/watch?v=ZG-wH3-Up9Y).  
[yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) | Wrapper for matplotlib for diagnosic ML plots.  
[bokeh](https://bokeh.pydata.org/en/latest/) | Interactive visualization library, [All plots](https://demo.bokehplots.com/), [Examples](https://bokeh.pydata.org/en/latest/docs/user_guide/server.html), [Examples](https://github.com/WillKoehrsen/Bokeh-Python-Visualization).   
[altair](https://altair-viz.github.io/) | Declarative statistical visualization library.  
[holoviews](http://holoviews.org/) | Visualization library.  
[plotly](https://plot.ly/) | Visualization library.  
[dtreeviz](https://github.com/parrt/dtreeviz) | Decision tree visualization and model interpretation.  
[chartify](https://github.com/spotify/chartify/) | Generate charts.   
[panel](https://panel.pyviz.org/index.html) | Dashboarding solution.  
[dash](https://dash.plot.ly/gallery) | Dashboarding solution.  
[VivaGraphJS](https://github.com/anvaka/VivaGraphJS) | Graph visualization (JS package).   
[pm](https://github.com/anvaka/pm) | Navigatable 3D graph visualization (JS package), [example](https://w2v-vis-dot-hcg-team-di.appspot.com/#/galaxy/word2vec?cx=5698&cy=-5135&cz=5923&lx=0.1127&ly=0.3238&lz=-0.1680&lw=0.9242&ml=150&s=1.75&l=1&v=hc).   
[visdom](https://github.com/facebookresearch/visdom) | Dashboarding library.   
[python-ternary](https://github.com/marcharper/python-ternary) | Triangle plots.  

#### Geopraphical Tools
[folium](https://github.com/python-visualization/folium) | Plot geographical maps using the Leaflet.js library.  
[stadiamaps](https://stadiamaps.com/) | Plot geographical maps.  
[datashader](https://github.com/bokeh/datashader) | Draw millions of points on a map.  
[sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.BallTree.html) | BallTree, [Example](https://tech.minodes.com/experiments-with-in-memory-spatial-radius-queries-in-python-e40c9e66cf63).  
[pynndescent](https://github.com/lmcinnes/pynndescent) | Nearest neighbor descent for approximate nearest neighbors.  
[geocoder](https://github.com/DenisCarriere/geocoder) | Geocoding of addresses, IP addresses.  
Conversion of different geo formats: [talk](https://www.youtube.com/watch?v=eHRggqAvczE), [repo](https://github.com/dillongardner/PyDataSpatialAnalysis)   
[geopandas](https://github.com/geopandas/geopandas) | Tools for geographic data    
Low Level Geospatial Tools (GEOS, GDAL/OGR, PROJ.4)   
Vector Data (Shapely, Fiona, Pyproj)  
Raster Data (Rasterio)   
Plotting (Descartes, Catropy)   
Predict economic indicators from Open Street Map [ipynb](https://github.com/njanakiev/osm-predict-economic-measurements/blob/master/osm-predict-economic-indicators.ipynb).  

#### Recommender Systems
[List](https://github.com/grahamjenson/list_of_recommender_systems)  
Examples: [1](https://lazyprogrammer.me/tutorial-on-collaborative-filtering-and-matrix-factorization-in-python/), [2](https://medium.com/@james_aka_yale/the-4-recommendation-engines-that-can-predict-your-movie-tastes-bbec857b8223), [2-ipynb](https://github.com/khanhnamle1994/movielens/blob/master/Content_Based_and_Collaborative_Filtering_Models.ipynb), [3](https://www.kaggle.com/morrisb/how-to-recommend-anything-deep-recommender).  
[surprise](https://github.com/NicolasHug/Surprise) | Recommender, [talk](https://www.youtube.com/watch?v=d7iIb_XVkZs).  
[turicreate](https://github.com/apple/turicreate) | Recommender.  
[implicit](https://github.com/benfred/implicit) | Fast Python Collaborative Filtering for Implicit Feedback Datasets.  
[spotlight](https://github.com/maciejkula/spotlight) | Deep recommender models using PyTorch.  
[lightfm](https://github.com/lyst/lightfm) | Recommendation algorithms for both implicit and explicit feedback.  


#### Decision Trees
[lightgbm](https://github.com/Microsoft/LightGBM) | Gradient boosting (GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, [doc](https://sites.google.com/view/lauraepp/parameters).  
[xgboost](https://github.com/dmlc/xgboost) | Gradient boosting (GBDT, GBRT or GBM) library, [doc](https://sites.google.com/view/lauraepp/parameters).  
[catboost](https://github.com/catboost/catboost) | Gradient boosting.  
[h2o](https://github.com/h2oai/h2o-3) | Gradient boosting.   
[forestci](https://github.com/scikit-learn-contrib/forest-confidence-interval) | Confidence intervals for random forests.  
[scikit-garden](https://github.com/scikit-garden/scikit-garden) | Quantile Regression.  
[grf](https://github.com/grf-labs/grf) | Generalized random forest.  
[dtreeviz](https://github.com/parrt/dtreeviz) | Decision tree visualization and model interpretation.  
[rfpimp](https://github.com/parrt/random-forest-importances) | Feature Importance for RandomForests using Permuation Importance.  
Why the default feature importance for random forests is wrong: [link](http://explained.ai/rf-importance/index.html)  
[treeinterpreter](https://github.com/andosa/treeinterpreter) | Interpreting scikit-learn's decision tree and random forest predictions.  
[bartpy](https://github.com/JakeColtman/bartpy) | Bayesian Additive Regression Trees.  


#### Natural Language Processing (NLP) / Text Processing
[List: NLP Progress](https://github.com/sebastianruder/NLP-progress), [List: Awesome Sentence Embedding](https://github.com/Separius/awesome-sentence-embedding).   
[talk](https://www.youtube.com/watch?v=6zm9NC9uRkk)-[nb](https://nbviewer.jupyter.org/github/skipgram/modern-nlp-in-python/blob/master/executable/Modern_NLP_in_Python.ipynb), [nb2](https://ahmedbesbes.com/how-to-mine-newsfeed-data-and-extract-interactive-insights-in-python.html), [talk](https://www.youtube.com/watch?time_continue=2&v=sI7VpFNiy_I).   
[Text classification Intro](https://mlwhiz.com/blog/2018/12/17/text_classification/).    
[gensim](https://radimrehurek.com/gensim/) | NLP, doc2vec, word2vec, text processing, topic modelling (LSA, LDA), [Example](https://markroxor.github.io/gensim/static/notebooks/gensim_news_classification.html), [Coherence Model](https://radimrehurek.com/gensim/models/coherencemodel.html) for evaluation.  
Embeddings | [GloVe](https://nlp.stanford.edu/projects/glove/) ([[1](https://www.kaggle.com/jhoward/improved-lstm-baseline-glove-dropout)], [[2](https://www.kaggle.com/sbongo/do-pretrained-embeddings-give-you-the-extra-edge)]), [StarSpace](https://github.com/facebookresearch/StarSpace), [wikipedia2vec](https://wikipedia2vec.github.io/wikipedia2vec/pretrained/).   
[pyldavis](https://github.com/bmabey/pyLDAvis) | Visualization for topic modelling.  
[spaCy](https://spacy.io/) | NLP.   
[NTLK](https://www.nltk.org/) | NLP, helpful `KMeansClusterer` with `cosine_distance`.    
[pytext](https://github.com/facebookresearch/PyText) | NLP from Facebook.   
[fastText](https://github.com/facebookresearch/fastText) | Efficient text classification and representation learning.  
[annoy](https://github.com/spotify/annoy) | Approximate nearest neighbor search.  
[faiss](https://github.com/facebookresearch/faiss) | Approximate nearest neighbor search.  
[pysparnn](https://github.com/facebookresearch/pysparnn) | Approximate nearest neighbor search.  
[infomap](https://github.com/mapequation/infomap) | Cluster (word-)vectors to find topics, [example](https://github.com/mapequation/infomap/blob/master/examples/python/infomap-examples.ipynb).   
[textract](https://github.com/deanmalmgren/textract) | Extract text from any document.   
[datasketch](https://github.com/ekzhu/datasketch) | Probabilistic data structures for large data (MinHash, HyperLogLog).   
[flair](https://github.com/zalandoresearch/flair) | NLP Framework by Zalando.   

##### Papers
[Search Engine Correlation](https://arxiv.org/pdf/1107.2691.pdf)

#### Automated Machine Learning
[AdaNet](https://github.com/tensorflow/adanet) | Automated machine learning based on tensorflow.  
[tpot](https://github.com/EpistasisLab/tpot) | Automated machine learning tool, optimizes machine learning pipelines.  
[auto_ml](https://github.com/ClimbsRocks/auto_ml) | Automated machine learning for analytics & production.  

#### Evolutionary Algorithms & Optimization
[deap](https://github.com/DEAP/deap) | Evolutionary computation framework (Genetic Algorithm, Evolution strategies).  
[evol](https://github.com/godatadriven/evol) | DSL for composable evolutionary algorithms, [talk](https://www.youtube.com/watch?v=68ABAU_V8qI&t=11m49s).  
[platypus](https://github.com/Project-Platypus/Platypus) | Multiobjective optimization.  
[nevergrad](https://github.com/facebookresearch/nevergrad) | Derivation-free optimization.   

#### Neural Networks
[Intro](https://karpathy.github.io/neuralnets/), [Another Intro](http://d2l.ai/chapter_crashcourse/autograd.html), [List](https://github.com/ChristosChristofidis/awesome-deep-learning)   
[keras](https://keras.io/) | Neural Networks on top of [tensorflow](https://www.tensorflow.org/).   
[hyperas](https://github.com/maxpumperla/hyperas) | Keras + Hyperopt: Convenient hyperparameter optimization wrapper.   
[elephas](https://github.com/maxpumperla/elephas) | Distributed Deep learning with Keras & Spark.   
[tflearn](https://github.com/tflearn/tflearn) | Neural Networks on top of tensorflow.   
[tensorlayer](https://github.com/tensorlayer/tensorlayer) |  Neural Networks on top of tensorflow, [tricks](https://github.com/wagamamaz/tensorlayer-tricks).   
[tensorforce](https://github.com/reinforceio/tensorforce) | Tensorflow for applied reinforcement learning.   

#### Regression
[pyearth](https://github.com/scikit-learn-contrib/py-earth) | Multivariate Adaptive Regression Splines (MARS), [tutorial](https://uc-r.github.io/mars).  
[pygam](https://github.com/dswah/pyGAM) | Generalized Additive Models (GAMs), [Explanation](https://multithreaded.stitchfix.com/blog/2015/07/30/gam/).  

#### Clustering
[pyclustering](https://github.com/annoviko/pyclustering) | All sorts of clustering algorithms.  
[somoclu](https://github.com/peterwittek/somoclu) | Self-organizing map.  
[hdbscan](https://github.com/scikit-learn-contrib/hdbscan) | Clustering algorithm.  
[nmslib](https://github.com/nmslib/nmslib) | Dimilarity search library and toolkit for evaluation of k-NN methods.   

#### Interpretable Classifiers and Regressors
[sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys) | Interpretable classifiers, producing easily understood decision rules instead of black box models.  
[sklearn-interpretable-tree](https://github.com/tmadl/sklearn-interpretable-tree) | Simplified tree-based classifier and regressor for interpretable machine learning.  
[skope-rules](https://github.com/scikit-learn-contrib/skope-rules) | Interpretable classifier, IF-THEN rules.  

#### Multi-label classification
[scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn) | Multi-label classification, [talk](https://www.youtube.com/watch?v=m-tAASQA7XQ&t=18m57s).  

#### Time Series
[List](https://github.com/MaxBenChrist/awesome_time_series_in_python), [List](https://github.com/rob-med/awesome-TS-anomaly-detection)    
[statsmodels](https://www.statsmodels.org/dev/tsa.html) | Time series analysis, [seasonal decompose](https://www.statsmodels.org/dev/generated/statsmodels.tsa.seasonal.seasonal_decompose.html) [example](https://gist.github.com/balzer82/5cec6ad7adc1b550e7ee), [SARIMA](https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html), [granger causality](http://www.statsmodels.org/dev/generated/statsmodels.tsa.stattools.grangercausalitytests.html).  
[pyramid](https://github.com/tgsmith61591/pyramid), [pmdarima](https://github.com/tgsmith61591/pmdarima) | Wrapper for (Auto-) ARIMA.   
[pyflux](https://github.com/RJT1990/pyflux) | Time series prediction algorithms (ARIMA, GARCH, GAS, Bayesian).   
[prophet](https://github.com/facebook/prophet) | Time series prediction library.   
[htsprophet](https://github.com/CollinRooney12/htsprophet) | Hierarchical Time Series Forecasting using Prophet.   
[tensorflow](https://github.com/tensorflow/tensorflow/) | LSTM and others, examples: [link](
https://machinelearningmastery.com/time-series-forecasting-long-short-term-memory-network-python/
), [link](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/timeseries), [link](https://github.com/hzy46/TensorFlow-Time-Series-Examples).   
[tspreprocess](https://github.com/MaxBenChrist/tspreprocess) | Preprocessing: Denoising, Compression, Resampling.  
[tsfresh](https://github.com/blue-yonder/tsfresh) | Time series feature engineering.  
[thunder](https://github.com/thunder-project/thunder) | Data structures and algorithms for loading, processing, and analyzing time series data.   
[gatspy](https://www.astroml.org/gatspy/) | General tools for Astronomical Time Series, [talk](https://www.youtube.com/watch?v=E4NMZyfao2c).   
[gendis](https://github.com/IBCNServices/GENDIS) | shapelets, [example](https://github.com/IBCNServices/GENDIS/blob/master/gendis/example.ipynb).  
[tslearn](https://github.com/rtavenar/tslearn) | Time series clustering and classification, `TimeSeriesKMeans`, `TimeSeriesKMeans`.  
[pastas](https://pastas.readthedocs.io/en/latest/examples.html) | Simulation of time series.  
[fastdtw](https://github.com/slaypni/fastdtw) | Dynamic Time Warp Distance.  
[fable](https://www.rdocumentation.org/packages/fable/versions/0.0.0.9000) | Time Series Forecasting (R package).  
[CausalImpact](https://github.com/tcassou/causal_impact) | Causal Impact Analysis ([R package](https://google.github.io/CausalImpact/CausalImpact.html)).  
[PyAF](https://github.com/antoinecarme/pyaf) | Automatic Time Series Forecasting.   
[luminol](https://github.com/linkedin/luminol) | Anomaly Detection and Correlation library from Linkedin.  
[matrixprofile-ts](https://github.com/target/matrixprofile-ts) | Detecting patterns and anomalies.   

#### Financial Data
[pyfolio](https://github.com/quantopian/pyfolio) | Portfolio and risk analytics.  
[zipline](https://github.com/quantopian/zipline) | Algorithmic trading.  
[alphalens](https://github.com/quantopian/alphalens) | Performance analysis of predictive stock factors.  

#### Survival Analysis
[Time-dependent Cox Model in R](https://stats.stackexchange.com/questions/101353/cox-regression-with-time-varying-covariates).  
[lifelines](https://lifelines.readthedocs.io/en/latest/) | Survival analysis, Cox PH Regression, [talk](https://www.youtube.com/watch?v=aKZQUaNHYb0), [talk2](https://www.youtube.com/watch?v=fli-yE5grtY).  
[scikit-survival](https://github.com/sebp/scikit-survival) | Survival analysis.   
[survivalstan](https://github.com/hammerlab/survivalstan) | Survival analysis, [intro](http://www.hammerlab.org/2017/06/26/introducing-survivalstan/).  
[convoys](https://github.com/better/convoys) | Analyze time lagged conversions.   
RandomSurvivalForests (R packages: randomForestSRC, ggRandomForests).   

#### Outlier Detection & Anomaly Detection
[List](https://github.com/rob-med/awesome-TS-anomaly-detection)  
[sklearn](https://scikit-learn.org/stable/modules/outlier_detection.html) | Isolation Forest and others.  
[pyod](https://pyod.readthedocs.io/en/latest/pyod.html) | Outlier Detection / Anomaly Detection.  
[eif](https://github.com/sahandha/eif) | Extended Isolation Forest.  
[AnomalyDetection](https://github.com/twitter/AnomalyDetection) | Anomaly detection (R package).   
[luminol](https://github.com/linkedin/luminol) | Anomaly Detection and Correlation library from Linkedin.  


#### Ranking
[lightning](https://github.com/scikit-learn-contrib/lightning) | Large-scale linear classification, regression and ranking.  

#### Bayes
[Intro](https://erikbern.com/2018/10/08/the-hackers-guide-to-uncertainty-estimates.html), [Guide](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)   
[PyMC3](https://docs.pymc.io/) | Baysian modelling, [intro](https://docs.pymc.io/notebooks/getting_started)  
[pomegranate](https://github.com/jmschrei/pomegranate) | Probabilistic modelling, [talk](https://www.youtube.com/watch?v=dE5j6NW-Kzg).  
[pmlearn](https://github.com/pymc-learn/pymc-learn) | Probabilistic machine learning.  
[arviz](https://github.com/arviz-devs/arviz) | Exploratory analysis of Bayesian models.   


#### Stacking Models
[mlxtend](https://github.com/rasbt/mlxtend) | `EnsembleVoteClassifier`, `StackingRegressor`, `StackingCVRegressor` for model stacking.  
[vecstack](https://github.com/vecxoz/vecstack) | Stacking ML models.  
[StackNet](https://github.com/kaz-Anova/StackNet) | Stacking ML models.   

#### Model Evaluation
[pycm](https://github.com/sepandhaghighi/pycm) | Multi-class confusion matrix.  
[pandas_ml](https://github.com/pandas-ml/pandas-ml) | Confusion matrix.  
Plotting learning curve: [link](http://www.ritchieng.com/machinelearning-learning-curve/).  
[yellowbrick](http://www.scikit-yb.org/en/latest/api/model_selection/learning_curve.html) | Learning curve.  

#### Model Explanation
[List: Awesome Machine Learning Interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability), [Book](https://christophm.github.io/interpretable-ml-book/agnostic.html), [Examples](https://github.com/jphall663/interpretable_machine_learning_with_python)   
[shap](https://github.com/slundberg/shap) | Explain predictions of machine learning models.  
[treeinterpreter](https://github.com/andosa/treeinterpreter) | Interpreting scikit-learn's decision tree and random forest predictions.  
[lime](https://github.com/marcotcr/lime) | Explaining the predictions of any machine learning classifier.  
[lime_xgboost](https://github.com/jphall663/lime_xgboost) | Create LIMEs for XGBoost.  
[FairML](https://github.com/adebayoj/fairml) | Model explanation, feature importance.  
[pybreakdown](https://github.com/MI2DataLab/pyBreakDown) | Generate feature contribution plots.  
[eli5](https://github.com/TeamHG-Memex/eli5) | Inspecting machine learning classifiers and explaining their predictions.  
[pycebox](https://github.com/AustinRochford/PyCEbox) | Individual Conditional Expectation Plot Toolbox.  
[pdpbox](https://github.com/SauceCat/PDPbox) | Partial dependence plot toolbox, [example](https://www.kaggle.com/dansbecker/partial-plots).  
[partial_dependence](https://github.com/nyuvis/partial_dependence) | Visualize and cluster partial dependence.  
[skater](https://github.com/datascienceinc/Skater) | Unified framework to enable model interpretation.  
[anchor](https://github.com/marcotcr/anchor) | High-Precision Model-Agnostic Explanations for classifiers.  
[l2x](https://github.com/Jianbo-Lab/L2X) | Instancewise feature selection as methodology for model interpretation.  
[contrastive_explanation](https://github.com/MarcelRobeer/ContrastiveExplanation) | Contrastive explanations.  

#### Hyperparameter Tuning
[sklearn](https://scikit-learn.org/stable/index.html) | [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html), [RandomizedSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html).  
[hyperopt](https://github.com/hyperopt/hyperopt) | Hyperparameter optimization.  
[skopt](https://scikit-optimize.github.io/) | `BayesSearchCV` for Hyperparameter search.  
[tune](https://ray.readthedocs.io/en/latest/tune.html) | Hyperparameter search with a focus on deep learning and deep reinforcement learning.  
[optuna](https://github.com/pfnet/optuna) | Hyperparamter optimization.  

#### Reinforcement Learning
[Youtube](https://www.youtube.com/playlist?list=PL7-jPKtc4r78-wCZcQn5IqyuWhBZ8fOxT), [Youtube](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs)   
Intro to Monte Carlo Tree Search (MCTS) | [1](https://jeffbradberry.com/posts/2015/09/intro-to-monte-carlo-tree-search/), [2](http://mcts.ai/about/index.html), [3](https://medium.com/@quasimik/monte-carlo-tree-search-applied-to-letterpress-34f41c86e238)         
AlphaZero methodology | [1](https://github.com/AppliedDataSciencePartners/DeepReinforcementLearning), [2](https://web.stanford.edu/~surag/posts/alphazero.html), [3](https://github.com/suragnair/alpha-zero-general), [Cheat Sheet](https://medium.com/applied-data-science/alphago-zero-explained-in-one-diagram-365f5abf67e0)       
[RLLib](https://ray.readthedocs.io/en/latest/rllib.html) | Library for reinforcement learning.  
[Horizon](https://github.com/facebookresearch/Horizon/) | Facebook RL framework.  

#### Frameworks
[h2o](https://github.com/h2oai/h2o-3) | Scalable machine learning.  
[turicreate](https://github.com/apple/turicreate) | Apple Machine Learning Toolkit.  
[astroml](https://github.com/astroML/astroML) | ML for astronomical data.   

#### Lifecycle Management 
[mlflow](https://mlflow.org/) | Manage the machine learning lifecycle, including experimentation, reproducibility and deployment.   
[modelchimp](https://github.com/ModelChimp/modelchimp) | Experiment Tracking.  
[skll](https://github.com/EducationalTestingService/skll) | Command-line utilities to make it easier to run machine learning experiments.   

#### Other
[daft](https://github.com/dfm/daft) | Render probabilistic graphical models using matplotlib.  
[unyt](https://github.com/yt-project/unyt) | Working with units.  
[scrapy](https://github.com/scrapy/scrapy) | Web scraping library.  
[VowpalWabbit](https://github.com/VowpalWabbit/vowpal_wabbit) | ML Toolkit from Microsoft.  

#### General Python Programming
[funcy](https://github.com/Suor/funcy) | Fancy and practical functional tools.  
[more_itertools](https://more-itertools.readthedocs.io/en/latest/) | Extension of itertools.  
[dill](https://pypi.org/project/dill/) | Serialization, alternative to pickle.   
[pendulum](https://github.com/sdispater/pendulum) | Alternative to python datetimes.   
[arrow](https://github.com/crsmithdev/arrow) | Another alternative to python datetimes.   
[pyre](https://www.facebook.com/notes/protect-the-graph/pyre-fast-type-checking-for-python/2048520695388071/) | Static type checking library from facebook.    
[attrs](https://github.com/python-attrs/attrs) | Python classes without boilerplate.  

#### Other Lists
[Awesome AI booksmarks](https://github.com/goodrahstar/my-awesome-AI-bookmarks)  
[Awesome Python Data Science](https://github.com/krzjoa/awesome-python-datascience)   

#### Paradoxes 
Inspection paradox | [link](https://allendowney.blogspot.com/2015/08/the-inspection-paradox-is-everywhere.html), [link](https://jakevdp.github.io/blog/2018/09/13/waiting-time-paradox/)   
Simpsons paradox | [link](https://en.wikipedia.org/wiki/Simpson%27s_paradox)   
Berksons paradox | [link](https://en.wikipedia.org/wiki/Berkson%27s_paradox)    
Base rate fallacy | [link](https://en.wikipedia.org/wiki/Base_rate_fallacy)   
Sampling bias | [link](https://en.wikipedia.org/wiki/Sampling_bias)  

#### Things I google a lot
[Frequency codes for time series](https://pandas.pydata.org/pandas-docs/stable/timeseries.html#offset-aliases)     

