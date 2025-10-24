## Jeremy Magland

Hello! I am a Data Scientist in the [Center for Computational Mathematics](https://www.simonsfoundation.org/flatiron/center-for-computational-mathematics) at the [Flatiron Institute](https://www.simonsfoundation.org/flatiron).

I develop computational tools and open-source software for scientific research, with a focus on data visualization, cloud-based platforms, and making complex datasets more accessible to researchers. My work spans various domains and emphasizes creating portable, reproducible solutions for the scientific community.

Recent presentations:
* [AI Agents for Data Science: How To and Should We?](https://magland.github.io/ai-agents-for-data-science-how-to-and-should-we/) - Flatiron Wide Autumn Meeting, October 2025
* [Figpack Overview: Portable, Interactive Scientific Visualizations](https://magland.github.io/figpack-overview-presentation/)
* [Browser-based collaborative neuroscience: transforming data exploration and analysis through web accessibility](https://users.flatironinstitute.org/~magland/presentations/2025/magland-ODIN-april-2025.pdf) - Open Data In Neuroscience (ODIN) Symposium, April, 2025

Here are a few of my recent projects

### Neurosift

Neurosift is a browser-based tool designed for the visualization of neuroscience data with a focus on NWB (Neurodata Without Borders) files, and enables interactive exploration of the DANDI Archive, EMBER Archive, and OpenNeuro online repositories.

- Live: [Neurosift Live](https://neurosift.app/)
- Source: [Neurosift on GitHub](https://github.com/flatironinstitute/neurosift/tree/main-v2)
- Paper: [Neurosift JOSS Paper](https://joss.theoj.org/papers/10.21105/joss.06590)

With the CatalystNeuro team

### Figpack

figpack is a Python package for creating interactive scientific visualizations that can be displayed directly in web browsers and easily shared. Unlike traditional plotting libraries, figpack produces self-contained HTML bundles that include both the rendering logic and the underlying data. This makes figures portable, reproducible, and suitable for long-term archiving (for example, uploading to Zenodo).

- Home page: [Figpack](https://flatironinstitute.github.io/figpack/)
- Source: [Figpack on GitHub](https://github.com/flatironinstitute/figpack)

[Figpack Slides Demo Presentation](https://magland.github.io/figpack-slides-demo-presentation/)

### Stan Playground

Stan Playground is a browser-based editor and runtime environment for [Stan](https://mc-stan.org/) models. Users can edit, compile, and run models, as well as analyze the results using built-in plots and statistics or custom analysis code in Python or R, all with no local installation required.

- Live: [Stan Playground](https://stan-playground.flatironinstitute.org/)
- Source: [Stan Playground on GitHub](https://github.com/flatironinstitute/stan-playground)
- Forum Post: [Stan Playground on mc-stan.org](https://discourse.mc-stan.org/t/stan-playground-stan-without-installing-stan/37085)

With Brian Ward and Jeff Soules

### DANDI AI Notebooks

An AI-powered system that helps researchers explore and analyze neurophysiology datasets in the [DANDI Archive](https://dandiarchive.org/). It includes a chat assistant for data exploration and an automated notebook generator that creates instructional Python notebooks tailored to specific datasets. This tool makes complex neuroscience data more accessible to researchers by reducing technical barriers to data reuse.

- Preprint: [Facilitating analysis of open neurophysiology data on the DANDI Archive using large language model tools](https://www.biorxiv.org/content/10.1101/2025.07.17.663965v2)

With Ben Dichter, Ryan Ly, and Oliver Ruebel

### Isosplit 6

Isosplit is a non-parametric clustering method that does not require adjustable parameters nor parametric assumptions about the underlying cluster distributions. The only assumption is that clusters are unimodal and separated from one another by hyperplanes of relatively low density. The technique uses a variant of Hartigan's dip statistic and isotonic regression in its kernel operation.

- Source: [Isosplit 6 on GitHub](https://github.com/magland/isosplit6)

### MountainSort 5

Spike sorting software that uses isosplit clustering.

- Source: [Mountainsort 5 on GitHub](https://github.com/flatironinstitute/mountainsort5)

### LINDI

LINDI is a cloud-friendly file format and Python library designed for managing scientific data, especially Neurodata Without Borders (NWB) datasets. It offers an alternative to HDF5 and Zarr, maintaining compatibility with both, while providing features tailored for linking to remote datasets stored in the cloud, such as those on the DANDI Archive. LINDI's unique structure and capabilities make it particularly well-suited for efficient data access and management in cloud environments.

- Source: [LINDI on GitHub](https://github.com/neurodatawithoutborders/lindi)

With Neurodata Without Borders (NWB) team

## simple_ans

A Python package that provides efficient lossless compression of integer datasets through Asymmetric Numeral Systems (ANS). While there are many ANS implementations that are parts of other packages, this one strives to be as simple as possible, with the C++ implementation being just a small amount of code in a single file. The Python interface is also simple and easy to use. At the same time it attempts to be as efficient as possible both in terms of compression ratio and encoding/decoding speed.

- Source: [simple_ans on GitHub](https://github.com/flatironinstitute/simple_ans)

## NWB Assistant

An experimental AI chat assistant for the Neurodata Without Borders ecosystem. This tool is designed to help users navigate NWB documentation and find relevant information quickly through an intuitive chat interface.

- Live: [NWB Assistant](https://magland.github.io/nwb-assistant/chat)
- Source: [NWB Assistant on GitHub](https://github.com/magland/nwb-assistant)

## Stan Assistant

An experimental AI chat assistant for the Stan software, with access to the Stan User's Guide.

- Live: [Stan Assistant](https://magland.github.io/stan-assistant/chat)
- Source: [Stan Assistant on GitHub](https://github.com/magland/stan-assistant)

## Spurious Discovery Tests

Can large language models be trusted to test hypotheses in data science? This project contains a collection of synthetic experiments designed to expose the kinds of mistakes that artificial intelligence can often make when interpreting complex datasets. Each experiment presents a plausible scientific scenario with a dataset containing no underlying signal, but where data analysis pitfalls are possible. Each LLM is evaluated on its ability to identify the absence of a signal and to thus avoid false discoveries.

- Source: [Spurious Discovery Tests on GitHub](https://github.com/magland/spurious-discovery-tests)

## minicline

Command-line and Python interface for performing software engineering tasks using large language models. It is based on Cline, but is simpler, uses fewer input tokens, has fewer capabilities, is more secure by default, and does not depend on VSCode. This package was created during the 2025 Pre-COSYNE Brainhack in Montreal.

- Source: [minicline on GitHub](https://github.com/magland/minicline)

## Neurosift chat

Experimental AI chat assistant for exploring the DANDI Archive and OpenNeuro repository.

- Live: [Neurosift chat](https://chat.neurosift.app/)

## MCMC Monitor

MCMC Monitor enables tracking and visualization of MCMC processes executed with Stan in local or remote web browsers. When you run a sampler, you can configure Stan to generate output to a directory on your computer. MCMC Monitor reads this output and displays it in the web app, with real-time updates. As you track the progress of the run, MCMC provides diagnostic plots and statistics.

- Source: [MCMC Monitor on GitHub](https://github.com/flatironinstitute/mcmc-monitor)

With Jeff Soules

## nbfiddle

nbfiddle is a web-based Jupyter notebook interface that leverages your browser’s storage for saving and managing notebooks. It is designed for self-contained Python notebooks that focus on data analysis, particularly when working with remote data sources such as the DANDI archive.

- Live: [nbfiddle](https://nbfiddle.app/)
- Source: [nbfiddle on GitHub](https://github.com/flatironinstitute/nbfiddle)

## SpikeInterface

I was part of the original team that created [SpikeInterface](https://spikeinterface.readthedocs.io/en/latest/), a Python package that provides a unified framework for spike sorting and electrophysiological data analysis. Although I am no longer actively involved in its development, I contributed to its initial design and implementation.

- Source: [SpikeInterface on GitHub](https://github.com/SpikeInterface/spikeinterface)

## Benchcompress

A benchmarking framework for evaluating compression algorithms on scientific data arrays.

- Live: [Latest benchmark results](https://magland.github.io/benchcompress/)
- Source: [Benchcompress on GitHub](https://github.com/magland/benchcompress)

## Remfile

Provides a file-like object for reading a remote file over HTTP, optimized for use with h5py.

- Source: [Remfile on GitHub](https://github.com/magland/remfile)

## Older projects

* [Figurl](https://github.com/flatironinstitute/figurl/blob/main/doc/intro.md) - replaced by figpack
* [Kachery](https://github.com/flatironinstitute/kachery-cloud/blob/main/README.md) - replaced by figpack
* [SortingView](https://github.com/magland/sortingview/blob/main/README.md) - replaced by figpack
* [Mountainsort 4](https://github.com/magland/mountainsort4) - replaced by Mountainsort 5
* [SequenceTree](https://github.com/magland/sequencetree4) - visual MRI pulse sequence programming
