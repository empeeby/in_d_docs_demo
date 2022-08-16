.. _in_d_about:

About in_d
=========================

This site is a fork of the official PyTerrier documention docs, with the addition of some pages demonstrating the in_d demonstration system.

The in_d system is an collection of interactive demonstrations which allow the user to enter input and parameters to a given PyTerrier process, and see the corresponding output update in real time.

It is particularly targeted at users who are new to PyTerrier and/or Information Retrieval in general and designed to act as a complement to the static aspects of the documentation. The user can quickly and intuitively experiment and observe the behaviour of a given process directly while learning about the process and referring to the technical documentation, without the need to run a python environment or worry about syntax or downloading data indexes. This allows active engagement and a 'learn by doing' approach to be integrated into the documentation.

Should the user wish to experiment further, a code example describing the current state of the demo is available at the bottom of each demo window and can be copied into any python environment (e.g. a `Colab notebook <https://colab.research.google.com/>`_). This code example automatically updates as the input and parameters of the demo are adjusted.

It is intended that this system can be expanded upon in the future to include demonstrations for more PyTerrier processes, as well as other IR toolkits (such as PISA).

This Site 
---------------------
Although there are currently only a handful of pages containing demos, a copy of the full PyTerrier documentation is included in this site. This is intended to provide a realistic use-case in which the user has the full documentation easily at hand should they wish to cross-reference details, cover background knowledge or read further.

If you are here to trial the in_d system as part of an evaluation survey I'd like to be clear that you are not expected to read all the pages in this site! Only the following three pages, that are included under the heading 'in_d Demonstration Pages' at the top of the menu, are required. You may wish to refer to other pages as part of your exploration.


The Demos 
------------------
:ref:`in_d_retrieval` (1 demo)
:ref:`in_d_rewrite` (2 demos)
:ref:`in_d_operators` (1 demo)


PyTerrier Primer
-------------------
For evaluation participants who may be new to Information Retrieval and/or PyTerrier, this is a quick primer with some background knowledge that may be helpful.

PyTerrier is a declarative platform for information retrieval experiments in Python. It uses the Java-based Terrier information retrieval platform internally to support indexing and retrieval operations.

Wikipedia definition of Information Retrieval:
    Information retrieval (IR) in computing and information science is the process of obtaining information system resources that are relevant to an information need from a collection of those resources. Searches can be based on full-text or other content-based indexing. Information retrieval is the science[1] of searching for information in a document, searching for documents themselves, and also searching for the metadata that describes data, and for databases of texts, images or sounds.

    Automated information retrieval systems are used to reduce what has been called information overload. An IR system is a software system that provides access to books, journals and other documents; stores and manages those documents. Web search engines are the most visible IR applications. 

The PyTerrier data model (:ref:`datamodel.md`)

There are 4 base types of process that


