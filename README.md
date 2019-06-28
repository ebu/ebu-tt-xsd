## Current status: DRAFT, work in progress

Please consider this work as non-final for the time being.

## This repository

This repository contains an XML Schema for entities defined in the EBU-TT Part 1 specification,
[Tech3350](https://tech.ebu.ch/publications/tech3350).

* Copyright 2019, EBU, www.ebu.ch
* Version of XML Schema: 0.9
* Creation: 24/05/2019

The publication of this EBU-TT XML Schema for EBU-TT Part 1 is intended to support the 
implementation of the specification in EBU-Tech 3350 version 1.2.

Please note that the EBU-TT XML Schema is a helping document and NOT normative but informative.

## Cloning

This schema depends on the w3c/ebu-tt-m-xsd repository and imports it via a git submodule.

If cloning from the command line make sure to include the `--recurse-submodules` option,
or after cloning run `git submodule init` then `git submodule update`.

## Style guide

If either the `minOccurs` or `maxOccurs` attributes on an element do not have their default value of 1,
_both_ attributes should be specified.

The `use` attribute should only be specified when its value is `required` - in all other
cases the default `optional` value applies and does not need to be specified.
