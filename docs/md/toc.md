Table of Contents
=================

-   [Introduction](#Intro)
    -   [Design goals](#design-goals)
    -   [About this manual](#about-this-manual)
-   [Installing and Running JFlex](#Installing)
    -   [Installing JFlex](#installing-jflex)
    -   [Running JFlex](#running-jflex)
    -   [Maven plugin](#maven-plugin)
    -   [JFlex Ant Task](#jflex-ant-task)
-   [A simple Example: How to work with JFlex](#Example)
    -   [Code to include](#ExampleUserCode)
    -   [Options and Macros](#ExampleOptions)
    -   [Rules and Actions](#ExampleLexRules)
    -   [How to get it building](#how-to-get-it-building)
-   [Lexical Specifications](#Specifications)
    -   [User code](#user-code)
    -   [Options and declarations](#options-and-declarations)
    -   [Lexical rules](#LexRules)
-   [The generated class](#GeneratedJavaCode)
    -   [Name of the generated class](#GeneratedClassName)
    -   [Scanning method](#ScanningMethod)
    -   [Scanner methods and fields accessible in actions (API)](#ScannerMethods)
-   [Encodings, Platforms, and Unicode](#sec:encodings)
    -   [The Problem](#the-problem)
    -   [Scanning text files](#scanning-text-files)
    -   [Scanning binaries](#scanning-binaries)
    -   [Conformance with Unicode Regular Expressions
        UTS\#18](#unicoderegexconformance)
-   [A few words on performance](#performance)
-   [Porting Issues](#Porting)
    -   [Porting from JLex](#porting-from-jlex)
    -   [Porting from lex/flex](#porting-from-lexflex)
-   [Working together](#WorkingTog)
    -   [JFlex and CUP](#CUPWork)
    -   [JFlex and BYacc/J](#BYaccJ)
    -   [JFlex and Jay](#jflex-and-jay)
-   [Bugs and Deficiencies](#Bugs)
    -   [Deficiencies](#deficiencies)
    -   [Bugs](#bugs)
-   [Copying and License](#Copyright)
-   [References](#references)

