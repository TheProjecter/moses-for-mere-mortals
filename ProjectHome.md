
---

# This project  is deprecated and exists only for reference. It was moved to Github (https://github.com/jladcr/Moses-for-Mere-Mortals) #

---


This site offers a set of Bash scripts and Windows executables add-ins that, together, create a **basic translation chain prototype** able of processing **_very large corpora_**. It uses **Moses**, a widely known statistical machine translation system.

The idea is to help build a translation chain for the **real world**, but it should also enable a quick evaluation of Moses for actual translation work and guide users in their first steps of  using Moses.

A **Help/Short Tutorial** (http://moses-for-mere-mortals.googlecode.com/files/Help-Short-Tutorial.doc) and a **demonstration corpus** (too small for doing justice to the qualitative results that can be achieved with Moses, but able of giving a realistic view of the relative duration of the steps involved) are available.

Two Windows add-ins allow the creation of Moses input files from `*`.TMX translation memories (Extract\_TMX\_Corpus.exe), as well as the creation of `*`.TMX files from Moses output files (Moses2TMX.exe). _A synergy between **machine translation** and **translation memories** is therefore created_.

Moses for Mere Mortals (MMM) has been tested with the following 64 bit (AMD64) Linux distributions:

  * Ubuntu 11.04

Documents used for corpora training should be perfectly aligned and saved in **UTF-8** character encoding. Documents to be translated should also be in UTF-8 format. _One would expect the users of these scripts, perhaps after having tried the provided demonstration corpus, to immediately use and get results with the real corpora they are interested in_.

Moses for Mere Mortals has been **tested and used in a professional translation context**.
