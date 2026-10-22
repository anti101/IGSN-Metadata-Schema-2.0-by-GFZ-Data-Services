# IGSN Metadata Schema 2.0 — Core

**Status: in development**  
The schema and this repository are still under active development. Structures, element definitions, and documentation may change before a stable release.

## About this repository
This repository contains the **IGSN Metadata Schema 2.0 Core**, developed by GFZ Data Services.

Core is the common structural basis for subject-specific IGSN metadata profiles. It defines metadata elements and attributes that are relevant across sample types and disciplines. It is **not intended to be used on its own for the complete description or registration of samples**. Instead, subject profiles build on Core to describe sample types in more detail.

### This repository provides:
- the IGSN Metadata Schema 2.0 Core
- a locally adapted version of the DataCite Metadata Schema 4.7, modified to allow the reuse of globally defined types within the Core Schema
- brief documentation of the Core elements and attributes
- tabular overview of all elements and their associated attributes

This repository is intended as a technical and documentary resource for:

- developing and validating subject-specific IGSN metadata profiles
- schema validation of IGSN-related sample metadata
- metadata transformation workflows, for example from templates or databases to IGSN XML
- harmonising sample metadata across disciplines and institutions

## Scope of Core

Core describes the metadata elements that are relevant to all material samples, independent of their scientific domain or sample type. It provides a shared structural foundation, but does not replace discipline-specific or sample-type-specific metadata.

Subject profiles extend Core with additional elements and constraints for particular sample types, research domains, or institutional workflows. The registration of an IGSN ID requires metadata compatible with the DataCite Metadata Schema; Core supports the structured preparation and harmonisation of such metadata, but does not itself constitute a registration interface.

## Continuity and modernisation

IGSN Metadata Schema 2.0 Core is a modernisation of previous IGSN metadata schema work. It builds on earlier schema versions and related metadata models, harmonising their concepts from an information-science perspective.

The aim is not to discard this prior work, but to carry it forward in a more modular and maintainable form:

- previous IGSN schema approaches remain an important conceptual and historical reference
- Core consolidates recurring metadata concepts into a shared foundation
- the structure supports reusable, subject-specific profiles
- the schema is aligned with current DataCite metadata requirements for IGSN ID registration

Core should therefore be understood as a continuation and modernisation of the IGSN metadata tradition, designed to make sample metadata more consistent, interoperable, and reusable.

## Background 
### IGSN e.V.
IGSN e.V. is a non-profit organisation, founded in 2011 to manage the allocation and registration of International Generic Sample Numbers (IGSNs).
The IGSN e.V. works with DataCite to provide a globally recognised persistent identifier for sample identification and tracking that facilitates the efficient sharing of samples and their associated metadata among researchers, institutions, and databases.
Additionally, IGSN e.V. works to promote the use of IGSNs in research and to establish partnerships with other data infrastructures to enhance the integration and interoperability of sample data and metadata. The organisation also provides a range of services related to IGSNs, such as training, support, and software tools for managing and sharing sample data and metadata.

### IGSN 
The application and long-term usefulness of sample-based data depend critically on the availability of information (metadata) about the samples, links to other datasets derived from individual samples, and access to the samples themselves. Achieving this is hindered by several issues, including incomplete sample documentation in publications, the use of ambiguous sample names, and the lack of web-accessible catalogues that provide information on existing samples and their archiving location. Using persistent identifiers for physical samples, such as the International Generic Sample Number (IGSN), can solve these problems.

The IGSN ID is a globally unique, persistent, domain-agnostic identifier for material samples. Samples can be any material from anywhere in the universe, not just from Earth. Although the IGSN originated in the geosciences, it is now applicable to all sample types and disciplines.

### GFZ DataServices
GFZ Data Services has long been involved in IGSN registration and sample metadata management. IGSN Metadata Schema 2.0 Core harmonises previous schema versions and provides a modern, modular basis for describing samples and developing subject-specific metadata profiles.

## Relation to FAIR AIMS

This repository is closely related to the broader development context of FAIR WISH and FAIR AIMS. Within FAIR WISH, standardised, discipline-specific IGSN metadata schemas and templates were developed for various sample types within the Helmholtz research field of Earth and Environment. Workflows were also developed for generating machine-readable metadata from these templates and databases.

FAIR AIMS builds on these results and aims to provide an online template generator, automated IGSN registration workflows, integration of linked-data vocabularies and metadata quality checks during upload. Structured metadata schemas, such as the one documented here, form an important technical basis for template generation, XML creation, landing pages and quality-controlled submission workflows in this context.

